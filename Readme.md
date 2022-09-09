## Single-page Application for only 1$ on AWS — S3 & Cloudfront

Template repository for tech article, [Check it on medium](https://medium.com/aws-tip/spa-static-website-for-only-1-on-aws-with-s3-cloudfront-and-route53-2d0191954924)! 

**Dev**

    # creazione ammbiente virtuale 
    pip3 install --upgrade virtualenv 
    mkdir -pv venv 
    python3 -m virtualenv venv
    
    # install pacchetti
    source venv/bin/activate
    pip3 install -r requirements.txt
    pre-commit install

**Deploy**

Cloudformation select region and create stack:

- **website.yml**

## Mantained by

- **[Fabrizio Cafolla](https://github.com/FabrizioCafolla)**
  <a href="https://www.buymeacoffee.com/fabriziocafolla" target="_blank"><img  align="right" src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 30px !important; width: 150px !important" ></a>
