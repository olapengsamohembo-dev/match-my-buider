<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Building Botswana</title>
<style>
/* ===== CSS ===== */
:root{--blue:#1E3A8A;--yellow:#FFB400;--light:#F8FAFC;--muted:#6B7280;--green:#10B981;--botswana-blue:#00AEEF;}
body{margin:0;font-family:Inter,Arial,sans-serif;background:white;color:#475569;}a{text-decoration:none;}button{cursor:pointer;}
.container{max-width:980px;margin:0 auto;padding:0 16px;}h1,h2,h3,h4,h5{margin:0;}p{margin:0 0 12px 0;}input, select, textarea{font-family:inherit;font-size:14px;}button, .btn-primary, .btn-secondary, .btn-view{transition:all 0.2s ease;}

/* HERO */
.hero{background:var(--light);padding:64px 16px;text-align:left;}
.hero h1{color:var(--blue); font-size:38px;font-weight:700;margin-bottom:12px;}
.hero p{color:var(--muted);font-size:16px;margin-bottom:24px;}
.search{display:flex;gap:8px;flex-wrap:wrap;}
.search input{flex:1 1 260px;padding:12px 14px;border:1px solid #E5E7EB;border-radius:6px;}
.search button{background:var(--yellow);color:var(--blue);border:none;padding:12px 18px;border-radius:6px;font-weight:700;}

/* TRUST & QUALITY */
.trust-quality{background:var(--botswana-blue);padding:80px 16px;text-align:center;color:#fff;}
.trust-quality h2{color:#000;font-size:34px;font-weight:700;margin-bottom:16px;}
.trust-quality p{margin-bottom:48px;}
.trust-cards{display:grid;gap:28px;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));}
.trust-cards .card{background:#fff;color:#000;padding:28px 20px;border-radius:12px;box-shadow:0 2px 8px rgba(0,0,0,0.05);text-align:left;}
.trust-cards h3{font-size:20px;margin-bottom:8px;}
.trust-cards p{font-size:15px;line-height:1.6;}

/* HOW IT WORKS */
.how-it-works{background:var(--light);padding:80px 16px;text-align:center;}
.how-it-works h2{color:var(--blue); font-size:34px;font-weight:700;margin-bottom:8px;}
.how-it-works .tagline{color:var(--muted); font-size:16px;margin-bottom:48px;}
.steps{display:grid;gap:28px;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));margin-bottom:48px;}
.step{background:white;padding:28px 20px;border-radius:12px;box-shadow:0 2px 8px rgba(0,0,0,0.05);text-align:left;}
.step:hover{transform:translateY(-4px);}
.number{background:var(--yellow);color:var(--blue);width:36px;height:36px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-weight:700;margin-bottom:12px;}
.step h3{color:var(--blue);font-size:20px;margin-bottom:8px;}
.step p{color:var(--muted);font-size:15px;line-height:1.6;}
.cta{margin-top:20px;display:flex;justify-content:center;gap:16px;flex-wrap:wrap;}
.btn-primary, .btn-secondary{padding:12px 24px;border-radius:8px;font-weight:700;text-decoration:none;font-size:15px;}
.btn-primary{background:var(--yellow);color:var(--blue);}
.btn-primary:hover{background:#F4A100;}
.btn-secondary{background:var(--blue);color:#fff;}
.btn-secondary:hover{background:#17316C;}

/* CONTRACTOR REGISTRATION */
.registration{background:var(--light);padding:80px 16px;text-align:center;}
.registration h1{color:var(--blue);font-size:34px;margin-bottom:16px;}
.registration p{color:var(--muted);margin-bottom:32px;}
.registration-form{background:white;padding:32px;border-radius:12px;box-shadow:0 2px 8px rgba(0,0,0,0.05);text-align:left;}
.registration-form form{display:flex;flex-direction:column;gap:16px;}
.registration-form label{font-weight:600;margin-bottom:4px;}
.registration-form input, .registration-form select, .registration-form textarea{padding:12px;border:1px solid #CBD5E1;border-radius:8px;font-size:14px;width:100%;}
.registration-form button{background:var(--yellow);color:var(--blue);border:none;padding:12px;border-radius:8px;font-weight:700;font-size:16px;}
.registration-form button:hover{background:#F4A100;}
.fee-note{color:#475569;font-weight:600;margin-bottom:16px;}

@media(max-width:600px){.hero h1{font-size:28px;}.how-it-works h2{font-size:28px;}.steps{grid-template-columns:1fr;}.trust-cards{grid-template-columns:1fr;}}
html{scroll-behavior:smooth;}
</style>
</head>
<body>

<!-- HERO -->
<section class="hero">
<div class="container">
<h1>Find reliable builders near you</h1>
<p>Connecting you to trusted builders near you.</p>
<form class="search">
<input type="text" name="project" placeholder="What do you need built?" aria-label="project">
<input type="text" name="location" placeholder="Location (city or postcode)" aria-label="location">
<button type="submit">Find My Builder</button>
</form>
</div>
</section>

<!-- TRUST & QUALITY -->
<section class="trust-quality">
<div class="container">
<h2>Build with Confidence</h2>
<p>At Building Botswana, we connect you with trusted, verified builders who deliver high-quality work, on time, and exactly as promised.</p>
<div class="trust-cards">
<div class="card">
<h3>Quality You Can Trust</h3>
<p>All builders are verified, experienced, and reviewed to ensure top-notch craftsmanship on every project.</p>
</div>
<div class="card">
<h3>On-Time Delivery</h3>
<p>Track progress with ease and know your project will be completed within agreed timelines.</p>
</div>
<div class="card">
<h3>Transparent & Clear</h3>
<p>From project scope to pricing and milestones, everything is clear—no surprises, just results.</p>
</div>
</div>
</div>
</section>

<!-- HOW IT WORKS -->
<section class="how-it-works">
<div class="container">
<h2>How It Works</h2>
<p class="tagline">Connecting you to trusted builders near you.</p>
<div class="steps">
<div class="step"><div class="number">1</div><h3>Post Your Project</h3><p>Describe your building project, send to verified builders near you.</p></div>
<div class="step"><div class="number">2</div><h3>Get Matched</h3><p>Receive quotes, compare profiles, chat, find perfect match.</p></div>
<div class="step"><div class="number">3</div><h3>Hire & Build</h3><p>Hire your preferred builder, track progress, make secure payments.</p></div>
<div class="step"><div class="number">4</div><h3>Review & Recommend</h3><p>Rate your builder and share experience to help others.</p></div>
</div>
<div class="cta">
<a href="#registration" class="btn-secondary">Contractor Registration</a>
</div>
</div>
</section>

<!-- CONTRACTOR REGISTRATION -->
<section class="registration" id="registration">
<div class="container">
<h1>Contractor Registration</h1>
<p>Register as a contractor to start receiving projects. Registration fee: <strong>P200</strong>.</p>
<div class="registration-form">
<p class="fee-note">Registration Fee: P200 (Payable via your preferred method below)</p>
<form id="contractorForm">
<label for="name">Full Name</label><input type="text" id="name" name="name" required>
<label for="business">Business Name</label><input type="text" id="business" name="business" required>
<label for="email">Email</label><input type="email" id="email" name="email" required>
<label for="phone">Phone Number</label><input type="tel" id="phone" name="phone" required>
<label for="specialty">Specialty</label><select id="specialty" name="specialty" required>
<option value="">Select specialty</option>
<option value="construction">Construction</option>
<option value="plumbing">Plumbing</option>
<option value="electrical">Electrical</option>
<option value="painting">Painting</option>
<option value="other">Other</option>
</select>
<label for="experience">Years of Experience</label><input type="number" id="experience" name="experience" required>
<label for="description">Brief Description</label><textarea id="description" name="description" rows="4" required></textarea>
<label for="payment-method">Select Payment Method</label>
<select id="payment-method" name="paymentMethod" required>
<option value="">Choose method</option>
<option value="orange-money">Orange Money</option>
<option value="fnb">FNB</option>
<option value="smega">Smega</option>
<option value="access">Access Bank</option>
</select>
<div id="payment-instructions" style="margin-bottom:16px;font-weight:600;"></div>
<button type="submit">Submit Registration</button>
</form>
</div>
</div>
</section>

<!-- ADMIN PANEL -->
<section class="admin" id="admin">
<div class="container">
<h1>Admin Panel</h1>
<input type="password" id="adminPassword" placeholder="Enter password">
<button id="loadData">Load Registrations</button>
<div id="adminTable"></div>
</div>
</section>

<script>
// Payment instructions
const paymentSelect = document.getElementById('payment-method');
const instructionsDiv = document.getElementById('payment-instructions');
paymentSelect.addEventListener('change', ()=>{
const method = paymentSelect.value;
let instructions = '';
if(method==='orange-money'){instructions='Send P200 via Orange Money to: 071XXXXXXX. Use your name as reference.';}
else if(method==='fnb'){instructions='Deposit P200 to FNB Account: 250-XXXX-XXXXXX. Use your name as reference.';}
else if(method==='smega'){instructions='Send P200 via Smega to: 071XXXXXXX. Include your name in the message.';}
else if(method==='access'){instructions='Deposit P200 to Access Bank Account: XXXX-XXXX-XXXX. Include your name as reference.';}
instructionsDiv.textContent=instructions;
});

// Submit form
const form = document.getElementById('contractorForm');
form.addEventListener('submit', e=>{
e.preventDefault();
const data={
name:document.getElementById('name').value,
business:document.getElementById('business').value,
email:document.getElementById('email').value,
phone:document.getElementById('phone').value,
specialty:document.getElementById('specialty').value,
experience:document.getElementById('experience').value,
description:document.getElementById('description').value,
paymentMethod:document.getElementById('payment-method').value
};
fetch('YOUR_GOOGLE_SCRIPT_WEBAPP_URL',{method:'POST',mode:'no-cors',headers:{'Content-Type':'application/x-www-form-urlencoded'},body:new URLSearchParams(data)}).then(()=>{alert('Registration submitted! Please make the P200 payment using the instructions.');form.reset();instructionsDiv.textContent='';}).catch(err=>{alert('Error submitting form. Try again.');console.error(err);});

// Admin panel
document.getElementById('loadData').addEventListener('click', ()=>{
const pwd=document.getElementById('adminPassword').value;
if(pwd!=='buildbotswana2025'){alert('Incorrect password');return;}
fetch('YOUR_GOOGLE_SCRIPT_WEBAPP_URL?action=getRegistrations').then(res=>res.json()).then(data=>{
let html='<table border="1" cellpadding="6" style="width:100%;border-collapse:collapse;"><tr><th>Name</th><th>Business</th><th>Email</th><th>Phone</th><th>Specialty</th><th>Experience</th><th>Description</th><th>Payment Method</th><th>Timestamp</th></tr>';
data.forEach(r=>{html+=`<tr><td>${r.name}</td><td>${r.business}</td><td>${r.email}</td><td>${r.phone}</td><td>${r.specialty}</td><td>${r.experience}</td><td>${r.description}</td><td>${r.paymentMethod}</td><td>${r.timestamp}</td></tr>`;});
html+='</table>';document.getElementById('adminTable').innerHTML=html;
}).catch(err=>{alert('Error loading data');console.error(err);});
});
</script>
</body>
</html>

