# Super Mario RL

This project demonstrates how to teach an AI agent to play **Super Mario Bros** using Reinforcement Learning (RL). The implementation leverages the following libraries:

- **gym-super-mario-bros**: A custom OpenAI Gym environment for Super Mario Bros.
- **nes-py**: A Python NES emulator.
- **OpenAI Gym**: A toolkit for developing and comparing RL algorithms.

---

## Features
- **Reinforcement Learning**: Uses RL to enable Mario to learn optimal gameplay strategies.
- **Custom Environment**: Powered by `gym-super-mario-bros` and `nes_py`.
- **Expandable Design**: Can be adapted to other NES games.

---

## Setup Instructions

### Prerequisites
Ensure you have the following installed:
- Python 3.8 or higher
- Git
- Virtual environment tools (e.g., `venv` or `conda`)

### Installation Steps

1. Clone the Repository:
   ```bash
   git clone https://github.com/your-username/SuperMarioRL.git
   cd SuperMarioRL
   ```

2. Create a Virtual Environment and Activate It:
   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On macOS/Linux
   source venv/bin/activate
   ```

3. Install Dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Install Required Libraries:
   ```bash
   pip install gym-super-mario-bros nes-py gym
   ```

---

## Usage

### Running the AI Agent
Run the following command to start the AI:
```bash
python main.py
```

### Expected Behavior
- Mario will interact with the environment, exploring and learning to complete levels through trial and error.
- Over time, the AI improves as it receives rewards for progressing through the game.

---

## File Structure
```
SuperMarioRL/
├── README.md             # Project documentation
├── requirements.txt      # Python dependencies
├── main.py               # Main script to run the AI agent
├── models/               # Pre-trained models (if any)
├── utils/                # Utility functions
├── environments/         # Custom environment wrappers
├── data/                 # Logs, results, and other data
└── tests/                # Testing scripts
```

---

## Dependencies
The project relies on the following Python libraries:
- `gym-super-mario-bros`
- `nes-py`
- `gym`
- `numpy`

Install these dependencies using the `requirements.txt` file.

---

## Future Improvements
- Integrate advanced RL algorithms like Proximal Policy Optimization (PPO) or A3C.
- Add visualization tools to display the agent’s progress.
- Train the agent on different levels and game modes.

---

## Acknowledgments
- [gym-super-mario-bros](https://github.com/Kautenja/gym-super-mario-bros)
- [nes-py](https://github.com/Kautenja/nes-py)
- [OpenAI Gym](https://gym.openai.com/)
