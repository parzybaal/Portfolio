<template>
    <!-- SUPER-MARKET -->
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
                    <span className="text-[#f9b82c] dark:text-[#00FF00] text-sm font-medium">{{ text.work05.subtitle }}</span>
                    <h3 className=" text-2xl font-semibold">{{ text.work05.title }}</h3>
                </div>
                <div className="md:p-4 md:w-[130%] rounded md:bg-slate-300 dark:md:bg-[#112240] z-10">
                    <p className=" text-sm font-medium dark:font-normal">
                        {{ text.work05.description }}
                    </p>
                </div>
                <div className="flex md:w-[130%] z-10 pt-4">
                    <ul className="flex flex-wrap text-sm font-medium text-[#4a6087] dark:text-slate-400" :style="{'-webkit-text-stroke': '0.1px black'}">
                        <li className="pr-4 dark:text-[#06a608]"> <p>React</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Redux</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Node</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Nest</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>MySQL</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>MaterialUI</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Sass</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Prisma</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Typescript</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Docker</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>AWS(S3, RDS, EC2)</p> </li>
                    </ul>
                </div>
                <div className="flex relative bottom-[-20px]">
                    <a className='flex justify-between items-center dark:text-white pr-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://github.com/parzybaal/super-market-client' target='_blank' rel="noreferrer"> 
                        <fa :icon="['fab', 'github']" class="fa-lg" />
                    </a>
                    <a className='flex justify-between items-center dark:text-white pr-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://github.com/parzybaal/super-market-server' target='_blank' rel="noreferrer"> 
                        <fa icon="arrow-up-right-from-square" class="fa-lg" />
                    </a>
                </div>
            </div>
            <a className="hidden md:flex w-[100%] h-[200px] my-auto z-0 overflow-hidden" href='https://github.com/parzybaal/super-market-client' target='_blank' rel="noreferrer">
                <img src="https://i.postimg.cc/DwhXW0x7/super-market.png" className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300"/>
            </a>
        </div>
        <!-- INDIAN & CO -->
        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-in">
            <a className="hidden md:flex w-[100%] h-[250px] my-auto z-0 overflow-hidden" href='https://www.indianandco.com.ar/' target='_blank' rel="noreferrer">
                <img src="https://i.postimg.cc/Hkt7bmNX/indianandco.png" className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300"/>
            </a>
            <div className="flex flex-col md:w-[60%] py-4">
                <div className="flex flex-col relative top-[-35px] text-right">
                    <span className="text-[#f9b82c] dark:text-[#64ffda] text-sm font-medium">{{ text.work04.subtitle }}</span>
                    <h3 className=" text-2xl font-semibold">{{ text.work04.title }}</h3>
                </div>
                <div className="md:p-4 md:w-[130%] relative md:right-[30%]  rounded md:bg-slate-300 dark:md:bg-[#112240] z-10">
                    <p className=" text-sm text-justify font-medium dark:font-normal">
                        {{ text.work04.description }}
                    </p>
                </div>
                <div className="flex md:w-[130%] relative md:right-[30%] z-10 pt-4">
                    <ul className="flex flex-wrap md:justify-end text-sm font-medium text-[#4a6087] dark:text-slate-400" :style="{'-webkit-text-stroke': '0.1px black'}">
                        <li className="md:pl- pr-4 md:pr-0 dark:text-[#0000FF]"> <p>React</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#0000FF] text-shadow: 8px 8px 8px rgb(0, 0, 0);"> <p>MaterialUI</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#0000FF]"> <p>Express</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#0000FF]"> <p>Javascript</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#0000FF]"> <p>MongoDB</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#0000FF]"> <p>Express</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#0000FF]"> <p>Mongoose</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#0000FF]"> <p>Cloudinary</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#0000FF]"> <p>Passport</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#0000FF]"> <p>JWT</p> </li>
                    </ul>
                </div>
                <div className="flex relative bottom-[-20px] justify-end">
                    <a className='flex justify-between items-center dark:text-white pl-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://www.indianandco.com.ar/' target='_blank' rel="noreferrer"> 
                        <fa icon="arrow-up-right-from-square" class="fa-lg" />
                    </a>
                </div>
            </div>
        </div>
        <!-- MUNIA -->
        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-in">
            <div className="flex flex-col md:w-[60%] py-4">
                <div className="flex flex-col relative top-[-35px]">
                    <span className="text-[#f9b82c] dark:text-[#64ffda] text-sm font-medium">{{ text.work03.subtitle }}</span>
                    <h3 className=" text-2xl font-semibold">{{ text.work03.title }}</h3>
                </div>
                <div className="md:p-4 md:w-[130%] rounded md:bg-slate-300 dark:md:bg-[#112240] z-10">
                    <p className=" text-sm text-justify font-medium dark:font-normal">
                        {{ text.work03.description }}
                    </p>
                </div>
                <div className="flex md:w-[130%] z-10 pt-4">
                    <ul className="flex flex-wrap text-sm font-medium text-[#4a6087] dark:text-slate-400" :style="{'-webkit-text-stroke': '0.1px black'}">
                        <li className="pr-4 dark:text-[#06a608]"> <p>React</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>MaterialUI</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Javascript</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Sass</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Redux</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Typescript</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>PostgreSQL</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Prisma</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Express</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>React-Query</p> </li>
                    </ul>
                </div>
                <div className="flex relative bottom-[-20px]">
                    <a className='flex justify-between items-center dark:text-white pr-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://munia.co/' target='_blank' rel="noreferrer"> 
                        <fa icon="arrow-up-right-from-square" class="fa-lg" />
                    </a>
                </div>
            </div>
            <a className="hidden md:flex w-[100%] h-[250px] my-auto z-0 overflow-hidden" href='https://munia.co/' target='_blank' rel="noreferrer">
                <img src="https://i.postimg.cc/FKWdnZNK/munia.png" className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300"/>
            </a>
        </div>
        <!-- MARVEL COMICS  -->
        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-in">
            <div className="flex flex-col md:w-[60%] py-4">
                <div className="flex flex-col relative top-[-35px]">
                    <span className="text-[#f9b82c] dark:text-[#64ffda] text-sm font-medium">{{ text.work06.subtitle }}</span>
                    <h3 className=" text-2xl font-semibold">{{ text.work06.title }}</h3>
                </div>
                <div className="md:p-4 md:w-[130%] rounded md:bg-slate-300 dark:md:bg-[#112240] z-10">
                    <p className=" text-sm text-justify font-medium dark:font-normal">
                        {{ text.work06.description }}
                    </p>
                </div>
                <div className="flex md:w-[130%] z-10 pt-4">
                    <ul className="flex flex-wrap text-sm font-medium text-[#4a6087] dark:text-slate-400" :style="{'-webkit-text-stroke': '0.1px black'}">
                        <li className="pr-4 dark:text-[#0000FF]"> <p>React</p> </li>
                        <li className="pr-4 dark:text-[#0000FF]"> <p>MaterialUI</p> </li>
                        <li className="pr-4 dark:text-[#0000FF]"> <p>Javascript</p> </li>
                        <li className="pr-4 dark:text-[#0000FF]"> <p>Sass</p> </li>
                        <li className="pr-4 dark:text-[#0000FF]"> <p>Redux</p> </li>
                        <li className="pr-4 dark:text-[#0000FF]"> <p>AWS(S3)</p> </li>
                    </ul>
                </div>
                <div className="flex relative bottom-[-20px]">
                    <a className='flex justify-between items-center dark:text-white pr-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='http://juanpabloosudar-spa-marvel.s3-website.us-east-2.amazonaws.com/' target='_blank' rel="noreferrer"> 
                        <fa :icon="['fab', 'github']" class="fa-lg" />
                    </a>
                </div>
            </div>
            <a className="hidden md:flex w-[100%] h-[250px] my-auto z-0 overflow-hidden" href='http://juanpabloosudar-spa-marvel.s3-website.us-east-2.amazonaws.com/' target='_blank' rel="noreferrer">
                <img src="https://i.postimg.cc/9fFwpS3S/marvel.png" className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300"/>
            </a>
        </div>
        <!-- E-LATAM -->

        <div className='flex bg-slate-300 dark:bg-[#112240] bg-cover px-8 py-12 md:bg-transparent dark:md:bg-transparent md:p-0 mb-12' data-aos="fade-in">
            <a className="hidden md:flex w-[100%] h-[250px] my-auto z-0 overflow-hidden" href='https://pf-e-latam.netlify.app/' target='_blank' rel="noreferrer">
                <img src="https://i.postimg.cc/tT55Dg5j/e-latam.png" className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300"/>
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
                        <li className="md:pl- pr-4 md:pr-0 dark:text-[#06a608]"> <p>React</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608] text-shadow: 8px 8px 8px rgb(0, 0, 0);"> <p>Redux toolkit</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Express</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Firebase</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>PostgreSQL</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Sequelize</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>JWT</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Cloudinary</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>SCRUM</p> </li>
                        <li className="md:pl-4 pr-4 md:pr-0 dark:text-[#06a608]"> <p>Nodemailer</p> </li>
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
        <!-- HENRY DOGS -->
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
                        <li className="pr-4 dark:text-[#06a608]"> <p>React</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Redux</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Node</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Express</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>PostgreSQL</p> </li>
                        <li className="pr-4 dark:text-[#06a608]"> <p>Sequelize</p> </li>
                    </ul>
                </div>
                <div className="flex relative bottom-[-20px]">
                    <a className='flex justify-between items-center dark:text-white pr-4 hover:text-pink-600 dark:hover:text-pink-600 duration-300' href='https://github.com/parzybaal/PI-Dogs-main' target='_blank' rel="noreferrer"> 
                        <fa :icon="['fab', 'github']" class="fa-lg" />
                    </a>
                </div>
            </div>
            <a className="hidden md:flex w-[100%] h-[250px] my-auto z-0 overflow-hidden" href='https://github.com/parzybaal/PI-Dogs-main' target='_blank' rel="noreferrer">
                <img src="https://i.postimg.cc/d3V9fKHT/Henry-Dogs.jpg" className="bg md:flex w-full h-full my-auto z-0 bg-cover hover:bg-transparent duration-300"/>
            </a>
        </div>
      </div>
  </div>
  
</template>

<script>

export default {
    data() {
        return {
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
                work03: {
                    title: 'E-latam commerce',
                    subtitle: 'Featured Project',
                    description: 'An e-commerce of electronic products that consumes its own database allows users to register, browse, filter, order and add products to the cart. They can also modify their profile and make payments securely through an integration with Stripe. In addition, the administrator is provided with a control panel where he can modify products, hide products, grant privileges, delete user reviews and use sales statistics to manage trade efficiently.'
                },
                work04: {
                    title: 'E-latam commerce',
                    subtitle: 'Featured Project',
                    description: 'An e-commerce of electronic products that consumes its own database allows users to register, browse, filter, order and add products to the cart. They can also modify their profile and make payments securely through an integration with Stripe. In addition, the administrator is provided with a control panel where he can modify products, hide products, grant privileges, delete user reviews and use sales statistics to manage trade efficiently.'
                },
                work05: {
                    title: 'E-latam commerce',
                    subtitle: 'Featured Project',
                    description: 'An e-commerce of electronic products that consumes its own database allows users to register, browse, filter, order and add products to the cart. They can also modify their profile and make payments securely through an integration with Stripe. In addition, the administrator is provided with a control panel where he can modify products, hide products, grant privileges, delete user reviews and use sales statistics to manage trade efficiently.'
                },
                work06: {
                    title: 'Marvel Comics',
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
                work03: {
                    title: 'Munia',
                    subtitle: 'Proyecto Destacado',
                    description: 'Contribución al logro de crear una sección donde usuarios, empresas y profesionales de la salud puedan registrarse en la plataforma y administrar ellos mismos sesiones entre sí de una manera sencilla y segura. Ofreciéndole a Munia la posibilidad de administrar y monitorear desde su dashboard la web.'

                },
                work04: {
                    title: 'Indian & Co',
                    subtitle: 'Proyecto Destacado',
                    description: 'Trabajo colaborativo en un equipo para el desarrollo de un e-commerce autoadministrable utilizando la metodología SCRUM. Desempeño de roles duales como Product Owner y desarrollador full stack para todo el ciclo de vida de desarrollo de la aplicación. Contribución al éxito del desarrollo del e-commerce Indian & Co resultando en el aumento de fortalecer y expandir la presencia de la marca en línea.'
                },
                work05: {
                    title: 'Super-Market',
                    subtitle: 'Proyecto aún en desarrollo',
                    description: 'Diseño y desarrollo de un super mercado para realizar compras y pedidos online, registros de usuarios, estadísticas, autoadministrable, filtros por categorías y subcategorías, reseñas, todos los metodos de pago, envíos, etc...'
                },
                work06: {
                    title: 'Marvel Comics',
                    subtitle: 'Featured Project',
                    description: 'Prueba técnica donde el objetivo era desarrollar una SPA donde se puedan buscar y visualizar de manera paginada cómics traídos desde la API pública de Marvel Comics utilizando un stack específico y desplegarlo.'
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
        background-color: #00808099;
        background-blend-mode: lighten;
        border-radius: 0.25rem;
        color: #06a608;
    }

    .bg:hover {
        cursor: pointer;
    }
</style>