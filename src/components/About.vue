<template>
    <div id='about' className='w-full md:w-[90%] min-h-screen flex flex-row mx-auto bg-slate-100 dark:bg-[#0a192f]' >
        <div className='flex flex-col justify-center items-center w-full h-full m-auto px-8'>
            <div className='max-w-[750px] w-full grid grid-cols-2 gap-8' data-aos="fade-in" >
                <div className='pb-8'>
                    <p className='text-4xl text-[#0a192f] dark:text-gray-300 font-bold inline border-b-4 border-pink-600'>{{ text.section }}</p>
                </div>
                <div></div>
                </div>
                <div className='max-w-[750px] w-full first:grid sm:grid-cols-2 gap-8'>
                    <div className='text-4xl font-bold text-[#f9b82c]' data-aos="fade-in">
                        <p>{{text.title}}</p>
                    </div>
                    <div>
                        <p className='text-slate-700 font-medium dark:text-slate-100 dark:font-normal text-justify my-4' data-aos="fade-in">
                            {{ text.text }} <br> <br> {{ text.subtext }}
                        </p>
                    </div>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    data() {
        return {
            eng: {
                section: 'About',
                title: 'Nice to meet you. Please take a look around.',
                text: 'Since I was very young, I have been interested in technology. At the age of 15, I built my first PC. I enjoy playing video games, meeting new people, and facing challenges that put my skills to the test.',
                subtext: "Up to date, I have completed a practical UX/UI course at educaciónIT and an advanced HTML/CSS course at Coderhouse. I have also successfully finished the Henry bootcamp. I keep studying and seeking new challenges to enhance my skills. If you're looking for a collaborator or a new recruit, feel free to contact me!"
            },
            es: {
                section: 'Sobre mi',
                title: '¡Siéntete libre de explorar mi portafolio!',
                text: 'Desde muy pequeño estuve interesado en la tecnología. A los 15 años, armé mi primera PC. Me gustan los videojuegos, conocer nuevas personas y enfrentar desafíos que pongan a prueba mis habilidades.',
                subtext: 'A la fecha, he completado un curso práctico de UX/UI en educaciónIT y otro sobre HTML/CSS avanzado en Coderhouse. Asimismo, finalicé exitosamente el bootcamp de Henry. Sigo estudiando y buscando nuevos desafíos para mejorar mis habilidades. Si estás en busca de un colaborador o un nuevo miembro en tu equipo, ¡no dudes en contactarme!',
            },
            isVisible: false,
        }
    }, computed: {
        text() {
            return this.$store.state.lang === 'en' ? this.eng : this.es
        }
    }
}
</script>