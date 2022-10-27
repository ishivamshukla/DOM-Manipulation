# DOM Manipulation 

## Coding in Browser Console
---


1. Webiste Name: [Dev To](https://dev.to/)


### Code

    document.querySelector(".side-bar .crayons-subtitle-2").innerHTML = "Shivam Shukla"
    document.querySelector(".side-bar .color-base-70").innerHTML ="I write Code"

### Output

![Output](./assets/Images/Pic2.png)

2. Website Name: [Apple](https://support.apple.com/en-in)


### Code

     let arr = []; document.querySelectorAll(".as-imagegrid-item").forEach((e) => arr.push(e.innerText.replace("\nSupport", ""))); 

### Output

['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']

---

3. Webiste Name: [Youtube Support](https://support.google.com/youtube/)



### Code

     let card = document.querySelector(".article .accordion-homepage"); let list = document.createElement("section"); list.className = "parent"; list.appendChild(document.createElement("h3")); list.querySelector("h3").textContent = "My New Faq"; card.appendChild(list);

### Output

![Output](./assets/Images/Pic5.png)
​

---

4. Webiste Name: [OnePlus](https://www.oneplus.in/support)



### Code

     document.querySelector(".customer-support .one-tel-number").innerText = "7677263012"

### Output

![Output](./assets/Images/Pic7.png)

---
5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)



### Code

      document.querySelector(".feature-column-carousel__button .cta").innerText = "Check Out"

### Output

![Output](./assets/Images/Pic9.png)

---
6. Webiste Name: [Adidas](https://www.adidas.co.in/)



### Code

     document.querySelector(".searchinput___zXLAR").style.backgroundColor="red"

### Output

![Output](./assets/Images/Pic11.png)

---
7. Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)



### Code

      function search(e){
      let input = document.querySelector("#hp-search-input");
      input.value = e;
      let form = document.querySelector("#hp-search-form");
      form.submit();
      }
      search('css'); 

### Output

![Output](./assets/Images/Pic13.png)

---
8. Webiste Name: [Google](https://www.google.com/)



### Code

     let arr = document.querySelectorAll("#SIvCob a");
     for(let i = 0; i < arr.length; i++){
     if(i % 2 == 0){
          arr[i].remove();
          }
     }

### Output

![Output](./assets/Images/Pic15.png)


---
9. Webiste Name: [Code Wars](https://www.codewars.com/)



### Code

    document.querySelector(".display-heading-1").style.fontFamily = "monospace"
    document.querySelector(".display-heading-1").style.backgroundColor = "orange"
    document.querySelector(".display-heading-1").style.color = "red"
     

### Output

![Output](./assets/Images/Pic17.png)

---
10. Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)



### Code
     document.querySelector(".col-lg-8 .login-btn-text").addEventListener("mouseover", function hover() {document.querySelector(".col-lg-8 .login-btn-text").style.backgroundColor = "red";});

### Output

![Output](./assets/Images/Pic19.png)


---
11. Webiste Name: [realme](https://www.realme.com/in/)



### Code

     document.querySelector(".logo .icon").style.backgroundImage = "url('https://ineuron.ai/images/ineuron-logo.png')";

### Output

![Output](./assets/Images/Pic21.png)


---
12. Webiste Name: [Github](https://github.com/)



### Code

     document.querySelector(".dashboard-sidebar .Details.js-repos-container .f4 .btn").style.backgroundColor = "blue";

### Output

![Output](./assets/Images/Pic23.png)


---
13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)



### Code

      document.querySelector(".fl-module-content .fl-heading").innerText = "JSBootcamp";

### Output

![Output](./assets/Images/Pic25.png)


---
14. Webiste Name: [Asus](https://www.asus.com/in/)



### Code

     document.querySelector(".HotDealsAll__HotCampaignsEventsContainer__FK0V2 .HotDealsAll__Heading__2fIbe").style.fontSize="80px;

### Output

![Output](./assets/Images/Pic27.png)


---
15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)



### Code

     document.querySelector("#main-content-container .row .col-md-6 .mb-2 .mb-md-0 .page-title").style.textAlign = "right";

### Output

![Output](./assets/Images/Pic29.png)


---
16. Webiste Name: [Vercel](https://vercel.com/)



### Code

document.querySelector(".section-title_title__VEDfK").innerText = "Start with Scratch";

### Output

![Output](./assets/Images/Pic31.png)


---
17. Webiste Name: [Sony](https://www.sony.co.in/)



### Code

     let date = new Date; document.querySelector(".btn-container").innerText = date;

### Output

![Output](./assets/Images/Pic32.png)

---
18. Webiste Name: [Philips](https://www.philips.co.in/)


### Code

     querySelector(".globalfooter .p-f03-footer-container .p-footer").style.backgroundColor = "orange";

### Output

![Output](./assets/Images/Pic35.png)


---
19. Webiste Name: [Canon](https://in.canon/)



### Code

     document.querySelector(".navbar-brand").innerText = "https://in.canon/assets/brand/logo-300-002e45a4aec98fd92899838da9d5560f.png"

### Output

![Output](./assets/Images/Pic37.png)

---
20. Webiste Name: [Oppo](https://www.oppo.com/in/)



### Code

document.querySelector(".product-card-content .wide .desc").style.color = "orange";

### Output

![Output](./assets/Images/Pic39.png)