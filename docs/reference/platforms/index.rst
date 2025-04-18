.. _platform-support-key:

================
Platform support
================

.. toctree::
   :hidden:

   macOS/index
   windows/index
   linux/index
   iOS/index
   android/index
   web/index

+-----+-------------------------------------+
| |f| | Supported and tested in CI          |
+-----+-------------------------------------+
| |y| | Supported and tested by maintainers |
+-----+-------------------------------------+
| |v| | Supported but not tested regularly  |
+-----+-------------------------------------+


.. |Gradle| replace:: **Gradle project**
.. _Gradle: ./android/gradle.html

.. |iOS| replace:: **Xcode project**
.. _iOS: ./iOS/xcode.html

.. |AppImage| replace:: AppImage
.. _AppImage: ./linux/appimage.html

.. |Flatpak| replace:: Flatpak
.. _Flatpak: ./linux/flatpak.html

.. |System| replace:: **System package**
.. _System: ./linux/system.html

.. |macOSApp| replace:: **.app bundle**
.. _macOSApp: ./macOS/app.html

.. |Xcode| replace:: Xcode project
.. _Xcode: ./macOS/xcode.html

.. |Web| replace:: **Static**
.. _Web: ./web/static.html

.. |WindowsApp| replace:: **Windows app**
.. _WindowsApp: ./windows/app.html

.. |VisualStudio| replace:: Visual Studio project
.. _VisualStudio: ./windows/visualstudio.html

+---------+-----------------+--------+-------+---------+--------+---+-----+--------+-----+-------+
| Target App Format         | Host System                                                        |
+                           +--------+-------+---------+--------+---+-----+--------+-----+-------+
|                           | macOS          | Windows              | Linux                      |
+                           +--------+-------+-----+--------+-------+-----+--------+-----+-------+
|                           | x86‑64 | arm64 | x86 | x86‑64 | arm64 | x86 | x86‑64 | arm | arm64 |
+=========+=================+========+=======+=====+========+=======+=====+========+=====+=======+
| Android | |Gradle|_       | |f|    | |f|   |     | |f|    |       | |v| | |f|    | |v| | |v|   |
+---------+-----------------+--------+-------+-----+--------+-------+-----+--------+-----+-------+
| iOS     | |iOS|_          | |f|    | |f|   |     |        |       |     |        |     |       |
+---------+-----------------+--------+-------+-----+--------+-------+-----+--------+-----+-------+
| Linux   | |AppImage|_     | |v|    | |v|   |     |        |       | |v| | |v|    | |v| | |v|   |
+         +-----------------+--------+-------+-----+--------+-------+-----+--------+-----+-------+
|         | |Flatpak|_      |        |       |     |        |       | |v| | |f|    | |v| | |f|   |
+         +-----------------+--------+-------+-----+--------+-------+-----+--------+-----+-------+
|         | |System|_       | |y|    | |y|   |     |        |       | |v| | |f|    | |v| | |f|   |
+---------+-----------------+--------+-------+-----+--------+-------+-----+--------+-----+-------+
| macOS   | |macOSApp|_     | |f|    | |f|   |     |        |       |     |        |     |       |
+         +-----------------+--------+-------+-----+--------+-------+-----+--------+-----+-------+
|         | |Xcode|_        | |f|    | |f|   |     |        |       |     |        |     |       |
+---------+-----------------+--------+-------+-----+--------+-------+-----+--------+-----+-------+
| Web     | |Web|_          | |f|    | |f|   | |v| | |f|    | |v|   | |v| | |f|    | |v| | |f|   |
+---------+-----------------+--------+-------+-----+--------+-------+-----+--------+-----+-------+
| Windows | |WindowsApp|_   |        |       |     | |f|    |       |     |        |     |       |
+         +-----------------+--------+-------+-----+--------+-------+-----+--------+-----+-------+
|         | |VisualStudio|_ |        |       |     | |f|    |       |     |        |     |       |
+---------+-----------------+--------+-------+-----+--------+-------+-----+--------+-----+-------+
