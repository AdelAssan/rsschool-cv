# rsschool-cv
# Assanova Adel
## Contacts
* Location: Astana, Kazakhstan
* Phone: +77086253569
* Email: adelassanova@gmail.com
* GitHub: AdelAssan

## About Me

#### I live in the city of Astana, I graduated from the IT-technologies faculty of ENU. I love to read, and I also enjoy dancing. Started web development courses in 2021. Currently looking for a dream job.

## Skills
* HTML
* CSS
* JavaScript
* React
* Git
* Node.js
* WebPack

## Code Example

```
request.onload = function() {
  if (request.status >= 200 && request.status < 400) {
    let data = JSON.parse(request.response);
    for(let i = 0; i < data.length; i++){
        if(data[i].price < 5){
            //console.log(data[i].name + data[i].price);
            let arr = data[i];
            //console.log(arr);
            sliderText.forEach((n) => n.textContent = arr.name);
            sliderAuthor.forEach((n) => n.textContent = arr.price);
        }
    }
  } else {
    console.log(request.status + "Ошибка")
  }
};
request.send();
```
## Education
* L.N.Gumilyov Eurasian National University: Computer Science and Software
* Yandex Practicum: web-developer

## Languages
* Russian - native
* Kazakh - conversational level
* English - B1