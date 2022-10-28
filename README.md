# om-retirement-scorer

The scorer only for the om-retirement private repository.

## Environment Configuration

This notebook can be executed in any environment where jupyter notebooks is configured as long as the dependencies in `requirements.txt` are installed.

### Existing Conda Environment

The simplest way to install the dependencies is simply to clone the repository in your existing (perhaps conda) environment as follows:

```bash
git clone https://github.com/JohnnyFoulds/om-retirement-scorer.git
cd om-retirement-scorer
pip install -r requirements.txt
```

### New Virtual Environment (Windows 10/11)

Alternatively, a new virtual environment can be created and the dependencies installed as follows:

```powershell
# create the environment
mkdir $HOME/om-retirement
mkdir $HOME/om-retirement/venv/
python3 -m venv $HOME/om-retirement/venv

# activate the new environment
.$HOME/om-retirement/venv/Scripts/Activate.ps1 
# use `source $HOME/om-retirement/venv/bin/activate` for linux/mac

# clone the repository
cd $HOME/om-retirement
git clone https://github.com/JohnnyFoulds/om-retirement-scorer.git
cd om-retirement-scorer

# install the requirements
pip install -r requirements.txt
```
