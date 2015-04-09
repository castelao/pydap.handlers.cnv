=================
PyDAP.Handler.CNV
=================


On my machine I was able to:::

    pip install pydap.handlers.cnv
    paster create -t pydap myserver
    paster serve ./myserver/server.ini

Than I copied some CTD data files into ./myserver/data, and that's all. That CTD data is now available at http://localhost:8001/    
