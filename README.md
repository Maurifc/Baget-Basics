
Run baget server
docker run --rm --name baget -p 5555:80 --env-file baget.env -v "$(pwd)/baget-data:/var/baget" loicsharma/baget:latest

## Create .Net App
```bash
dotnet new console -o App -n DotNet.Docker
```

## Install a package