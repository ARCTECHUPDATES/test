<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Manual UPI</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/axios/1.6.7/axios.min.js"
        integrity="sha512-NQfB/bDaB8kaSXF8E77JjhHG5PM6XVRxvHzkZiwl3ddWCEPBa23T76MuWSwAJdMGJnmQqM0VeY9kFszsrBEFrQ=="
        crossorigin="anonymous" referrerpolicy="no-referrer">
        </script>
</head>

<body>
    <style>
        html {
            height: 100%;
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        
        .pay-button {
  background-color: #4CAF50;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
  font-weight: bold;
}

.pay-button:hover {
  background-color: #3e8e41;
}

.pay-button i {
  margin-right: 10px;
}

        main {
            display: flex;
            flex-direction: column;
            gap: 15px;
            height: 100%;
            max-width: 550px;
            margin-left: auto;
            margin-right: auto;
        }

        header {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 6px;
            margin-left: auto;
            margin-right: auto;
            border-radius: 12px;
            margin: 15px 10px;
        }

        footer {
            background-color: #fff;
            padding: 6px;
            text-align: center;
            border-top-left-radius: 12px;
            border-top-right-radius: 12px;
            margin: 0px 10px;
            margin-top: auto;
        }

        .tutorial_root {
            display: flex;
            flex-direction: column;
            align-items: center;
            background: #fff;
            padding: 0px 25px 20px;
            margin-left: auto;
            margin-right: auto;
            border-radius: 12px;
            margin: 15px 10px;
        }

        .tutorial_content p {
            display: flex;
            gap: 6px;
        }

        .tutorial_content p strong {
            white-space: nowrap;
        }

        @media (min-width: 500px) {
            .tutorial_root {
                padding: 0px 20px 20px;
            }
        }

        .upi_display_root {
            display: flex;
            flex-direction: column;
            align-items: center;
            background: #fff;
            padding: 0px 25px 20px;
            margin-left: auto;
            margin-right: auto;
            border-radius: 12px;
            margin: 15px 10px;
        }

        .upi_display_root h2 {
            margin: 20px 0px 5px;
            font-weight: 600;
        }

        .upi_display_content {
            margin-top: 10px;
            padding: 0px 13px;
            border-radius: 9px;
            border: 1px solid #ccc;
            font-size: 14px;
            cursor: pointer;
        }

        .upi_display_content p {
            display: flex;
            gap: 6px;
        }

        .upi_display_content p strong {
            white-space: nowrap;
        }

        .upi_display_content__img {
            width: 15px;
            height: 15px;
            cursor: pointer;
            margin-left: 5px;
        }

        .verification_form__root {
    display: flex;
    align-items: center;
    gap: 10px;
    background: #fff;
    padding: 10px 25px 25px;
    margin-left: auto;
    margin-right: auto;
    border-radius: 12px;
    margin: -49px 10px;
}

.verification_form__root label {
    font-weight: 600;
}

.verification_form__root input {
    flex: 1;
    padding: 10px 13px;
    border-radius: 9px;
    border: 1px solid #ccc;
    font-size: 14px;
}


        .verification_form__root input::placeholder {
            font-size: 14px;
        }

        .verification_form__root button {
    margin-top: 0px;
    padding: 10px;
    border-radius: 3px;
    border: 1px solid #ccc;
    background-color: #2196F3;
    color: white;
    width: 78px;
    font-size: 13px;
    cursor: pointer;
}

        .upi_pay_now {
            margin-top: 10px;
            padding: 10px 15px;
            border-radius: 9px;
            border: 1px solid #ccc;
            background-color: #1c4ff7;
            background: linear-gradient(40deg,
                    rgba(172, 10, 154, 1) 0%,
                    rgba(0, 39, 255, 1) 100%);
            font-weight: 500;
            color: white;
            font-size: 16px;
            cursor: pointer;
            text-decoration: none;
            text-align: center;
        }
    </style>

    <main>
        <header>
            <h2 style="color: rgb(73, 138, 159);">RUJIA-PAY</h2>
            <h2 class="upi_display_title">
                ₹ <span id="display_amount">
                   <%=Amount%>
               </span>
            </h2>
            <div class="header-line"></div> <!-- Blue line -->
        </header>
        <div class="content-section">
            <!-- Remark section with Copy button -->
            <p class="remark-section" style="color: silver; display: flex; justify-content: space-between; margin-bottom: 10px;">
                <span class="left-align">Remark</span>
                <span class="right-align" style="color: rgb(0, 0, 0);">vNoF</span>
                <!-- Copy button for Remark -->
                <button onclick="copyText('remarkText')" style="background-color: transparent; border: none; color: rgb(0, 0, 0); cursor: pointer;">Copy</button>
            </p>
        
            <!-- UPI ID section with Copy button -->
            <p class="upi-id-section" style="color: silver; display: flex; justify-content: space-between;">
                <span class="left-align">UPI ID</span>
                <span class="right-align" style="color: red;" id="upiText">demo@sbi</span>
                <!-- Copy button for UPI ID -->
                <button onclick="copyText('upiText')" style="background-color: transparent; border: none; color: red; cursor: pointer;">Copy</button>
            </p>
        </div>
        <style>
            .upi_qr__img {
                width: 65%;
                margin-bottom: 30px;
            }
        </style>
        <style>
            button:hover {
                background-color: rgb(41, 179, 225);
                color: #ffffff;
                border: 2px solid rgb(41, 179, 225);
            }
        </style>
        <script>
            // JavaScript code to automatically update UPI ID
document.addEventListener("DOMContentLoaded", function() {
    // Get the value from the first span with id="upi_id_field"
    var upiId = document.getElementById("upi_id_field").textContent;

    // Update the second span with class="right-align" and id="upiText"
    document.getElementById("upiText").textContent = upiId;
});
document.addEventListener("DOMContentLoaded", async function () {
    try {
        const res = await axios.get("/api/bank-info?typer=momo"); // ya koi filter
        const data = res.data;

        if (data?.username) {
            document.getElementById("qrImage").src = data.username;
        }
    } catch (err) {
        console.error("Failed to load QR image from username field:", err);
    }
});


        </script>
        <but class="upi_display_root">
            <div class="upi-qr-section" style="text-align: center;">
                <!-- QR Image -->
                <img id="qrImage" src="" alt="QR Image"
     style="max-width: 100%; height: auto; display: block; margin: 0 auto;">

            
         
<h3 style="color: rgb(255, 128, 0);">Have you paid successfully?</h3>
<!-- Buttons -->
<button onclick="payNow('net.one97.paytm')">Pay with Paytm</button>
<button onclick="payNow('com.phonepe.app')">Pay with PhonePe</button>
<button onclick="payNow('com.google.android.apps.nbu.paisa.user')">Pay with Google Pay</button>
<button onclick="payNow()">Pay with Other UPI</button>

<script>
  function payNow(packageName = '') {
    // UPI URI
    const uri = `upi://pay?pa=${upiId}&pn=${name}&am=${amount}&cu=INR`;

    // If specific package given (Paytm, GPay, etc.)
    if (packageName) {
      window.location.href = `intent:${uri}#Intent;package=${packageName};scheme=upi;end`;
    } else {
      // Open generic UPI app chooser
      window.location.href = uri;
    }
  }
</script>




            </div>
            <button class="upi_display_content" id="copy_upi_id">
                <p>
                    
                    <strong>UPI ID: </strong>
                    <span id="upi_id_field">
                        <%=UpiId%>
                    </span>
                    <img class="upi_display_content__img"
                        src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz48c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IiB2aWV3Qm94PSIwIDAgMTE1Ljc3IDEyMi44OCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgMTE1Ljc3IDEyMi44OCIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+PHN0eWxlIHR5cGU9InRleHQvY3NzIj4uc3Qwe2ZpbGwtcnVsZTpldmVub2RkO2NsaXAtcnVsZTpldmVub2RkO308L3N0eWxlPjxnPjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik..."
                        alt="copy UPI id" />
                </p>
            </button>
        </but>
        
        <!-- Below the header, add the Remark and UPI ID -->

        
                 
                

        <form class="verification_form__root" action="submit.php" method="post">
            <label for="upi_ref_no">UTR</label>
            <input type="text" id="upi_ref_no" name="upi_ref_no" required placeholder="Input 12-digit here " />
            <button id="submit_button" type="submit">Submit</button>
            
        </form>

        <div class="tutorial_root">
            <p class="tutorial_title">Important remainder:After completing the UPI <br>transaction,please backfill Ref No./UTR<br>No/GooglePay,UPI Transaction ID/Freecharge.</p>
        </div>

        <footer>
            <p></p>
        </footer>
    </main>

    <script>
        const copyUpiId = document.getElementById("copy_upi_id");

        copyUpiId.addEventListener("click", function () {
            let upi_id = document.getElementById("upi_id_field").innerText;
            console.log(upi_id);
            navigator.clipboard.writeText(upi_id);
        });

        // const displayAmount = document.getElementById("display_amount");
        // const urlParams = new URLSearchParams(window.location.search);
        // const amount = urlParams.get("am");
        // displayAmount.innerText = amount;

        // const upiPayNow = document.getElementById("upi_pay_now");

        const alertMessage = (text) => {
            const msg = document.createElement('div');
            msg.setAttribute('data-v-1dcba851', '');
            msg.className = 'msg';

            const msgContent = document.createElement('div');
            msgContent.setAttribute('data-v-1dcba851', '');
            msgContent.className = 'msg-content v-enter-active v-enter-to';
            msgContent.style = '';
            msgContent.textContent = text;

            msg.appendChild(msgContent);
            document.body.appendChild(msg);

            setTimeout(() => {
                msgContent.classList.remove('v-enter-active', 'v-enter-to');
                msgContent.classList.add('v-leave-active', 'v-leave-to');

                setTimeout(() => {
                    document.body.removeChild(msg);
                }, 100);
            }, 1000);
        }
        function copyText(elementId) {
    var text = document.getElementById(elementId).innerText;  // Get the text content of the element
    var textarea = document.createElement("textarea");  // Create a temporary textarea to copy the text
    textarea.value = text;  // Set the text value of the textarea
    document.body.appendChild(textarea);  // Append the textarea to the body
    textarea.select();  // Select the content of the textarea
    document.execCommand("copy");  // Copy the selected text to the clipboard
    document.body.removeChild(textarea);  // Remove the textarea from the DOM
}


        const submitButton = document.getElementById("submit_button");
        submitButton.addEventListener("click", async (event) => {
            try {


                event.preventDefault();
                const upiRefNo = document.getElementById("upi_ref_no").value;
                const amount = '<%=Amount%>';

                const response = await axios.post("/wallet/paynow/manual_upi_request", {
                    money: amount,
                    utr: upiRefNo,
                })

                if (!response?.data) {
                    alertMessage("Something went Wrong!")
                    return
                }

                if (response?.data?.status === false) {
                    alertMessage(response?.data?.message)
                    return
                }

                alertMessage(response?.data?.message)

                window.location.href = "/wallet/rechargerecord"
            } catch (error) {
                console.log(error);
                alertMessage("Something went Wrong!")
            }
        });
    </script>
    <style>
        .upi_display_title {
        color: rgb(66, 119, 169); /* Sets the text color to blue */
    }
    </style>
  
  <style>
    .header-line {
        width: 100%; /* Full width of the container */
        height: 1px; /* Thickness of the line */
        background-color: rgb(64, 64, 60); /* Color of the line */
        margin-top: 1px; /* Space between the header and the line */
    }
    .upi_content_details {
    margin-top: 20px;
    font-size: 16px;
}

.upi_content_details p {
    margin: 10px 0;
}

.upi_content_details strong {
    font-weight: bold;
}

.left-align {
        flex: 1; /* Makes the left content take up the available space */
        text-align: left; /* Aligns the text to the left */
    }

    .right-align {
        flex: 1; /* Makes the right content take up the available space */
        text-align: right; /* Aligns the text to the right */
    }

    .remark-section, .upi-id-section {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    /* Optional: Space between the text and the button */
    button {
        margin-left: 10px;
    }
    .tutorial_title {
    font-size: 1.3rem; /* Equivalent to the size of an h3 */
    font-weight: 2; /* Same weight as h3 */
    color: rgb(255, 0, 64); /* Set text color to red */
    text-align: center; /* Justify the text */
}
.upi_display_content {
    display: none;
}

</style>

    
</body>

</html>
