Class **Phalcon\\Forms\\Manager**
=================================

.. role:: raw-html(raw)
   :format: html

:raw-html:`<a href="https://github.com/dreamsxin/cphalcon7/blob/master/ext/forms/manager.c" class="btn btn-default btn-sm">Source on GitHub</a>`

Manages forms within the application. Allowing the developer to access them from any part of the application


Methods
-------

public  **__construct** ()

...


public :doc:`Phalcon\\Forms\\Form <Phalcon_Forms_Form>`  **create** ([*string* $name], [*object* $entity])

Creates a form registering it in the forms manager



public :doc:`Phalcon\\Forms\\Form <Phalcon_Forms_Form>`  **get** (*string* $name)

Returns a form by its name



public *boolean*  **has** (*string* $name)

Checks if a form is registered in the forms manager



public :doc:`Phalcon\\Forms\\Manager <Phalcon_Forms_Manager>`  **set** (*string* $name, :doc:`Phalcon\\Forms\\Form <Phalcon_Forms_Form>` $form)

Registers a form in the Forms Manager



