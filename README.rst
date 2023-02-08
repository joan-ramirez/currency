Currency
================================
Library to see the value of a currency in comparison with another, it accepts the change of all the currencies in the world.

Installation
------------

Add ``joan-ramirez/currency`` as a require dependency in your ``composer.json`` file:

.. code-block:: bash

    composer require joan-ramirez/currency

Usage
-----
Create a currency instance

.. code-block:: php

    use JoanRamirez/Currency/Currency;

    $currency = new Currency();
    
    
Get USD value converted to EUR ``change()->get()`` methods

.. code-block:: php

    $currency->change('USD', 'EUR')->get();   


Get the value of $100 USD converted to EUR with the ``amount()`` method

.. code-block:: php

    $currency->change('USD', 'EUR')->amount(100)->get();   


License
-------

Currency is licensed under the MIT license.
