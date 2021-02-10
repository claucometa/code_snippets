# code_snippets

`typeof(Startup).Assembly.ExportedTypes.Where(x=>typeof(IInstaler).IsAssignableFrom(x) && !x.IsInterface && !x.IsAbstract).Select(Activator.CreateInstance).Cast<IInstaler>().ToList().ForEach(installer => installer.InstallServices(services, Configuration));`

OneOf
https://www.youtube.com/watch?v=r7QUivYMS3Q

Docker
https://www.youtube.com/watch?v=fAtfVu569CY

Clean API with Mediatr
https://www.youtube.com/watch?v=YzOBrVlthMk

API Versioning
https://www.youtube.com/watch?v=iVHtKG0eU_s
https://www.youtube.com/watch?v=WFEE5yVJwGU&t=183s

Validation 
https://www.youtube.com/watch?v=Ut6mRRFT2vM (FluentValidation)
https://www.youtube.com/watch?v=2JzQuIvxIqk (Mediatr)

Mapster
https://www.youtube.com/watch?v=UIslFVEHkzA&t=648s

Scrutor 
https://www.youtube.com/watch?v=m77s48tTdfU

Feature Flags
https://www.youtube.com/watch?v=6EebLChouDE

Redis
https://www.youtube.com/watch?v=jwek4w6als4

Mediatr
https://www.youtube.com/watch?v=2JzQuIvxIqk

Scalable solution
https://www.youtube.com/watch?v=rzjy2DDPwio

Integration Testing
https://www.youtube.com/watch?v=7roqteWLw4s

GitHub Actions
https://www.youtube.com/watch?v=BO2C5qAyl4w
