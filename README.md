<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>ICEMR 2025 - SBMJFGC, KGF</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Typography & layout */
    body { font-family: "Times New Roman", Times, serif; background: linear-gradient(135deg,#f0f4ff 0%, #fff0f6 50%, #fff9e6 100%); }
    header, section { scroll-margin-top: 80px; }
    p, li { text-align: justify; line-height: 1.5; }
    h1,h2,h3 { font-weight: 700; }
    h1 { font-size: 2rem; }
    /* Animations */
    .fade-in { animation: fadeIn .9s ease both; }
    @keyframes fadeIn { from { opacity: 0; transform: translateY(8px);} to { opacity:1; transform: translateY(0);} }
    /* Accordion */
    .accordion { cursor: pointer; padding: .6rem 1rem; width: 100%; text-align: left; border-radius: .5rem; border: 1px solid rgba(99,102,241,.12); background: rgba(99,102,241,.04); transition: all .25s; font-weight:700; }
    .accordion:hover { transform: translateY(-3px); box-shadow: 0 6px 18px rgba(15,23,42,.06); }
    .panel { display: none; padding: .8rem 1rem; margin-top: .5rem; background: rgba(243,244,246,1); border-left: 4px solid #6366f1; border-radius: .25rem; }
    /* responsive container */
    .container { max-width: 1100px; margin-left: auto; margin-right: auto; padding: 1.25rem; }
    /* nav */
    nav { position: fixed; inset: 0 auto auto 0; right: 0; left: 0; top: 0; z-index: 60; backdrop-filter: blur(6px); }
    .navlink { transition: color .15s, transform .15s; }
    .navlink:hover { transform: translateY(-2px); color: #f59e0b; }
    /* table */
    table { border-collapse: collapse; width: 100%; }
    th, td { border: 1px solid rgba(99,102,241,.18); padding: .6rem; text-align:left; }
    thead th { background: rgba(99,102,241,.08); font-weight:700; }
    /* small screens adjust */
    @media (max-width: 640px) {
      h1 { font-size: 1.25rem; }
      .container { padding: .75rem; }
    }
  </style>
</head>
<body>

  <!-- NAV -->
  <nav class="bg-indigo-900 text-white">
    <div class="container flex items-center justify-between py-3">
      <div class="flex items-center gap-3">
        <div class="rounded-full bg-white/10 p-2"><strong>ICEMR</strong></div>
        <div>
          <div class="text-sm font-semibold">International Conference on Emerging Frontiers in Materials Science (ICEMR - 2025)</div>
          <div class="text-xs text-indigo-200">22nd - 23rd December 2025 · Hybrid Mode</div>
        </div>
      </div>

      <div class="hidden md:flex items-center gap-4 text-sm">
        <a class="navlink" href="#college">College</a>
        <a class="navlink" href="#dept">Department</a>
        <a class="navlink" href="#kprg">KPRG</a>
        <a class="navlink" href="#conference">Conference</a>
        <a class="navlink" href="#topics">Topics</a>
        <a class="navlink" href="#venue">Venue</a>
        <a class="navlink" href="#committees">Committees</a>
        <a class="navlink" href="#papers">Call for Papers</a>
        <a class="navlink" href="#registration">Registration</a>
        <a class="navlink" href="#contact">Contact</a>
      </div>
    </div>
  </nav>

  <!-- HERO -->
  <header class="pt-28 pb-12 text-center fade-in">
    <div class="container">
      <h1 class="text-3xl md:text-4xl text-indigo-900">International Conference on Emerging Frontiers in Materials Science & Radiation Physics (ICEMR - 2025)</h1>
      <p class="mt-4 text-sm md:text-base text-gray-700">Jointly organised by the Department of Physical and Life Science, Sri Bhagawan Mahaveer Jain First Grade College (SBMJFGC), KGF and Kolar Physics Research Group (KPRG), Government First Grade College, Devanahalli. Dates: <strong>22nd & 23rd December 2025</strong>. Hybrid mode.</p>
      <div class="mt-6 inline-flex gap-3">
        <a href="#papers" class="px-4 py-2 bg-indigo-700 text-white rounded shadow hover:bg-indigo-800">Call for Papers</a>
        <a href="#registration" class="px-4 py-2 bg-yellow-500 text-indigo-900 rounded shadow hover:bg-yellow-600">Register</a>
      </div>
    </div>
  </header>

  <main class="container space-y-8">

    <!-- College -->
    <section id="college" class="bg-white p-6 rounded-lg shadow fade-in">
      <h2 class="text-indigo-800 text-xl mb-2">College</h2>
      <p>
        SBMJFGC, KGF is the 21st constituent of the JGI, located in the heart of the town, and is committed to providing quality-oriented education to the rural community while fostering a culture of effective learning. The institution has completed two decades of dedicated service in the field of education, nurturing inquisitive minds and preparing learners to face challenges with zeal and confidence. It has been re-accredited by NAAC. The institution ensures equal opportunities for growth and development for every learner, empowering them to meet the relentless challenges of the modern world.
      </p>
    </section>

    <!-- Department -->
    <section id="dept" class="bg-white p-6 rounded-lg shadow fade-in">
      <h2 class="text-indigo-800 text-xl mb-2">Department of Science</h2>
      <p>
        The institution offers several branches of science, including Physics, Mathematics, Computer Science, Biotechnology, Biochemistry, and Genetics. The Department of Sciences strives to cultivate excellence among young creative minds and inspire innovative ideas, while fostering the value of learning and the dissemination of scientific knowledge.
      </p>
    </section>

    <!-- KPRG -->
    <section id="kprg" class="bg-white p-6 rounded-lg shadow fade-in">
      <h2 class="text-indigo-800 text-xl mb-2">Kolar Physics Research Group (KPRG)</h2>
      <p>
        The Kolar Physics Research Group (KPRG) is a premier centre for nuclear and materials research, with 35 active scholars, including 8 doctorates, headed by Dr. H.C. Manjunatha, Professor, Department of Physics, Government First Grade College, Devanahalli, Karnataka. The group has published over 350 research papers and earned several national awards.
      </p>
      <p>
        The research covers Nuclear Theory and Superheavy Elements (Z = 119–123), with emphasis on isotope prediction and theoretical models for alpha decay, cluster decay, fission, and proton radioactivity. In the area of reaction dynamics, the group investigates quasifission processes, entrance channel influences, and fusion barrier trends. Alongside this, KPRG actively contributes to nanoscience, focusing on photoluminescent nanoparticles, supercapacitors, triboelectric nanogenerators, and biomedical advancements, including radiation shielding and targeted drug delivery.
      </p>
      <p>
        The research group places strong emphasis on student development, mentoring MSc projects and supervising PhD scholars, and fosters international collaboration. Its active associations with IUAC, BARC, RIKEN (Japan), and research teams in Taiwan enhance its global reach and strengthen its role in advancing nuclear science.
      </p>
    </section>

    <!-- Conference -->
    <section id="conference" class="bg-gradient-to-r from-green-50 to-blue-50 p-6 rounded-lg shadow fade-in">
      <h2 class="text-indigo-900 text-xl mb-2">Conference Overview</h2>
      <p>
        Material science and radiation physics have become the backbone of modern technological progress, driving innovations that are reshaping industries and everyday life. The International Conference on Emerging Frontiers in Materials Science (ICEMR - 2025) is jointly organised by the Department of Physical and Life Science of SBMJFGC, KGF, Karnataka, India, and Kolar Research Group, GFGC, Devanahalli, Karnataka, India, on <strong>22nd and 23rd December 2025</strong>. This conference will be conducted in hybrid mode, and will be a premier platform that brings together researchers, academicians, industry experts, and students from across the globe to exchange knowledge, present innovations, and discuss emerging trends in the field of materials science and radiation physics.
      </p>
      <p>
        On the first day, the conference will emphasise recent advancements in nanomaterials, biomaterials, functional materials, electronic and photonic materials, polymers, composites, and sustainable energy materials, together with their diverse applications across science, engineering, technology, and industry. On the second day, the focus will shift to both the fundamental principles and applied aspects of radiation science, encompassing topics such as radiation detection and measurement, medical applications of radiation, nuclear energy, radiation safety, environmental impacts, and advanced radiation materials. The conference covers keynote addresses and technical sessions by eminent speakers, panel discussions, and oral and poster presentations that foster interdisciplinary collaborations and knowledge sharing.
      </p>
    </section>

    <!-- Topics -->
    <section id="topics" class="bg-white p-6 rounded-lg shadow fade-in">
      <h2 class="text-indigo-800 text-xl mb-2">Conference Topics</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <div>
          <h3 class="font-semibold">Material Science</h3>
          <ul class="list-disc ml-5 mt-2">
            <li>Advanced Materials</li>
            <li>Energy and Sustainable Materials</li>
            <li>Nanomaterials &amp; Nanotechnology</li>
            <li>Smart &amp; Responsive Materials</li>
            <li>Structural and Mechanical Materials</li>
            <li>Sustainable &amp; Green Materials</li>
            <li>Electronic and Photonic Materials</li>
            <li>Environmental and Green materials</li>
            <li>Nano biotechnology</li>
            <li>Smart and Functional Materials</li>
            <li>Nanomedicine and Nanomaterials</li>
            <li>Characterization and Simulation</li>
          </ul>
        </div>
        <div>
          <h3 class="font-semibold">Radiation Physics</h3>
          <ul class="list-disc ml-5 mt-2">
            <li>Fundamental Radiation Physics</li>
            <li>Medical Radiation Physics</li>
            <li>Nuclear &amp; Reactor Physics</li>
            <li>Environmental &amp; Space Radiation</li>
            <li>Health Physics and Radiation Protection</li>
            <li>Dosimetric Materials and Dosimetry</li>
            <li>Shielding Materials</li>
            <li>Computational &amp; Experimental Techniques</li>
            <li>Emerging and Interdisciplinary Topics</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Venue -->
    <section id="venue" class="bg-gradient-to-r from-yellow-50 to-red-50 p-6 rounded-lg shadow fade-in">
      <h2 class="text-indigo-900 text-xl mb-2">Venue</h2>
      <p>
        Sri Bhagawan Mahaveer Jain First Grade College, Kolar Gold Fields, Kolar (District), Karnataka, India.
      </p>
      <p class="mt-3">
        Kolar Gold Fields (KGF), located in the Kolar district of Karnataka, is a historically significant township with a unique blend of industrial heritage, cultural diversity, and natural surroundings, situated about 100 km from Bengaluru. This area is known for its mineral-rich land, particularly gold-bearing quartz reefs, which made KGF one of the most prominent mining centers in India. KGF gold mines once renowned as one of the deepest and richest gold mining regions in the world, Champion Reef mine, in particular, reached depths of about 3,000 meters. In 1902, it became one of the first towns in Asia to receive electricity. Bharat Earth Movers Limited (BEML) was established in 1964 at KGF, to manufacture rail coaches, spare parts, defence vehicle, and heavy earth-moving equipment. The climate of KGF is classified as semi-arid. Summers are hot, with temperatures often rising above 35°C, while winters are relatively mild and pleasant. KGF, often referred to as “Little England” during colonial times, has a unique cultural blend influenced by the Anglo-Indian community and Indian traditions.
      </p>

      <h3 class="mt-4 font-semibold">How to Reach the Conference Venue?</h3>
      <ul class="list-disc ml-5 mt-2">
        <li><strong>By Air</strong><br>
          The nearest airport to KGF is Kempegowda International Airport in Bengaluru, which is about 94 km away and approximately a 2 hour journey. From the airport, you can hire a taxi or use public transport to reach KGF.
        </li>
        <li class="mt-2"><strong>By Train</strong><br>
          The nearest railway junction is Bangarpet Junction, which is 18 km from KGF, and is well-connected to major cities like Bengaluru, Chennai, Vellore, Coimbatore, Trivandrum, Mumbai, Kolkata and Delhi. From the railway station, you can hire a taxi or use public transport to reach KGF. You can check the Indian Railways website or apps like IRCTC for train schedules and bookings.
        </li>
        <li class="mt-2"><strong>By Bus/Car</strong><br>
          KGF is well-connected by state highways and the city is located on the Bengaluru-Chennai Expressway, making it accessible by road.
        </li>
      </ul>
    </section>

    <!-- Committees (accordion with full expanded lists inside panels, but collapsed by default) -->
    <section id="committees" class="bg-white p-6 rounded-lg shadow fade-in">
      <h2 class="text-indigo-800 text-xl mb-3">Committees</h2>

      <!-- International -->
      <button class="accordion">International Advisory Committee</button>
      <div class="panel">
        <ul class="list-disc ml-5">
          <li>Dr. M V Reddy, Mc Gill University, Montreal, Canada</li>
          <li>Dr. Shrinivasrao R. Kulkarni, Quality Department, Mynaric Lasercom GmbH, Munich, Germany</li>
          <li>Dr. Mayeen Khandaker, Department of Physics, Sunway University, Sunway, Malaysia</li>
          <li>Dr. Raju Khanal, Central Department of Physics, Tribhuvan University, Kathmandu, Nepal</li>
          <li>Dr. Mohammad Ibrahim Abualsayed, Department of Physics, Isra University, Amman, Jordan</li>
          <li>Dr. C. Shivakumara, Solid State and Structural Chemistry Unit, IISc, Bangalore, India</li>
          <li>Dr. Narayana Prasad Adhiraki, Department of Physics, Tribhuvan University, Kathmandu, Nepal</li>
          <li>Dr. Chamila Liyanage, Department of Material Science and Engineering, National University of Singapore</li>
          <li>Dr. Jayasingam Jeyasugiththan, Department of Nuclear Science, University of Colombo, Sri Lanka</li>
          <li>Dr. Jivendra S. Wickramasinghe, Department of Nuclear Science, University of Colombo, Sri Lanka</li>
          <li>Dr. Pahan Godakumbura, Department of Chemistry, University of Sri Jayewardenepura, Nugegoda, Sri Lanka</li>
          <li>Dr. Fan Zhang, Department of Chemistry, Laboratory of Advanced Materials, Fudan University, Shanghai, China</li>
          <li>Dr. Hansinee S. Sitinamaluwa, Department of Materials Science and Engineering, University of Moratuwa, Sri Lanka</li>
          <li>Dr. Dashty T. Akrawy, Department of Physics, Salahaddin University, Iraq</li>
          <li>Dr. Xu, Hushan, Institute of Modern Physics, Chinese Academy of Sciences, Lanzhou, China</li>
          <li>Dr. Chong Qi, Department of Physics, KTH Royal Institute of Technology, Stockholm, Sweden</li>
          <li>Dr. Zaiguo Gan, University of Chinese Academy of Sciences, Beijing, China</li>
          <li>Dr. K. Manjunatha, Department of Physics, National Dong Hwa University, Hualien, Taiwan</li>
        </ul>
      </div>

      <!-- National -->
      <button class="accordion mt-3">National Advisory Committee</button>
      <div class="panel">
        <ul class="list-disc ml-5">
          <li>Dr. Shankar Kumar Selvaraja, Centre for Nanoscience and Engineering, IISc, Bangalore, India</li>
          <li>Dr. V. P. Singh, Narora Atomic Power Station, Bulandshahr, Uttar Pradesh, India</li>
          <li>Dr. Deva Prasad Raju, Department of Physics, Sri Venkateswara University, Andhra Pradesh, India</li>
          <li>Dr. Balaji Rao Ravuri, Department of Physics, Central University of Jammu, Jammu and Kashmir, India</li>
          <li>Dr. V. Gunasekaran, Department of Materials Science, Central University of Tamil Nadu, Tamil Nadu, India</li>
          <li>Dr. M. S. Vishnu, ESL (Kaiga) &amp; DAE Radiation Emergency Response Centre, Kaiga, Karnataka, India</li>
          <li>Dr. Naveen Kumar, HomiBhabha National Institute, Maharashtra, India</li>
          <li>Dr. Sashi Sekhar Behera, Department of Physics, Berhampur University, Odisha, India</li>
          <li>Dr. Jadab Sharma, Center for Nano Science and Nano Technology, Panjab University, Chandigarh, India</li>
          <li>Dr. Kiran D. Pawar, School of Nanoscience and Technology, Shivaji University, Maharashtra, India</li>
          <li>Dr. C. Viswanathan, Nanoscience and Technology Department, Bharathiar University, Tamil Nadu, India</li>
          <li>Dr. G. Ramalingam, Department of Nanoscience and Technology, Alagappa University, Tamil Nadu, India</li>
          <li>Dr. Poornesh Kumar K, Department of Mechanical Engineering, NIT, Surathkal, Karnataka, India</li>
          <li>Dr. M. Arivandhan, Centre for Nanoscience and Technology, Anna University, Tamil Nadu, India</li>
          <li>Dr. J. Sudagar, School of Advanced Science, VIT University, Andhra Pradesh, India</li>
          <li>Dr. R. Ajay Rakkesh, Department of Physics and Nanotechnology, SRM Institute of Science and Technology, Tamil Nadu, India</li>
          <li>Dr. S. Swaminathan, Center for Nanotechnology and Advanced Biomaterials, SASTRA University, Tamilnadu, India</li>
          <li>Dr. K. Kamala Bharathi, Department of Physics and Nanotechnology, SRM Institute of Science and Technology, Tamil Nadu, India</li>
          <li>Dr. Sandeep Kumar, Jamia Milia Islamia University, New Delhi, India</li>
          <li>Dr. Mahua Ghosh Chaudhuri, Jadavpur University, West Bengal, India</li>
          <li>Dr. P. Kathirvel, PSG College of Technology, Coimbatore, Tamil Nadu, India</li>
          <li>Dr. Y. Narayana, Department of Physics, Mangalore University, Karnataka, India</li>
          <li>Dr. S. Krishnaveni, Department of Physics, Mysore University, Karnataka, India</li>
          <li>Dr. M. Srinivas, Department of Physics, Osmania University, Telangana, India</li>
          <li>Dr. Ajay Kumar Tyagi, Department of Physics, BHU, Varanasi, Uttar Pradesh, India</li>
          <li>Dr. H.C. Manjunatha, Government First Grade College, Devanahalli, Karnataka, India</li>
          <li>Dr. Piyush Kumar Patel, MANIT, Bhopal, Madhya Pradesh, India</li>
          <li>Dr. Vidya Y. S, Government Science College, Chitradurga, Karnataka, India</li>
          <li>Dr. Dhananjaya N, BMSIT, Bangalore, Karnataka, India</li>
          <li>Dr. Seenappa L, GFGC, Mulbagal, Karnataka, India</li>
          <li>Dr. A. Dhayal Raj, Department of Physics, Sacred Heart College, Tamil Nadu, India</li>
          <li>Dr. Kanagasabapathy M, Department of Chemistry, Rajapalayam Rajus College, Tamil Nadu, India</li>
        </ul>
      </div>

      <!-- Regional -->
      <button class="accordion mt-3">Regional Advisory Committee</button>
      <div class="panel">
        <ul class="list-disc ml-5">
          <li>Dr. Seenappa L, Department of Physics, GFGC, Mulbagal, Karnataka</li>
          <li>Dr. K. N Sreedhar, Department of Physics, GFGC, Malur, Karnataka</li>
          <li>Dr. Sowmya N, Department of Physics, GFGC, Chickballapur, Karnataka</li>
          <li>Dr. M G Srinivas, Department of Physics, GCW, Kolar, Karnataka</li>
          <li>Dr. Nagaraj, Department of Physics, GCB, Kolar, Karnataka</li>
          <li>Dr. B Chinnappa Reddy, Department of Physics, GCW, Kolar, Karnataka</li>
          <li>Dr. Umashankararaja R, Department of Physics, Sapthagiri NPS University, Bangalore, Karnataka</li>
          <li>Dr. Priyanka M, Department of Physics, Cambridge Institute of Technology, Bangalore, Karnataka</li>
          <li>Mr. Sounder, Department of Physics, GCW, Kolar, Karnataka</li>
          <li>Mr. Vishwalinga Prasad, Department of Physics, GCW, Kolar, Karnataka</li>
          <li>Mr. Madhu S, Department of Physics, GFGC, Chintamani, Karnataka</li>
          <li>Mr. Munirathnam R, Department of Physics, Bharathidasan University, Tamil Nadu, India</li>
          <li>Mrs. Susheela R S, Department of Physics, GFGC, Nanjungud, Karnataka</li>
          <li>Mr. Mahesh Babu A V, Department of Physics, VTU, Karnataka</li>
          <li>Ms. Anushree H S, Department of Physics, VTU, Karnataka, India</li>
          <li>Mr. Damodar P S, Department of Physics, Bharathidasan University, Tamil Nadu, India</li>
          <li>Mr. Manjunath N, Department of Physics, Bharathidasan University, Tamil Nadu, India</li>
          <li>Mrs. Reddi Rani L, Department of Physics, GFGC, Malur, Karnataka</li>
          <li>Ms. Vasudha, Department of Physics, Reva University, Karnataka, India</li>
          <li>Mr. Srinath, Department of Physics, Reva University, Karnataka, India</li>
          <li>Mrs. Roopa K N, Department of Physics, Reva University, Karnataka, India</li>
          <li>Mrs. Manjula K, Department of Physics, Reva University, Karnataka, India</li>
        </ul>
      </div>

      <!-- Organizing -->
      <button class="accordion mt-3">Organizing Committee</button>
      <div class="panel">
        <p><strong>Chief Patron:</strong> Dr. Chenraj Roychand, Founder &amp; Chairman, JGI.</p>
        <p><strong>Patron:</strong> Mr. Mahender Munoth, Managing Trustee, SBMJFGC, KGF.</p>
        <p><strong>Chair Person:</strong> Dr. Rekha Sethi, Principal, SBMJC, KGF.</p>
        <p><strong>Also:</strong> Prof. Manjaiah. D, Principal, GFGC, Devanahalli, Karnataka</p>

        <h3 class="mt-3 font-semibold">Coordinators</h3>
        <ul class="list-disc ml-5 mt-1">
          <li>Coordinator: Dr. H.C. Manjunatha, Professor, Government First Grade College, Devanahalli, Karnataka</li>
          <li>Co-Coordinator: Mr. Munirathnam R, Department of Physics, Bharathidasan University, Tamil Nadu</li>
          <li>Organizing Secretary: Mr. A. Kalai Chalvan, Associate Professor &amp; Head, Department of Physics, SBMJFGC, KGF</li>
        </ul>

        <h3 class="mt-3 font-semibold">Core Committee</h3>
        <ul class="list-disc ml-5 mt-1">
          <li>Dr. Jayapandiyan, IQAC, Coordinator, SBMJFGC, KGF</li>
          <li>Mrs. Roselin, Department of Biochemistry, SBMJFGC, KGF</li>
          <li>Mrs. Louisena Vinoth Priya, Department of Biotechnology, SBMJFGC, KGF</li>
          <li>Mr. Muniraja D K, Department of Physical Science, SBMJFGC, KGF</li>
          <li>Mr. Uday N V, Department of Physical Science, SBMJFGC, KGF</li>
          <li>Mrs. Lavenya, Department of Biotechnology, SBMJFGC, KGF</li>
          <li>Mrs. Cinthiya D, Department of Biotechnology, SBMJFGC, KGF</li>
          <li>Mrs. Dizy, Department of Biochemistry, SBMJFGC, KGF</li>
          <li>Mrs. Aruna N, Department of Physical Science, SBMJFGC, KGF</li>
          <li>Ms. Abiyal J S, Department of Physical Science, SBMJFGC, KGF</li>
          <li>Prof. Kavitha Kandaswamy, IQAC Coordinator, GFGC, Devanahalli, Karnataka</li>
          <li>Prof. Savitha S, Department of Physics, GFGC, Devanahalli, Karnataka</li>
          <li>Prof. Sowmya C R, Department of Chemistry, GFGC, Devanahalli, Karnataka</li>
          <li>Prof. Veena, Department of Mathematics, GFGC, Devanahalli, Karnataka</li>
          <li>Prof. Sridhar, Department of Mathematics, GFGC, Devanahalli, Karnataka</li>
        </ul>
      </div>

      <!-- Technical Assistance -->
      <button class="accordion mt-3">Technical Assistance</button>
      <div class="panel">
        <ul class="list-disc ml-5">
          <li>Mr. Navendran D, PRO, SBMJFGC, KGF</li>
          <li>Mr. Ranjeeth Prabhagaran P, System Admin, SBMJFGC, KGF</li>
          <li>Mr. Teekshith Kumar M, Assistant Professor,Department Of Computer Science ,SBMJFGC, KGF</li>
        </ul>
      </div>
    </section>

    <!-- Call for Papers -->
    <section id="papers" class="bg-gradient-to-r from-purple-50 to-indigo-50 p-6 rounded-lg shadow fade-in">
      <h2 class="text-indigo-900 text-xl mb-2">Call for Papers</h2>
      <p>
        The authors are invited to submit their manuscripts of the research findings on the specified scientific topics. The manuscripts should be prepared according to the template; the title of the paper should be in Times New Roman with a font size of 14, and the rest of the text in font size 12 with line spacing of 1.5. Shortlisted papers will be published in peer-reviewed Scopus/UGC CARE-listed journals, and the authors have to purchase the hard copy of the conference proceedings at actual cost, if any. Send your manuscripts in Word format to the e-mail <a href="mailto:sbmjcicemr@gmail.com" class="text-indigo-700">sbmjcicemr@gmail.com</a>.
      </p>

      <div class="mt-4">
        <h3 class="font-semibold">Important dates</h3>
        <ul class="list-disc ml-5 mt-2">
          <li>Last date for submission of abstract: <strong>26/11/2025</strong></li>
          <li>Intimation of acceptance: <strong>04/12/2025</strong></li>
          <li>Last date for registration: <strong>12/12/2025</strong></li>
          <li>Last date for submission of full paper: <strong>15/12/2025</strong></li>
        </ul>
      </div>

      <div class="mt-4">
        <a href="https://docs.google.com/forms/d/1yA7E_GgykFIVa9omTJrgFccXmiMmNNCOi0V3uWC1d1o/edit" target="_blank" rel="noopener noreferrer" class="inline-block px-4 py-2 bg-indigo-700 text-white rounded shadow hover:bg-indigo-800">Registration Form</a>
      </div>
    </section>

    <!-- Registration & Bank -->
    <section id="registration" class="bg-white p-6 rounded-lg shadow fade-in">
      <h2 class="text-indigo-800 text-xl mb-2">Registration &amp; Fees</h2>

      <table class="mt-2">
        <thead>
          <tr>
            <th>Category</th>
            <th>Indian authors</th>
            <th>Foreign authors</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Scholars/Students</td>
            <td>₹1000/-</td>
            <td>$35</td>
          </tr>
          <tr>
            <td>Faculty/Scientists</td>
            <td>₹1500/-</td>
            <td>$35</td>
          </tr>
          <tr>
            <td>Industry Delegates</td>
            <td>₹2500/-</td>
            <td>$35</td>
          </tr>
        </tbody>
      </table>

      <p class="mt-4">
        <strong>Note:</strong> Registration fee includes conference kit and meals. Accommodation charges will be borne by participants and details will be available on the conference web page; the same will also be communicated through mail and WhatsApp group. Young Scientist Award for outstanding contributions in research area will be awarded. Best Paper Presentation award for outstanding paper presentation will be awarded.
      </p>

      <div class="mt-4">
        <h3 class="font-semibold">Bank Details</h3>
        <p>
          Bank: State Bank of India<br/>
          Branch: Visweswarapuram, Bangalore<br/>
          Account Name: Sri Bhagawan Mahaveer Jain First Grad College<br/>
          Account No: <strong>34872561619</strong><br/>
          IFSC Code: <strong>SBIN0040292</strong><br/>
          MICR Code: <strong>560002381</strong>
        </p>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="bg-gradient-to-r from-indigo-50 to-yellow-50 p-6 rounded-lg shadow fade-in">
      <h2 class="text-indigo-900 text-xl mb-2">Contact Address</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
        <div class="bg-white p-4 rounded">
          <h3 class="font-semibold">Coordinator</h3>
          <p><strong>Dr. H.C. Manjunatha</strong><br/>
          Coordinator,<br/>
          Professor, Department of Physics<br/>
          Government First Grade College, Devanahalli - 562110, Karnataka<br/>
          Mobile: <a href="tel:+918296626337" class="text-indigo-700">8296626337</a><br/>
          Email: <a href="mailto:manjunathhc@rediffmail.com" class="text-indigo-700">manjunathhc@rediffmail.com</a></p>
        </div>

        <div class="bg-white p-4 rounded">
          <h3 class="font-semibold">Organizing Secretary</h3>
          <p><strong>Mr. A. Kalai Chalvan</strong><br/>
          Organizing Secretary<br/>
          Associate Professor &amp; Head, Department of Physics<br/>
          Sri Bhagawan Mahaveer Jain First Grade College<br/>
          Geetha Road, Robertsonpet<br/>
          Kolar Gold Fields - 563122<br/>
          Mobile: <a href="tel:+919701036424" class="text-indigo-700">9701036424</a><br/>
          Email: <a href="mailto:akchalvan@gmail.com" class="text-indigo-700">akchalvan@gmail.com</a></p>
        </div>
      </div>
    </section>

  </main>

  <footer class="mt-10 py-6 text-center text-sm text-white bg-indigo-900">
    © ICEMR 2025 | SBMJFGC, KGF · All information as provided in the uploaded document.
  </footer>

  <!-- JS for accordion behavior -->
  <script>
    document.querySelectorAll('.accordion').forEach(btn => {
      btn.addEventListener('click', () => {
        const panel = btn.nextElementSibling;
        const isOpen = panel.style.display === 'block';
        // close all sibling panels (optional - keep only one open)
        //document.querySelectorAll('.panel').forEach(p => p.style.display = 'none');
        panel.style.display = isOpen ? 'none' : 'block';
        if (!isOpen) panel.scrollIntoView({behavior: 'smooth', block: 'center'});
      });
    });
  </script>
</body>
</html>
