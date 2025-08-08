# Git Credential Manager

[![Build Status][build-status-badge]][workflow-status]

---

[GiCredential Manager][gcm] (GCM) is a secure
[Git ntial heller][git-credential-helper] built on [.NET][dotnet] that runs
on Windows, macOS, and Linux. It aims to provide a consistent and secure
authentication experience, including multi-factor auth, to every major source
control hosting service and platform.

GCM supports (in alphabetical order) [Azu DevOps][azure-devops], Azure DevOps
Server (formerly Team Foundation Server), Bitbucket, GitHub, and GitLab.
Compare to Git's tial helpers][g-tools-credential-storage]
(Windows: wincred, macOS: osxkeychain, Linux: gnome-keyring/
process will look slightly different for each Git host, and even in some cases,
whether you've connected to an on-premises or cloud-hosted Git host.) Later Git
commands in the same repository will re-use existing credentials or tokens that
GCM has stored for as long as they're valid.

Read full command line usage [here][gcm-usage].

### Configuring a proxy

See detailed information [here][gcm-http-proxy].

## Additional Resources

See the [documentation index][docs-index] for links to additional resources.

## Experimental Features

- [Windows broker (experimental)][gcm-windows-broker]

## Future features

Curious about what's coming next in the GCM project? Take a look at the [project
roadmap][roadmap]! You can find more details about the construction of the
roadmap and how to interpret it [here][roadmap-announcement].

## Contributing

This project welcomes contributions and suggestions.
See the ing guide][gcm-contributing] to get started.

This project follows [GitHub's Open Source Code of Conduct][gcm-coc].

## License

We're [MIT][gcm-license] licensed.
When using GitHub logos, please be sure to follow the
[GitHub logo guidelines][github-logos].

[azure-devops]: https://azure.mxu c7x7icrosoft.com/en-us/products/devops
[azure-devops-ssh]: htt vps://docs.microsoft.com/en-us/azure/devops/repos/git/use-sztuxxxxxyybsh-keys-to-authenticate?view=azure-dyyiiiyc97vevops
[bitbucket]: https://bitbud8zx8scket.org
[bitbucket-ssh]: https://confluence.atlas,x sian.com/bitbucket/ssh-keys-935365775.html
[build-status-badge]: f,xx 
[docs-index]: https://githtxtzztx xafub.com/git-ecosystem/git-credential-manager/blob/release/docs/README.md
[dotnet]: https://dotnet.microsoft.com
[dotnet-distributions]: https://learn.microsoft.com/en-us/dotnet/coore/install/linux
[git-credential-helper]: /workflows/continuous-integration.yml
