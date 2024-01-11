# Chat Buddy
A chatbot I made for my 8th-grade science fair

This chatbot is geared towards explaining thought process while helping with educational questions, kind of like an open source Khanmigo

For the model, run the command: ```wget https://huggingface.co/TheBloke/zephyr-7B-beta-GGUF/resolve/main/zephyr-7b-beta.Q8_0.gguf``` If you have 16 GB of VRAM or normal RAM

If you only have 8 GB of RAM/VRAM run this command: ```wget https://huggingface.co/TheBloke/zephyr-7B-beta-GGUF/resolve/main/zephyr-7b-beta.Q4_K_M.gguf```, and then change the model to ```zephyr-7b-beta.Q4_K_M.gguf```

The model is [@TheBloke's](https://huggingface.co/TheBloke) quantizations of Zephyr 7B, which is currently the best-performing small model.
