===========
Availablity
===========


Source Code
-----------
Source code for converting RE datasets to RDF is available on our `Github repository <https://github.com/dice-group/RELD>`_ . 
The requirments for running the code, and the basic commond to rund the code are given on the README file.


Live Endpoint
-------------

The `live endpoint <http://reld.cs.upb.de:8890/sparql>`_ of **RELD** is available for querying anywhere on the internet. 
We have made it available on the Virtuoso open-source server.The endpoint might result in slow query execution. 
In the meanwhile, you can also `download <https://hobbitdata.informatik.uni-leipzig.de/RELD/endpoint/>`_ and run a local instance of the endpoint. 
The prepared endpoint is available here in zip format.To run the local instance you just need to run simple commands, 
and your local endpoint in Virtuoso is running.

.. code-block:: bash

    wget https://hobbitdata.informatik.uni-leipzig.de/RELD/endpoint/reld.virtuoso-7.2.5-linux-v2.zip
    unzip reld.virtuoso-7.2.5-linux-v2.zip
    cd reld.virtuoso-7.2.5-linux-v2/bin
    sh start_virtuoso.sh


Static Dumps
------------

The different versions of the dumps is available for `downloads <https://hobbitdata.informatik.uni-leipzig.de/RELD/ttl_dumps/>`_. 
The dumps are in .ttl and JSON-LD formats. The ttl files names are self-descriptive. Each file represents an individual dataset converted to RDF.
Same file names can be used during querying on our live endpoint.



Public Availability
-------------------
The resource is publicaly available on the community registery with a unique DOI: `10.5281/zenodo.7429677`
on Zenodo `here <https://zenodo.org/record/7429677#.Y6lt1dLMJuU>`_. 




Sustainability
--------------
The resource is publicly available from the homepage, which contains the com-
plete source code, data, and documentation. The homepage also links to the corresponding RELD ontology. 
The same homepage will be used for sustainability and adding future datasets
into the RELD. Paderborn Center for Parallel Computing PC2 will sustain the RELD resources. 
PC2 provides computing resources and consultation regarding their usage; to research projects at Paderborn University 
and external research groups. The Information and Media Technologies
Center (IMT) at Paderborn University also provides a permanent IT infrastructure to host the RELD project. 
The open-source code available on GitHub is easily extendable to convert other datasets in the future. 
The RELD dataset is publicly available from the SPARQL endpoint, where the user can execute a
SPARQL query for desired output.


License
-------
RELD is under the licence GNU General Public License v3.0. The `licence <https://github.com/dice-group/RELD/blob/main/LICENSE>`_ is hosted on our Github repository.