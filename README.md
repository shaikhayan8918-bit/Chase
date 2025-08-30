# Chase
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <!-- Ensures proper rendering and touch zooming on mobile devices -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chase AI Mentorship Program</title>
    
    <!-- Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
    
    <style>
        /* CSS Reset for consistent rendering */
        *, *::before, *::after { box-sizing: border-box; }
        body, h1, h2, h3, h4, p, figure, blockquote, dl, dd { margin: 0; }
        ul[role='list'], ol[role='list'] { list-style: none; padding: 0; }
        html:focus-within { scroll-behavior: smooth; }
        body { min-height: 100vh; text-rendering: optimizeSpeed; line-height: 1.5; }
        a:not([class]) { text-decoration-skip-ink: auto; }
        img, picture, video, canvas, svg { max-width: 100%; height: auto; display: block; }
        input, button, textarea, select { font: inherit; }
        @media (prefers-reduced-motion: reduce) {
          html:focus-within { scroll-behavior: auto; }
          *, *::before, *::after {
            animation-duration: 0.01ms !important;
            animation-iteration-count: 1 !important;
            transition-duration: 0.01ms !important;
            scroll-behavior: auto !important;
          }
        }

        /* Base styles */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0A0A0A;
            color: #EAEAEA;
            /* Prevents horizontal scrolling */
            overflow-x: hidden;
        }

        .container-wrapper {
            width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 1.5rem;
            padding-right: 1.5rem;
        }

        .main-container {
            width: 100%;
            max-width: 800px; /* Design limit for readability */
        }
        
        .cta-button {
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0, 190, 150, 0.3);
        }
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0, 190, 150, 0.5);
        }

        /* Play button SVG style for the VSL icon */
        .play-button-svg {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 30%;
            max-width: 80px;
            height: auto;
            opacity: 0.8;
            transition: opacity 0.3s ease;
        }
        .vsl-container:hover .play-button-svg {
            opacity: 1;
        }

        /* Bullet point checkmark style */
        .bullet-point {
            display: flex;
            align-items: flex-start;
            margin-bottom: 1rem;
        }
        .bullet-point svg {
            flex-shrink: 0;
            width: 1.5rem;
            height: 1.5rem;
            margin-right: 0.75rem;
            color: #00BE96;
        }
    </style>
</head>
<body class="antialiased">

    <!-- HERO SECTION -->
    <section class="py-16 md:py-24">
        <div class="container-wrapper">
            <div class="main-container mx-auto text-center">
                <p class="font-semibold text-lg text-emerald-400 mb-4">FOR ASPIRING AI AGENCY FOUNDERS TIRED OF ZERO-DOLLAR COURSES</p>
                <h1 class="text-4xl md:text-6xl font-black leading-tight mb-6">Launch Your AI Agency And Land Your First Paying Client... <span class="text-emerald-400">In The Next 90 Days.</span></h1>
                <p class="text-xl md:text-2xl text-gray-300 mb-8">...Without burning thousands on useless theory or spending months guessing what clients *actually* want to buy.</p>
                
                <!-- VSL Icon - Looks like a clickable video -->
                <div class="vsl-container relative w-full max-w-2xl mx-auto rounded-lg overflow-hidden shadow-2xl cursor-pointer mb-10">
                    <img src="https://placehold.co/1280x720/1a1a1a/333333?text=Click+To+Watch" alt="Video presentation thumbnail" class="w-full">
                    <svg class="play-button-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true">
                        <path fill-rule="evenodd" d="M2.25 12c0-5.385 4.365-9.75 9.75-9.75s9.75 4.365 9.75 9.75-4.365 9.75-9.75 9.75S2.25 17.385 2.25 12zm14.024-.983a1.125 1.125 0 010 1.966l-5.603 3.113A1.125 1.125 0 019 15.113V8.887c0-.857.921-1.4 1.671-.983l5.603 3.113z" clip-rule="evenodd" style="fill: rgba(255, 255, 255, 0.9);"></path>
                    </svg>
                </div>
                
                <a href="#apply" class="cta-button inline-block bg-emerald-500 text-gray-900 font-bold text-xl py-4 px-12 rounded-lg">
                    APPLY FOR 1-ON-1 MENTORSHIP
                </a>
            </div>
        </div>
    </section>

    <!-- PROBLEM IDENTIFICATION -->
    <section class="py-16 md:py-24 bg-gray-900/50">
        <div class="container-wrapper">
            <div class="main-container mx-auto">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">Is The "AI Gold Rush" Just Passing You By?</h2>
                
                <p class="text-lg text-gray-300 mb-6">Let me guess.</p>
                <p class="text-lg text-gray-300 mb-6">You see everyone on Twitter talking about AI...</p>
                <p class="text-lg text-gray-300 mb-6">...how it's the biggest opportunity since the internet.</p>
                <p class="text-lg text-gray-300 mb-10">And you feel that pit in your stomach. The one that says you’re on the verge of missing out. *Again*.</p>

                <p class="text-lg text-gray-300 font-semibold mb-6">So you've probably tried a few things...</p>
                <p class="text-lg text-gray-300 mb-6">Maybe you bought a $497 course that just rehashed stuff you could find on YouTube.</p>
                <p class="text-lg text-gray-300 mb-6">Or you spent weeks building AI-powered "services" nobody wanted.</p>
                <p class="text-lg text-gray-300 mb-10">You send a few cold emails... and get nothing back.</p>
                
                <p class="text-lg text-gray-300 mb-6">The initial excitement fades.</p>
                <p class="text-lg text-gray-300 mb-6">And the big fear creeps in: “What if I waste the next 12 months on this and end up exactly where I am now... just broker and more frustrated?”</p>
                <p class="text-lg text-gray-300 mb-6">That feeling of being stuck while others are cashing in? It’s paralyzing.</p>
                <p class="text-lg text-gray-300 font-bold mb-6">But what if the problem isn’t you?</p>
                <p class="text-lg text-gray-300">What if the entire model of "learn first, earn later" is fundamentally broken?</p>
            </div>
        </div>
    </section>

    <!-- ORIGIN STORY -->
    <section class="py-16 md:py-24">
        <div class="container-wrapper">
            <div class="main-container mx-auto">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">I Wasted $10,000 On "Expert" Advice Before I Had My Breakthrough</h2>
                
                <p class="text-lg text-gray-300 mb-6">A couple of years ago, I was you.</p>
                <p class="text-lg text-gray-300 mb-6">I knew AI was the future. I was hungry. I was willing to do the work.</p>
                <p class="text-lg text-gray-300 mb-6">I bought the high-ticket masterminds. I watched all the webinars. I filled notebooks with strategies.</p>
                <p class="text-lg text-gray-300 mb-10">My bank account was getting drained, and I still didn't have a single paying client to show for it.</p>
                
                <p class="text-lg text-gray-300 mb-6">The "gurus" all said the same thing: "Build a portfolio! Offer free work!"</p>
                <p class="text-lg text-gray-300 mb-10">It was terrible advice. I had no confidence, no real-world experience, and my "free work" was just ignored.</p>

                <p class="text-lg text-gray-300 mb-6">My breakthrough came when I stopped trying to *learn* how to get clients...</p>
                <p class="text-lg font-bold text-emerald-400 mb-6">...and focused on getting one single result for one single person.</p>
                
                <p class="text-lg text-gray-300 mb-6">I found a business owner in my network, listened to his problems, and built a simple AI solution. He paid me. It worked.</p>
                <p class="text-lg text-gray-300 mb-6">Suddenly, I had proof. I had a case study. I had confidence.</p>
                <p class="text-lg text-gray-300">And I realized: Conventional courses fail because they give you a map without a vehicle. All theory, zero momentum.</p>
                <p class="text-lg text-gray-300">They teach you to build a car engine piece by piece, but you never actually get to drive.</p>
            </div>
        </div>
    </section>

    <!-- SOLUTION REVELATION -->
    <section class="py-16 md:py-24 bg-gray-900/50">
        <div class="container-wrapper">
            <div class="main-container mx-auto">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">The "Client-First" Method: Get Paid While You Gain Experience</h2>
                
                <p class="text-lg text-gray-300 mb-6 text-center">Imagine skipping the months of self-doubt and trial-and-error...</p>
                <p class="text-lg text-gray-300 mb-10 text-center">...and starting your agency journey with a paying client from day one.</p>

                <div class="bg-gray-800 p-8 rounded-lg border border-gray-700">
                    <p class="text-lg text-gray-300 mb-6">Here's how it works. It's the opposite of every course you've seen.</p>
                    <p class="text-lg text-gray-300 mb-6"><b class="text-white">Step 1:</b> You're accepted into the 1-on-1 mentorship.</p>
                    <p class="text-lg text-gray-300 mb-6"><b class="text-white">Step 2:</b> I personally source a <b class="text-emerald-400">real, paying client</b> for you from my network.</p>
                    <p class="text-lg text-gray-300 mb-6"><b class="text-white">Step 3:</b> We work <b class="text-white">together, 1-on-1,</b> to deliver the work for that client.</p>
                    <p class="text-lg text-gray-300"><b class="text-white">Step 4:</b> You get paid, get your first case study, and gain the skills & confidence to land the next client on your own.</p>
                </div>
                
                <p class="text-xl font-bold text-center my-12">This isn't theory. It's a real-world apprenticeship.</p>

                <div class="bullet-point">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                    <div>
                        <p class="font-bold text-lg">Work on a guaranteed, PAID client project so you build real-world experience immediately. You become an agency owner who gets results, not just a student who consumes content.</p>
                    </div>
                </div>
                <div class="bullet-point">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                    <div>
                        <p class="font-bold text-lg">Get 1-on-1 guidance directly from me on weekly calls. You get your exact questions answered instantly, making you a confident expert who can solve any client problem.</p>
                    </div>
                </div>
                <div class="bullet-point">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                    <div>
                        <p class="font-bold text-lg">Receive all my proven frameworks for client acquisition and service delivery, so you have a repeatable system for growth. You become a true business owner, not just a freelancer chasing the next gig.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- PRODUCT INTRODUCTION -->
    <section class="py-16 md:py-24">
        <div class="container-wrapper">
            <div class="main-container mx-auto text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-8">Introducing The Chase AI Mentorship Program</h2>
                <p class="text-xl text-gray-300 mb-12">This is the only program in the world that gets you a paying client *before* you're expected to be an expert.</p>
                
                <div class="text-left border-2 border-emerald-500 rounded-lg p-8 bg-gray-900">
                    <h3 class="text-2xl font-bold mb-6 text-white">Here's a look at what we'll do together:</h3>
                    <ul class="space-y-4 text-lg text-gray-300">
                        <li class="flex items-start"><span class="text-emerald-400 mr-3 font-bold">✓</span><div><b>One-on-One Coaching:</b> Just you and me. No group calls, no getting lost in a crowd. Your agency is our only focus.</div></li>
                        <li class="flex items-start"><span class="text-emerald-400 mr-3 font-bold">✓</span><div><b>A Guaranteed Real Client:</b> I put my reputation on the line to find you a project. This removes the #1 barrier holding people back.</div></li>
                        <li class="flex items-start"><span class="text-emerald-400 mr-3 font-bold">✓</span><div><b>Joint Work Sessions:</b> We'll build the client's solution side-by-side. You see how a pro operates in real-time, from proposal to delivery.</div></li>
                        <li class="flex items-start"><span class="text-emerald-400 mr-3 font-bold">✓</span><div><b>My Full 'Agency-in-a-Box' Toolkit:</b> You get every template, script, and system I use to run my own six-figure operation.</div></li>
                    </ul>
                </div>
                
                <p class="text-lg mt-12">The typical agency course sells you information and leaves you to figure out the hard parts.</p>
                <p class="text-lg font-bold">We do the hardest part—getting your first client—*for you*.</p>
            </div>
        </div>
    </section>

    <!-- OFFER STRUCTURE -->
    <section id="apply" class="py-16 md:py-24 bg-gray-900/50">
        <div class="container-wrapper">
            <div class="main-container mx-auto text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-8">Ready to Stop Learning and Start Earning?</h2>
                <p class="text-xl text-gray-300 mb-12">If you're accepted, you're not just buying mentorship. You're securing your first client, your first case study, and your first real step toward agency ownership.</p>

                <div class="bg-gray-800 border border-gray-700 rounded-lg p-8 max-w-2xl mx-auto mb-10 text-left">
                    <h3 class="text-2xl font-bold text-center text-white mb-6">Here's Everything You Secure:</h3>
                    <ul class="space-y-4 text-lg">
                        <li class="bullet-point">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                            <span><b class="text-white">3 Months of 1-on-1 Mentorship</b> with Weekly Private Sessions.</span>
                        </li>
                        <li class="bullet-point">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                            <span>A <b class="text-emerald-400">Guaranteed, Hand-Picked Paying Client</b> to work on together.</span>
                        </li>
                         <li class="bullet-point">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                            <span><b class="text-white">Direct-Access Messaging Support</b> for questions between calls.</span>
                        </li>
                        <li class="bullet-point">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                            <span><b class="text-white">Lifetime Access to All My Agency Systems,</b> Contracts, and Client-Getting Scripts.</span>
                        </li>
                    </ul>
                </div>

                <div class="bg-emerald-900/30 border-2 border-emerald-500 rounded-lg p-8 max-w-2xl mx-auto mb-12">
                    <h3 class="text-2xl font-bold text-white mb-4">My "You Get A Client, Or You Don't Pay" Guarantee</h3>
                    <p class="text-lg text-emerald-100">It's simple. If I fail to bring you a real, paying client to work on within the mentorship period, I will refund your entire investment. The risk is entirely on me to deliver.</p>
                </div>
                
                <p class="font-bold text-lg text-yellow-400 mb-6">To ensure I can provide a guaranteed client and personal attention, I only accept 3 new apprentices each month. The application process is selective.</p>

                <a href="#application-form-placeholder" class="cta-button inline-block bg-emerald-500 text-gray-900 font-bold text-xl py-4 px-12 rounded-lg">
                    APPLY NOW TO SECURE YOUR SPOT
                </a>
                <p class="text-sm mt-4 text-gray-400">Applications are reviewed within 48 hours.</p>

            </div>
        </div>
    </section>

    <!-- FAQ SECTION -->
    <section class="py-16 md:py-24">
        <div class="container-wrapper">
            <div class="main-container mx-auto">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">Your Questions, Answered.</h2>

                <div class="space-y-8">
                    <div class="bg-gray-900 p-6 rounded-lg">
                        <h3 class="font-bold text-xl mb-2 text-white">What if I have no technical skills?</h3>
                        <p class="text-gray-300">This isn't a coding bootcamp. It's an agency mentorship. I'll show you how to package and sell AI solutions that often use existing tools. The point of the mentorship is for me to guide you through the technical delivery on the first project, so you learn by doing.</p>
                    </div>
                    <div class="bg-gray-900 p-6 rounded-lg">
                        <h3 class="font-bold text-xl mb-2 text-white">Is the investment worth it?</h3>
                        <p class="text-gray-300">Consider the cost of the alternative: spending another year and thousands of dollars on courses with no results, no clients, and no income. This mentorship is an investment in a guaranteed outcome: your first paying client and the proven experience to get more. You start earning back your investment during the program itself.</p>
                    </div>
                     <div class="bg-gray-900 p-6 rounded-lg">
                        <h3 class="font-bold text-xl mb-2 text-white">How do I know the client is real and not just a setup?</h3>
                        <p class="text-gray-300">My reputation is on the line with every person I mentor. These are real businesses from my professional network who need AI solutions. You'll be on calls with them, you'll see the contract, and you'll receive the payout. My success is directly tied to your success.</p>
                    </div>
                    <div class="bg-gray-900 p-6 rounded-lg">
                        <h3 class="font-bold text-xl mb-2 text-white">I work a full-time job. How much time is needed?</h3>
                        <p class="text-gray-300">This is designed for busy professionals. Expect to dedicate 5-10 hours per week. We have one weekly 1-on-1 call, and the rest is project work you can do on your own schedule. The goal is to build an agency that eventually *replaces* your job, not adds another one to your plate.</p>
                    </div>
                </div>

                <div class="text-center mt-16">
                     <h3 class="text-2xl font-bold text-white mb-6">Stop waiting for the "perfect time". The time is now.</h3>
                     <a href="#apply" class="cta-button inline-block bg-emerald-500 text-gray-900 font-bold text-xl py-4 px-12 rounded-lg">
                        APPLY TO LAUNCH YOUR AI AGENCY
                    </a>
                </div>
            </div>
        </div>
    </section>
    
    <footer class="text-center py-8">
        <div class="container-wrapper">
            <p class="text-gray-500">&copy; 2025 Chase AI Mentorship. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>
