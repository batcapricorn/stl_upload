# STL Upload Application

## About
This is a small web application written in HTML and JavaScript that allows you to upload STL files and immediately view them in a STL viewer. I employed the [viewstl](https://www.viewstl.com/plugin/) package.

## Development Setup
Here's how to get the site running on your machine:
1. Get into a UNIX-like environment (e.g. using a VM or WSL2. If you're already on Linux/Mac, there is no action needed)

You need to employ some kind of http server, e.g. `http-server` by npm:

2. If necessary, install npm by running `curl https://npmjs.org/install.sh | sh`
3. Install http-server: `npm install http-server -g`
4. Clone repository: `git clone git@github.com:lukasboehm97/stl_upload.git`
5. Move into the directory: `cd stl_upload`
6. Start server: `http-server ./src`
7. You can now access the app at `http://127.0.0.1:8080`