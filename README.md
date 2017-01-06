![Beego from scratch](https://guides.nanobox.io/assets/quickstart-icons/beego.png)

# Beego from scratch

Run a Beego app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>

## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-beego.git

# cd into the beego app
cd nanobox-beego
```

## Run the app

```bash
# Run Beego as you would normally, with Nanobox
nanobox run bee run
```

## Check it out

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local beego.dev
```

Visit your app at <a href="http://beego.dev:8080" target="\_blank">beego.dev:8080</a>

## Explore
With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where golang is installed,
go version

# git is installed,
git --version

# and your code is mounted
ls
```

## Now What?
For more details about running Beego apps with nanobox visit [guides.nanobox.io/golang/beego/](https://guides.nanobox.io/golang/beego/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
