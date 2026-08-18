.. _model-service:

Configure Model Service
=======================

.. configure-model-service-start

.. warning:: 

	Example values are provided for store configuration in this document. If
	you are a Dedicated Snap Store customer, you will be provided with a set of
	documentation with the details of your store.

When following the instructions for configuring your Model Service, keep in mind
the following information:

* Your model name is: ``alpha``,
* Your Brand account email is: ``brand@acme.com``, and
* your Brand account ID is: ``brand-account``

The Model Service is accessed via the store dashboard at
https://snapcraft.io/admin, specifically at the below URLs:

* https://snapcraft.io/admin/acme-store/models
* https://snapcraft.io/admin/acme-id/signing-keys

On the “Signing keys” page, create a key which will be used for signing serial
assertions for devices. A common name for the key is “serial”.

In the “Models” page, create a new model ``alpha``. You may
provide your own API key, or generate one with the “Generate key” button.

Once a model has been added, select it and navigate to the “Policies” tab.
Create a new policy, selecting the serial key you created previously. Gadgets
using the Model Service should set their ``device-service.url`` configuration
value to https://api.snapcraft.io/v1/.

The explanation section provides some useful context for what a lot of the terms
you'll encounter when working with your Dedicated Snap Store mean.
