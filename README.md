![MasterHead](https://res.cloudinary.com/dfl02brcp/image/upload/v1720587133/pic2_t4zbuv.jpg)
<h1 align="center">An Integrated Eco-System to use AI for mass Bengali people</h1>

<h4 align="center">In an era where Artificial Intelligence (AI) is revolutionizing global sectors, Bangladesh faces unique challenges in harnessing its full potential. Our project aims to break down the language barrier that prevents many Bengali speakers, especially those with limited English proficiency, from accessing and benefiting from AI technologies.</h4>
<br>
<h2 align="left">Our Vision</h2>
<p>We're developing an integrated eco-system that brings AI to the masses in Bangladesh:</p>
<ul>
  <li>
    <strong>Voice-Assisted AI in Bengali:</strong> An end-to-end Bangla voice assistance system that allows interaction with AI products without requiring English knowledge.
  </li>
  <li>
    <strong>Inclusivity:</strong> Focusing on accessibility for all, including the poor, uneducated, and differently-abled.
  </li>
  <li>
    <strong>Practical Applications:</strong> Demonstrating real-world use cases, such as empowering visually impaired individuals with cost-effective digital solutions.
  </li>
</ul>

<h2>Why It Matters</h2>
<p>By leveraging open-source AI resources and adapting them for Bengali speakers, we're not just translating technology – we're transforming lives. Our system aims to democratize AI access, bringing Bangladesh closer to realizing its 'Smart Bangladesh' vision.
Join us in this journey to make AI accessible to every Bengali speaker, regardless of their background or abilities. Together, we can ensure that language is no longer a barrier to progress in the AI age.</p>


<h2>How are we going to achieve:</h2>
<p></p>We want to develop an end-to-end Bangla voice assistance system using existing models and research. With the help of this system, people with zero to minimal English knowledge can interact with products that previously required English for interaction.</p>



<h2>Example: ThirdEye</h2>

<p>We will demonstrate one of the many use cases of our developed system by implementing it for blind people in Bangladesh. In the context of developing nations like Bangladesh, there is a lack of adequate facilities to address and enhance the conditions of visually impaired individuals. Our aim is to develop a comprehensive system utilizing cost-effective and readily available digital integrated technology, designed to empower blind or partially blind individuals in carrying out their daily tasks with little to no assistance from others.</p>

![MasterHead](https://res.cloudinary.com/dfl02brcp/image/upload/v1720621249/shoe_kpsq4n.jpg)

### ThirdEyeCameraX

ThirdEyeCameraX is an android application that can capture image/video and after capture is completed it appears in a
bottom sheet. It is stored in the gallery of the device. It is also written in Kotlin and Jetpack Compose following
MVVM(Model View View Model) pattern.

### Available Approaches & Our Choice

<strong>Monolithic Architecture:</strong> We could build both the application together as a single application. It is
called monolithic architecture. But it would have lead to several problems. First of all parallel development would have
been impossible. Second testing would have been difficult.

<strong>Microservices Architecture:</strong> By following microservices architecture we're able to do parallel
development. It saved our time. Also now it's easier to test. If any malfunction happens we would know which part is
causing problem.

![MasterHead](https://res.cloudinary.com/dfl02brcp/image/upload/v1720608508/final1_w4z94v.jpg)

<h3>Models and Their Functions</h3>

<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>Function</th>
      <th>How It Works</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Pretrained ASR Model</td>
      <td>Bangla Voice to Bangla Text</td>
      <td>Converts spoken Bangla into written Bangla text.</td>
    </tr>
    <tr>
      <td>Pretrained Byte5 Model</td>
      <td>Bangla Text to English Text</td>
      <td>Translates Bangla text into English text.</td>
    </tr>
    <tr>
      <td>Pretrained Grounding DINO</td>
      <td>Text to Image Finding</td>
      <td>Uses the translated English text to find relevant images.</td>
    </tr>
    <tr>
      <td>Pretrained Byte5 Model</td>
      <td>English Text to Bangla Text</td>
      <td>Translates the response text back into Bangla.</td>
    </tr>
    <tr>
      <td>Google Python API</td>
      <td>Bangla Text to Bangla Voice</td>
      <td>Converts the Bangla text back into spoken Bangla.</td>
    </tr>
  </tbody>
</table>

<h3>Link to model notebooks</h3>
Pretrained ASR Model for Bangla Voice to Bangla Text: (https://www.kaggle.com/code/nasiatfahim/book1-bangla-voice-to-bangla-text)<br>
Pretrained Byte5 Model for Bangla Text to English Text: (https://www.kaggle.com/code/nasiatfahim/book2-bangla-text-to-english-text)<br>
Pretrained Grounding DINO for Text to Image Finding: (https://www.kaggle.com/code/nasiatfahim/book3-text-to-image-finding)<br>
Pretrained Byte5 Model for English Text to Bangla Text & Google Python API: (https://www.kaggle.com/code/nasiatfahim/book4-english-text-to-bangla-voice)<br>

<h3>Some detection with our models</h3>

<table>
  <tr>
    <td align='center'><strong>রুবিক্স কিউব</strong></td>
    <td align='center'><strong>জুতা</strong></td>
    <td align='center'><strong>সানগ্লাস</strong></td>
    <td align='center'><strong>কলম</strong></td>
  </tr>
  <tr>
    <td><img src="https://res.cloudinary.com/dfl02brcp/image/upload/v1720604798/rubik_s_cube_ziptjc.jpg" alt="Image 1" width="200"/></td>
    <td><img src="https://res.cloudinary.com/dfl02brcp/image/upload/v1720604798/shoe_boaymq.jpg" alt="Image 2" width="200"/></td>
    <td><img src="https://res.cloudinary.com/dfl02brcp/image/upload/v1720604798/sunglass_dhca07.jpg" alt="Image 3" width="200"/></td>
    <td><img src="https://res.cloudinary.com/dfl02brcp/image/upload/v1720604798/pen_qy0leq.jpg" alt="Image 4" width="200"/></td>
  </tr>
</table>


<h2>Conclusion</h2>
<p>Language or technical barriers shouldn't hinder progress in the age of AI. We must actively participate in the revolution using our Bengali resources and leverage open-source foreign AI resources. Our system will make it easy for the mass Bengali population, regardless of their background, to join this journey and bring Bangladesh a step closer to a 'Smart Bangladesh'.</p>


<h1 align='center'>Diagrams form Project2</h1>
<h2>Bluetooth Car</h2>

![MasterHead](https://res.cloudinary.com/dfl02brcp/image/upload/v1720622156/Picture1_fss9cy.png)
![MasterHead](https://res.cloudinary.com/dfl02brcp/image/upload/v1720622156/Picture2_zdmkyj.png)
![MasterHead](https://res.cloudinary.com/dfl02brcp/image/upload/v1720622156/Picture3_fujhbo.png)
![MasterHead](https://res.cloudinary.com/dfl02brcp/image/upload/v1720622156/Picture4_ljdscn.png)

## Contact Information

For any further problems contact us: <br /> <br /> <strong>ML model developers:</strong> <br />

Name: Nasiat Hasan Fahim <br /> Registration No:2020331013 <br /> Email:nhfahim18@gmail.com <br /> CSE, SUST <br /> <br /> Name: Niloy
Sarker <br /> Registration No:2020331033 <br /> Email:niloysucker22@gmail.com <br /> CSE, SUST <br /> <br /> Name: Iqbal Mahmood Sajid
<br /> Registration No:2020331103 <br /> Email:imsajid428@gmail.com <br /> CSE, SUST <br />

<strong>App developers:</strong> <br /> <br /> Name: Rezaul Karim Sumon <br /> Registration No:2020331029 <br /> Email:rezaul0818@gmail.com
<br /> CSE, SUST <br />

Name: Md. Abid Ullah Muhib <br /> Registration No:2020331089 <br /> Email: uusshas12@gmail.com <br /> CSE, SUST <br />
