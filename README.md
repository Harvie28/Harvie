<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alexis Harvie Lagrimas - Virtual Assistant Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Light blue-gray background */
            scroll-behavior: smooth;
        }
        /* Custom scrollbar for a cleaner look */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1; /* Gray-300 */
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #94a3b8; /* Gray-400 */
        }
        /* Simple loading spinner for the AI assistant */
        .spinner {
            border: 4px solid rgba(0, 0, 0, 0.1);
            border-left-color: #6366f1; /* Indigo-500 */
            border-radius: 50%;
            width: 24px;
            height: 24px;
            animation: spin 1s linear infinite;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        /* Animation for fade-in effect */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .fade-in {
            animation: fadeIn 0.8s ease-out forwards;
        }
    </style>
</head>
<body class="text-gray-800">

    <!-- Navigation Bar -->
    <nav class="bg-white shadow-sm py-4 px-6 md:px-12 fixed w-full z-20 top-0 rounded-b-lg">
        <div class="container mx-auto flex justify-between items-center">
            <a href="#hero" class="text-2xl font-bold text-indigo-600">Alexis VA</a>
            <div class="hidden md:flex space-x-8">
                <a href="#about" class="text-gray-600 hover:text-indigo-600 transition duration-300">About</a>
                <a href="#services" class="text-gray-600 hover:text-indigo-600 transition duration-300">Services</a>
                <a href="#samples" class="text-gray-600 hover:text-indigo-600 transition duration-300">Work Samples</a>
                <a href="#cover-letter-assistant" class="text-gray-600 hover:text-indigo-600 transition duration-300">AI Assistant</a>
                <a href="#contact" class="text-gray-600 hover:text-indigo-600 transition duration-300">Contact</a>
            </div>
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" class="md:hidden text-gray-600 hover:text-indigo-600 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                </svg>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden mt-4 space-y-2">
            <a href="#about" class="block text-gray-600 hover:text-indigo-600 transition duration-300 px-4 py-2 rounded-md">About</a>
            <a href="#services" class="block text-gray-600 hover:text-indigo-600 transition duration-300 px-4 py-2 rounded-md">Services</a>
            <a href="#samples" class="block text-gray-600 hover:text-indigo-600 transition duration-300 px-4 py-2 rounded-md">Work Samples</a>
            <a href="#cover-letter-assistant" class="block text-gray-600 hover:text-indigo-600 transition duration-300 px-4 py-2 rounded-md">AI Assistant</a>
            <a href="#contact" class="block text-gray-600 hover:text-indigo-600 transition duration-300 px-4 py-2 rounded-md">Contact</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="hero" class="relative bg-gradient-to-r from-indigo-500 to-purple-600 text-white pt-32 pb-24 md:pt-40 md:pb-32 flex items-center justify-center min-h-screen-75 rounded-b-xl">
        <div class="container mx-auto text-center px-6">
            <!-- IMPORTANT: Replace this src with a link to your own photo -->
            <img src="https://placehold.co/150x150/ffffff/6366f1?text=A.H.L" alt="Alexis Harvie Lagrimas" class="rounded-full w-36 h-36 mx-auto mb-6 shadow-lg border-4 border-white">
            <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-4 fade-in">
                Alexis Harvie Lagrimas
            </h1>
            <p class="text-xl md:text-2xl font-light mb-8 fade-in" style="animation-delay: 0.2s;">
                Your Dedicated Virtual Assistant for Seamless Operations
            </p>
            <a href="#contact" class="bg-white text-indigo-600 hover:bg-indigo-100 font-bold py-3 px-8 rounded-full shadow-lg transition duration-300 transform hover:scale-105 fade-in" style="animation-delay: 0.4s;">
                Let's Work Together!
            </a>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about" class="py-16 md:py-24 bg-white rounded-xl shadow-lg mx-4 md:mx-auto max-w-6xl -mt-16 relative z-10 px-6 md:px-12">
        <div class="container mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-gray-900 mb-8">About Me</h2>
            <div class="max-w-3xl mx-auto text-lg leading-relaxed text-gray-700">
                <p class="mb-4">
                    Hi! I’m Alexis, a highly organized and dependable Virtual Assistant with a strong background in healthcare, customer service, and BPO. I specialize in administrative support, customer communication, and social media assistance.
                </p>
                <p class="mb-4">
                    With years of experience in managing emails, schedules, data entry, and client interactions, I help business owners stay focused by handling the back-end tasks that keep things running smoothly.
                </p>
                <p class="mb-4">
                    I'm proficient in tools like Google Workspace, Canva, Zoom, Excel, and Facebook — and I’m comfortable working independently in remote environments. I take pride in being detail-oriented, fast to learn, and genuinely committed to providing excellent support.
                </p>
                <p>
                    Whether it’s replying to client inquiries, organizing daily operations, or managing simple content tasks, I’m here to help you stay on top of things — so you can focus on what matters most.
                </p>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 md:py-24 bg-gray-50 rounded-xl shadow-lg mx-4 md:mx-auto max-w-6xl mt-8 px-6 md:px-12">
        <div class="container mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-gray-900 mb-12">Services I Offer</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Service Card 1: Administrative Support -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300 transform hover:-translate-y-1">
                    <div class="text-indigo-500 mb-4 text-4xl text-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01" /></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3 text-center">Administrative Support</h3>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li>Email & Calendar Management</li>
                        <li>Appointment Scheduling</li>
                        <li>Data Entry (Sheets/Excel)</li>
                        <li>File Organization (Google Drive)</li>
                    </ul>
                </div>

                <!-- Service Card 2: Customer Support -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300 transform hover:-translate-y-1">
                    <div class="text-green-500 mb-4 text-4xl text-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z" /></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3 text-center">Customer Support</h3>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li>Email & Chat Response</li>
                        <li>Response Template Creation</li>
                        <li>Customer Feedback Management</li>
                        <li>CRM Updates & Tracking</li>
                    </ul>
                </div>

                <!-- Service Card 3: Social Media Assistance -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300 transform hover:-translate-y-1">
                    <div class="text-pink-500 mb-4 text-4xl text-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3 text-center">Social Media Assistance</h3>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li>Basic Canva Graphics</li>
                        <li>Content Scheduling</li>
                        <li>Inbox & Comment Management</li>
                        <li>Hashtag & Competitor Research</li>
                    </ul>
                </div>

                <!-- Service Card 4: Research & Documentation -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition duration-300 transform hover:-translate-y-1">
                    <div class="text-blue-500 mb-4 text-4xl text-center">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 21h7a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v14a2 2 0 002 2z" /></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3 text-center">Research & Documentation</h3>
                    <ul class="list-disc list-inside text-gray-700 space-y-2">
                        <li>Market or Product Research</li>
                        <li>Competitor Analysis</li>
                        <li>Report Formatting</li>
                        <li>Creating SOPs</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills & Tools Section -->
    <section id="skills" class="py-16 md:py-24 bg-white rounded-xl shadow-lg mx-4 md:mx-auto max-w-6xl mt-8 px-6 md:px-12">
        <div class="container mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-gray-900 mb-12">Skills & Tools</h2>
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6 text-center">
                <div class="bg-gray-100 p-4 rounded-lg shadow-sm"><p class="font-semibold text-lg text-gray-800">Google Workspace</p></div>
                <div class="bg-gray-100 p-4 rounded-lg shadow-sm"><p class="font-semibold text-lg text-gray-800">Canva</p></div>
                <div class="bg-gray-100 p-4 rounded-lg shadow-sm"><p class="font-semibold text-lg text-gray-800">Zoom</p></div>
                <div class="bg-gray-100 p-4 rounded-lg shadow-sm"><p class="font-semibold text-lg text-gray-800">Microsoft Excel</p></div>
                <div class="bg-gray-100 p-4 rounded-lg shadow-sm"><p class="font-semibold text-lg text-gray-800">Facebook Pages</p></div>
                <div class="bg-gray-100 p-4 rounded-lg shadow-sm"><p class="font-semibold text-lg text-gray-800">Customer Service</p></div>
                <div class="bg-gray-100 p-4 rounded-lg shadow-sm"><p class="font-semibold text-lg text-gray-800">Time Management</p></div>
                <div class="bg-gray-100 p-4 rounded-lg shadow-sm"><p class="font-semibold text-lg text-gray-800">Communication</p></div>
            </div>
        </div>
    </section>

    <!-- Mock Samples Section -->
    <section id="samples" class="py-16 md:py-24 bg-gray-50 rounded-xl shadow-lg mx-4 md:mx-auto max-w-6xl mt-8 px-6 md:px-12">
        <div class="container mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold text-center text-gray-900 mb-12">Work Samples</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Email Response Template -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold text-gray-900 mb-4">Email Response Template</h3>
                    <p class="text-gray-700 mb-2 font-medium">Customer Inquiry:</p>
                    <p class="italic text-gray-600 mb-4">“Hi, I’d like to check the status of my order #001234.”</p>
                    <p class="text-gray-700 mb-2 font-medium">My Reply:</p>
                    <div class="bg-gray-100 p-4 rounded-md border border-gray-200">
                        <p class="text-gray-800">Hi [Customer Name],</p>
                        <p class="text-gray-800 my-2">Thank you for reaching out! I’ve checked your order #001234 and it’s currently being processed. You can expect your tracking number within 24–48 hours. If you have any other questions, feel free to reach out anytime — I’m happy to assist.</p>
                        <p class="text-gray-800">Best regards,<br>Alexis</p>
                    </div>
                </div>

                <!-- Simple Data Entry Sample -->
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold text-gray-900 mb-4">Data Entry Sample</h3>
                    <p class="text-gray-700 mb-4">
                        This is a sample of how I organize and track data.
                        <!-- For a real portfolio, replace the image src with a link to your own screenshot -->
                    </p>
                    <img src="https://placehold.co/600x300/e2e8f0/4a5568?text=Screenshot+of+a+Client+Log+in+Google+Sheets" alt="Data Entry Sample: Client Contact Log" class="w-full h-auto rounded-md shadow-sm border">
                    <p class="text-sm text-gray-500 mt-2">Example: Client Contact Log with Status and Follow-up Notes</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Cover Letter Assistant Section -->
    <section id="cover-letter-assistant" class="py-16 md:py-24 bg-indigo-50 rounded-xl shadow-lg mx-4 md:mx-auto max-w-6xl mt-8 px-6 md:px-12">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-8">✨ AI Cover Letter Assistant ✨</h2>
            <p class="text-lg text-gray-700 mb-8 max-w-2xl mx-auto">
                Paste a job description below, and this AI tool will help you draft a tailored cover letter based on my skills and experience.
            </p>
            <div class="max-w-3xl mx-auto bg-white p-8 rounded-lg shadow-xl text-gray-800">
                <div class="space-y-6">
                    <div>
                        <label for="job-description" class="block text-left text-sm font-medium text-gray-700 mb-1">Job Description</label>
                        <textarea id="job-description" rows="10" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="Paste the full job description here..."></textarea>
                    </div>
                    <button id="generate-cover-letter-btn" class="w-full bg-indigo-600 text-white py-3 px-6 rounded-md font-semibold hover:bg-indigo-700 transition duration-300 shadow-md flex items-center justify-center">
                        <span id="button-text">Generate Cover Letter</span>
                        <div id="spinner" class="spinner ml-3 hidden"></div>
                    </button>
                    <div id="cover-letter-output" class="mt-6 p-4 bg-gray-100 border border-gray-200 rounded-md text-left whitespace-pre-wrap hidden"></div>
                    <div id="error-message" class="mt-4 text-red-600 text-sm hidden"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 md:py-24 bg-indigo-600 text-white rounded-xl shadow-lg mx-4 md:mx-auto max-w-6xl mt-8 px-6 md:px-12">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-8">Let's Connect!</h2>
            <p class="text-lg mb-8 max-w-2xl mx-auto">
                Ready to streamline your business? Reach out and let's discuss how I can help you achieve your goals.
            </p>
            <div class="max-w-xl mx-auto bg-white p-8 rounded-lg shadow-xl text-gray-800">
                <!-- For a live site, you would connect this form to a service like Formspree or Netlify Forms -->
                <form id="contact-form" class="space-y-6">
                    <div>
                        <label for="name" class="block text-left text-sm font-medium text-gray-700 mb-1">Your Name</label>
                        <input type="text" id="name" name="name" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="John Doe" required>
                    </div>
                    <div>
                        <label for="email" class="block text-left text-sm font-medium text-gray-700 mb-1">Your Email</label>
                        <input type="email" id="email" name="email" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="you@example.com" required>
                    </div>
                    <div>
                        <label for="message" class="block text-left text-sm font-medium text-gray-700 mb-1">Message</label>
                        <textarea id="message" name="message" rows="4" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="Tell me about your needs..." required></textarea>
                    </div>
                    <button type="submit" class="w-full bg-indigo-600 text-white py-3 px-6 rounded-md font-semibold hover:bg-indigo-700 transition duration-300 shadow-md">
                        Send Message
                    </button>
                </form>
                <div id="form-message" class="mt-4 text-sm text-center hidden"></div>
            </div>
            <div class="mt-8 text-lg">
                <!-- IMPORTANT: Replace these with your actual contact details -->
                <p class="mb-2">Email: <a href="mailto:alexis.lagrimas.va@email.com" class="underline hover:text-indigo-200">alexis.lagrimas.va@email.com</a></p>
                <p>Location: <span class="hover:text-indigo-200">Naic, Cavite, Philippines</span></p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8 mt-12 text-center rounded-t-lg">
        <div class="container mx-auto px-6">
            <p>&copy; 2025 Alexis Harvie Lagrimas. All rights reserved.</p>
            <p class="mt-2 text-sm text-gray-400">Built with passion and dedication.</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    targetElement.scrollIntoView({ behavior: 'smooth' });
                }
                // Close mobile menu if open
                const mobileMenu = document.getElementById('mobile-menu');
                if (!mobileMenu.classList.contains('hidden')) {
                    mobileMenu.classList.add('hidden');
                }
            });
        });

        // Toggle mobile menu visibility
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Simple contact form submission (for demonstration, no backend)
        const contactForm = document.getElementById('contact-form');
        const formMessage = document.getElementById('form-message');
        contactForm.addEventListener('submit', function(e) {
            e.preventDefault();
            formMessage.className = 'mt-4 text-sm text-center text-green-600';
            formMessage.textContent = 'Thank you for your message! I will get back to you soon.';
            contactForm.reset();
            setTimeout(() => {
                formMessage.className = 'mt-4 text-sm text-center hidden';
            }, 5000);
        });

        // Gemini API Integration for Cover Letter Assistant
        const generateCoverLetterBtn = document.getElementById('generate-cover-letter-btn');
        const jobDescriptionInput = document.getElementById('job-description');
        const coverLetterOutput = document.getElementById('cover-letter-output');
        const spinner = document.getElementById('spinner');
        const buttonText = document.getElementById('button-text');
        const errorMessage = document.getElementById('error-message');

        generateCoverLetterBtn.addEventListener('click', async () => {
            const jobDescription = jobDescriptionInput.value.trim();
            if (!jobDescription) {
                errorMessage.textContent = 'Please paste a job description to generate a cover letter.';
                errorMessage.classList.remove('hidden');
                coverLetterOutput.classList.add('hidden');
                return;
            }

            // UI updates for loading state
            errorMessage.classList.add('hidden');
            coverLetterOutput.classList.add('hidden');
            spinner.classList.remove('hidden');
            buttonText.textContent = 'Generating...';
            generateCoverLetterBtn.disabled = true;

            // --- AI Prompt Configuration ---
            // This is where you define your persona for the AI.
            const myName = "Alexis Harvie Lagrimas";
            const mySkills = "administrative support, customer communication, social media assistance, email and calendar management, appointment scheduling, data entry, Google Sheets/Excel tracking, file organization, responding to customer inquiries via email or chat, creating and updating response templates, managing customer feedback or tickets, CRM updates, basic Canva graphics for posts and stories, scheduling content on Facebook/Instagram, inbox management, comment replies, researching hashtags and competitors, market research, product research, competitor research, report formatting, documentation. Proficient in Google Workspace, Canva, Zoom, Excel, and Facebook.";
            const myBackground = "a background in healthcare, customer service, and BPO. I am highly organized, dependable, detail-oriented, a fast learner, and genuinely committed to providing excellent support. I am comfortable working independently in remote environments.";
            const myLocation = "Naic, Cavite, Philippines";

            const prompt = `Draft a professional cover letter for a Virtual Assistant position. The letter is from ${myName}, who is based in ${myLocation}.

My skills and experience include:
${mySkills}.

My professional background is:
${myBackground}.

The tone should be professional, confident, and helpful. Highlight how my skills and background align with the specific requirements in the job description provided below.

Start with a general but professional greeting (e.g., "Dear Hiring Manager," or "To the Hiring Team at [Company Name if discoverable],"). Do not use placeholders like "[Your Name]" or "[Your Contact Information]" as this will be handled separately. End with a clear call to action.

Here is the job description:
---
${jobDescription}
---`;

            let chatHistory = [{ role: "user", parts: [{ text: prompt }] }];
            const payload = { contents: chatHistory };
            const apiKey = ""; // This will be automatically provided by the environment.

            try {
                const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;
                const response = await fetch(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });

                if (!response.ok) {
                    const errorData = await response.json();
                    throw new Error(`API error: ${response.status} - ${errorData.error?.message || 'Unknown error'}`);
                }

                const result = await response.json();

                if (result.candidates?.[0]?.content?.parts?.[0]?.text) {
                    coverLetterOutput.textContent = result.candidates[0].content.parts[0].text;
                    coverLetterOutput.classList.remove('hidden');
                } else {
                    throw new Error("Received an empty or invalid response from the AI.");
                }
            } catch (error) {
                console.error('Error generating cover letter:', error);
                errorMessage.textContent = `Failed to generate cover letter: ${error.message}`;
                errorMessage.classList.remove('hidden');
            } finally {
                // Restore button to its original state
                spinner.classList.add('hidden');
                buttonText.textContent = 'Generate Cover Letter';
                generateCoverLetterBtn.disabled = false;
            }
        });
    </script>
</body>
</html>
