Setting Up OpenUI: A Step-by-Step Guide
To begin using the powerful OpenUI tool for generating UI components with AI, follow these steps:
Create Project Folder: Start by creating a new folder on your local machine to host the OpenUI project. Let's call it openUI_You-ve_Got_Frontend_Friend_in_me.
Clone Repository: Open your terminal or command prompt, navigate to the openUI_You-ve_Got_Frontend_Friend_in_me. folder, and clone the OpenUI repository using the following command:

git clone https://github.com/aniket-work/openUI_You-ve_Got_Frontend_Friend_in_me.git
This will download the necessary project files to your local folder.
3. Change Directory: Once the cloning process is complete, navigate into the project folder:
cd openUI_You-ve_Got_Frontend_Friend_in_me
4. Clone OpenUI Core: OpenUI relies on the core OpenUI repository from Weights & Biases (W&B). Clone this repository by running:
git clone https://github.com/wandb/openui.git
5. Create Virtual Environment: It's best practice to set up a virtual environment to isolate the project dependencies. Create a new virtual environment using Python's built-in venv module:
python -m venv openUI_You-ve_Got_Frontend_Friend_in_me
6. Activate the virtual environment:
On Windows:
openUI_You-ve_Got_Frontend_Friend_in_me\Scripts\activate

On Unix or MacOS:
source openUI_You-ve_Got_Frontend_Friend_in_me/bin/activate
7. Install Dependencies: With the virtual environment active, navigate to the openui/backend folder and install the required Python packages 
cd openui\backend
    pip install .