.. meta::
    :description: Explanation of Dedicated Snap Store concepts and architecture, including custom application stores for software distribution across device fleets with secure over-the-air updates.

Explanation
===========

A Dedicated Snap Store is a custom application store tailored to software
distribution across fleets of devices. This store allows you to create, publish
and distribute software on one centralized platform, with reliable over-the-air
updates to your devices in a secure and validated way. Dedicated Snap Stores are
adopted by a large number of enterprises around the world, with a variety of IoT
use cases. It is the private, enterprise equivalent of the global Snap Store.

The following documents provide more information on Dedicated Snap Stores,
including information on interfaces and general store security.

.. list-table::

    * - :doc:`explanation/base-stores-and-device-view-stores`
      - What are the differences between base stores and device view stores?
    * - :doc:`explanation/brand-accounts`
      - What is a brand account?
    * - :doc:`explanation/managing-an-app-store`
      - What snaps can I include, and can I monitor devices?
    * - :doc:`explanation/security`
      - What credentials does my store contain, and how are they managed?
    * - :doc:`explanation/snap-inclusion`
      - Can I decide what snaps are available in my store?

.. rubric:: Related Ubuntu Core and snapd topics

.. list-table::

    * - :doc:`explanation/connecting-devices`
      - How does an Ubuntu Core device connect to a Dedicated Snap Store?
    * - :doc:`explanation/controlling-updates`
      - How can snap updates be controlled on connected devices?
    * - :doc:`explanation/snapd-interface-connections`
      - How do snapd interface connections and reviews affect published snaps?

.. rubric:: Helpful resources

For more information, please see the following:

* `Dedicated Snap Stores <https://ubuntu.com/internet-of-things/appstore>`_
* `Dedicated Snap Store Datasheet <https://assets.ubuntu.com/v1/d6d1d3fc-IoT+App+Store+Datasheet+v3.pdf>`_

.. toctree::
   :maxdepth: 1
   :glob:
   :hidden:

   explanation/*
