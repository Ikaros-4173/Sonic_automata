# sonic_automata
Cree en el mundo de sonic usando gym un controlador que mueva al jugador utilizando un autómata finito determista o un autómata de pila.   Entregables Código del controlador, Demostración Imágenes de la representación del autómata.  Deben importar el archivo MD y el archivo sonic.py.

Pasos a seguir.

virtualenv -p python3 env
source env/bin/activate
pip install gym-retro==0.7.0
pip install gym==0.12.1
pip install imutils==0.5.2
pip install numpy==1.16.3
pip install opencv-python==4.1.0.25
pip install pygame==1.9.6
pip install python-statemachine
python -m retro.import
python sonic.py
