ICSR 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ICSR Case Processing Steps in Pharmacovigilance</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            background-color: #f4f6f9;
            color: #333;
        }
        header {
            background-color: #003366;
            color: #ffffff;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        h1, h2, h3 {
            margin-top: 0;
        }
        .container {
            max-width: 900px;
            margin: auto;
        }
        .section {
            background: #ffffff;
            padding: 20px;
            margin-bottom: 15px;
            border-radius: 6px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .timeline-table, .qualification-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }
        .timeline-table th, .timeline-table td,
        .qualification-table th, .qualification-table td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        .timeline-table th, .qualification-table th {
            background-color: #004080;
            color: white;
        }
        .step {
            border-left: 4px solid #004080;
            padding-left: 15px;
            margin-bottom: 15px;
        }
        .video-link {
            margin-top: 15px;
            display: inline-block;
            background-color: #cc0000;
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 4px;
        }
        .video-link:hover {
            background-color: #990000;
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>ICSR Case Steps in Pharmacovigilance</h1>
        <p>A complete summary based on the tutorial by <strong>Drug Safety</strong></p>
    </header>

    <div class="section">
        <h2>Overview & Regulatory Timelines</h2>
        <p>Day 0 is the date the pharmaceutical manufacturer receives an adverse event report (solicited or unsolicited). This starts the regulatory clock.</p>
        
        <table class="timeline-table">
            <thead>
                <tr>
                    <th>Seriousness / Severity</th>
                    <th>Reporting Timeline</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Fatal and Life-Threatening Cases</td>
                    <td>7 Days</td>
                </tr>
                <tr>
                    <td>Other Serious Cases (Hospitalization, Disability, etc.)</td>
                    <td>15 Days</td>
                </tr>
                <tr>
                    <td>Non-Serious Cases</td>
                    <td>90 Days</td>
                </tr>
            </tbody>
        </table>
    </div>

    <div class="section">
        <h2>5 Key Steps in ICSR Case Processing</h2>
        
        <div class="step">
            <h3>1. Triage / Book-In [00:01:28]</h3>
            <ul>
                <li>Verify report validity (all 4 validity criteria must be met).</li>
                <li>Perform duplicate search in safety databases (e.g., Argus, ArisG).</li>
                <li>Book the case into the safety database and request missing information if needed.</li>
            </ul>
        </div>

        <div class="step">
            <h3>2. Data Entry [00:01:49]</h3>
            <ul>
                <li>Enter complete and accurate case information into the database.</li>
                <li>Code medical events/history using <strong>MedDRA</strong> (Medical Dictionary for Regulatory Activities).</li>
                <li>Code suspect/co-medication drugs using <strong>WHO Drug Dictionary</strong>.</li>
                <li>Write case narrative and submit query requests for missing data.</li>
            </ul>
        </div>

        <div class="step">
            <h3>3. Quality Review (QC) [00:02:30]</h3>
            <ul>
                <li>Perform quality check on data entered by the Data Entry Associate.</li>
                <li>Verify MedDRA coding, WHO Drug coding, and narrative correctness.</li>
                <li>Give approval (green flag) or request clarification/edits before pushing forward.</li>
            </ul>
        </div>

        <div class="step">
            <h3>4. Medical Review [00:03:00]</h3>
            <ul>
                <li>Performed by a qualified physician (MBBS / MD).</li>
                <li>Evaluate causality between the drug and the adverse event.</li>
                <li>Assess medical sense, event seriousness, and add company comments.</li>
            </ul>
        </div>

        <div class="step">
            <h3>5. Submission [00:03:25]</h3>
            <ul>
                <li>Perform final completeness and validity check.</li>
                <li>Submit the completed ICSR to the relevant regulatory authority.</li>
            </ul>
        </div>
    </div>

    <div class="section">
        <h2>Qualification & Experience Requirements [00:03:51]</h2>
        <table class="qualification-table">
            <thead>
                <tr>
                    <th>Role</th>
                    <th>Required Qualification</th>
                    <th>Experience</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Triage, Data Entry, QC, Submission</td>
                    <td>Life Science Degree (B.Pharm, Nursing, BDS, etc.)</td>
                    <td>Freshers accepted for Data Entry; 1+ years experience preferred for other roles.</td>
                </tr>
                <tr>
                    <td>Medical Reviewer</td>
                    <td>MBBS or MD (Medical Doctor)</td>
                    <td>Medical background required.</td>
                </tr>
            </tbody>
        </table>
    </div>

    <div style="text-align: center;">
        <a class="video-link" href="https://www.youtube.com/watch?v=ryof8pJbX1o" target="_blank">Watch Original Video on YouTube</a>
    </div>
</div>

</body>
</html>
