
<h1>🌍 Climate Action Pledge Microsite</h1>
<p>
This project is a responsive, interactive single-page web application that enables individuals to take a <strong>climate action pledge</strong>, instantly receive a personalized certificate, and get featured on a public pledge wall. The site also displays live community impact metrics.
</p>

<h2>✨ Key Features</h2>
<ul>
<li><strong>Hero Section</strong> – Inspiring banner with clear messaging and a call-to-action button.</li>
<li><strong>Live KPIs</strong> – Shows target pledges (1,000,000), achieved pledges, and breakdown by Students / Working Professionals.</li>
<li><strong>Why Take Climate Action</strong> – Short impact statement encouraging personal responsibility.</li>
<li><strong>Pledge Form</strong> – Collects name, email, mobile, state, profile type, and multiple climate commitments.</li>
<li><strong>Certificate Generator</strong> – Creates a downloadable PNG certificate with the user’s name, a “Cool Enough to Care!” message, and a heart rating.</li>
<li><strong>Public Pledge Wall</strong> – Displays pledge ID, name, date, state, profile type, and love-for-planet stars (no email/mobile shown).</li>
<li><strong>Privacy Note</strong> – Email and mobile collected for validation only, never publicly displayed.</li>
</ul>

<h2>🛠 Technologies Used</h2>
<ul>
<li>HTML5, CSS3, JavaScript (Vanilla)</li>
<li>Tailwind CSS for styling</li>
<li>Google Fonts (<code>Inter</code>)</li>
<li>html2canvas for certificate image generation</li>
<li>LocalStorage for saving pledges in the browser</li>
</ul>

<h2>📂 Project Structure</h2>
<pre>
climate-action-pledge-microsite/
├── climate-action-pledge-microsite.html  # Main single-page application
└── README.html                           # Project documentation
</pre>

<h2>🚀 How It Works</h2>
<ol>
<li>User clicks <em>Take the Pledge</em> button → Scrolls to pledge form.</li>
<li>User fills form with required details and selects climate commitments.</li>
<li>On submission:
    <ul>
        <li>Data is validated.</li>
        <li>Number of commitments determines heart rating (1–5).</li>
        <li>Pledge is saved to LocalStorage.</li>
        <li>KPI metrics update dynamically.</li>
        <li>Public pledge wall refreshes with new entry.</li>
        <li>Personalized certificate is generated and displayed.</li>
    </ul>
</li>
<li>User can download the certificate as a PNG file.</li>
</ol>

<h2>📊 KPI Metrics</h2>
<ul>
<li><strong>Target Pledges</strong>: Static value of 1,000,000.</li>
<li><strong>Achieved Pledges</strong>: Count of total saved pledges.</li>
<li><strong>Students Pledged</strong>: Filtered count by profile type.</li>
<li><strong>Professionals Pledged</strong>: Filtered count by profile type.</li>
</ul>

<h2>🔒 Privacy</h2>
<div class="highlight">
<p><strong>Note:</strong> Email and mobile number are collected only for verification and engagement purposes. They are never shown on the public pledge wall or shared.</p>
</div>

<h2>📥 Installation</h2>
<p>No build tools required — simply open the HTML file in a browser.</p>
<pre>
# Clone the repository
git clone https://github.com/your-username/climate-action-pledge-microsite.git

# Open in browser
cd climate-action-pledge-microsite
open climate-action-pledge-microsite.html
</pre>

<h2>🌐 Deployment</h2>
<ul>
<li>You can host this project on GitHub Pages, Netlify, or Vercel.</li>
<li>Simply upload <code>climate-action-pledge-microsite.html</code> as your main entry file.</li>
</ul>

<h2>🤝 Contributing</h2>
<p>Feel free to fork this repository, submit issues, and make pull requests to improve features and design.</p>

<h2>📄 License</h2>
<p>This project is licensed under the MIT License.</p>

</body>
</html>
