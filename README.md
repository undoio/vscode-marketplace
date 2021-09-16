Undo's assets for Microsoft's Visual Studio Code marketplace
------------------------------------------------------------

Microsoft's Visual Studio Code marketplace [displays the contents of the `README.md` file in the extension package](https://code.visualstudio.com/api/references/extension-manifest#marketplace-presentation-tips). See, for example, the [Time Travel Debug for C/C++ extension](https://marketplace.visualstudio.com/items?itemName=Undo.udb).

There are two approaches to including images in the extension description: (i) include the images in the extension package and then "provide relative path image links in the `README.md`"; (ii) publish the images on the Internet and link them in the `README.md`. Approach (i) unnecessarily increases the size of the extension package and the download time; accordingly, we prefer approach (ii), with the images stored in this repository on GitHub and available via raw.githubusercontent.com.
