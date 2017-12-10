# Zeppelindex 

## Abstract
Zeppelindex is a Web application that provides an index of [Apache Zeppelin](https://zeppelin.apache.org/) notebooks.

## Issues this Product Tackles with
* On the current version (i.e. 0.7.3) of Apache Zeppelin, it is difficult for administrators of Apache Zeppelin to monitor the status of the use of Apache Zeppelin by general users because administrators cannot see all of notebooks unless every general user permits them to read her/his notebooks.
* It is also difficult for general users to monitor the status of the use of the notebooks when there are a lot of notebooks that they can access.

## Solutions
* This product makes an index of notebooks and provides it to both administrators and general users as a form of a Web application.
* This product provides optional LDAP authentication and authorization functionality to distinguish between administrators and general users.
    * Administrators can see the status of all of the notebooks
    * General users can only see the status of the notebooks that they can access.
