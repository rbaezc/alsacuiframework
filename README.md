# Front End Assignment: Make A Transaction - UI Framework

This project was created to build sass files and then compile them to css, 
in package.json file i added the next rule in the scripts section:

-- "scss": "node-sass --watch scss -o css"

Then to be able to compile the files you need to run the next command (for each new file):
-- npm run scss

Then everytime you modify a sass file, the css file will get modified also with the new css compiled version.