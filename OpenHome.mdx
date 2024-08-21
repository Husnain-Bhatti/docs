# OpenHome

👋 Hello, world

I'm thrilled to introduce you to OpenHome - an open-source AI smart speaker project.

<a href='https://openhome.xyz/' target='_blank'>
    <img src='https://i.postimg.cc/02Yq2NgB/OpenHome.png' border='0' alt='OpenHome' width='250' height='250'/>
</a>

<b>OpenHome Vision:</b> Imagine a world where your smart speaker is your companion. It adapts, learns, and grows with you. That's what we're building with OpenHome – a groundbreaking open-source AI smart speaker project designed to push the boundaries of imagination

At OpenHome, we believe in the power of community-driven development to create technology that's not only advanced but also accessible. Whether you're a seasoned developer, a curious beginner, or somewhere in between, OpenHome is your opportunity to contribute to an AI smart speaker that's as simple to get started with as it is powerful.

<b>Our Mission:</b> To build an AI smart speaker that's cutting edge, open, customizable, and versatile for every user. We're not just creating a product, we're creating an ecosystem where every idea counts and is integrated to one giant super brain.

# What sets OpenHome apart? Here, you'll find:

<li><b>Accessibility:</b></li> Easy-to-understand codebase and well-documented features for all skill levels.
<li><b>Innovation:</b></li>  A playground for your most creative ideas to take shape and evolve.
<li><b>Community:</b></li>  A supportive and collaborative space where questions are welcomed, and knowledge is shared.
<li><b>Open-Source:</b></li>  We're committed to being open-source and empowering people to create the technology they want.


## Project Architecture Overview
Work in Progress Technical Architecture: https://docs.google.com/document/d/1PInWfbWBY9571Hq4R0nf5Uj01agy6YVXV2UTBonUc4A/edit

<b>The Heart of OpenHome:</b> A Dynamic, Ever-Evolving Core At the core of OpenHome is a unique and powerful loop that continuously evolves the personality of your smart speaker. This isn't just about responding to commands; it's about creating an experience that's deeply personal and constantly refreshing. Every interaction with OpenHome is a step towards a more nuanced and tailored experience.

<b>How It Works:</b> The Magic Behind the Scenes Dynamic Personality: OpenHome begins with a foundation of diverse personalities, each ready to provide a distinct interaction experience. But here's the twist – these personalities aren't static. They evolve with every conversation, adapting to your preferences, your style, and your world.

<b>Seamless Interactions:</b> Through our advanced audio module, OpenHome listens and understands, converting your spoken words into a digital format that it can process. This is where the conversation begins.

<b>Smart Processing:</b> Leveraging the power of OpenAI's GPT model, OpenHome intelligently processes your input. Whether it's a command, a query, or casual chatter, the system is designed to understand and respond in the most relevant way.

<b>Personalized Responses:</b> The heart of OpenHome beats in its ability to learn from each interaction. Using our DynamicPersonalityConstructor, the system crafts responses that aren't just accurate but also personalized, taking into account your history and preferences.

<b>Audible Magic:</b> What good is a smart response if it can't be enjoyed? Our text-to-speech module brings the conversation to life, turning text responses into natural, fluent speech.



## Install and configure

To get the project running locally install pdm using python3.11.

Check your python version if it is below 3.11 run these two python related commands else you can directly run the curl command.

To add python repo to your system run the folowing deadsnakes command.

```bash
sudo add-apt-repository ppa:deadsnakes/ppa
```

After adding python repo to your system install python 3.11.


```bash
sudo apt install python3.11
```

You can install `curl` using the following command if it is not already installed.

```bash
sudo apt  install curl
```

```bash
curl -sSL https://pdm-project.org/install-pdm.py | python3 -
```

After install run the prompted command

```bash
export PATH=/Users/your-username/.local/bin:$PATH
```

Next install the required dependencies.


### Install dependencies

To install the required dependencies, run the following command:

```bash
pdm install
```
After running `pdm install` command if you encounter the following error.

![Error log](/assets/pyAudio_error.png?raw=true "PyAudio Error")

Run the following command to fix PyAudio error.

```bash
sudo apt install python3.11-dev build-essential gcc
```
And again run.

```bash
pdm install
```
You can also use homebrew to install these modules. brew install ffmpeg, portaudio, etc

## Running the Main Pipeline

**Add Your API Key to the `.env` File:**
   - Start by copying the `.env.example` file and save it as `.env` in the main project directory.
   - Navigate to our temporary [Dashboard](https://www.sporepress.org) and sign up. Retrieve your `OPENHOME_API_KEY` from the Settings tab.
   - Paste your `OPENHOME_API_KEY` into the `.env` file.

### How to Run?

To execute the main pipeline, use the following command:

```bash
pdm run main
```
### Flags

You can use the following flags to customize the behavior of the main pipeline:

- `--debug`: Shows all logs for debugging purposes.
- `--default-conf`: Loads the preset/default personality configuration.
- `--wipe-memory`: Resets both agent and user memory.
- `--speech-off`: Disables speech output, with results visible in logs.

## How to build a capability?

To begin developing a new capability, follow these steps:

1. Copy and paste the template folder in the `capabilities/` directory.
2. Name the copied folder according to your capability.
3. Modify the files within the folder to implement your capability.

### File Structure

The capability folder should contain the following file `main.py`.

This file contains the necessary classes and functions to set up your capability. Implement your capability logic within this file.

```python
class YourCapability(MatchingCapability):
    @classmethod
    def register_capability(cls) -> "MatchingCapability":
        return cls(
            unique_name="unique capability name, e.g., timer",
            matching_hotwords=["write words to trigger capability, e.g., 'set a timer for ten minutes'"],
        )

    def call(
        self,
        msg: str,
        agent: BotAgent,
        text_respond: SynchronousTTT,
        speak_respond: None,
        audio: str,
        worker: AgentWorker,
        meta: dict[str, Any],
        interrupt_str: SharedValue,
    ):
        # Write your capability code here
        return "Your Capability Called!"
```

### Registering Capability

In the `register_capability` method of `main.py`, specify the details of your capability:

- `unique_name`: Name of your capability.
- `matching_hotwords`: List of keywords to trigger the capability.

### Call Function

The `call` function is invoked when the capability is triggered. This is where your capability logic resides. The returned string will be played with the agent's voice.

### CapabilityWorker

If you need to develop a capability capable of pausing the main loop, you can use  [CapabilityWorker](src/agent/CapabilityWorker.md). CapabilityWorker is initialized with a worker and is utilized for speech and listening functionalities.

If you want to pause the main flow in the backend at specific intervals use [DaemonWorker](src/agent/DaemonWorker.md).

### Capability Installation

Once your capability is developed, you can install it into the system as a system capability:

**System-wide Installation**: Add the capability name to the `SYSTEM_CAPABILITIES` list in `src/system_conf.py` to make it accessible to all agents.

**Publishing a Capability or Assigning to a Specific Agent**: If you've finalized your capability and wish to make it public or assign it to a specific agent, follow these steps:

1. **Compress Capability Folder:**
   - Compress the folder containing your capability files, including `main.py` and any other necessary files, into a zip file.

2. **Upload to Temporary Cloud Dashboard:**
   - Head over to the temporary cloud [Dashboard](https://sporepress.org/add_capability).
   - Upload the zip file containing your capability folder.
   
