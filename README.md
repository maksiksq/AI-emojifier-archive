# Notice:
This moved to [this repo](https://github.com/maksiksq/AI-emojify)
And I stopped working and paying for that repo as well, more details there.

# AI-emojifier
A website made with pyscript, utilizing OpenAI's GPT3 API.
This took me a few days and a lot of trial and error to make, I had to explore some barely charted grounds with Pyscript and making it work with OpenAI.

### A lot of the code is yoinked from:
[Medium article](https://medium.com/@ivancampos) by Ivan Campos

This should from my knowledge be easily possible in Node.js and Django I just took a weird route.

## Important:
Sadly my project has to use old GPT 3 models instead of moder GPT 3.5 and 4 because openai module is not yet supported on Pyodide since both Pyscript and Pyodide are very new. You can however speed up this process by bumping more attention to this issue on their repo: 
[OpenAI module request](https://github.com/pyodide/pyodide/issues/3588)

Update: they added it
