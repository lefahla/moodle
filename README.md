# moodle
<h4>MOH moodle training instances</h4>
  
<h2>A. Setting up a moodle training instance</h2>
Assuming you have installed docker and docker-compose on your host machine, follow the steps below. 
<ol>
  <li>Clone this repo.<pre><code>git clone https://github.com/lefahla/moodle-docker.git</code></pre></li>
  <li>Navigate to the moodle directory<pre><code>cd moodle-docker</code></pre></li>
  <li><pre><code>docker-compose docker-compose.yml up -d</code></pre></li>
  <li>When both containers are up, a base moodle instance should be accessible at: <pre><code>http://ip-address</code></pre>
    <li>
    Defaults:
    <br/>
    Teacher :
      <table>
        <tr><td>Username</td><td>Password</td></tr>        
        <tr><td>nthako</td><td>Thabonthako@1</td></tr>
      </table>
    </li>
    <li>
      <br/>
    Student :
      <table>
        <tr><td>Username</td><td>Password</td></tr>        
        <tr><td>student</td><td>Demo@1234</td></tr>
      </table>
    </li>
  </li>

</ol>
