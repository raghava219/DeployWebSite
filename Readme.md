# BUILDING FOR PRODUCTION

- Combine CSS and JS files. -- Using a build tool.
- Minify JS/CSS files -- Using a build tool.
- Optimize images -- So far we are doing using Photoshop and claudconvert.com

# BUILD TOOLS

-- Webpack -- it has lots of configuration.
-- Rollup
-- Parcel is best -- www.parceljs.org

Parcel combines a great out-of-the-box development experience with a scalable architecture that can take your project from just getting started to massive production application.

-- To use install Node

-- Before installing any software, we need to initiaize npm package manager by running below script

npm init -y

Above command will create package.json file.

npm i -g parcel-bundler

Run parcel build by below command

parcel build .\putting-all-together.html
