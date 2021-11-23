## Dev

    # creazione ammbiente virtuale 
    pip3 install --upgrade virtualenv 
    mkdir -pv venv 
    python3 -m virtualenv venv
    
    # install pacchetti
    source venv/bin/activate
    pip3 install -r requirements.txt
    pre-commit install

## Deploy

Cloudformation select region and create stack:

- **website.yml**