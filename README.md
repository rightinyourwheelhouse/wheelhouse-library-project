# wheelhouse-library-project
Main repo of the wheelhouse library project. Containing a docker-compose configuration to start the project locally and the app and api as submodules.

When cloning the project use `--recurse-submodules` to make sure you pull the submodules 
> git clone git@github.com:rightinyourwheelhouse/wheelhouse-library-project.git --recurse-submodules

Don't forget create a `.env` file in the root of the project with the following filled in:

```
SLACK_OAUTH_TOKEN=token
SLACK_CLIENT_ID=id
SLACK_CLIENT_SECRET=secret
GOOGLE_API_KEY=key
```

For local development start the project using: 
> docker-compose up -d
