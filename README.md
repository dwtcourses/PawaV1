## Stride - Conversational Landing Pages

Stride is a bot designed to give your landing pages a more interactive and attractive feel. With Stride you can make each landing page visit seem like a conversation between your service and your consumers. Stride is completely customizable, from the style and story.

[DEMO](http://stride.technopathic.me)

## Screenshots
![Screenshot](https://technopathic.me/storage/stridescreen1.png)
![Screenshot](https://technopathic.me/storage/stridescreen2.png)

## Getting Started
To quickly get started, fork this repo or clone it onto your local computer. Then run `npm install` to install all of the necessary libraries.
```
git clone https://github.com/Technopathic/Stride.git
cd stride
npm install
```
From there you can then edit the story.json file inside of the data folder. Each JSON object within the array is a chat block. You have a set of available types of chat blocks to display using Stride.

* Text
* Image
* Option
* Link
* Input

You also have the ```_this.addblock(input)``` available and the ```input``` parameter is exposed with each Option and Input type.

To run the server, simply do `npm run start` and your development website will be on http://localhost:3000.

To build the production release, run `npm run build`. .

## License
MIT
