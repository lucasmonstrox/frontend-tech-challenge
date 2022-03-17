# Frontend

A registration form must be built with the following fields:

- Name
- Email
- Password

All fields must be validated.

## Form Status

The form should have 3 status:

- Default, when form is not filled
- Processing, when data is submitting to api
- Success, when data is sent successfully to api

## Api

It is possible to create a fake timeout to simulate the request to the server using a dummy function or create a dummy endpoint and use it with Cypress with mocks.

# Optional tasks

- Using Jest, create a simple render/integration test to validate the form status.
- Using Cypress, create an automation test to verify the form success status.

# Extra(if applicable)

- Code principles like:
  - Clean Code
  - KISS(keep it simple stupid)
  - SOLID
  - Design Patterns
- Conventional Commits(in English) & Commitlint(husky)
- Documentation onboarding(a README explaining how to setup, start, test & lint the project)
- Linter
- Prettier & Editorconfig
- Set package.json properties like(name, version, description, license, etc)
- Lock node engine to specific version used by project
- Source Map Explorer to watch build details

# Avoid

- DRY(Don't repeat yourself)
- Inheritance instead of composition
- Overengineering
- YAGNI(You aren't gonna need it)

# Obligatory technologies

- React
- TypeScript
- Material-UI
- Formik
- Webpack
