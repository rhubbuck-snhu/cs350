The purpose of this project was to build a 'thermostat',  in which our SimpleLink board was able to connect to the cloud via Wi-Fi, sense ambiant temperature, increase or decrease set points 
based on user button interaction, turn on heat (or a LED in this case) at a certain point, and relay details back to a server via the UART channel. This project was very beneficial because
I have never developed for embedded systems before. I feel that I did a fairly good job of properly integrating the peripherals, and I am happy with the effectiveness and simplicity of the code
I wrote. Moving forward, I am now more comfortable coding in C, which is not a language I have a ton of experience with. Additionally, I made it a focus for my code to be readable and maintainable.
Functions are abstracted and modularized so that the main thread does not contain too much code, and this would also help ensure that this code could be ported over to new systems seeking similar
functionality.
