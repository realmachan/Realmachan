
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RealMachan - Your Trusted Partner in Real Estate</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            color: #333;
        }
        .text-primary { color: #007bff; } /* Example primary color */
        .bg-primary { background-color: #007bff; }
        .hover\:bg-primary-dark:hover { background-color: #0056b3; } /* Darker shade for hover */
        .border-primary { border-color: #007bff; }
        .card {
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }
        .card:hover {
            transform: translateY(-5px);
        }
    </style>
</head>
<body class="bg-gray-50">

    <header class="bg-white shadow-md py-4 px-6 md:px-12 flex justify-between items-center sticky top-0 z-50">
        <div class="text-2xl md:text-3xl font-bold text-green-700">RealMachan</div>
        <nav class="hidden md:flex space-x-6">
            <a href="#explore" class="text-gray-600 hover:text-green-700 font-medium">Explore</a>
            <a href="#buyers" class="text-gray-600 hover:text-green-700 font-medium">Buyers</a>
            <a href="#sellers" class="text-gray-600 hover:text-green-700 font-medium">Sellers</a>
            <a href="#about" class="text-gray-600 hover:text-green-700 font-medium">About Us</a>
            <a href="#contact" class="text-gray-600 hover:text-green-700 font-medium">Contact</a>
        </nav>
        <div class="flex items-center space-x-4">
            <a href="https://wa.me/9207074002" target="_blank" class="hidden md:block bg-green-500 text-white px-4 py-2 rounded-full hover:bg-green-600 transition duration-300">Chat on WhatsApp</a>
            <a href="https://www.instagram.com/yourinstagramhandle" target="_blank" class="hidden md:block text-red-500 hover:text-red-700">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-instagram"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg>
            </a>
            <button class="md:hidden text-gray-600 hover:text-green-700 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
            </button>
        </div>
    </header>

    <section class="relative bg-cover bg-center h-96 flex items-center justify-center text-white" style="background-image: url('https://via.placeholder.com/1500x500/6B8E23/FFFFFF?text=Lush+Tea+Plantation+View')">
        <div class="absolute inset-0 bg-black opacity-50"></div>
        <div class="z-10 text-center px-4">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-4 animate-fade-in-up">Welcome to RealMachan</h1>
            <p class="text-xl md:text-2xl font-light">Your trusted partner in real estate.</p>
            <p class="text-lg md:text-xl mt-2">Discover picturesque properties of Kerala beyond India.</p>
            <a href="#explore" class="mt-8 inline-block bg-green-600 text-white px-8 py-3 rounded-full text-lg font-semibold hover:bg-green-700 transition duration-300">Start Exploring</a>
        </div>
    </section>

    <section id="explore" class="py-16 bg-white px-6 md:px-12">
        <h2 class="text-4xl font-bold text-center mb-12 text-gray-800">Explore Your Dream Property</h2>
        <p class="text-center text-lg text-gray-600 mb-10 max-w-3xl mx-auto">
            At RealMachan, finding your ideal property is simple and intuitive. Browse our curated categories, just like scrolling through your favorite feed, and discover unique listings tailored to your desires.
        </p>

        <div class="mb-12 flex flex-wrap justify-center gap-4">
            <button class="px-6 py-2 rounded-full bg-green-100 text-green-800 font-semibold hover:bg-green-200 transition duration-200 focus:outline-none focus:ring-2 focus:ring-green-500 active:bg-green-300">All Properties</button>
            <button class="px-6 py-2 rounded-full bg-blue-100 text-blue-800 font-semibold hover:bg-blue-200 transition duration-200 focus:outline-none focus:ring-2 focus:ring-blue-500 active:bg-blue-300">For Sale</button>
            <button class="px-6 py-2 rounded-full bg-purple-100 text-purple-800 font-semibold hover:bg-purple-200 transition duration-200 focus:outline-none focus:ring-2 focus:ring-purple-500 active:bg-purple-300">For Rent</button>
            <button class="px-6 py-2 rounded-full bg-yellow-100 text-yellow-800 font-semibold hover:bg-yellow-200 transition duration-200 focus:outline-none focus:ring-2 focus:ring-yellow-500 active:bg-yellow-300">Plantations</button>
            <button class="px-6 py-2 rounded-full bg-red-100 text-red-800 font-semibold hover:bg-red-200 transition duration-200 focus:outline-none focus:ring-2 focus:ring-red-500 active:bg-red-300">Residences</button>
            <button class="px-6 py-2 rounded-full bg-indigo-100 text-indigo-800 font-semibold hover:bg-indigo-200 transition duration-200 focus:outline-none focus:ring-2 focus:ring-indigo-500 active:bg-indigo-300">Under ₹50 Lakhs</button>
            <button class="px-6 py-2 rounded-full bg-teal-100 text-teal-800 font-semibold hover:bg-teal-200 transition duration-200 focus:outline-none focus:ring-2 focus:ring-teal-500 active:bg-teal-300">₹50 Lakh - ₹1 Cr</button>
            <button class="px-6 py-2 rounded-full bg-orange-100 text-orange-800 font-semibold hover:bg-orange-200 transition duration-200 focus:outline-none focus:ring-2 focus:ring-orange-500 active:bg-orange-300">₹1 Cr - ₹5 Cr</button>
            <button class="px-6 py-2 rounded-full bg-cyan-100 text-cyan-800 font-semibold hover:bg-cyan-200 transition duration-200 focus:outline-none focus:ring-2 focus:ring-cyan-500 active:bg-cyan-300">₹5 Cr & Above</button>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-8">

            <div class="bg-white rounded-lg overflow-hidden shadow-lg card">
                <img src="https://via.placeholder.com/400x300/A0522D/FFFFFF?text=Mountain+View+Villa" alt="Mountain View Villa" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="font-bold text-xl mb-2 text-gray-800">₹50 Lakh - Mountain View Villa</h3>
                    <p class="text-gray-600 text-sm mb-4">A charming 2BHK villa with stunning views of the Western Ghats, located near Vagamon. Perfect for a peaceful escape or a holiday home.</p>
                    <div class="flex justify-between items-center text-sm text-gray-500 mb-4">
                        <span><strong class="text-gray-700">Type:</strong> Residence, For Sale</span>
                        <span><strong class="text-gray-700">Area:</strong> 1500 sqft</span>
                    </div>
                    <button class="w-full bg-green-600 text-white py-2 rounded-full hover:bg-green-700 transition duration-300">View Details</button>
                </div>
            </div>

            <div class="bg-white rounded-lg overflow-hidden shadow-lg card">
                <img src="https://via.placeholder.com/400x300/8B4513/FFFFFF?text=Hilltop+Cottage" alt="Hilltop Cottage" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="font-bold text-xl mb-2 text-gray-800">₹75 Lakh - Hilltop Cottage</h3>
                    <p class="text-gray-600 text-sm mb-4">A cozy 3BHK cottage nestled on a serene hilltop in Munnar, offering privacy and panoramic landscapes. Ideal for nature lovers.</p>
                    <div class="flex justify-between items-center text-sm text-gray-500 mb-4">
                        <span><strong class="text-gray-700">Type:</strong> Residence, For Sale</span>
                        <span><strong class="text-gray-700">Area:</strong> 2000 sqft</span>
                    </div>
                    <button class="w-full bg-green-600 text-white py-2 rounded-full hover:bg-green-700 transition duration-300">View Details</button>
                </div>
            </div>

            <div class="bg-white rounded-lg overflow-hidden shadow-lg card">
                <img src="https://via.placeholder.com/400x300/556B2F/FFFFFF?text=Tea+Estate+Plot" alt="Tea Estate Plot" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="font-bold text-xl mb-2 text-gray-800">₹1.2 Crore - Budding Tea Estate Plot</h3>
                    <p class="text-gray-600 text-sm mb-4">An expansive 5-acre plot in a developing tea plantation area, perfect for agricultural investment or building a private resort.</p>
                    <div class="flex justify-between items-center text-sm text-gray-500 mb-4">
                        <span><strong class="text-gray-700">Type:</strong> Plantation, For Sale</span>
                        <span><strong class="text-gray-700">Area:</strong> 5 Acres</span>
                    </div>
                    <button class="w-full bg-green-600 text-white py-2 rounded-full hover:bg-green-700 transition duration-300">View Details</button>
                </div>
            </div>

            <div class="bg-white rounded-lg overflow-hidden shadow-lg card">
                <img src="https://via.placeholder.com/400x300/6A5ACD/FFFFFF?text=Riverside+Home" alt="Riverside Home" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="font-bold text-xl mb-2 text-gray-800">₹90,000/month - Riverside Home (Rental)</h3>
                    <p class="text-gray-600 text-sm mb-4">A spacious 4BHK house with direct river access and scenic views, ideal for long-term rental near Periyar. Fully furnished.</p>
                    <div class="flex justify-between items-center text-sm text-gray-500 mb-4">
                        <span><strong class="text-gray-700">Type:</strong> Residence, For Rent</span>
                        <span><strong class="text-gray-700">Area:</strong> 3000 sqft</span>
                    </div>
                    <button class="w-full bg-green-600 text-white py-2 rounded-full hover:bg-green-700 transition duration-300">View Details</button>
                </div>
            </div>

            <div class="bg-white rounded-lg overflow-hidden shadow-lg card">
                <img src="https://via.placeholder.com/400x300/4682B4/FFFFFF?text=Coffee+Estate" alt="Coffee Estate" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="font-bold text-xl mb-2 text-gray-800">₹3.5 Crore - Established Coffee Estate</h3>
                    <p class="text-gray-600 text-sm mb-4">A productive 10-acre coffee estate with mature plants and a small workers' quarters, located in Wayanad. Excellent investment.</p>
                    <div class="flex justify-between items-center text-sm text-gray-500 mb-4">
                        <span><strong class="text-gray-700">Type:</strong> Plantation, For Sale</span>
                        <span><strong class="text-gray-700">Area:</strong> 10 Acres</span>
                    </div>
                    <button class="w-full bg-green-600 text-white py-2 rounded-full hover:bg-green-700 transition duration-300">View Details</button>
                </div>
            </div>

            <div class="bg-white rounded-lg overflow-hidden shadow-lg card">
                <img src="https://via.placeholder.com/400x300/D2B48C/FFFFFF?text=Cozy+Studio+Apartment" alt="Cozy Studio Apartment" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="font-bold text-xl mb-2 text-gray-800">₹25,000/month - Cozy Studio Apartment</h3>
                    <p class="text-gray-600 text-sm mb-4">Compact and modern studio apartment for rent in a serene hillside locality near Kochi, perfect for singles or couples.</p>
                    <div class="flex justify-between items-center text-sm text-gray-500 mb-4">
                        <span><strong class="text-gray-700">Type:</strong> Residence, For Rent</span>
                        <span><strong class="text-gray-700">Area:</strong> 600 sqft</span>
                    </div>
                    <button class="w-full bg-green-600 text-white py-2 rounded-full hover:bg-green-700 transition duration-300">View Details</button>
                </div>
            </div>

            <div class="bg-white rounded-lg overflow-hidden shadow-lg card">
                <img src="https://via.placeholder.com/400x300/6B8E23/FFFFFF?text=Lakeside+Plot" alt="Lakeside Plot" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="font-bold text-xl mb-2 text-gray-800">₹85 Lakh - Lakeside Development Plot</h3>
                    <p class="text-gray-600 text-sm mb-4">A prime 1-acre plot directly on the lakefront, ideal for building a custom villa or a boutique resort. High appreciation potential.</p>
                    <div class="flex justify-between items-center text-sm text-gray-500 mb-4">
                        <span><strong class="text-gray-700">Type:</strong> For Sale, Land</span>
                        <span><strong class="text-gray-700">Area:</strong> 1 Acre</span>
                    </div>
                    <button class="w-full bg-green-600 text-white py-2 rounded-full hover:bg-green-700 transition duration-300">View Details</button>
                </div>
            </div>

            <div class="bg-white rounded-lg overflow-hidden shadow-lg card">
                <img src="https://via.placeholder.com/400x300/483D8B/FFFFFF?text=Luxury+Bungalow" alt="Luxury Bungalow" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="font-bold text-xl mb-2 text-gray-800">₹6 Crore - Grand Luxury Bungalow</h3>
                    <p class="text-gray-600 text-sm mb-4">An exquisite 5BHK luxury bungalow with sprawling gardens and panoramic hill views, featuring modern amenities and classic charm.</p>
                    <div class="flex justify-between items-center text-sm text-gray-500 mb-4">
                        <span><strong class="text-gray-700">Type:</strong> Residence, For Sale</span>
                        <span><strong class="text-gray-700">Area:</strong> 6000 sqft</span>
                    </div>
                    <button class="w-full bg-green-600 text-white py-2 rounded-full hover:bg-green-700 transition duration-300">View Details</button>
                </div>
            </div>

        </div> </section>

    <section id="buyers" class="py-16 bg-gray-100 px-6 md:px-12">
        <h2 class="text-4xl font-bold text-center mb-8 text-gray-800">For Buyers</h2>
        <p class="text-center text-lg text-gray-600 mb-10 max-w-3xl mx-auto">
            Your dream property is just a few clicks away. We offer personalized assistance and detailed insights into each listing to help you make the best decision.
        </p>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-5xl mx-auto">
            <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                <h3 class="text-xl font-semibold mb-3 text-green-700">Curated Listings</h3>
                <p class="text-gray-600">Access exclusive properties in nature-rich destinations, perfect for peacefulliving or smart investment.</p>
            </div>
            <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                <h3 class="text-xl font-semibold mb-3 text-green-700">Expert Guidance</h3>
                <p class="text-gray-600">Our experienced team provides comprehensive support from inquiry to acquisition.</p>
            </div>
            <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                <h3 class="text-xl font-semibold mb-3 text-green-700">Seamless Process</h3>
                <p class="text-gray-600">We streamline the buying process, ensuring a smooth and hassle-free experience.</p>
            </div>
        </div>
        <div class="text-center mt-12">
            <a href="#contact" class="inline-block bg-green-600 text-white px-8 py-3 rounded-full text-lg font-semibold hover:bg-green-700 transition duration-300">Talk to a Buyer's Agent</a>
        </div>
    </section>

    <section id="sellers" class="py-16 bg-white px-6 md:px-12">
        <h2 class="text-4xl font-bold text-center mb-8 text-gray-800">For Sellers</h2>
        <p class="text-center text-lg text-gray-600 mb-10 max-w-3xl mx-auto">
            List your unique property with RealMachan and connect with a wide network of genuine, interested buyers from across the globe. We highlight what makes your property special.
        </p>
        <div class="max-w-3xl mx-auto bg-gray-50 p-8 rounded-lg shadow-lg">
            <h3 class="text-2xl font-semibold mb-6 text-green-700 text-center">Ready to List Your Property?</h3>
            <p class="text-gray-700 text-center mb-6">
                RealMachan offers tailored marketing strategies to showcase your property's unique charm and reach the right audience. Whether it's a sprawling tea estate, a cozy hillside cottage, or a riverside retreat, we ensure it stands out.
            </p>
            <div class="text-center">
                <a href="#contact" class="inline-block bg-blue-600 text-white px-8 py-3 rounded-full text-lg font-semibold hover:bg-blue-700 transition duration-300">Contact Us to List Your Property</a>
            </div>
        </div>
    </section>

    <section id="about" class="py-16 bg-gray-100 px-6 md:px-12">
        <h2 class="text-4xl font-bold text-center mb-8 text-gray-800">About RealMachan</h2>
        <div class="max-w-4xl mx-auto text-center text-lg text-gray-700">
            <p class="mb-6">
                RealMachan is your dedicated partner in navigating the unique and picturesque real estate market of india. With our deep local knowledge, especially in kerala and an extensive network, we ensure a seamless experience for both buyers and sellers.
            </p>
            <p class="mb-6">
                Our mission is to connect people with their dream properties in these idyllic locales, be it a cozy hill station cottage, a sprawling tea estate, a peaceful riverside retreat, or a vibrant residency. We pride ourselves on transparency, integrity, and a personalized approach to real estate.
            </p>
            <p>
                Trust RealMachan to help you find your perfect piece of paradise in the enchanting landscapes of Kerala.
            </p>
        </div>
    </section>

    <section id="contact" class="py-16 bg-white px-6 md:px-12">
        <h2 class="text-4xl font-bold text-center mb-8 text-gray-800">Get in Touch</h2>
        <div class="max-w-2xl mx-auto bg-gray-50 p-8 rounded-lg shadow-lg">
            <p class="text-center text-lg text-gray-700 mb-6">
                Have questions, need assistance, or want to discuss a specific property? Our team is here to help!
            </p>
            <form action="#" method="POST" class="space-y-6">
                <div>
                    <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Your Name</label>
                    <input type="text" id="name" name="name" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-green-500 focus:border-green-500 sm:text-sm" placeholder="John Doe">
                </div>
                <div>
                    <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Your Email</label>
                    <input type="email" id="email" name="email" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-green-500 focus:border-green-500 sm:text-sm" placeholder="john.doe@example.com">
                </div>
                <div>
                    <label for="phone" class="block text-sm font-medium text-gray-700 mb-1">Phone Number (Optional)</label>
                    <input type="tel" id="phone" name="phone" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-green-500 focus:border-green-500 sm:text-sm" placeholder="+91 9207074002">
                </div>
                <div>
                    <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Your Message</label>
                    <textarea id="message" name="message" rows="5" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-green-500 focus:border-green-500 sm:text-sm" placeholder="Tell us about your property needs or inquiry..."></textarea>
                </div>
                <div class="text-center">
                    <button type="submit" class="inline-flex justify-center py-3 px-8 border border-transparent shadow-sm text-base font-medium rounded-full text-white bg-green-600 hover:bg-green-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-green-500 transition duration-300">Send Message</button>
                </div>
            </form>
            <div class="text-center mt-8 text-gray-600">
                <p>Alternatively, reach us directly:</p>
                <p class="mt-2 text-xl font-semibold text-green-700">Phone: +91-XXXXXXXXXX</p>
                <p class="mt-1 text-xl font-semibold text-green-700">Email: info@realmachan.com</p>
                <p class="mt-4 text-sm">Address: [Your Office Address], Kochi, Kerala, India</p>
            </div>
        </div>
    </section>

    <footer class="bg-gray-800 text-white py-8 px-6 md:px-12 text-center">
        <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-8">
            <div>
                <h4 class="text-xl font-bold mb-4">RealMachan</h4>
                <p class="text-gray-400">Your trusted partner in real estate across tea plantations and hills.</p>
                <div class="flex justify-center space-x-4 mt-4">
                    <a href="https://wa.me/yourphonenumber" target="_blank" class="text-gray-400 hover:text-white">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor" class="feather feather-whatsapp"><path d="M12.001 2.001C6.478 2.001 2 6.479 2 12.001c0 2.508.91 4.805 2.454 6.551L2.015 22.01l4.004-1.288A9.957 9.957 0 0 0 12.001 22.001c5.523 0 10-4.478 10-10C22.001 6.479 17.523 2.001 12.001 2.001zm3.623 13.928c-.198.37-.872.482-1.298.243-.427-.24-.657-.34-.94-.492a7.042 7.042 0 0 1-2.073-1.12c-.57-.49-.96-1.07-1.173-1.46-.213-.39-.022-.602.16-.79l.5-.59c.18-.21.28-.35.41-.53.13-.18.26-.41.38-.6.12-.19.1-.35-.06-.51l-.4-.51c-.16-.16-.3-.21-.44-.24-.14-.03-.28-.02-.43-.02-.14 0-.3-.02-.45-.02-.16 0-.38.06-.58.26-.2.2-.76.75-.76 1.83s.77 2.12.87 2.26c.1.14 1.51 2.3 3.65 3.12 2.14.82 2.57.7 3.03.62.46-.09.91-.48 1.05-.71.14-.23.14-.42.06-.57-.08-.15-.24-.32-.4-.51z"></path></svg>
                    </a>
                    <a href="https://www.instagram.com/yourinstagramhandle" target="_blank" class="text-gray-400 hover:text-white">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-instagram"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg>
                    </a>
                </div>
            </div>
            <div>
                <h4 class="text-xl font-bold mb-4">Quick Links</h4>
                <ul class="space-y-2">
                    <li><a href="#explore" class="text-gray-400 hover:text-white">Explore Properties</a></li>
                    <li><a href="#buyers" class="text-gray-400 hover:text-white">For Buyers</a></li>
                    <li><a href="#sellers" class="text-gray-400 hover:text-white">For Sellers</a></li>
                    <li><a href="#about" class="text-gray-400 hover:text-white">About Us</a></li>
                    <li><a href="#contact" class="text-gray-400 hover:text-white">Contact Us</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-xl font-bold mb-4">Locations</h4>
                <ul class="space-y-2 text-gray-400">
                    <li>Kochi</li>
                    <li>Munnar</li>
                    <li>Vagamon</li>
                    <li>Wayanad</li>
                    <li>Thekkady</li>
                    <li>Alleppey</li>
                </ul>
            </div>
        </div>
        <div class="border-t border-gray-700 mt-8 pt-6 text-sm text-gray-400">
            &copy; 2025 RealMachan. All rights reserved.
        </div>
    </footer>

</body>
</html>

<!--
**realmachan/Realmachan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
