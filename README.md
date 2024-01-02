<h1 align="center">
  <br>
  <a href="https://github.com/mkdirlove/ImageGen-AI"><img src="https://github.com/mkdirlove/ImageGen-AI/blob/main/logo.png" alt="ImageGen-AI"></a>
  <br>
  Yet another AI based text-to-image generator tool using Polination AI and Replicate AI. 
  <br>
</h1>

#### Installation

Copy-paste this into your terminal:

```sh
git clone https://github.com/mkdirlove/ImageGen-AI.git
```
```
cd ImageGen-AI
```
```
./ImageGen-AI
```
#### Usage
``` 
	┳         ┏┓      ┏┓┳
 	┃┏┳┓┏┓┏┓┏┓┃┓┏┓┏┓━━┣┫┃
 	┻┛┗┗┗┻┗┫┗ ┗┛┗ ┛┗  ┛┗┻
         ┛             
  An AI based image generation tool.

Usage: ./ImageGen-AI [--query|-q QUERY] [--output|-o OUTPUT_FILE] [--api|-a API_NAME] [--display|-d] [--help|-h]
  --query, -q      Specify the query for the selected API
  --output, -o     Specify the output file for the image
  --api, -a        Specify the API to use ('polination' or 'replicate')
  --display, -d    Display the image in the terminal
  --help, -h       Display this help message

```
#### Example

Using Polinations AI API
```
./ImageGen-AI -q "a cute cat with sword" -a polination -o cat1.png -d
```

Using Replicate AI API
```
./ImageGen-AI -q "a cute cat with sword" -a replicate -o cat2.png -d
```
