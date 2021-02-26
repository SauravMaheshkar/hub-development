# Development Workflow for Hub

How to Start Working

1. Setup Virtual Environment

```
pip install virtualenv
python3 -m venv myenv

# Unix or MacOS
source myenv/bin/activate

# Windows
myenv\Scripts\activate.bat
```

2. Clone the Repository

```
git clone --recurse-submodules https://github.com/SauravMaheshkar/hub-development.git
cd hub-development
git submodule init && git submodule update
git checkout <feature-name>
pip install -r requirements.txt
```

3. Make Changes

```
cd Hub
# Make Changes
git commit -a -m "Made Changes"
git push
```