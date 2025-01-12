---
layout: page
title: Inopia Foundation (my non profit)
description: an other project with a background image and giscus comments
img: assets/img/team.jpg
importance: 2
category: work
related_publications: true
---

### The Beginnings of INOPIA Foundation

The **INOPIA Foundation** started taking shape back in **2019**, when I was already juggling various student and volunteer initiatives—like UNICEF, SNEEP, and the Young Initiative at the Neues Museum Nürnberg. Through these experiences, I realized that I not only wanted to help people but also wanted to apply my **information systems** in a practical way. Originally, I considered launching a typical startup, but I also saw the potential in establishing a nonprofit—one that could **experiment with new ideas**, focus on real-world impact, and bring creative solutions to social challenges. By early **2020**, after navigating some pandemic-related delays, my friends and I officially founded the Inopia Foundation.

From the beginning, we decided to center our efforts on **education** and **sustainability**, inspired by the **UN Sustainable Development Goals** as well as my earlier work in organizations emphasizing resource stewardship and ethical leadership. This vision resonated with my colleagues, who all shared the same passion for bridging gaps and contributing to community well-being. In practical terms, INOPIA became our place for social innovation—a place where we could develop and test projects that might otherwise remain just ideas on paper.

---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/team.jpg" title="The Team Behind INOPIA" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---

#### Computer Refurbishment Project

One of our very first big projects was all about **Second Hand Second Chance - Refurbishing Computers**—an idea that was inspired by my mother. She observed that many companies replace their older PCs once they’ve been fully written off, even though these devices are still perfectly suited for tasks like schoolwork or online browsing. During the COVID-19 pandemic, we saw firsthand how the **digital divide** was widening as schools switched to online learning. Kids who didn’t have access to a computer were at an immediate disadvantage.

So, we partnered with local businesses—mostly **SMEs and family-owned places**—to **collect and refurbish** these discarded machines. We put free, open-source software like Linux on them so the children (and sometimes their families) could jump straight into online classes without worrying about costly licenses or hardware constraints. We also joined forces with the **Stabstelle Bürgerschaftliches Engagement** (part of Nuremberg’s Department of Social Affairs) to identify families in need and distribute over **250 computers** in total. It was really uplifting to see how something that simple—giving a child a working PC—could reduce educational gaps and bring us closer to the local community, including city officials and other small organizations who helped us along the way.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/computer.jpg" title="Refurbishing Computers" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/computer2.jpg" title="Distributing Refurbished Computers" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---

#### INOPIA One

After we got the computer project running smoothly, we realized that, well, just handing out hardware often isn’t enough. Lots of kids also need **tutoring**, or maybe they could use a “reading buddy” to practice their reading skills. That’s how **INOPIA One** was born—a unified **all-in-one solution** that brought together all of our educational help under one roof.

We used **JIRA** to create a **matchmaking system** so that volunteers could sign up, list their skills (e.g., math tutoring, reading sessions, etc.), and note the age group they’re comfortable working with. Families would then hop on the website, sign-up their child and the system would automatically connect them with a suitable volunteer. This not only streamlined everything (so people wouldn’t have to dig around multiple programs) but also made it really easy for new volunteers to see exactly where they could pitch in. It was a great example of how **IT and social work** can fit together seamlessly when you plan it right.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/inopia_one.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
---
#### Greenopia: Ideas for Sustainability

From day one, **sustainability** was also a huge priority for INOPIA. We wanted to do something that would get the community more involved and let them share their own ideas. So we launched **Greenopia**, which was basically a little “ideation challenge” focused on three big issues.

1. **Sustainable mobility** (fewer cars, more eco-friendly transport)
2. **Reducing litter** (less garbage on the streets)
3. **Cutting down on food waste**

To make sure we were addressing the city’s real problems, we ran an **eight-week survey** asking people about **sustainability** issues they cared about most. We sent the survey to other non-profits, shared it on social media, and encouraged as many people as possible to take part. This helped us gather a wide range of opinions and insights from different parts of the community.

After that, we teamed up with local startup incubators like **Zollhof**, the **UmweltBank**, **Guampa** (a local, sustainable energy drink), and once again the **Stabstelle Bürgerschaftliches Engagement**. They provided things like **design thinking workshops**, prize money, and Goodies from our partners to motivate participants.

In the end, we received **four submissions** that tackled the key challenges identified in the survey. Two of the proposals focused on **sustainable transportation**, while the others addressed **food waste**. It was inspiring to see the creativity and thoughtfulness of the participants as they presented their ideas.

A jury made up of representatives from the UmweltBank, Zollhof, Guampa, and the City of Nuremberg came together to review the submissions and decide who would receive the top prize. Even though the entire event was held online, it was a rewarding experience for everyone involved.

Afterward, we packed up prizes and goodies (a mix of stuff from our partners plus the prize money) and personally delivered them to the winners. It was such a fun and rewarding project—it felt like proof that when you ask people for ideas and give them the tools to act on them, they can come up with some really amazing stuff.

Here is an overview of our results:

<div id="pdf-container" style="width: 100%; height: 90vh; overflow-y: auto; background: #f9f9f9; border: 1px solid #ccc; border-radius: 10px; padding: 10px;">
    <div id="loading-message" style="text-align: center; font-size: 16px; color: #555; padding: 20px;">
        Loading PDF, please wait...
    </div>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/2.16.105/pdf.min.js"></script>
<script>
    // Path to the PDF file
    const pdfUrl = '/assets/pdf/Greenopia.pdf';

    // Set worker source for PDF.js
    pdfjsLib.GlobalWorkerOptions.workerSrc = 'https://cdnjs.cloudflare.com/ajax/libs/pdf.js/2.16.105/pdf.worker.min.js';

    // Get the container and loading message
    const container = document.getElementById('pdf-container');
    const loadingMessage = document.getElementById('loading-message');

    // Load the PDF and render it
    pdfjsLib.getDocument(pdfUrl).promise.then(pdf => {
        // Remove the loading message
        if (loadingMessage) {
            loadingMessage.remove();
        }

        // Render each page in the PDF
        for (let pageNum = 1; pageNum <= pdf.numPages; pageNum++) {
            pdf.getPage(pageNum).then(page => {
                const viewport = page.getViewport({ scale: 1.2 });

                // Create a canvas element for each page
                const canvas = document.createElement('canvas');
                const ctx = canvas.getContext('2d');
                canvas.width = viewport.width;
                canvas.height = viewport.height;
                canvas.style = "margin: 10px auto; display: block; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); border-radius: 5px;";

                // Append canvas to the container
                container.appendChild(canvas);

                // Render the PDF page into the canvas
                page.render({
                    canvasContext: ctx,
                    viewport: viewport
                });
            });
        }
    }).catch(error => {
        // Display an error message
        container.innerHTML = '<p style="color: red; text-align: center;">Failed to load the PDF. Please try again later.</p>';
        console.error('Error loading PDF:', error);
    });
</script>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/greens.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>

#### Ballot Bins for Sustainability

Another fun project we tested was introducing **ballot bins**—you know, those see-through ashtrays with two slots, so smokers can “vote” with their cigarette butts based on funny or provocative questions. It sounds goofy, but it’s a proven way to reduce street litter by giving smokers an interactive alternative to just tossing their butt on the ground. We placed a few bins at **Amar’s Barbershop** in Nuremberg, another barbershop in Fürth, and **Nordkurve** (a cultural venue in Gostenhof), and people actually loved it. Cleanup got easier for the owners, and it sparked fun little debates outside about the question being asked.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/gigi.png" title="Refurbishing Computers" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ballot.png" title="Distributing Refurbished Computers" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Responding to the Russian War on Ukraine: Refugee Matchmaking and NFTs

In **February 2022**, as the **Russian invasion** of Ukraine triggered a significant refugee crisis, the INOPIA Foundation identified an urgent need to support the influx of Ukrainian refugees seeking safety in Germany. Leveraging the technical expertise of our team and our prior experience with the INOPIA One JIRA infrastructure, we rapidly developed a matchmaking platform to connect Ukrainian refugees with local families willing to host them.

This system allowed families interested in providing assistance to register through a secure process. Participants were required to comply with stringent GDPR regulations, which included uploading ID documents for verification and agreeing to detailed data security and data sharing agreements. These agreements enabled us to securely collaborate with local nonprofits and the city’s referral channels, ensuring both the privacy of participants and the efficient distribution of resources.

The initiative served as a **crucial bridge between the city authorities**, who needed a clear overview of available resources, and refugees arriving in need of immediate assistance. By centralizing data and streamlining communication, we enabled a coordinated response that maximized impact during a time of immense urgency.

Simultaneously, we **co-initiated the Ukrainehilfe Netzwerk Nürnberg**, a loose network of nonprofits and city representatives. This network facilitated regular collaboration, including weekly and bi-weekly meetings, where challenges were discussed, solutions brainstormed, and information shared. One of our key contributions was the creation of multilingual guides in German, Ukrainian, and Russian. These documents provided step-by-step instructions for registering children in schools, accessing financial assistance, and navigating essential services in Germany. The network not only strengthened local support structures but also empowered refugees with the information they needed to rebuild their lives.

In parallel with these efforts, we experimented with an innovative fundraising initiative during the peak of the NFT hype. Recognizing the global fascination with NFTs and the potential for digital assets to generate funds, we launched a creative project aimed at combining technology and compassion. We reached out to Ukrainian families, both within Germany and in Ukraine, **inviting children to submit drawings or artwork that reflected their traumatic experiences**. These pieces were then transformed into NFTs and sold on OpenSea, raising €600 in total. Every euro was donated to <a href="https://voices.org.ua/en/" target="_blank" rel="noopener">Voices.org</a>, an organization providing psychological support and therapy to ukrainian children traumatized by war.

This NFT initiative also contributed to academic research. As a supervisor for a bachelor’s thesis, I guided an analysis of the feasibility of NFTs as a fundraising tool for nonprofits. While the study identified limitations, such as high transaction fees, it also highlighted the potential of NFTs to engage a younger, tech-savvy donor base. The thesis, which was awarded a **commendable 1.3 grade**, underscored the value of exploring unconventional methods to support charitable causes.
Down

Down below, you can see the **OpenSea account** where we showcased the NFT collection created from the drawings of Ukrainian children. Alongside, there’s a picture of Margareta, a Ukrainian student in Germany who co-initiated the NFT project with us. This photo was taken during an interview with **Nürnberger Nachrichten**, the **largest print newspaper in Nuremberg**.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ukraine.jpg" title="Helping Ukrainian Refugees with NFTs" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div id="pdf-container" style="width: 100%; height: 90vh; overflow-y: auto; background: #f9f9f9; border: 1px solid #ccc; border-radius: 10px; padding: 10px;">
    <div id="loading-message" style="text-align: center; font-size: 16px; color: #555; padding: 20px;">
        Loading PDF, please wait...
    </div>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/2.16.105/pdf.min.js"></script>
<script>
    // Path to the PDF file
    const pdfUrl = '/assets/pdf/nft.pdf';

    // Set worker source for PDF.js
    pdfjsLib.GlobalWorkerOptions.workerSrc = 'https://cdnjs.cloudflare.com/ajax/libs/pdf.js/2.16.105/pdf.worker.min.js';

    // Get the container and loading message
    const container = document.getElementById('pdf-container');
    const loadingMessage = document.getElementById('loading-message');

    // Load the PDF and render it
    pdfjsLib.getDocument(pdfUrl).promise.then(pdf => {
        // Remove the loading message
        if (loadingMessage) {
            loadingMessage.remove();
        }

        // Render each page in the PDF
        for (let pageNum = 1; pageNum <= pdf.numPages; pageNum++) {
            pdf.getPage(pageNum).then(page => {
                const viewport = page.getViewport({ scale: 1.2 });

                // Create a canvas element for each page
                const canvas = document.createElement('canvas');
                const ctx = canvas.getContext('2d');
                canvas.width = viewport.width;
                canvas.height = viewport.height;
                canvas.style = "margin: 10px auto; display: block; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); border-radius: 5px;";

                // Append canvas to the container
                container.appendChild(canvas);

                // Render the PDF page into the canvas
                page.render({
                    canvasContext: ctx,
                    viewport: viewport
                });
            });
        }
    }).catch(error => {
        // Display an error message
        container.innerHTML = '<p style="color: red; text-align: center;">Failed to load the PDF. Please try again later.</p>';
        console.error('Error loading PDF:', error);
    });
</script>

---

### Recognition and Reflection

At the heart of INOPIA was a team of 28 passionate volunteers, each of whom took ownership of specific areas such as fundraising, sustainability, events, and education. We encouraged autonomy and purpose, believing that motivated individuals could achieve incredible results. This decentralized approach fostered creativity and commitment, ensuring that every volunteer felt empowered to contribute meaningfully.

INOPIA’s efforts were widely recognized. We received the Young Engagement Award for our Computer Refurbishment and Ballot Bins projects, and we participated in the StartSocial Initiative, a nationwide competition for volunteering projects in Germany. These accolades validated the foundation’s work and underscored the power of community-driven solutions.

By late 2024, as many team members transitioned to full-time careers and I moved abroad to Kuala Lumpur for my studies, we faced challenges in finding successors to take over INOPIA’s leadership. Ultimately, we made the bittersweet decision to conclude the foundation’s journey. However, we reflected on our accomplishments with immense pride and gratitude.

The INOPIA Foundation was more than just a nonprofit—it was a testament to the power of purpose-driven action. From bridging the digital divide to promoting sustainability and supporting refugees, INOPIA left a lasting impact on the community it served. Though its journey has come to an end, the lessons and experiences it provided will continue to inspire us and others to strive for a better world.

Below are screenshots of our website for your review. Please feel free to take a look!

<div id="pdf-container" style="width: 100%; height: 90vh; overflow-y: auto; background: #f9f9f9; border: 1px solid #ccc; border-radius: 10px; padding: 10px;">
    <div id="loading-message" style="text-align: center; font-size: 16px; color: #555; padding: 20px;">
        Loading PDF, please wait...
    </div>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/2.16.105/pdf.min.js"></script>
<script>
    // Path to the PDF file
    const pdfUrl = '/assets/pdf/inopia_main.pdf';

    // Set worker source for PDF.js
    pdfjsLib.GlobalWorkerOptions.workerSrc = 'https://cdnjs.cloudflare.com/ajax/libs/pdf.js/2.16.105/pdf.worker.min.js';

    // Get the container and loading message
    const container = document.getElementById('pdf-container');
    const loadingMessage = document.getElementById('loading-message');

    // Load the PDF and render it
    pdfjsLib.getDocument(pdfUrl).promise.then(pdf => {
        // Remove the loading message
        if (loadingMessage) {
            loadingMessage.remove();
        }

        // Render each page in the PDF
        for (let pageNum = 1; pageNum <= pdf.numPages; pageNum++) {
            pdf.getPage(pageNum).then(page => {
                const maxWidth = container.clientWidth; // Get container width
                const scale = maxWidth / page.getViewport({ scale: 1 }).width; // Calculate scale dynamically
                const viewport = page.getViewport({ scale }); // Apply the dynamic scale

                // Create a canvas element for each page
                const canvas = document.createElement('canvas');
                const ctx = canvas.getContext('2d');
                canvas.width = viewport.width;
                canvas.height = viewport.height;
                canvas.style = "margin: 10px auto; display: block; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); border-radius: 5px;";

                // Append canvas to the container
                container.appendChild(canvas);

                // Render the PDF page into the canvas
                page.render({
                    canvasContext: ctx,
                    viewport: viewport
                });
            });
        }
    }).catch(error => {
        // Display an error message
        container.innerHTML = '<p style="color: red; text-align: center;">Failed to load the PDF. Please try again later.</p>';
        console.error('Error loading PDF:', error);
    });
</script>
