How to host a lan server?
~~~system terminal:
echo "Step-1: Install the server package"
sudo apt install sauerbraten-server

echo "Step-2: Create a server"
sauerbraten-server -nMY_DESCRIPTION -c5 -mmasterserver
echo "Note: You can add a password by adding -yYOUR_PASSWORD to the command"
~~~

3. Lunch sauerbraten
~~~system terminal:
sauerbraten
~~~

4. Connect client to server
> You can also do it manually from the game UI.
~~~in-game terminal:
/connect YOUR_LOCAL_IP
~~~

5 Load map
~~~in-game terminal:
/map MAP_NAME
~~~
