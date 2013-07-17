Bootstrap Modal - Strict Close extension
====================

An extension of the Bootstrap Modal script to prevent accidentally closing the modal when, for example, filling in a form.

To use, include the `bootstrap-modal-strict-close.js` script in your HTML and add the `data-strict-close="true"` attribute:

`<button type="button" data-toggle="modal" data-strict-close="true" data-target="#myModal" class="btn btn-primary">Launch modal</button>`

You can also do this programmatically by passing an object to the `modal()` method:

`$('#myModal').modal({ strictClose: true });`

This will disable closing the modal by clicking outside of it. It will instead only close by clicking on an element with the `data-dismiss` attribute. This typically is a *close* button.



Credits
-------

This repository includes styles and scripts from the Twitter Bootstrap project, which is released under the Apache License, Version 2.0.

Contribute
----------

Feel free to submit pull requests, advice or suggestions. @ontolecabaret

Copyright and license
---------------------

    Copyright (C) 2013 Joris Ooms

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the `LICENSE` file, or at:

  [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
