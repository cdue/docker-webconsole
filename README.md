# Web-console

This image allows to run a terminal in a browser.
It uses the [web-console](http://web-console.org/) open source project.

## Running a web-console container

Run the following command:
`docker run -it --rm -p80:80 -v $PWD/directory_to_mount/:/mounted_directory cdue/webconsole:latest`

(no need to use the -v option if you don't need to mount a directory inside the container)

Then access your web-console at: http://localhost

