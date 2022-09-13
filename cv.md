# rsschool-cv
# Assanova Adel
## Contacts
* Location: Nur-Sultan, Kazakhstan
* Phone: +77086253569
* Email: adelassanova@gmail.com
* GitHub: AdelAssan

## About Me

#### I live in the city of Nur-Sultan (Astana), I graduated from the IT-technologies faculty of ENU. I love to read, and I also enjoy dancing. Started web development courses in 2021. Currently looking for a dream job.

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
React.useEffect(() => {
        if (loggedIn) {
            setIsLoadingAllData(true);
            api.getAllData()
                .then((data) => {
                        const [userData, cardsData] = data;
                        putCards(cardsData.reverse());
                        setCurrentUser(userData);
                    }
                ).catch(error => console.log(error))
                .finally(() => {
                    setIsLoadingAllData(false);
                })
        }
    }, [loggedIn]);
```
## Education
* L.N.Gumilyov Eurasian National University
+ Computer Science and Software
* Yandex Practicum
+ web-developer

## Languages
* Russian - native
* Kazakh - conversational level
* English - B1