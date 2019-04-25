# fb-example-service

Form Builder example form


## Usage

The easiest way to get this form up and running is to use the `Form Builder Editor Console`.

It can be downloaded [here](https://github.com/ministryofjustice/fb-editor-console-electron/releases)

- Open the app and wait for installation to complete
- Click `Add existing form`
- Enter this repo address (`https://github.com/ministryofjustice/fb-example-service.git`) in the `Repository address` field
- Click `Add form`
- Click `Start` link

The form will open in a new window in your default browser.

### Alternative ways

You can also run the form directly using the Form Builder Editor or Runner

- [Editor installation instructions](https://github.com/ministryofjustice/fb-editor-node)
- [Runner installation instructions](https://github.com/ministryofjustice/fb-runner-node)

```
git clone git@github.com:ministryofjustice/fb-example-service.git

cd /path/to/editor-or-runner

SERVICE_PATH=/path/to/fb-example-service npm start
```
