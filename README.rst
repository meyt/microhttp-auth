microhttp-auth
==============

Role based JWT stateless/ful authentication module for
`microhttp <https://github.com/meyt/microhttp>`_.



Install
-------


.. code-block:: bash

    pip install microhttp-auth

Note: Need to setup ``redis`` database, if using stateful authenticator.


Configuration
-------------

.. code-block:: yaml

    auth:
      jwt_secret_key: <SECRET_KEY>
      jwt_algorithm: # Algorithm supported by pyjwt
      redis:  # Redis configuration [optional]
        host:
        port:
