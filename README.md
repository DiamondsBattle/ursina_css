# Ursina CSS

Ursina CSS extends your game possibilities by allowing your game to run in the user's browser, to extend game compatibilty.

You can simply code your game as a standard game* and then open ``start_server.bat`` (*Windows*) or open your terminal, navigate to your game directory and run ``python3 -m http.server <port>``.
If you do not specify the port, it will be by default 8000.
You then just need to open your browser to ``localhost:<port>`` and enjoy.

* You must include the ``ursina`` and the ``Brython-3.8.6`` in the root folder.