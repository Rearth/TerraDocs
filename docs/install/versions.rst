========
Versions
========

.. toctree::
    :hidden:
    :glob:

    versions/legacy/*/*

On this page you can find the latest releases of Terra for each platform & Minecraft version.

.. warning::

    \*Releases labelled :bdg-secondary:`In Development` are strictly available for previewing and development only.
    You should not use any of these releases in production as they may be unstable and subject to changes.

.. _fabric-versions:

Fabric
------

All releases of Fabric Terra can be found on Modrinth `here <https://modrinth.com/mod/terra/versions>`__.

:doc:`Fabric Installation </install/fabric>` :octicon:`chevron-right`

.. list-table::
    :header-rows: 1
    
    *
        - Minecraft Version [1]_
        - Latest Terra Version [2]_
        - Supported [3]_
        - Maintained [4]_
        - Download [5]_
        - Backwards Compatibility [6]_

    *
        - **1.20**
        - 6.3.1 :bdg-warning:`Beta`
        - :bdg-success:`Yes`
        - :bdg-success:`Yes`
        - `Modrinth <https://modrinth.com/plugin/terra/version/6.3.1-BETA-fabric/>`__
        - N/A

    *
        - **1.19**
        - 6.3.0 :bdg-warning:`Beta`
        - :bdg-success:`Yes`
        - :bdg-danger:`No`
        - `Modrinth <https://modrinth.com/plugin/terra/version/6.3.0-BETA-fabric/>`__
        - N/A

    *
        - **1.18**
        - 6.1.1 :bdg-warning:`Beta`
        - :bdg-danger:`No`
        - :bdg-danger:`No`
        - `Modrinth <https://modrinth.com/mod/terra/version/6.1.1-BETA/>`__
        - N/A

    *
        - **1.17**
        - 5.4.1 :bdg-warning:`Beta`
        - :bdg-danger:`No`
        - :bdg-danger:`No`
        - :doc:`Modrinth <versions/legacy/fabric/5.4.1>`
        - N/A

    *
        - **1.16.5**
        - 5.3.3 :bdg-warning:`Beta`
        - :bdg-danger:`No`
        - :bdg-danger:`No`
        - :doc:`Modrinth <versions/legacy/fabric/5.3.3>`
        - N/A

.. _bukkit-versions:

Bukkit
------

All releases of Bukkit Terra can be found on Modrinth `here <https://modrinth.com/mod/terra/versions>`__.

:doc:`Bukkit Installation </install/bukkit>` :octicon:`chevron-right`

.. list-table::
    :header-rows: 1

    *
        - Minecraft Version [1]_
        - Latest Terra Version [2]_
        - Supported [3]_
        - Maintained [4]_
        - Download [5]_
        - Backwards Compatibility [6]_

    *
        - **1.20**
        - 6.3.1 :bdg-warning:`Beta`
        - :bdg-success:`Yes`
        - :bdg-success:`Yes`
        - `Modrinth <https://modrinth.com/mod/terra/version/6.3.1-BETA-bukkit>`__
        - N/A

    *
        - **1.19**
        - 6.3.0 :bdg-warning:`Beta`
        - :bdg-success:`Yes`
        - :bdg-danger:`No`
        - `Modrinth <https://modrinth.com/mod/terra/version/6.3.0-BETA-bukkit>`__
        - N/A

    *
        - **1.18**
        - 6.1.2 :bdg-warning:`Beta`
        - :bdg-danger:`No`
        - :bdg-danger:`No`
        - `SpigotMC <https://www.spigotmc.org/resources/terra.85151/download?version=456104/>`__
        - N/A

    *
        - **1.17**
        - 5.4.1 :bdg-warning:`Beta`
        - :bdg-danger:`No`
        - :bdg-danger:`No`
        - :doc:`Modrinth <versions/legacy/bukkit/5.4.1>`
        - N/A

    *
        - **1.16.5**
        - 5.3.3 :bdg-warning:`Beta`
        - :bdg-danger:`No`
        - :bdg-danger:`No`
        - :doc:`Modrinth <versions/legacy/bukkit/5.3.3>`
        - 1.13+

.. note::

    Lots of people get confused about what the difference is between Bukkit, Spigot, and Paper.

    **Bukkit** is an API, a way for developers to interface with and write plugins
    for the Minecraft server.

    **Spigot** is an *implementation* of the Bukkit API, It's a platform that allows the Minecraft
    server to load and run Bukkit plugins. Bukkit itself is no longer maintained by the Bukkit team,
    so now SpigotMC maintains both Bukkit (the API) and Spigot (the implementation).

    **Paper** is a *fork* of Spigot, a project based on Spigot that extends It's functionality. Paper
    adds many performance optimizations to the Minecraft server, and also extends the Bukkit API.

    **What does this have to do with Terra?**

    We refer to the entire Bukkit ecosystem (Bukkit API, Spigot, Paper and friends..) as *Bukkit*
    simply because Bukkit is the name of the API. **However** - Terra develops against and tests on
    Paper. We do this because Bukkit and Spigot simply do not expose the required API for Terra to
    be fully functional. Paper's extended API does. This means that while Terra will still *work*
    on Spigot, there will be (important) features missing.

    **TL;DR - Use Paper, or a fork of Paper.**

.. _forge-versions:

Forge
-----

All releases of Forge Terra can be found on Modrinth `here <https://modrinth.com/mod/terra/versions>`__.

.. list-table::
    :header-rows: 1

    * 
        - Minecraft Version [1]_
        - Latest Terra Version [2]_
        - Supported [3]_
        - Maintained [4]_
        - Download [5]_
        - Backwards Compatibility [6]_

    *
        - **1.19**
        - 6.2.1 :bdg-danger:`Alpha`
        - :bdg-success:`Yes`
        - :bdg-danger:`No`
        - `Modrinth <https://modrinth.com/mod/terra/version/6.2.1-BETA-forge>`__
        - N/A

    *
        - **1.16.5**
        - 5.3.3 :bdg-danger:`Alpha`
        - :bdg-danger:`No`
        - :bdg-danger:`No`
        - :doc:`Modrinth <versions/legacy/forge/5.3.3>`
        - N/A

.. _quilt-versions:

Quilt
-----

All releases of Quilt Terra can be found on Modrinth `here <https://modrinth.com/mod/terra/versions>`__.

.. list-table::
    :header-rows: 1

    *
        - Minecraft Version [1]_
        - Latest Terra Version [2]_
        - Supported [3]_
        - Maintained [4]_
        - Download [5]_
        - Backwards Compatibility [6]_

    *
        - **1.19**
        - 6.2.1 :bdg-danger:`Alpha`
        - :bdg-success:`Yes`
        - :bdg-danger:`No`
        - `Modrinth <https://modrinth.com/mod/terra/version/6.2.1-BETA-quilt>`__
        - N/A

Definitions
===========

.. [1] **Minecraft Version** - The vanilla Minecraft version for the relevant platform.

.. [2] **Latest Terra Version** - The latest Terra version supporting the corresponding Minecraft version.  

.. [3] **Supported** - Whether or not you will receive official support for using the release.

.. [4] **Maintained** - Whether or not new Terra releases will be developed for the corresponding Minecraft version.

.. [5] **Download** - Downloads for the latest Terra version for the corresponding Minecraft version.

.. [6] **Backwards Compatibility** - Some releases of Terra are backwards compatible with older versions of Minecraft, the oldest of which is listed under this column. This however does not guarantee backwards compatibility of config packs shipped with the release.

