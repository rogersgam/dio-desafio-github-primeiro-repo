## Git-Credential-Manager-Core

https://github.com/microsoft/Git-Credential-Manager-Core

Once it's installed and configured, Git Credential Manager Core is called implicitly by Git. You don't have to do anything special, and GCM Core isn't intended to be called directly by the user. For example, when pushing (git push) to Azure DevOps, Bitbucket, or GitHub, a window will automatically open and walk you through the sign-in process. (This process will look slightly different for each Git host, and even in some cases, whether you've connected to an on-premises or cloud-hosted Git host.) Later Git commands in the same repository will re-use existing credentials or tokens that GCM Core has stored for as long as they're valid.


Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.

remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.

fatal: Authentication failed for 'https://github.com/rogersgam/dio-desafio-github-primeiro-repo.git/'
