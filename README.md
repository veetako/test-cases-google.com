
<h2>Test Cases</h2>

<table>
  <thead>
    <tr>
      <th style="min-width: 200px;">Test Case ID</th>
      <th>Title</th>
      <th>Description</th>
      <th>Precondition</th>
      <th>Steps</th>
      <th>Expected Result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TC-001</td>
      <td>Search returns results</td>
      <td>Verify that entering a valid search term returns a relevant results page</td>
      <td>User is on homepage</td>
      <td>1. Open google.com<br>2. Type "table"<br>3. Press Enter</td>
      <td>A page with search results is shown</td>
    </tr>
    <tr>
      <td>TC-002</td>
      <td>Autocompletion suggestions</td>
      <td>Check if suggestions work as intended</td>
      <td>User is on homepage</td>
      <td>1. Open google.com<br>2. Type "tabl"</td>
      <td>Suggestions related to "tabl" appeared</td>
    </tr>
    <tr>
      <td>TC-003</td>
      <td>“I’m Feeling Lucky” button functionality</td>
      <td>Check if "I'm Feeling Lucky" button works</td>
      <td>User is on homepage</td>
      <td>1. Open google.com<br>2. Type "YouTube"<br>3. Click "I'm Feeling Lucky"</td>
      <td>User is redirected to the top search result</td>
    </tr>
    <tr>
      <td>TC-004</td>
      <td>Search bar handles empty input</td>
      <td>Check if search bar properly handles the empty input</td>
      <td>User is on homepage</td>
      <td>1. Open google.com<br>2. Leave the search field empty<br>3. Press Enter or click the search button</td>
      <td>No search is performed. The page stays on the homepage or reloads with no results shown.</td>
    </tr>
    <tr>
      <td>TC-005</td>
      <td>“Sign In” button redirects to login page</td>
      <td>Check if user is able to login and sign in button redirects to the accounts page</td>
      <td>User is on the homepage as a guest</td>
      <td>1. Open google.com<br>2. Click on the “Sign In” button (top right corner)</td>
      <td>User is redirected to the accounts.google.com</td>
    </tr>
    <tr>
      <td>TC-006</td>
      <td>Search bar handles long input gracefully</td>
      <td>Check if search bar correctly handles long input without breaking UI and crashing</td>
      <td>User is on the homepage</td>
      <td>1. Open google.com<br>2. Type a string of 1,000 random characters into the search field<br>3. Press Enter</td>
      <td>Google processes the input without crashing or error. UI remains functional.</td>
    </tr>
    <tr>
      <td>TC-007</td>
      <td>Voice Search icon</td>
      <td>Verify that clicking the microphone icon triggers the voice search prompt</td>
      <td>User is on the homepage</td>
      <td>1. Open google.com<br>2. Click on the microphone icon</td>
      <td>Browser prompts for microphone permission (if not granted) or starts voice input</td>
    </tr>
    <tr>
      <td>TC-008</td>
      <td>Footer Privacy link</td>
      <td>Verify that the Privacy link opens the correct Privacy Policy page</td>
      <td>User is on the homepage</td>
      <td>1. Open google.com<br>2. Scroll down to the footer<br>3. Click "Privacy" link</td>
      <td>Google Privacy Policy page is opened</td>
    </tr>
    <tr>
      <td>TC-009</td>
      <td>Homepage layout adapts to mobile screen size</td>
      <td>Verify that the Google homepage layout adjusts correctly on smaller screen sizes</td>
      <td>User opens Google homepage on a mobile device</td>
      <td>1. Open google.com<br>2. Resize the browser to width &lt;768px (or open on phone)<br>3. Observe layout</td>
      <td>UI is still usable and readable</td>
    </tr>
    <tr>
      <td>TC-010</td>
      <td>Clicking the Google logo returns to homepage</td>
      <td>Verify that clicking the Google logo on a results page navigates the user back to the homepage</td>
      <td>User is on the search results page after performing a search</td>
      <td>1. Open google.com<br>2. Search for "QA engineer"<br>3. On the results page, click the Google logo (top-left)</td>
      <td>User is returned to the Google homepage</td>
    </tr>
  </tbody>
</table>
