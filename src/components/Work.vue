<template>
  <div id='works' className='flex w-full md:w-[90%] min-h-screen my-auto mx-auto text-[#0a192f] dark:text-gray-300 bg-slate-100 dark:bg-[#0a192f]'>
      <div className='max-w-[750px] m-auto p-4 flex flex-col justify-center w-full h-full'>
        <div className='pb-8'>
            <p className='text-4xl font-bold inline border-b-4 text-[#0a192f] dark:text-gray-300 border-pink-600' data-aos="fade-in">
                {{ text.title }}
            </p>
            <p className='py-3 text-[#112240] font-medium dark:text-[#f9b82c] dark:font-normal' data-aos="fade-in">{{ text.subtitle }}</p>
        </div>

        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-in">
            <div className="flex flex-col md:w-[60%] py-4">
                <div className="flex flex-col relative top-[-35px]">
                    <span className="text-[#f9b82c] dark:text-[#64ffda] text-sm font-medium">{{ text.work01.subtitle }}</span>
                    <h3 className=" text-2xl font-semibold">{{ text.work01.title }}</h3>
                </div>
                <div className="md:p-4 md:w-[130%] rounded md:bg-slate-300 dark:md:bg-[#112240] z-10">
                    <p className=" text-sm text-justify font-medium dark:font-normal">
                        {{ text.work01.description }}
                    </p>
                </div>
                <div className="flex md:w-[130%] z-10 pt-4">
                    <ul className="flex flex-wrap text-sm font-medium text-[#4a6087] dark:text-slate-400" :style="{'-webkit-text-stroke': '0.1px black'}">
                        <li className="pr-4"> <p>React</p> </li>
                        <li className="pr-4"> <p>Redux</p> </li>
                        <li className="pr-4"> <p>Node</p> </li>
                        <li className="pr-4"> <p>Express</p> </li>
                        <li className="pr-4"> <p>PostgreSQL</p> </li>
                        <li className="pr-4"> <p>Sequelize</p> </li>
                    </ul>
                </div>
                <div className="flex relative bottom-[-20px]">
                    <a className='flex justify-between items-center dark:text-white pr-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://github.com/parzybaal/PI-Dogs-main' target='_blank' rel="noreferrer"> 
                        <fa :icon="['fab', 'github']" class="fa-lg" />
                    </a>
                    <a className='flex justify-between items-center dark:text-white pr-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://github.com/parzybaal/PI-Dogs-main' target='_blank' rel="noreferrer"> 
                        <fa icon="arrow-up-right-from-square" class="fa-lg" />
                    </a>
                </div>
            </div>
            <a className="hidden md:flex w-[70%] h-[250px] my-auto z-0 overflow-hidden" href='https://github.com/parzybaal/PI-Dogs-main' target='_blank' rel="noreferrer">
                <div className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300" :style="{'background-image': 'url(' + HenryDogs + ')'}"/>
            </a>
        </div>

        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-in">
            <a className="hidden md:flex w-[70%] h-[250px] my-auto z-0 overflow-hidden" href='https://pf-e-latam.netlify.app/' target='_blank' rel="noreferrer">
                <div className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300" :style="{'background-image': 'url(' + ELatam + ')'}"/>
            </a>
            <div className="flex flex-col md:w-[60%] py-4">
                <div className="flex flex-col relative top-[-35px] text-right">
                    <span className="text-[#f9b82c] dark:text-[#64ffda] text-sm font-medium">{{ text.work02.subtitle }}</span>
                    <h3 className=" text-2xl font-semibold">{{ text.work02.title }}</h3>
                </div>
                <div className="md:p-4 md:w-[130%] relative md:right-[30%]  rounded md:bg-slate-300 dark:md:bg-[#112240] z-10">
                    <p className=" text-sm text-justify font-medium dark:font-normal">
                        {{ text.work02.description }}
                    </p>
                </div>
                <div className="flex md:w-[130%] relative md:right-[30%] z-10 pt-4">
                    <ul className="flex flex-wrap md:justify-end text-sm font-medium text-[#4a6087] dark:text-slate-400" :style="{'-webkit-text-stroke': '0.1px black'}">
                        <li className="md:pl- pr-4 md:pr-0"> <p>React</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0"> <p>Redux toolkit</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0"> <p>Express</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0"> <p>Firebase</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0"> <p>PostgreSQL</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0"> <p>Sequelize</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0"> <p>JWT</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0"> <p>Cloudinary</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0"> <p>SCRUM</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0"> <p>Nodemailer</p> </li>
                    </ul>
                </div>
                <div className="flex relative bottom-[-20px] justify-end">
                    <a className='flex justify-between items-center dark:text-white pl-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://github.com/parzybaal/PF-E-Latam' target='_blank' rel="noreferrer"> 
                        <fa :icon="['fab', 'github']" class="fa-lg" />
                    </a>
                    <a className='flex justify-between items-center dark:text-white pl-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://pf-e-latam.netlify.app/' target='_blank' rel="noreferrer"> 
                        <fa icon="arrow-up-right-from-square" class="fa-lg" />
                    </a>
                </div>
            </div>
        </div>
      </div>
  </div>
</template>

<script>
import ELatam from '../assets/e-latam.png'
import HenryDogs from '../assets/HenryDogs.jpeg'

export default {
    data() {
        return {
            ELatam,
            HenryDogs,
            eng: {
                title: 'Work',
                subtitle: '// Check out some of my recent work',
                work01: {
                    title: 'Dogs app',
                    subtitle: 'Featured Project',
                    description: 'A SPA that consumes data from an external API, and allows the visualization of general and detailed information of more than 100 species of dogs, among the functionalities that this APP has available is filtering and ordering dogs by temperaments, weight, height and names, in addition of the creation of new species of dogs, through a controlled form.'
                },
                work02: {
                    title: 'E-latam commerce',
                    subtitle: 'Featured Project',
                    description: 'An e-commerce of electronic products that consumes its own database allows users to register, browse, filter, order and add products to the cart. They can also modify their profile and make payments securely through an integration with Stripe. In addition, the administrator is provided with a control panel where he can modify products, hide products, grant privileges, delete user reviews and use sales statistics to manage trade efficiently.'
                },
            }, 
            es: {
                title: 'Proyectos',
                subtitle: '// Mira algunos de mis proyectos más recientes',
                work01: {
                    title: 'Aplicación de Perros',
                    subtitle: 'Proyecto Destacado',
                    description: 'Una SPA que consume datos de una API externa, y permite la visualización de información general y detallada de más de 100 especies de perros, entre las funcionalidades que dispone esta APP está el filtrar y ordenar perros por temperamentos, peso, altura y nombres, además de la creación de nuevas especies de perros, mediante un formulario controlado.'
                },
                work02: {
                    title: 'E-latam comercio digital',
                    subtitle: 'Proyecto Destacado',
                    description: 'Un e-commerce de productos electronicos consumiendo una base de datos propia donde el usuario puede registrarse, navegar, filtrar, ordenar y agregar productos al carrito, modificar perfil y pagar de manera segura con una integración de Stripe. Así como un admin puede con su dashboard modificar productos, ocultar, dar privilegios o eliminar reseñas de usuarios y utilizar estadisticas de ventas para gestionar su comercio de la manera mas eficiente'
                },
            },
        }
    }, 
    computed: {
        text() {
            return this.$store.state.lang === 'en' ? this.eng : this.es
        }
    },
}
</script>

<style scoped>
    .bg {
        background-color: rgba(0, 128, 128, 0.6);
        background-blend-mode: lighten;
        border-radius: 0.25rem;
    }

    .bg:hover {
        cursor: pointer;
    }
</style>