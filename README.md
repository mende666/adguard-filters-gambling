<!DOCTYPE html>
<html>
<head>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f4f7f9;
    padding: 40px;
    color: #333;
    line-height: 1.6;
  }

  .container {
    max-width: 900px;
    margin: auto;
    background-color: #ffffff;
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    padding: 30px 50px;
  }

  .header-section {
    text-align: center;
    margin-bottom: 40px;
  }

  .header-section h1 {
    color: #1e88e5;
    font-size: 2.8em;
    margin-bottom: 5px;
  }

  .header-section .subtitle {
    font-style: italic;
    color: #555;
    font-size: 1.1em;
  }

  .intro-text {
    font-size: 1.1em;
    color: #444;
    padding-bottom: 20px;
    border-bottom: 2px solid #e0e6ed;
    margin-bottom: 30px;
  }

  h2 {
    color: #1e88e5;
    border-bottom: 2px solid #e0e6ed;
    padding-bottom: 8px;
    margin-top: 40px;
    margin-bottom: 20px;
    font-size: 1.8em;
  }

  .feature-list, .installation-list, .usage-list, .contributing-list {
    list-style: none;
    padding: 0;
  }

  .feature-list li, .installation-list li, .usage-list li, .contributing-list li {
    background-color: #e3f2fd;
    border-left: 5px solid #1e88e5;
    margin-bottom: 15px;
    padding: 15px;
    border-radius: 8px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  
  .feature-list li:hover, .installation-list li:hover, .usage-list li:hover, .contributing-list li:hover {
    transform: translateX(5px);
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  }

  .feature-list li strong, .installation-list li strong, .usage-list li strong, .contributing-list li strong {
    color: #1565c0;
    font-weight: 700;
  }

  .link-style {
    color: #1e88e5;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
  }

  .link-style:hover {
    color: #ff9800;
  }

  code {
    background-color: #e0e0e0;
    padding: 2px 6px;
    border-radius: 4px;
    font-family: 'Courier New', Courier, monospace;
  }

  .final-text {
    margin-top: 30px;
    color: #555;
  }
</style>
</head>
<body>

  <h2>Features</h2>
  <ul class="feature-list">
    <li><strong style="font-size:1.1em;">UI Clutter:</strong> Hides scrolling text, cleans up inactive interface elements, & removes social media links.</li>
    <li><strong style="font-size:1.1em;">Advertisements:</strong> Eliminates embedded videos, promotional call-to-action buttons, & other advertisements.</li>
    <li><strong style="font-size:1.1em;">Pop-ups & Banners:</strong> Gets rid of site-wide announcements, information banners, & other floating or sticky elements.</li>
  </ul>

  <h2>Installation</h2>
  <ol class="installation-list">
    <li>Download <code>adguard-gambling-filter.txt</code> from this repo or copy its raw link.</li>
    <li>Open AdGuard (Chrome extension or app).</li>
    <li>Go to <strong>Filters > Custom Filters</strong>.</li>
    <li>Add a new filter by uploading the file or pasting the URL.</li>
  </ol>

  <h2>Usage</h2>
  <ul class="usage-list">
    <li>After installing the filter, make sure it is enabled in AdGuard’s Custom Filters.</li>
    <li>The filter will automatically block gambling sites and related ads/pop-ups as you browse.</li>
    <li>To get updates, check this repo regularly and re-import the latest version, or use the filter’s raw URL for automatic updates.</li>
    <li>If you notice a gambling site that is not blocked, or something gets blocked that shouldn’t, please <a href="https://github.com/mende666/adguard-filters-gambling/issues" class="link-style">open an issue</a>.</li>
    <li>You can disable the filter at any time from the AdGuard settings if needed.</li>
  </ul>

  <h2>Contributing</h2>
  <ul class="contributing-list">
    <li><a href="https://github.com/mende666/adguard-filters-gambling/issues" class="link-style">Opening an issue</a> for missed gambling sites, false positives, or suggestions.</li>
    <li>Submitting a pull request with new filter rules or fixes.</li>
    <li>Following the format of existing rules for consistency.</li>
    <li>Providing clear information about the site or issue you are reporting.</li>
  </ul>
  <p class="final-text">Thank you for helping to make this blocklist better for everyone!</p>

  <h2>License</h2>
  <p>This project is licensed under the MIT License.<br>
  See the <a href="./LICENSE" class="link-style">LICENSE</a> file for details.</p>

  <h2>Contact</h2>
  <p>For support, suggestions, or to report issues, please use the <a href="https://github.com/mende666/adguard-filters-gambling/issues" class="link-style">Issues</a> tab on GitHub.</p>

</div>

</body>
</html>
