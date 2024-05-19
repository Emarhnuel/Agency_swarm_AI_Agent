
# Setting Up Agency Swarm Script

### Prerequisites
1. **Create a Virtual Environment:**
   ```bash
   conda create -n swarm_env python=3.10 pip
   ```
   
2. **Activate the Virtual Environment:**
   ```bash
   conda activate swarm_env
   ```

### Clone and Navigate to the Repository
1. **Clone the Repo:**
   ```bash
   git clone https://github.com/Emarhnuel/Agency_swarm_AI_Agent.git
   ```

2. **Navigate to the Repo:**
   ```bash
   cd /path/to/your-repo/Agency_swarm_AI_Agent
   ```

3. **Install Requirements:**
   ```bash
   pip install -r requirements.txt
   ```

### Configure API Keys
1. **Open the `config.yaml`:**
   ```bash
   nano config.yaml
   ```

2. **Enter API Keys:**
   - **Serper API Key:** Get it from [https://serper.dev/](https://serper.dev/)
   - **OpenAI API Key:** Get it from [https://openai.com/](https://openai.com/)

### Run Your Query
```bash
python app.py "YOUR QUERY"
```
### Note!
settings.json is automatically created by Agency Swarm.
