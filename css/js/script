const hiddenElements = document.querySelectorAll('.hidden');

window.addEventListener('scroll', () => {

    hiddenElements.forEach(element => {

        const elementTop = element.getBoundingClientRect().top;

        if(elementTop < window.innerHeight - 100){
            element.classList.add('show');
        }

    });

});