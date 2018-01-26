# jinja
This example uses environment variables in templates.

    bash-4.2# ./jinja_example.py 
    I don't have an AGS :(

    bash-4.2# export AGS=testing_ags
    
    bash-4.2# ./jinja_example.py 
    My AGS = testing_ags

    bash-4.2# 
