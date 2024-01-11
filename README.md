# bunkerbuddytinyllama

Install UserLand linux terminal on your phone from play store. Its free
I choose Ubuntu from the menu to get going.
sudo apt-get update
sudo apt-get install ca-certificates
sudo apt-get install screen 

CTRL+a then press c to switch between terminals.
First Terminal:
curl https://ollama.ai/install.sh | sh
echo 'export OLLAMA_ORIGINS="*"' >> ~/.bashrc
After adding the line, you'll need to reload the .bashrc file or restart your terminal session for the changes to take effect:
Ollama serve

Second Terminal:
CTRL+a then press c to switch back to your chat terminal
ollama run tinyllama

DONE.
A fully local chatbot that now runs without internet. More to come and better use cases. 

https://www.youtube.com/watch?v=jQfRyDeT398&t=12s&ab_channel=EoinTolster
