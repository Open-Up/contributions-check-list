# Ideas of contributions

## Apache James

![James logo](http://james.apache.org/images/logos/james-logo.png)

[Apache James server](http://james.apache.org/#third) is a modern email server under heavy development. Learn about emails, backend, Java, etc...

Here is a selection of some [easy contributions](https://issues.apache.org/jira/issues/?jql=project%20%3D%20JAMES%20AND%20resolution%20%3D%20Unresolved%20AND%20labels%20%3D%20newbie%20ORDER%20BY%20priority%20DESC%2C%20updated%20DESC).

**REST API for administration**

 - Error handling in a REST API https://issues.apache.org/jira/browse/JAMES-2314
 - Add a web API for document re-indexing https://issues.apache.org/jira/browse/JAMES-2152
 - Better display emails in WebAdmin https://issues.apache.org/jira/browse/JAMES-2321
 - REST API for clearing a mail queue https://issues.apache.org/jira/browse/JAMES-2319
 - Use of the TaskManager behind a REST API https://issues.apache.org/jira/browse/JAMES-2320

**Docker related tasks:**

 - Writing a missing dockerfile https://issues.apache.org/jira/browse/JAMES-2153
 - Document docker network usage instead of docker links https://issues.apache.org/jira/browse/JAMES-2333

**Mail processing**

- A little configuration fix https://issues.apache.org/jira/browse/JAMES-2211
 - Handles priority in mail processing https://issues.apache.org/jira/browse/JAMES-2279
 - A easy code refactoring about vacation mode https://issues.apache.org/jira/browse/JAMES-2256
 - Improve the logging mailet https://issues.apache.org/jira/browse/JAMES-2171

**Various topics**

 - Annotation processing and maven plugins https://issues.apache.org/jira/browse/JAMES-2325
 - Performance tuning and measurement https://issues.apache.org/jira/browse/JAMES-2210
 - Expose more configuration options for ActiveMQ https://issues.apache.org/jira/browse/JAMES-2168
 - JPA should fail gracefully when too long mailbox name https://issues.apache.org/jira/browse/MAILBOX-300
 
 **MIME**
 
  - NPE in MimeBoundaryInputStream.java:67 https://issues.apache.org/jira/browse/MIME4J-266
  - SingleBody should expose a getSize method. https://issues.apache.org/jira/browse/MIME4J-264
 
 **SIEVE**
 
  - Vacation and Reject might actually infinitly loop https://issues.apache.org/jira/browse/JSIEVE-104
  - REJECT notification might not be sent to mailing lists https://issues.apache.org/jira/browse/JSIEVE-105
  
  
 
 James team will offer guidance for these different tasks. Just open pull requests on https://github.com/apache/james-project .
