# FavRecon
FavRecon is a web based favicon recon tool made using streamlit. It can be useful while doing recon in your security testing to quickly identify the service used by the application.

`Note: Contributions and suggestions are always welcome. I have tries to make it work for most cases but it may give erroneous results sometimes.`


# Usage
- You can directly use the tool from this link: [FavRecon](https://apth3hack3r-favrecon-favrecon-0mkd4s.streamlitapp.com/)
  I have used streamlit share to host the ap from github directly so anyone can use this from the above link.
  
- And if you want to use it localy then just follow the below steps:

  ```bash
  git clone https://github.com/apth3hack3r/favrecon
  cd favrecon
  pip install -r requirements.txt
  streamlit run favrecon.py
  ```
##### Note:
Data about the favicons is taken from this file: [https://github.com/sansatart/scrapts/blob/master/shodan-favicon-hashes.csv](https://github.com/sansatart/scrapts/blob/master/shodan-favicon-hashes.csv)

