<style>
    @media(min-width: 1024px) and (max-width: 1315px){
        .main-brand-cards{
            display: none;
        }
    }

    .company-image{
        cursor: pointer;
        transition: transform 500ms;
        transition: all 0.5s ease-in-out;
    }

    .company-image:hover{
        transform: translateY(-15px);
    }
</style>

<!--start of companies icon section-->
<section class="main-brand-cards invisible h-0 w-0 p-0 m-0 lg:mt-64 lg:w-full lg:h-48 lg:p-10 lg:visible" id="brands">
    <div class="flex w-4/5 m-auto justify-evenly">
        <div class="company-image border border-green-900 rounded-lg px-4 py-2 flex justify-center items-center shadow-md shadow-green-900/60 mx-4">
            <img class="w-80 p-100" alt="companies-icon-1" src="./images/company-icons/companies-icon-1.jpg"/>
        </div>
        <div class="company-image border border-green-900 rounded-lg px-4 py-2 flex justify-center items-center shadow-md shadow-green-900/60 mx-4">
            <img class="w-80 p-100" alt="companies-icon-2" src="./images/company-icons/companies-icon-2.jpg"/>
        </div>
        <div class="company-image border border-green-900 rounded-lg px-4 py-2 flex justify-center items-center shadow-md shadow-green-900/60 mx-4">
            <img class="w-80" alt="companies-icon-3" src="./images/company-icons/companies-icon-3.svg"/>
        </div>
    </div>
</section>
<!--end of companies icon section-->