
<div class="Box-body">
        <article class="markdown-body entry-content p-5" itemprop="text"><h1><a id="user-content-birdwatcher" class="anchor" aria-hidden="true" href="#SQL_Injection_Payload"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>SQL Injection  Vulnerability Payload List</h1>
<p>
        



<p>
          <a target="_blank" rel="noopener noreferrer" href="https://opensource.org/licenses/MIT"><img src="https://camo.githubusercontent.com/5d454a1a25b3f3d16a6a6301933cf1d1471704da/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f616e74692d64646f732f416e74692d44444f53" data-canonical-src="https://opensource.org/licenses/MIT" style="max-width:100%;"></a>
        <a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/13c4e50d88df7178ae1882a203ed57b641674f94/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f643733303566333864323966656437386661383536353265336136336531353464643865383832392f6d656469612f62616467652e737667"><img src="https://camo.githubusercontent.com/13c4e50d88df7178ae1882a203ed57b641674f94/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f643733303566333864323966656437386661383536353265336136336531353464643865383832392f6d656469612f62616467652e737667" data-canonical-src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" style="max-width:100%;"></a> 
           <a target="_blank" rel="noopener noreferrer" href="https://liberapay.com/slife/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg" data-canonical-src="https://liberapay.com/slife/donate" style="max-width:50%;"></a>
        



<b>Overview:</b>

A SQL injection attack consists of insertion or "injection" of a SQL query
via the input data from the client to the application. A successful SQL injection exploit
can read sensitive data from the database, modify database data (Insert/Update/Delete), 
execute administration operations on the database (such as shutdown the DBMS), recover the content of a
given file present on the DBMS file system and in some cases issue commands to the operating system.
SQL injection attacks are a type of injection attack, in which SQL commands are injected into data-plane input in order 
to effect the execution of predefined SQL commands.

<h2><a id="user-content-configuration" class="anchor" aria-hidden="true" href="#References"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>References</h2>


•	SQL Injection point_right https://www.owasp.org/index.php/SQL_Injection


<h2><a id="user-content-configuration" class="anchor" aria-hidden="true" href="#Download"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Download</h2>

<h5>Cloning an Existing Repository ( Clone with HTTPS )</h5>
<pre><code>
root@slife:~# git clone https://github.com/omurugur/SQL_Injection_Payload.git
</code></pre>
<h5>Cloning an Existing Repository ( Clone with SSH )</h5>
<pre><code>
root@slife:~# git clone git@github.com:omurugur/SQL_Injection_Payload.git
</code></pre>


<h2><a id="user-content-configuration" class="anchor" aria-hidden="true" href="#Contact"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Contact</h2>

<h5>Mail : omurugur12@gmail.com </h5>

<h5>Linkedin  : https://www.linkedin.com/in/omurugur-sibergüvenlik/ </h5>

<h5>GitHub  : https://github.com/omurugur </h5>

<h5>Twitter  : https://twitter.com/omurugurrr </h5>

<h5>Medium  : https://medium.com/@mruur </h5>

<h5>Donate!</h5>
</p>
Support the authors:
