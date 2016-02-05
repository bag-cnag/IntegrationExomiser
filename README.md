# IntExomiser 

# Run Exomiser

The client sends a vcf file together with a json file for a specific donor that queries from the Phenotips.
The Exomiser web service receives the two files,parses the json in order to get the HPO terms and runs the 
exomiser algorithms with inputs the vcf file and the hpo terms. 

It stores the results in the "results" folder and renders the HTML report from the "templates" folder.

```
#Run with the default server of Flask
./api.py 
#Run with the tornado server
./torn.py
#Run client code 
python client.py
```

