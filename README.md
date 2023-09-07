# Web Document Scanning with Mobile Capture
The sample showcases a scenario where documents can be captured using a mobile camera and uploaded as images to a remote document management system that has been developed using [Dynamic Web TWAIN](https://www.dynamsoft.com/web-twain/overview/). The images are loaded into the image viewer of Dynamic Web TWAIN and can be processed further.

## Usage
1. Install all Node.js dependencies with `npm install`:
    ```bash
    npm install
    ```
2. Create a SQLite3 database:
    ```bash
    npm creatdb.js
    ```
3. Apply for a [trial license](https://www.dynamsoft.com/customer/license/trialLicense?product=dwt) of Dynamic Web TWAIN and replace the license key in `index.html`:
    ```js
    Dynamsoft.DWT.ProductKey = "LICENSE-KEY";
    ```

4. Start the web server:
    ```bash
    node app.js
    ```
    
    https://github.com/yushulx/web-document-scanning-mobile-capture/assets/2202306/b1cd6ac1-17cd-4b7e-826f-b24009472387

