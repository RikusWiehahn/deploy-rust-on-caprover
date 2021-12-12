# Deploy a basic Rust API on Caprover 🚀

This is a super basic example project that shows how to deploy a minimal hello-world rust API server on Caprover.

The `captain-definition` file is the main thing that matters, the rest is just a default hello world app.

The name of your application in `Cargo.toml` must match the name of the folder used for building it in the captain-definition file. 
- I used `app_name`. 
- Dont't use kebab case, eg. `app-name` won't work.
