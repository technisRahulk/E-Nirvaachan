# E-Nirvaachan

## Installation

1. Install Truffle globally.
    ```javascript
    npm install -g truffle
    ```

2. Clone the repo. This also takes care of installing the necessary dependencies.
    ```javascript
    git clone https://github.com/technisRahulk/e-Nirvaachan.git
    ```

3. Run the development console.
    ```javascript
    truffle develop
    ```

4. Compile and migrate the smart contracts. Note inside the development console we don't preface commands with `truffle`.
    ```javascript
    compile
    migrate
    ```

5. Run the `liteserver` development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.
    ```javascript
    // Serves the front-end on http://localhost:3000
    npm run dev
    ```