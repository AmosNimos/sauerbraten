How to host a lan server?
~~~
echo "Step-1: Install the server package"
sudo apt install sauerbraten-server

echo "Step-2: Create a server"
sauerbraten-server -nMY_DESCRIPTION -c5 -mmasterserver
echo "Note: You can add a password by adding -yYOUR_PASSWORD to the command"
~~~

3. lunch sauerbraten
~~~
sauerbraten
~~~

4. connect client to server
~~~
/connect YOUR_LOCAL_IP
~~~

/map MAP_NAME
