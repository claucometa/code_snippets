# code_snippets

`typeof(Startup).Assembly.ExportedTypes.Where(x=>typeof(IInstaler).IsAssignableFrom(x) && !x.IsInterface && !x.IsAbstract).Select(Activator.CreateInstance).Cast<IInstaler>().ToList().ForEach(installer => installer.InstallServices(services, Configuration));`
