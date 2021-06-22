---
layout: default
title: "AI for Science: Mind the Gaps"
permalink: /

speakers:
  - info:
    - name: Yoshua Bengio
      url: https://yoshuabengio.org
    title: Machine Learning for Discovery
    image: assets/images/test.jpeg
  
  - info:
    - name: Shirley Ho
      url: https://users.flatironinstitute.org/~sho/index.html
    title: TBD
    image: assets/images/test.jpeg
    
  - info:
    - name: Debora Marks
      url: https://www.deboramarkslab.com/
    title: What kinds of machine learning should we use and develop to accelerate biomedical discovery?
    image: assets/images/test.jpeg

  - info:
    - name: Tomaso Poggio
      url: https://mcgovern.mit.edu/profile/tomaso-poggio
    title: Science and Engineering of Intelligence
    image: assets/images/test.jpeg

  - info:
    - name: Bharath Ramsundar
      url: https://rbharath.github.io/about/
    title: Open-source Community in AI for Science
    image: assets/images/test.jpeg

  - info:
    - name: Petar Veličković
      url: https://petar-v.com/
    title: TBA
    image: assets/images/test.jpeg
    
panels:
  - info:
    - name: Karianne Bergen
      url: https://www.kariannebergen.com/
      
  - info:
    - name: Connor Coley
      url: https://coley.mit.edu/
      
  - info:
    - name: Pushmeet Kohli
      url: https://sites.google.com/site/pushmeet/
      
  - info:
    - name: Irina Rish
      url: https://sites.google.com/site/irinarish

---

# About

Machine learning (ML) has revolutionized a wide array of scientific disciplines and solved problems that were unsolvable before: predicting protein structure, imaging black holes, automating drug discovery, and so on. Despite this promise, we observe the following gaps that stifle advancement:

+ **Gap 1: Unrealistic methodological assumptions or directions.** While ML researchers strive for methodology advances, they often make unrealistic assumptions that limit real-world adoption. For example, most state-of-the-art molecule generation ML models generate molecules that have low synthesizability.

+ **Gap 2: Overlooked scientific questions.** Scientific communities contend with crucial and unsolved problems but they are not formulated in the ML language and can thus be overlooked by the ML communities. For example, how can theoretical physical laws be parameterized to re-discover or discover new ones?

+ **Gap 3: Limited exploration on the intersections of multiple disciplines.** Solutions to grand challenges often stretch across multiple disciplines. For example, protein structure prediction requires collaboration across physics, chemistry, biology; single-cell imaging of whole-tumor can be approached by cosmology algorithms that connects cells as stars. 

+ **Gap 4: Science of science.** The principles of scientific methods have been unchanged since 17th century. How AI can facilitate the practice of scientific discovery itself is often undiscussed. For example, instead of the multiple hypothesizing-experimenting cycles to make sense of a phenomena, can AI reason and output nature laws directly?

However, little work has been done to bridge these gaps, mainly because of the missing conversations among the scientific communities. While we see many workshops focus on AI for individual scientific discipline, they all focus on method advances in a single field and are unable to answer the above important questions. Thus, this workshop is born to fulfill this unmet need. Particularly, the goal of this workshop aims to bridge each of the above gaps via:
+ Identify the directions that are currently used by ML researchers that are not effective for real-world scientific discovery. 
+ Bring important scientific questions with untapped potential for use of ML methodological advances to the AI community. 
+ Pinpoint grand challenges at the intersection of various scientific fields (biology, chemistry, physics, neuroscience, etc).
+ Highlight how ML can change or complement the classic scientific methods and facilitate the science of scientific discovery itself.

# Invited Talks

(In alphabetical order.)

<!-----
Topic: **Machine Learning for Discovery**

Speaker: [Yoshua Bengio (confirmed)](https://yoshuabengio.org/)

Topic: **TBA**

Speaker: [Shirley Ho (confirmed)](https://users.flatironinstitute.org/~sho/index.html)

Topic: **What kinds of machine learning should we use and develop to accelerate biomedical discovery?**

Speaker: [Debora Marks (confirmed)](https://www.deboramarkslab.com/)

Topic: **Science and Engineering of Intelligence**

Speaker: [Tomaso Poggio (confirmed)](https://mcgovern.mit.edu/profile/tomaso-poggio/)

Topic: **Open-source Community in AI for Science**

Speaker: [Bharath Ramsundar (confirmed)](https://rbharath.github.io/about/)

Topic: **TBA**

Speaker: [Petar Veličković (confirmed)](https://petar-v.com/)

---->

{% include team.html id="team" %}

<table>
  <tr>
    <th>Speaker</th>
    <th>Topic</th>
  </tr>
  {% for speaker in page.speakers %}
    <tr>
      <td>
      {% for i in speaker.info %}
        {% include href item=i %}<br>
      {% endfor %}
      </td>
      <td><b>{{ speaker.title }}</b></td>
    </tr>
  {% endfor %}
</table>

# Panels

**Frontiers, gaps, and futures of AI for Science**

Speakers (alphabetical order): 
<!----
[Karianne Bergen (confirmed)](https://www.kariannebergen.com/), [Connor Coley (confirmed)](https://coley.mit.edu/), [Pushmeet Kohli (confirmed)](https://sites.google.com/site/pushmeet/), [Irina Rish (confirmed)](https://sites.google.com/site/irinarish)
---->


<ul>
{% for panel in page.panels %}
<li>
{% for i in panel.info %}
    {% include href item=i %}<br>
{% endfor %}
</li>
{% endfor %}
</ul>

Moderator: TBA

# Important Dates

- Submission Deadline: Sep 17, 2021
- Author Notification: Oct 22, 2021
- Conference Date: Dec 6-14, 2021
- Workshop Date: Dec 13-14, 2021

# Organizers and Contact

Organizers in the alphabetical order. For any question, please contact [ai4sciencecommunity@gmail.com](mailto:ai4sciencecommunity@gmail.com).

- [Payal Chandak](https://www.payalchandak.com/)
- [Yuanqi Du](https://yuanqidu.github.io/)
- [Tianfan Fu](https://futianfan.github.io/)
- [Wenhao Gao](https://scholar.google.com/citations?user=s4eywrUAAAAJ&hl=en)
- [Kexin Huang](https://www.kexinhuang.com/)
- [Shengchao Liu](https://chao1224.github.io/)
- [Ziming Liu](https://kindxiaoming.github.io/)
- [Gabriel Spadon](https://www.spadon.com.br/)
- [Hanchen Wang](https://hansen7.github.io/)

- [Max Tegmark](https://space.mit.edu/home/tegmark/)
- [Adrian Weller](http://mlg.eng.cam.ac.uk/adrian/)
- [Max Welling](https://staff.fnwi.uva.nl/m.welling/)
- [Marinka Zitnik](https://zitniklab.hms.harvard.edu/)
