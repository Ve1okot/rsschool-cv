# Vyacheslav Skulkov


## Contact
- Discord: @Ve1okot
- Telegram: @Robin_Cat


![image](./photo.jpg "photo")


## About
I am 32 years old, live in Russia. I want to learn how to create web applications, understand how sites work in order to create good and user-friendly projects. I love my MTB, photography and cats.


## Skills
- HTML
- CSS
- SQL
 
* Photoshop
* Movavi Video Editor
* Figma
* VS Code


## Education
Bachelor of Science: **Automation of Technological Processes** - 2018,
**Moscow Institute of Steel and Alloys**

## Work Exp.
2013-2018 Production worker 
2018-2022 Process Control Engineer


## English А1. Beginner


## Code
```
const deleteBtn = document.querySelector('.delete_btn')
const deleteForm = document.querySelector('.form_delete')
    if (deleteBtn) {
        deleteBtn.addEventListener('click', (event) => {
        event.preventDefault()
        if (window.confirm("Удалить эту запись?")) {
            deleteForm.submit()
        }
    })
    }
   
const materTd = document.querySelectorAll('.mater_td')    
materTd.forEach((singleMater) => {
        if (singleMater.textContent.includes("Мел")) {
            singleMater.style.backgroundColor = "fcfcfc"
        } else if (singleMater.textContent.includes("Глина")) {
            singleMater.style.backgroundColor = "f5bb9f"
        } else if (singleMater.textContent.includes("Бокситы")) {
            singleMater.style.backgroundColor = "f5bb9f"
        } else if (singleMater.textContent.includes("Бой")) {
            singleMater.style.backgroundColor = "aaa"
        } else {
            singleMater.style.backgroundColor = ""
        }        
    })

    document.querySelector('.total_span').innerHTML = "<?=$i-1?>"
```