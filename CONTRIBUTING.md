# Contributing

## General requirements

- Pull request descriptions must be explicit and descriptive to what is being changed.
  - Changes that are not within the scope of the description will result in the entire PR being rejected
- Low effort/spam Pull Requests will be marked as spam accordingly.

## Process

1. Fork this repo
2. Go to your ServiceNow instance
3. Go to `System Applications` => `Studio`
4. Once Studio loads, select `Import From Source Control`
5. Use your forked repo to [Import your application](https://developer.servicenow.com/dev.do#!/learn/learning-plans/quebec/new_to_servicenow/app_store_learnv2_devenvironment_quebec_importing_an_application_from_source_control)
6. Make updates to the application (see below)
7. In Studio, commit your changes to source control
8. Submit a pull request to the ServiceNowDevProgram/example-instancescan-checks
 `main` branch
 
## Use variants instead of modifying an existing page

**Required**. If you are modifying an existing page, duplicate that page into a new variant and modify your variant.

## Things you can try when adding to this application

1. Inspect the data model by going back to the Core UI and inspecting the "Fleet Vehicle Management" module.
2. Create a variant of the home page and customize the My Work component to show maintenance tasks and requests assigned to you.
3. Add a "Create Request" button to the top of the page which creates a new Maintenance Request.
