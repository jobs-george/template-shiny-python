# Template Shiny App in Python

Server-side Shiny app example in Python hosted on ShinyApps:

<https://jobs-george.shinyapps.io/template-shiny-python/>

# Getting Started

Run the app locally by:

1.  Restoring the dependencies with

    -   `python -m venv venv`
    
    -   `source venv/bin/activate`
    
    -   `pip install -r requirements.txt`


2.  Run the app

    -   from the shell `shiny run --reload --launch-browser app.py`

    -   or with the VSCode shiny extension

# Deployment

Use the following steps to deploy the app:

1.  Install the `rsconnect` package (`pip install rsconnect-python`)

2.  Create a ShinyApp.IO account and token

3.  Set the fields of `rsconnect add --account <account> --name <name> --token <token> --secret <secret>`

4.  Deploy the app with `rsconnect deploy shiny "." --name <name> --title <my-title>`

# Contribute

N/A
