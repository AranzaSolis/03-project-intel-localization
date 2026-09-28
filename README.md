# Project 2: Intel Sustainability Journey
Build an interactive webpage that presents Intel's sustainability goals in a timeline format. Using AI and your knowledge of responsive design, you'll experiment with hover effects, transitions, and layouts to ensure it adapts seamlessly to both desktop and mobile.

Launch a Codespace to get started! Remember to Commit and Push your project changes to GitHub from Codespaces to prevent losing progress.









I'm adapting a webpage that already includes a timeline section, and I'm working to make the page RTL-compatible. I’ve added Bootstrap to enable right-to-left text flow. Now, I want to add a **new section** below the timeline that uses Bootstrap’s grid system to create a responsive three-column layout.

Important: the timeline section already works well using flexbox, so I do **not** want to modify or replace that section. Leave the existing timeline code as-is.

Help me generate the new HTML and Bootstrap classes for the three-column layout only, and explain what the code is doing.


Here is the text ONLY for the content for the three column section.
<!-- 3-Column Content Section -->
  <section>
    <div>
      
      <!-- Column 1 -->
      <div>
        <h2>RISE Strategy</h2>
        <p>
          Under its RISE (Responsible, Inclusive, Sustainable, Enabling) strategy, 
          Intel sets ambitious 2030 goals, including driving industry-wide 
          progress on climate action, water stewardship, and waste reduction.
        </p>
        <!-- Learn More Button -->
        <a href="#">Learn More</a>
      </div>

      <!-- Column 2 -->
      <div>
        <h2>Commitment</h2>
        <p>
          In 2022, Intel pledged to achieve net-zero greenhouse gas emissions 
          (Scope 1 and 2) by 2040. This commitment builds on decades of 
          environmental initiatives and partnerships across the semiconductor 
          industry.
        </p>
        <!-- Learn More Button -->
        <a href="#">Learn More</a>
      </div>

      <!-- Column 3 -->
      <div>
        <h2>Water &amp; Waste</h2>
        <p>
          Intel conserves billions of gallons of water annually and 
          collaborates with local communities to restore watersheds.
          Intel also upcycles and recycles materials to reduce waste and 
          advance a circular economy.
        </p>
        <!-- Learn More Button -->
        <a href="#">Learn More</a>
      </div>

    </div>
  </section>

  Three-Column Section: Use Bootstrap’s grid system to structure a new three-column layout that adapts to different screen sizes.
Integrate icons to visually enhance each column heading.
Style the "Learn More" links in each column.




now add a subscruption form: use bootstrap to build a simple form for subscribing to Intel’s sustainability newsletter.
  <!-- Subscription Form -->
  <section>
    <h2>Subscribe to our Newsletter</h2>
    <!-- Add form here -->
  </section>

  Build a Footer with content such as copyright notice or placeholder navigation links (e.g., Privacy Policy, Terms of Use, Contact).

  Adapt for RTL and Localization: modify bootstrap grid so layout adapts correctlly in RTL mode. use the bootstrap link













  The site achieves a score of 90 or more on Lighthouse accessibility tests, with proper color contrast, descriptive alt attributes, and an accessible subscription form

 Auto-Detect Language & Adjust Layout
Implemented JavaScript script to detect language changes and dynamically apply RTL mode.  to generate a script that detects when the page language changes (e.g., via Google Translate) and applies RTL as needed. Use the bootstrap link to java that I included at end of html.


Also, add a bootstrap component carousel to enhance the functionallity of user experience and introduce interactive elements that improve user  experience.








I want to make the background white but surround the timeline with the same gradient background as the header as well as the carousel. Important: the timeline section already works well using flexbox, so I do **not** want to modify or replace that section. Leave the existing timeline code as-is. also keep the carousel as is in terms of format.


make the carousel look like a 3D carousel with some nice and asthetic arrows that fit the intel style. make it look visually pleasing