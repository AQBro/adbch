<!DOCTYPE html>
<html lang="en">
<head>
   <h1>Script Installation Guide</h1>

<p>Welcome! Follow these steps to set up and run the script on Termux.</p>

<h2>Prerequisites</h2>

<p>Ensure you have Termux installed on your Android device. If not, download and install it from the following link:</p>

<p class="center">
  <a href="https://f-droid.org/repo/com.termux_1020.apk" target="_blank" class="btn">
    Download Termux
  </a>
</p>

<h2>Installation Steps</h2>

<p>After installing Termux, follow these steps to set up the script:</p>

<ol>
  <li>
    <strong>Update and Upgrade Packages</strong>
    <p>Open Termux and run:</p>
    <pre><code>pkg update && pkg upgrade</code></pre>
  </li>
  <li>
    <strong>Install Git</strong>
    <p>Install Git by running:</p>
    <pre><code>pkg install git && pkg install php</code></pre>
  </li>
  <li>
    <strong>Clone the Repository</strong>
    <p>Clone the script repository:</p>
    <pre><code>git clone https://github.com/AQBro/adbch</code></pre>
  </li>
  <li>
    <strong>Navigate to the Script Directory</strong>
    <p>Change to the script directory:</p>
    <pre><code>cd script</code></pre>
  </li>
  <li>
    <strong>Run the Script</strong>
    <p>Finally, run the script using PHP:</p>
    <pre><code>php bot.php</code></pre>
  </li>
</ol>

<hr>

</body>
</html>
