<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Customer Support - Agentforce Test</title>
    <!-- Tailwind CSS for modern styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        /* Use the Inter font family */
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <header class="bg-white shadow-sm">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-2xl font-bold text-gray-900">ACME Insurance</h1>
            <nav>
                <a href="#" class="text-gray-600 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium">Home</a>
                <a href="#" class="text-gray-600 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium">Claims</a>
                <a href="#" class="text-gray-600 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium">Services</a>
                <a href="#" class="bg-blue-600 text-white px-4 py-2 rounded-md text-sm font-medium hover:bg-blue-700">Contact Us</a>
            </nav>
        </div>
    </header>

    <main class="container mx-auto px-6 py-16 text-center">
        <div class="max-w-3xl mx-auto">
            <h2 class="text-4xl md:text-5xl font-extrabold text-gray-900 leading-tight">Welcome to Our Support Center</h2>
            <p class="mt-4 text-lg text-gray-600">
                Have a question about your claim or policy? Our support agents are here to help.
                The chat window should appear on this page automatically. If you need assistance, please use the chat to connect with a live agent.
            </p>
            <div class="mt-8">
                <a href="#" class="inline-block bg-blue-600 text-white font-bold py-3 px-8 rounded-lg shadow-lg hover:bg-blue-700 transition-transform transform hover:scale-105">
                    Start a New Claim
                </a>
            </div>
        </div>
    </main>


    <section class="bg-white py-20">
        <div class="container mx-auto px-6">
            <div class="text-center mb-12">
                <h3 class="text-3xl font-bold text-gray-900">How We Can Help</h3>
                <p class="text-gray-600 mt-2">Our team is ready to assist you with any inquiries.</p>
            </div>
            <div class="grid md:grid-cols-3 gap-8 text-center">
                <div class="p-6 border border-gray-200 rounded-lg">
                    <h4 class="text-xl font-semibold mb-2">File a Claim</h4>
                    <p class="text-gray-600">Quickly and easily submit a new insurance claim online.</p>
                </div>
                <div class="p-6 border border-gray-200 rounded-lg">
                    <h4 class="text-xl font-semibold mb-2">Check Claim Status</h4>
                    <p class="text-gray-600">Get real-time updates on your existing claims.</p>
                </div>
                <div class="p-6 border border-gray-200 rounded-lg">
                    <h4 class="text-xl font-semibold mb-2">Talk to an Agent</h4>
                    <p class="text-gray-600">Use our live chat to get instant answers from a support agent.</p>
                </div>
            </div>
        </div>
    </section>

    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DKd00000K3bKg',
				'test',
				'https://ac1744622081511.my.site.com/ESWtest1752490732868',
				{
					scrt2URL: 'https://ac1744622081511.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://ac1744622081511.my.site.com/ESWtest1752490732868/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>


    <!-- Footer Section -->
    <footer class="bg-gray-800 text-white">
        <div class="container mx-auto px-6 py-8 text-center">
            <p>&copy; 2024 ACME Insurance. All rights reserved.</p>
            <p class="text-sm text-gray-400 mt-2">This is a test page for Agentforce Messaging integration.</p>
        </div>
    </footer>


    
</body>
</html>
