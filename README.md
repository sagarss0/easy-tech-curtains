<!DOCTYPE html>
<html lang="hi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Easy Tech Innovation</title>
    
    <!-- External CSS (if needed) -->
    <link rel="stylesheet" href="style.css">
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800 font-sans relative">

    <!-- 1. Header / Navigation -->
    <header class="bg-white shadow-sm sticky top-0 z-40">
        <div class="max-w-7xl mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fa-solid fa-hospital-user text-blue-600 text-2xl"></i>
                <span class="text-xl font-bold text-gray-900">Easy Tech Innovation <span class="text-blue-600">Curtains</span></span>
            </div>
            <nav class="hidden md:flex space-x-6 font-medium text-gray-600">
                <a href="#products" class="hover:text-blue-600 transition">Products</a>
                <a href="certifications.html" target="_blank" class="hover:text-blue-600 transition">Certifications</a>
                <a href="#why-us" class="hover:text-blue-600 transition">Why Choose Us</a>
                <a href="#contact" class="hover:text-blue-600 transition">Contact Us</a>
            </nav>
            <a href="https://wa.me/9873205829" target="_blank" class="bg-green-600 text-white px-4 py-2 rounded-lg font-medium flex items-center gap-2 hover:bg-green-700 transition">
                <i class="fa-brands fa-whatsapp text-lg"></i> WhatsApp
            </a>
        </div>
    </header>

    <!-- 2. Hero Section -->
    <section class="bg-gradient-to-r from-blue-900 to-blue-700 text-white py-16 px-4">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-8 items-center">
            <div>
                <span class="bg-blue-500 text-xs uppercase px-3 py-1 rounded-full font-semibold tracking-wide">ISO & NFPA 701 Certified</span>
                <h1 class="text-3xl md:text-5xl font-extrabold mt-4 leading-tight">
                    Medical-Grade Anti-Bacterial & Fire Retardant Hospital Curtains
                </h1>
                <p class="mt-4 text-blue-100 text-lg">
                    Hospitals, ICUs aur Clinics ke liye premium cubicle curtains, heavy-duty ceiling tracks aur complete installation solutions.
                </p>
                <div class="mt-6 flex flex-wrap gap-4">
                    <a href="#quote" class="bg-white text-blue-900 font-bold px-6 py-3 rounded-lg hover:bg-gray-100 shadow-md transition">
                        Get Bulk Estimate
                    </a>
                    <button onclick="openModal()" class="border border-white text-white font-bold px-6 py-3 rounded-lg hover:bg-white hover:text-blue-900 transition">
                        View Lab Reports
                    </button>
                </div>
            </div>
            
            <!-- Quick Lead Form -->
            <div id="quote" class="bg-white text-gray-900 p-6 rounded-xl shadow-2xl">
                <h3 class="text-xl font-bold mb-2 text-blue-900">Query</h3>
                <p class="text-sm text-gray-500 mb-4">Direct bulk pricing & sample kit delivery ke liye form bhrein.</p>
                
                <!-- Success Message Container -->
                <div id="formSuccess" class="hidden bg-green-100 border border-green-400 text-green-700 px-4 py-3 rounded-lg mb-4 text-sm font-medium">
                    <i class="fa-solid fa-circle-check mr-1"></i> Your requirement has been submitted! We will contact you soon.
                </div>

                <!-- Form -->
                <form id="leadForm" onsubmit="handleFormSubmit(event)" class="space-y-3">
                    <input type="text" id="hospitalName" placeholder="Hospital / Business Name" required class="w-full p-2.5 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-600 outline-none">
                    <input type="text" id="contactPerson" placeholder="Contact Person & Phone Number" required class="w-full p-2.5 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-600 outline-none">
                    <div class="grid grid-cols-2 gap-2">
                        <input type="text" id="city" placeholder="City / Location" required class="p-2.5 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-600 outline-none">
                        <input type="number" id="bedCount" placeholder="Approx. Beds Count" required class="p-2.5 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-600 outline-none">
                    </div>
                    <button type="submit" class="w-full bg-blue-600 text-white font-bold py-3 rounded-lg hover:bg-blue-700 transition">
                        Submit Requirement
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- 3. Product Catalog Section -->
    <section id="products" class="py-16 max-w-7xl mx-auto px-4">
        <div class="text-center max-w-3xl mx-auto mb-12">
            <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">Our Specialized Offerings</h2>
            <p class="mt-3 text-lg text-gray-600">High-grade medical fabric meeting international hygiene & safety standards.</p>
        </div>

        <div class="grid md:grid-cols-3 gap-8">
            <!-- Product 1 -->
            <div class="bg-white rounded-2xl shadow-lg border border-gray-100 overflow-hidden hover:shadow-xl transition duration-300 flex flex-col justify-between">
                <div>
                    <div class="h-48 bg-blue-50 flex flex-col items-center justify-center border-b border-gray-100 text-blue-600">
                        <i class="fa-solid fa-shield-virus text-5xl mb-2"></i>
                        <span class="text-xs font-semibold tracking-wider uppercase text-blue-800">ISO 20743 Certified</span>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-900">Anti-Microbial Fabric Curtains</h3>
                        <p class="text-sm text-gray-600 mt-2 leading-relaxed">
                            Medical-grade fabric that inhibits the growth of MRSA and hazardous bacteria by 99.9%. Perfect for ICUs and operating theatres.
                        </p>
                        <div class="mt-4 space-y-2">
                            <div class="flex items-center text-xs text-gray-500 font-medium">
                                <i class="fa-solid fa-check text-green-500 mr-2"></i> Custom Mesh Upper Option (Sprinkler Safe)
                            </div>
                            <div class="flex items-center text-xs text-gray-500 font-medium">
                                <i class="fa-solid fa-check text-green-500 mr-2"></i> Stain Resistant & 100% Washable
                            </div>
                        </div>
                    </div>
                </div>
                <div class="p-6 pt-0 flex items-center justify-between border-t border-gray-50 mt-4">
                    <span class="text-xs bg-blue-100 text-blue-800 font-bold px-3 py-1 rounded-full">Anti-Bacterial</span>
                    <a href="https://rjocurtains.com/" target="_blank" class="text-blue-600 font-bold text-sm hover:text-blue-800 flex items-center gap-1">
                        Inquire Now <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>
            </div>

            <!-- Product 2 -->
            <div class="bg-white rounded-2xl shadow-lg border border-gray-100 overflow-hidden hover:shadow-xl transition duration-300 flex flex-col justify-between">
                <div>
                    <div class="h-48 bg-red-50 flex flex-col items-center justify-center border-b border-gray-100 text-red-600">
                        <i class="fa-solid fa-fire-extinguisher text-5xl mb-2"></i>
                        <span class="text-xs font-semibold tracking-wider uppercase text-red-800">NFPA 701 Certified</span>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-900">Fire Retardant (IFR) Curtains</h3>
                        <p class="text-sm text-gray-600 mt-2 leading-relaxed">
                           Curtains made from Inherent Flame Retardant (IFR) polyester yarn that prevent the spread of fire; ideal for hospital safety audits.
                        </p>
                        <div class="mt-4 space-y-2">
                            <div class="flex items-center text-xs text-gray-500 font-medium">
                                <i class="fa-solid fa-check text-green-500 mr-2"></i> Wash-proof Permanent Flame Resistance
                            </div>
                            <div class="flex items-center text-xs text-gray-500 font-medium">
                                <i class="fa-solid fa-check text-green-500 mr-2"></i> Heavy-duty Gliding Grommets Included
                            </div>
                        </div>
                    </div>
                </div>
                <div class="p-6 pt-0 flex items-center justify-between border-t border-gray-50 mt-4">
                    <span class="text-xs bg-red-100 text-red-800 font-bold px-3 py-1 rounded-full">Fire Safe</span>
                    <a href="https://scienceinsights.org/what-is-fire-resistance-and-how-is-it-measured/" target="_blank" class="text-blue-600 font-bold text-sm hover:text-blue-800 flex items-center gap-1">
                        Inquire Now <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>
            </div>

            <!-- Product 3 -->
            <div class="bg-white rounded-2xl shadow-lg border border-gray-100 overflow-hidden hover:shadow-xl transition duration-300 flex flex-col justify-between">
                <div>
                    <div class="h-48 bg-green-50 flex flex-col items-center justify-center border-b border-gray-100 text-green-600">
                        <i class="fa-solid fa-recycle text-5xl mb-2"></i>
                        <span class="text-xs font-semibold tracking-wider uppercase text-green-800">100% Recyclable</span>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-900">Disposable Non-Woven Curtains</h3>
                        <p class="text-sm text-gray-600 mt-2 leading-relaxed">
                            High-risk infection Wards aur ICUs ke liye cost-effective solution. Cross-contamination roknay ke liye quick-replacement feature.
                        </p>
                        <div class="mt-4 space-y-2">
                            <div class="flex items-center text-xs text-gray-500 font-medium">
                                <i class="fa-solid fa-check text-green-500 mr-2"></i> Pre-treated Anti-Microbial Shield
                            </div>
                            <div class="flex items-center text-xs text-gray-500 font-medium">
                                <i class="fa-solid fa-check text-green-500 mr-2"></i> Lightweight & Easy Hook Attachment
                            </div>
                        </div>
                    </div>
                </div>
                <div class="p-6 pt-0 flex items-center justify-between border-t border-gray-50 mt-4">
                    <span class="text-xs bg-green-100 text-green-800 font-bold px-3 py-1 rounded-full">Disposable</span>
                    <a href="https://rkcotweaving.com/100-polyester-fabric/" target="_blank" class="text-blue-600 font-bold text-sm hover:text-blue-800 flex items-center gap-1">
                        Inquire Now <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. Why Choose Us Section (Matched Exact Dark Royal Blue) -->
    <section id="why-us" class="bg-[#0d3ea8] text-white py-20 px-4">
        <div class="max-w-7xl mx-auto text-center">
            
            <!-- Subheading Tag -->
            <div class="flex items-center justify-center gap-2 mb-3">
                <span class="h-[1px] w-8 bg-blue-300"></span>
                <span class="text-blue-200 text-xs uppercase tracking-widest font-semibold">Why Choose Us</span>
                <span class="h-[1px] w-8 bg-blue-300"></span>
            </div>

            <h2 class="text-3xl md:text-5xl font-bold tracking-tight mb-4 text-white">
                Built on quality & commitment
            </h2>
            <p class="text-blue-100 max-w-2xl mx-auto text-base md:text-lg mb-16">
                Hospitals and homes across Delhi NCR trust Easy Tech Innovation for products that perform day after day.
            </p>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 text-left">
                
                <!-- Card 1 -->
                <div class="bg-[#092c7d] border border-blue-500/30 p-8 rounded-2xl hover:border-white/50 transition duration-300 flex flex-col justify-between shadow-lg">
                    <div>
                        <span class="text-blue-300 font-mono text-sm font-bold block mb-6">01</span>
                        <div class="w-12 h-12 rounded-xl bg-blue-600 text-white flex items-center justify-center mb-6 shadow-md">
                            <i class="fa-solid fa-hospital-user text-xl"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3 text-white">Quality First</h3>
                        <p class="text-blue-100 text-sm leading-relaxed">
                            Every curtain and track is inspected against strict standards before it leaves our workshop.
                        </p>
                    </div>
                </div>

                <!-- Card 2 -->
                <div class="bg-[#092c7d] border border-blue-500/30 p-8 rounded-2xl hover:border-white/50 transition duration-300 flex flex-col justify-between shadow-lg">
                    <div>
                        <span class="text-blue-300 font-mono text-sm font-bold block mb-6">02</span>
                        <div class="w-12 h-12 rounded-xl bg-blue-600 text-white flex items-center justify-center mb-6 shadow-md">
                            <i class="fa-regular fa-heart text-xl"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3 text-white">Customer Commitment</h3>
                        <p class="text-blue-100 text-sm leading-relaxed">
                            Clear timelines, honest advice and a single point of contact from enquiry to handover.
                        </p>
                    </div>
                </div>

                <!-- Card 3 -->
                <div class="bg-[#092c7d] border border-blue-500/30 p-8 rounded-2xl hover:border-white/50 transition duration-300 flex flex-col justify-between shadow-lg">
                    <div>
                        <span class="text-blue-300 font-mono text-sm font-bold block mb-6">03</span>
                        <div class="w-12 h-12 rounded-xl bg-blue-600 text-white flex items-center justify-center mb-6 shadow-md">
                            <i class="fa-solid fa-layer-group text-xl"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3 text-white">Durable Materials</h3>
                        <p class="text-blue-100 text-sm leading-relaxed">
                            Heavy-duty, easy-clean fabrics and corrosion-resistant tracks engineered for years of use.
                        </p>
                    </div>
                </div>

                <!-- Card 4 -->
                <div class="bg-[#092c7d] border border-blue-500/30 p-8 rounded-2xl hover:border-white/50 transition duration-300 flex flex-col justify-between shadow-lg">
                    <div>
                        <span class="text-blue-300 font-mono text-sm font-bold block mb-6">04</span>
                        <div class="w-12 h-12 rounded-xl bg-blue-600 text-white flex items-center justify-center mb-6 shadow-md">
                            <i class="fa-regular fa-clock text-xl"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3 text-white">Timely Delivery</h3>
                        <p class="text-blue-100 text-sm leading-relaxed">
                            Efficient in-house production keeps projects on schedule, from single rooms to full facilities.
                        </p>
                    </div>
                </div>

            </div>
        </div>
    </section>
    <!-- 5. Contact Us Section -->
    <footer id="contact" class="bg-gray-900 text-white py-12 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 grid md:grid-cols-2 gap-8 items-center">
            <div>
                <h2 class="text-2xl font-bold text-white mb-4">Contact Us</h2>
                <p class="text-gray-400 mb-6">Contact us For Further Inquiry.</p>
                <div class="space-y-4">
                    <div class="flex items-center space-x-3 text-lg">
                        <i class="fa-solid fa-phone text-blue-500 text-xl"></i>
                        <a href="tel:9873205829" class="hover:text-blue-400 transition">+91 9873205829</a>
                    </div>
                    <div class="flex items-center space-x-3 text-lg">
                        <i class="fa-solid fa-envelope text-blue-500 text-xl"></i>
                        <a href="mailto:Ssharma11299@gmail.com" class="hover:text-blue-400 transition">Ssharma11299@gmail.com</a>
                    </div>
                </div>
            </div>

            <div class="bg-gray-800 p-6 rounded-xl text-center md:text-left border border-gray-700">
                <h3 class="text-xl font-bold text-white mb-2">Instant Support</h3>
                <p class="text-gray-400 text-sm mb-4">Click Here For Whatsapp</p>
                <a href="https://wa.me/9873205829" target="_blank" class="inline-flex items-center gap-2 bg-green-600 hover:bg-green-700 text-white font-bold px-6 py-3 rounded-lg transition">
                    <i class="fa-brands fa-whatsapp text-xl"></i> Chat on WhatsApp
                </a>
            </div>
        </div>

        <div class="mt-12 text-center text-sm text-gray-500 border-t border-gray-800 pt-6">
            &copy; Easy Tech Innovation. All Rights Reserved.
        </div>
    </footer>

    <!-- 6. Floating Action Buttons (WhatsApp & Phone) -->
    <div class="fixed bottom-6 right-6 z-50 flex flex-col gap-3">
        <a href="https://wa.me/9873205829" target="_blank" aria-label="Chat on WhatsApp" class="w-14 h-14 bg-emerald-500 hover:bg-emerald-600 text-white rounded-full flex items-center justify-center shadow-2xl transition-all duration-300 hover:scale-110 border-2 border-white/20">
            <i class="fa-brands fa-whatsapp text-3xl"></i>
        </a>
        <a href="tel:9873205829" aria-label="Call Us" class="w-14 h-14 bg-[#0e5c6b] hover:bg-[#0b4854] text-white rounded-full flex items-center justify-center shadow-2xl transition-all duration-300 hover:scale-110 border-2 border-white/20">
            <i class="fa-solid fa-phone text-2xl"></i>
        </a>
    </div>

    <!-- LAB REPORT POPUP MODAL -->
    <div id="reportModal" class="fixed inset-0 bg-black/70 hidden items-center justify-center z-50 p-4">
        <div class="bg-white rounded-2xl max-w-2xl w-full p-6 relative shadow-2xl overflow-hidden">
            <button onclick="closeModal()" class="absolute top-4 right-4 text-gray-500 hover:text-red-600 text-2xl font-bold transition">
                &times;
            </button>
            <h3 class="text-xl font-bold text-gray-900 mb-4 flex items-center gap-2">
                <i class="fa-solid fa-file-contract text-blue-600"></i>
                NABL Accredited Lab Test Report
            </h3>
            <div class="max-h-[70vh] overflow-y-auto rounded-lg border border-gray-200">
                <img src="https://via.placeholder.com/800x1000?text=Lab+Report+Image+Here" alt="Lab Report Certificate" class="w-full h-auto">
            </div>
            <div class="mt-4 text-right">
                <button onclick="closeModal()" class="bg-gray-800 text-white px-5 py-2 rounded-lg font-medium hover:bg-gray-900 transition">
                    Close
                </button>
            </div>
        </div>
    </div>

    <!-- JavaScript Functions -->
    <script>
        // Modal Handlers
        function openModal() {
            document.getElementById('reportModal').classList.remove('hidden');
            document.getElementById('reportModal').classList.add('flex');
        }

        function closeModal() {
            document.getElementById('reportModal').classList.remove('flex');
            document.getElementById('reportModal').classList.add('hidden');
        }

        // Form Submit Handler
        function handleFormSubmit(event) {
            event.preventDefault();
            
            const successMsg = document.getElementById('formSuccess');
            successMsg.classList.remove('hidden');

            const name = document.getElementById('hospitalName').value;
            const contact = document.getElementById('contactPerson').value;
            const city = document.getElementById('city').value;
            const beds = document.getElementById('bedCount').value;

            const waText = `New Lead Requirement:%0A- *Hospital:* ${name}%0A- *Contact:* ${contact}%0A- *City:* ${city}%0A- *Beds:* ${beds}`;
            
            document.getElementById('leadForm').reset();

            setTimeout(() => {
                window.open(`https://wa.me/9873205829?text=${waText}`, '_blank');
            }, 1000);
        }
    </script>

</body>
</html>
