# File-Transfer-Program
这是一个在本地运行的，包含client，server和cache的文件传输程序实例。可以让client端做到对server端文件的增删改查。其中cache负责对文件进行缓存以提高读取相同文件的效率。

# The following are the functions I have completed:
1) A batch file for running the program.
2) A GUI interface that allows the user to display the list of files that are available on the
server.
3) A GUI interface that allows the user to select a file from the list of available files to
download.
4) A GUI interface that allows the user to display the contents of the downloaded file.
5) If the user requests for a file that has the same name as a previously downloaded file, the
cached copy of the file should be returned to the user.
6) A GUI interface for viewing the cache's log and the log is kept correctly.
7) A GUI interface for clearing the contents of the cache and the content can be cleared
correctly.
8) A GUI interface for viewing the list of cached files and the list is kept correctly.

# Operation method introduction:
When opening the folder, we can see a click_me.bat file, and double-click it to runit. At this time, two GUI interfaces will appear, one of which is the server interface from the administrator's perspective, and the other is the client interface from the user's perspective. As an administrator, you must first start the server, and then the user can operate the file on the client side. Please note that all the following client-side operation responses may have a certain delay, about 4~5s. Please wait patiently for the response to the request. After we click the get available files button, we can get the list of files available on the server. Of course, as an administrator, we can add new files to the available list at any time in the select file on the server. We can select a file in the list and click download file to download the file content and display it in the text box. We can see all the log records we downloaded through open cache, and the log contents include the cleaning date of the file and where the file was downloaded. In the GUI interface of cache, we can also see the list of files that have been cached in cache.
