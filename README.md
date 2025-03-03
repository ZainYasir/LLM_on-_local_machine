# LLM ON LOCAL MACHINE 
To run 1st download your model in .gguf format You can Download it from Hugging face </br>
after downloading build your enviroment/engine ,I build it already</br>
you may need C++ complier in your system and some dependencies</br></br>
##Dependencies
✅ MSVC v142 - VS 2019 C++ x64/x86 build tools</br>
✅ Windows 10 SDK </br>
✅ C++ CMake Tools for Windows </br></br>

If my build doesnt run downalaod Llama.cpp-master</br>
Then open cmd and write " cmake .. " in your llama.cpp-master/build directory</br>
If build was succcessful goto Llama.cpp-master\build\release\Llama-run.exe <model_path> <prompt></br></br>

Till 1st commit no use of .json file </br>
Model: tinyllama-1.1b-chat-v1.0.Q4_K_M </br>
Engine : Llama.cpp-master </br>
build: Llama.cpp-master\build\release\Llama-run.exe </br>
