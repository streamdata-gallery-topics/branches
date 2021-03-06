swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 1
info:
  title: Bitbucket
  description: code-against-the-bitbucket-api-to-automate-simple-tasks-embed-bitbucket-data-into-your-own-site-build-mobile-or-desktop-apps-or-even-add-custom-ui-addons-into-bitbucket-itself-using-the-connect-framework-
  termsOfService: https://www.atlassian.com/legal/customer-agreement
  contact:
    name: Bitbucket Support
    url: https://support.atlassian.com/bitbucket
    email: support@bitbucket.org
  version: 1.0.0
host: api.bitbucket.org
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repositories/{username}/{repo_slug}/refs/branches:
    get:
      summary: Get Repositories Username Repo Slug Refs Branches
      description: Get repositories username repo slug refs branches
      operationId: getRepositoriesUsernameRepoSlugRefsBranches
      x-api-path-slug: repositoriesusernamerepo-slugrefsbranches-get
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Refs
      - Branches
    parameters:
      summary: Parameters Repositories Username Repo Slug Refs Branches
      description: Parameters repositories username repo slug refs branches
      operationId: parametersRepositoriesUsernameRepoSlugRefsBranches
      x-api-path-slug: repositoriesusernamerepo-slugrefsbranches-parameters
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Refs
      - Branches
  /repositories/{username}/{repo_slug}/refs/branches/{name}:
    get:
      summary: Get Repositories Username Repo Slug Refs Branches Name
      description: Get repositories username repo slug refs branches name
      operationId: getRepositoriesUsernameRepoSlugRefsBranchesName
      x-api-path-slug: repositoriesusernamerepo-slugrefsbranchesname-get
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Refs
      - Branches
      - Name
    parameters:
      summary: Parameters Repositories Username Repo Slug Refs Branches Name
      description: Parameters repositories username repo slug refs branches name
      operationId: parametersRepositoriesUsernameRepoSlugRefsBranchesName
      x-api-path-slug: repositoriesusernamerepo-slugrefsbranchesname-parameters
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Refs
      - Branches
      - Name