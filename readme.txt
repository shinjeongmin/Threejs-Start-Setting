1. install package
npm i -D @babel/cli @babel/core @babel/preset-env babel-loader clean-webpack-plugin copy-webpack-plugin core-js cross-env html-webpack-plugin source-map-loader terser-webpack-plugin webpack webpack-cli webpack-dev-server
npm i three

2. run server
npm start

3. build  (for release)
npm run build

-> if error in command "npm start" or "npm run build", retry with changed node LTS version.
n lts

-> ERROR in unable to locate 'something...'
If the above error occurs, please check if there is a file set in CopyWebpack Plugin in webpack.config.js.
If you don't need CSS or an image folder, please annotate the entire CopyWebpackPlugin part in webpack.config.js.

