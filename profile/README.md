Weik.io is an open source GitOps integration platform that manages integrations, APIs, file transfers and events. Integrations in Weik.io are Apache Camel routes in YAML, XML or Java, and you keep them in Git and promote each version from devtest to production with the `weikio` CLI or the admin UI.

- Weik.io: https://weik.io
- Docs: https://weik.io/docs
- University: https://weik.io/university
- Weik.io Cloud: https://weikio.cloud
- Live demo: https://demo.weik.io
- GitHub: https://github.com/weikio/weikio

[weikio/weikio](https://github.com/weikio/weikio) has the releases with the CLI files, the JSON schemas, the discussions and the security policy. [weikio/gitops-example](https://github.com/weikio/gitops-example) has the examples that the docs use. Fork it to run them on your own installation from GitHub Actions. [weikio/try-weikio](https://github.com/weikio/try-weikio) runs the whole platform in a dev container on your machine.

### Libraries

The team behind Weik.io has published open source .NET libraries since 2019:

- [PluginFramework](https://github.com/weikio/PluginFramework), a plugin framework for .NET applications that loads plugins from .NET assemblies, NuGet packages and Roslyn scripts
- [ApiFramework](https://github.com/weikio/ApiFramework), which builds OpenAPI endpoints in ASP.NET Core from plain classes, NuGet packages, databases and other plugins
- [EventFramework](https://github.com/weikio/EventFramework), for creating, sending, receiving and handling CloudEvents in .NET
