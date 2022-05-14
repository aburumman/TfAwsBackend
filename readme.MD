This is the configuration to setup  s3 for terraform backend.

Main.tf  contains account config details

state.tf configuration for the backend

Note: Rn the configuration first without the First Code block (backend block) commented out, it would create the s3 bucket

Then run "terraform init" the second time with the First code block (backend block) uncommented.

This will initialized the backend and move the state file to s3.