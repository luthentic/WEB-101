# Lee's Personal CS Book
- [DataStructure](#datastructure)
    + LinkedList
    + Stack
    + Queue
    + Tree
    + Heap
    + HashTable
    + Graph
    
- [DesignPattern](#designpattern)
    + Creational Design Pattern
    + Structural Design Pattern
    + Behavior   Design Pattern
    
- [SEO](#seo)
    + Optimization
    + SEO Checklist
    
- [Security](#security)
    + Injection Attacks
    + XSS
    + CSRF
    + XSS
    
- [Protocol](#protocol)
    
---

## DataStructure

**Linked List**
```csharp
```


**Stack**

**Queue**

**Tree**

**Heap**

**HashTable**

**Graph**

---

## DesignPattern

**CreationalDesign Pattern**

`
The creational patterns encapsulate the information about which specific classes the system uses. They completely hide the details of how instances of these classes are created and how they fit together. 
`

`
In other words, creational patterns encapsulate the creation and composition of objects, providing flexibility so that the program structure is not heavily affected even if a specific object is created or changed. 
`

`
They promote reusability, flexibility, and maintainability by abstracting the process of object instantiation. These patterns can be used to instantiate objects in various ways, such as using inheritance, interfaces, or delegation, depending on the specific requirements and constraints of the application.
`

   + Factory Pattern
    
   + Abstract Factory Pattern

   + Builder Pattern

   + Prototype Pattern
   
   + Singleton Pattern
   
**StructuralDesign Pattern**

`
Structural patterns are design patterns that involve combining classes or objects to create larger structures. 
`

`
For example, they can be used to combine two objects with different interfaces into a single interface or to group objects together to provide new functionality.
`

   + Adapter Pattern
   
   + Bridge Pattern
   
   + Composite Pattern
   
   + Decorator Pattern
   
   + Facade Pattern
   
   + Flywight Pattern

   + Proxy Pattern
 
**BehaviorDesign Pattern**

`
Behavioral patterns are design patterns that deal with algorithms and the distribution of responsibilities between objects or classes. 
`

`
They focus on how to distribute tasks that cannot be performed by a single object among multiple objects, with an emphasis on minimizing the coupling between objects. 
`

`
These patterns are typically applied to classes or objects, depending on whether the pattern primarily applies at the class level or the object level.
`

   + Chain of responsibility Pattern
    
   + Command Pattern
    
   + Interpreter Pattern
   
   + Iterator Pattern
   
   + Mediator Pattern
    
   + Template Mehtod Pattern
    
   + Visitor Pattern
    
   + Memonto Pattern
    
   + Observer Pattern
    
   + State Pattern
   
   + Strategy Pattern

---

## SEO
### Optimization
 
**1. Conduct keyword research**: </br>Identify the keywords and phrases that your target audience is using to search for information related to your industry or niche. Use keyword research tools to find relevant keywords and incorporate them into your content.

**2. Create high-quality content**: </br>Focus on creating high-quality, original, and engaging content that provides value to your audience. Use your targeted keywords naturally throughout the content.

**3. Optimize your website**: </br>Make sure your website is mobile-friendly, has a fast loading speed, and has a clear and user-friendly structure. Optimize your website's title tags, meta descriptions, and URLs.

**4. Build quality backlinks**: </br>Backlinks from high-quality and authoritative websites can improve your website's search engine ranking. Focus on building natural and relevant backlinks.

**5. Use social media**: </br>Promote your content on social media platforms to increase visibility and drive traffic to your website. Social media can also help you build relationships with your audience and improve engagement.

**6. Monitor and analyze your results**:</br> Use tools like Google Analytics to track your website's traffic and user behavior. Use this data to identify areas for improvement and adjust your SEO strategy accordingly.

---
### SEO Checklist

1. robots.txt (Robot exclusion standard file), Sitemap.xml (Site map)
2. Proper tag usage
3. Design with clear hierarchy
4. Use valid HTML (Semantic Markup)
5. Follow recommended guidelines for images, videos, and structured data
6. Ensure all pages are linked (with href attribute in a tag)
7. Make sure <alt> attribute is specific and accurate
8. Social search engine optimization meta tag OpenGraph
9. Use secure protocol (HTTPS)
    
---
## Security

1. **Injection Attacks:** Injection attacks occur when attackers inject malicious code into a website or application. This can be done through forms, URL parameters, or cookies. Attackers can use injection attacks to steal data, modify data, or execute malicious code.


2. **Cross-Site Scripting (XSS):** XSS attacks occur when attackers inject malicious code into a website or application that is then executed by users who visit the site. This can allow attackers to steal data, modify data, or execute malicious code on users' computers.


3. **Cross-Site Request Forgery (CSRF):** CSRF attacks occur when attackers trick users into executing actions on a website or application without their knowledge or consent. This can allow attackers to perform actions on behalf of the user, such as changing their password or making unauthorized purchases.


4. **Broken Authentication and Session Management:** Authentication and session management are critical components of web and app security. If these systems are not implemented properly, attackers can easily gain access to sensitive data or perform unauthorized actions.


5. **Insufficient Authorization:** Authorization is the process of determining what actions a user is allowed to perform within a system. If authorization is not implemented properly, attackers can gain access to sensitive data or perform unauthorized actions.


6. **Insecure Communications:** Insecure communications can allow attackers to intercept and read sensitive data, such as usernames, passwords, or credit card information. This can occur when websites or apps use unencrypted connections, or when they use weak encryption algorithms.


7. **Malicious File Uploads:** Malicious file uploads occur when attackers upload files containing malware or other malicious code to a website or application. This can allow attackers to gain access to sensitive data or execute code on the server.
    
---
## Protocol  
    
The literal meaning of the term "protocol" refers to "communication protocols necessary to facilitate smooth data communication between multiple computers or terminals." In other words, a communication protocol is exactly what the term "protocol" implies.    
 
A communication protocol can be understood as an agreement or set of rules that enable communication between different entities. It provides a standardized way for devices or systems to exchange information and ensures that they can understand and interpret the data being transmitted. In simpler terms, a communication protocol can be seen as a set of conventions or agreements that govern communication, allowing devices or systems to effectively and reliably communicate with each other.
    
**7 Application Layer:** HTTP, SMTP, SNMP, FTP, Telnet, SSH & SCP, NFS, RTSP
    
**6 Presentation Layer:** XDR, ASN.1, SMB, AFP
    
**5 Session Layer:** TLS, SSL, ISO 8327 / CCITT X.225, RPC, NetBIOS, AppleTalk
    
**4 Transport Layer:** TCP, UDP, RTP, SCTP, SPX, AppleTalk
    
**3 Network Layer:** IP, ICMP, IGMP, X.25, CLNP, ARP, RARP, BGP, OSPF, RIP, IPX, DDP
    
**2 Data Link Layer:** Ethernet, Token Ring, PPP, HDLC, Frame Relay, ISDN, ATM, Wireless LAN, FDDI
    
**1 Physical Layer:** Wire, Wireless, Fiber Optics, Coaxial Cable, Twisted Pair, PSTN, Repeater, DSU, CSU, Modem
    
---
    
**HTTP:** primarily transmitted hypermedia documents like HTML, but in recent times, it has evolved into an application-layer protocol that can transmit various forms of information, including plain text, JSON, XML, and more.

While it was originally designed for communication between web browsers and web servers, HTTP is now also utilized for communication with other purposes such as mobile applications and IoT devices.

HTTP follows the traditional client-server model, where the client establishes a connection to generate a request and waits for the response until it is received.

HTTP is a stateless protocol, meaning that the server does not maintain any state or data between requests. However, efforts to maintain state are made using mechanisms like cookies and sessions.
Typically, HTTP operates on top of the reliable TCP/IP layer, serving as an application protocol.

**GET:**

A request to retrieve a specific resource. It should not be used for resource creation, modification, or deletion.

**POST:**

Used to create a new resource or execute a controller. Typically used when submitting form data or performing actions that result in resource creation.

**PUT:**

Used to update a mutable resource and should always include resource identification information. It is conventionally used to update the entire object and is less commonly used for partial updates.

**PATCH:**

Used for partial updates to a mutable resource and should always include resource identification information. It is typically used when updating specific fields or properties of a resource without replacing the entire object. PUT is often preferred for updating the entire object.

**DELETE:**

Used to remove a specific resource. Typically, the resource ID to be deleted is passed in the URI path rather than the request body.

**HEAD:**

Used when the client wants to retrieve only the headers of a resource without the body. It is commonly used to check for resource existence or retrieve metadata without fetching the full resource.

**OPTIONS:**

Used by the client to inquire about the available actions that can be performed on the server's resource. Typically, the server responds with an Allow header containing the HTTP request methods that can be used on the resource. It is often used in the context of Cross-Origin Resource Sharing.
![25](https://github.com/luthentic/LeeCsStudy/assets/33567830/48d754e6-ac33-40c1-a5aa-789987fb1849)

---

## Unity Piple lines

### Built-in Rendering Pipeline:

    The built-in rendering pipeline is the traditional rendering system provided by Unity. It offers a good balance between performance and visual quality and is suitable for most projects. It includes a fixed-function pipeline and supports a variety of platforms.

### Scriptable Render Pipeline (SRP):

    The Scriptable Render Pipeline (SRP) is a customizable rendering system introduced by Unity. It allows developers to create their own rendering pipelines tailored to their specific project requirements. It provides more flexibility and control over the rendering process compared to the built-in pipeline.

### Universal Render Pipeline (URP):

    The Universal Render Pipeline (URP), formerly known as the Lightweight Render Pipeline (LWRP), is a pre-built rendering pipeline optimized for performance on a wide range of platforms, including mobile devices and low-end hardware. It aims to provide a balance between efficiency and visual quality, making it suitable for projects with less demanding graphical requirements.

### High Definition Render Pipeline (HDRP):

    The High Definition Render Pipeline (HDRP) is a high-fidelity rendering pipeline designed to produce visually stunning graphics in Unity. It offers advanced features such as real-time ray tracing, physically based lighting, and advanced post-processing effects. HDRP is primarily intended for high-end platforms and projects that require top-notch visuals.
    
    


