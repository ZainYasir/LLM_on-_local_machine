# LLM ON LOCAL MACHINE 
To run 1st download your model in .gguf format. You can Download it from Hugging face </br>
after downloading build your enviroment/engine, I built it already</br>
you may need C++ complier in your system and some dependencies</br></br>
# Dependencies</br>
✅ MSVC v142 - VS 2019 C++ x64/x86 build tools</br>
✅ Windows 10 SDK </br>
✅ C++ CMake Tools for Windows </br></br>

If my build doesnt run, downalaod Llama.cpp-master</br></br>
# 🔹 Why Llama.cpp?</br>
1️⃣ Runs on CPU – No need for a high-end GPU. It’s optimized for CPU inference using GGML/GGUF quantization, which reduces model size while maintaining performance.</br>
2️⃣ Lightweight & Fast – Compared to traditional PyTorch models, it runs with lower memory usage and better efficiency.</br>
3️⃣ Supports RAG (Retrieval-Augmented Generation) – This is crucial for personalizing the chatbot with external knowledge.</br>
4️⃣ Fine-tuning & Customization – Allows you to tweak model behavior and responses.</br>
5️⃣ C++ Backend – It’s faster than Python-based alternatives like LlamaIndex for inference</br>
Then open cmd and write " cmake .. " in your llama.cpp-master/build directory you may need to creaet build folder manually </br></br></br>
If build was succcessful goto Llama.cpp-master\build\release\Llama-run.exe <model_path> <prompt></br></br>

# 🚀 How Llama.cpp and .gguf model like TinyLlama Work Together</br>
✅ Llama.cpp is the engine (software) that loads and runs models like TinyLlama (pre-trained AI model).</br>
✅ TinyLlama is the brain, while Llama.cpp is the body that makes it function smoothly on your PC.</br></br>

Till 1st commit no use of .json file </br>
Model: tinyllama-1.1b-chat-v1.0.Q4_K_M </br>
Engine : Llama.cpp-master </br>
build: Llama.cpp-master\build\release\Llama-run.exe </br>
