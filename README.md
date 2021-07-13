npm install
npm start
This is a small primer on how to use GLTF models on the web, specifically how to use them as dynamic assets.

How to compress assets and turn them into JSX components
npx gltf-pipeline -i model.gltf -o model.glb --draco.compressionLevel=7
npx gltfjsx model.glb
How to include them in your project
Set up react-three-fiber
Put model.glb into /public
Put Model.js (the output of gltfjsx) anywhere inside /src
