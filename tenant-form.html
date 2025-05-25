<!DOCTYPE html>
<html>
  <head>
    <base target="_top">
    <style>
      body {
        font-family: 'Segoe UI', sans-serif;
        max-width: 650px;
        margin: 40px auto;
        padding: 20px;
        background: #f9f9f9;
        border-radius: 8px;
        box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      }
      h2 {
        text-align: center;
      }
      label {
        font-weight: 600;
        display: block;
        margin-top: 12px;
      }
      input, select, textarea {
        width: 100%;
        padding: 10px;
        margin-top: 4px;
        border: 1px solid #ccc;
        border-radius: 4px;
      }
      button {
        margin-top: 20px;
        width: 100%;
        padding: 12px;
        font-size: 16px;
        background-color: #4CAF50;
        color: white;
        border: none;
        border-radius: 4px;
        cursor: pointer;
      }
      button:hover {
        background-color: #45a049;
      }
      #response {
        text-align: center;
        margin-top: 20px;
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <h2>Tenant Legal & Case Log</h2>
    <form id="caseForm" enctype="multipart/form-data">
      <label for="tenantId">Tenant ID *</label>
      <input id="tenantId" name="tenantId" list="tenantList" required>
      <datalist id="tenantList"></datalist>

      <label for="actionType">Action Type *</label>
      <select id="actionType" name="actionType" required>
        <option value="" disabled selected>Select an action</option>
        <option>Book Entry - Ledger Follow Up - Outstanding Balance Noted - Last Paid</option>
        <option>Court Appearance</option>
        <option>Current Status/Update From Lawyer</option>
        <option>Ledger Sent via Email</option>
        <option>Notice Sent Court Appearance</option>
        <option>Owner Request</option>
        <option>Repair Requested</option>
        <option>Repair Completed</option>
        <option>Scan Book</option>
        <option>Send Follow Up Email to Lawyer</option>
        <option>Send Ledger to Lawyer</option>
        <option>Sign Paperwork & Send Back to Lawyer</option>
        <option>Start Case- Give Files to Lawyer</option>
        <option>Stipulation/Settlement Entered</option>
        <option>Vacate Notice - Tenant Informed Landlord</option>
        <option>Other</option>
      </select>

      <label for="dateOfAction">Date of Action *</label>
      <input type="date" id="dateOfAction" name="dateOfAction" required>

      <label for="notes">Notes/Description</label>
      <textarea id="notes" name="notes" rows="4"></textarea>

      <label for="enteredBy">Entered By *</label>
      <select id="enteredBy" name="enteredBy" required>
        <option value="" disabled selected>Select who entered</option>
        <option value="Admin">Admin</option>
        <option value="Owner Indicated">Owner Indicated</option>
        <option value="Steven">Steven</option>
      </select>

      <label for="followUp">Follow-Up Needed?</label>
      <select id="followUp" name="followUp">
        <option value="Yes">Yes</option>
        <option value="No">No</option>
      </select>

      <label for="fileUpload">Upload File</label>
      <input type="file" id="fileUpload" name="fileUpload">

      <button type="submit">Submit</button>
    </form>

    <div id="response"></div>

    <script>
      const scriptUrl = 'https://script.google.com/macros/s/AKfycbzbb42mGFsmN5xy0Myl7nW8XVLdidoSAKf60nrFLHbIxPYOXu56bXa2zV9gnnKh8jtz/exec';
    
      // Load tenant IDs
      fetch(scriptUrl + '?load=1')
        .then(res => res.json())
        .then(data => {
          const list = document.getElementById('tenantList');
          data.forEach(item => {
            const opt = document.createElement('option');
            opt.value = item;
            list.appendChild(opt);
          });
        })
        .catch(error => {
          console.error('Failed to load tenant IDs:', error);
        });
    
      // Handle form submission
      document.getElementById('caseForm').addEventListener('submit', function (e) {
        e.preventDefault();
        const formData = new FormData(e.target);
    
        fetch(scriptUrl, {
          method: 'POST',
          body: formData
        })
        .then(res => res.text())
        .then(msg => {
          document.getElementById('response').innerText = msg;
          e.target.reset();
        })
        .catch(err => {
          console.error('Submission error:', err);
          document.getElementById('response').innerText = '❌ Submission failed.';
        });
      });
    </script>
    
  </body>
</html>

