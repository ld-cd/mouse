# mouse
Small script that manages a staging directory for runit.

## commands

    mouse enable SERVICE

enables a particular service

    mouse disable SERVICE

disables a particular service

mouse will pass any other command ie:

    mouse start SERVICE
    
will run

    sv start SERVICE
