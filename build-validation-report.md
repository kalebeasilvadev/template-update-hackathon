# 🚨 Relatório de Validação de Build

**Data:** 02/12/2025, 19:07:45
**Projeto:** /Users/kalebeandrade/Dev/geral/template-update-hackathon
**Comando:** npm run build
**Status:** ❌ FALHOU

## 🔴 Erros Encontrados (14)


### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/clients/clients-page/clients-page.component.html:6:26 - error TS2339: Property 'tagline' does not exist on type 'Client[]'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/clients/clients-page/clients-page.component.html:7:48 - error TS2339: Property 'title' does not exist on type 'Client[]'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/clients/clients-page/clients-page.component.html:8:50 - error TS2339: Property 'description' does not exist on type 'Client[]'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/navmenu/navmenu.component.html:5:29 - error TS2339: Property 'link' does not exist on type 'MenuItem'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/navmenu/navmenu.component.html:9:18 - error TS2339: Property 'title' does not exist on type 'MenuItem'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/testimonial/testimonial-page/testimonial-page.component.html:8:42 - error TS2339: Property 'tagline' does not exist on type 'Testimonial[]'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/testimonial/testimonial-page/testimonial-page.component.html:9:46 - error TS2339: Property 'title' does not exist on type 'Testimonial[]'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/clients/clients-page/clients-page.component.html:6:26 - error TS2339: Property 'tagline' does not exist on type 'Client[]'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/clients/clients-page/clients-page.component.html:7:48 - error TS2339: Property 'title' does not exist on type 'Client[]'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/clients/clients-page/clients-page.component.html:8:50 - error TS2339: Property 'description' does not exist on type 'Client[]'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/navmenu/navmenu.component.html:5:29 - error TS2339: Property 'link' does not exist on type 'MenuItem'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/navmenu/navmenu.component.html:9:18 - error TS2339: Property 'title' does not exist on type 'MenuItem'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/testimonial/testimonial-page/testimonial-page.component.html:8:42 - error TS2339: Property 'tagline' does not exist on type 'Testimonial[]'.

### unknown:0:0
**Código:** GENERIC_ERROR
**Mensagem:** Error: src/app/testimonial/testimonial-page/testimonial-page.component.html:9:46 - error TS2339: Property 'title' does not exist on type 'Testimonial[]'.


## ⚠️ Avisos (0)



## 🔧 Correções Aplicadas (0)



## 📝 Saída Completa do Build

```

> website-practise@0.0.0 build
> ng build --configuration=production

- Generating browser application bundles (phase: setup)...
✔ Browser application bundle generation complete.
✔ Browser application bundle generation complete.

Error: src/app/clients/clients-page/clients-page.component.html:6:26 - error TS2339: Property 'tagline' does not exist on type 'Client[]'.

6           <h1>{{ clients.tagline }}</h1>
                           ~~~~~~~

  src/app/clients/clients-page/clients-page.component.ts:11:15
    11  templateUrl: './clients-page.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component ClientsPageComponent.


Error: src/app/clients/clients-page/clients-page.component.html:7:48 - error TS2339: Property 'title' does not exist on type 'Client[]'.

7           <h1 class="section-title">{{ clients.title }}</h1>
                                                 ~~~~~

  src/app/clients/clients-page/clients-page.component.ts:11:15
    11  templateUrl: './clients-page.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component ClientsPageComponent.


Error: src/app/clients/clients-page/clients-page.component.html:8:50 - error TS2339: Property 'description' does not exist on type 'Client[]'.

8           <p class="section-subtitle">{{ clients.description }}</p>
                                                   ~~~~~~~~~~~

  src/app/clients/clients-page/clients-page.component.ts:11:15
    11  templateUrl: './clients-page.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component ClientsPageComponent.


Error: src/app/navmenu/navmenu.component.html:5:29 - error TS2339: Property 'link' does not exist on type 'MenuItem'.

5     routerLink="{{ menuItem.link }}"
                              ~~~~

  src/app/navmenu/navmenu.component.ts:8:15
    8  templateUrl: './navmenu.component.html',
                    ~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component NavmenuComponent.


Error: src/app/navmenu/navmenu.component.html:9:18 - error TS2339: Property 'title' does not exist on type 'MenuItem'.

9     >{{ menuItem.title }}</a
                   ~~~~~

  src/app/navmenu/navmenu.component.ts:8:15
    8  templateUrl: './navmenu.component.html',
                    ~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component NavmenuComponent.


Error: src/app/testimonial/testimonial-page/testimonial-page.component.html:8:42 - error TS2339: Property 'tagline' does not exist on type 'Testimonial[]'.

8     <h1 class="pull-down">{{ testimonial.tagline }}</h1>
                                           ~~~~~~~

  src/app/testimonial/testimonial-page/testimonial-page.component.ts:29:15
    29  templateUrl: './testimonial-page.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component TestimonialPageComponent.


Error: src/app/testimonial/testimonial-page/testimonial-page.component.html:9:46 - error TS2339: Property 'title' does not exist on type 'Testimonial[]'.

9     <h2 class="section-title">{{ testimonial.title }}</h2>
                                               ~~~~~

  src/app/testimonial/testimonial-page/testimonial-page.component.ts:29:15
    29  templateUrl: './testimonial-page.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component TestimonialPageComponent.



Command failed: npm run build
- Generating browser application bundles (phase: setup)...
✔ Browser application bundle generation complete.
✔ Browser application bundle generation complete.

Error: src/app/clients/clients-page/clients-page.component.html:6:26 - error TS2339: Property 'tagline' does not exist on type 'Client[]'.

6           <h1>{{ clients.tagline }}</h1>
                           ~~~~~~~

  src/app/clients/clients-page/clients-page.component.ts:11:15
    11  templateUrl: './clients-page.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component ClientsPageComponent.


Error: src/app/clients/clients-page/clients-page.component.html:7:48 - error TS2339: Property 'title' does not exist on type 'Client[]'.

7           <h1 class="section-title">{{ clients.title }}</h1>
                                                 ~~~~~

  src/app/clients/clients-page/clients-page.component.ts:11:15
    11  templateUrl: './clients-page.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component ClientsPageComponent.


Error: src/app/clients/clients-page/clients-page.component.html:8:50 - error TS2339: Property 'description' does not exist on type 'Client[]'.

8           <p class="section-subtitle">{{ clients.description }}</p>
                                                   ~~~~~~~~~~~

  src/app/clients/clients-page/clients-page.component.ts:11:15
    11  templateUrl: './clients-page.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component ClientsPageComponent.


Error: src/app/navmenu/navmenu.component.html:5:29 - error TS2339: Property 'link' does not exist on type 'MenuItem'.

5     routerLink="{{ menuItem.link }}"
                              ~~~~

  src/app/navmenu/navmenu.component.ts:8:15
    8  templateUrl: './navmenu.component.html',
                    ~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component NavmenuComponent.


Error: src/app/navmenu/navmenu.component.html:9:18 - error TS2339: Property 'title' does not exist on type 'MenuItem'.

9     >{{ menuItem.title }}</a
                   ~~~~~

  src/app/navmenu/navmenu.component.ts:8:15
    8  templateUrl: './navmenu.component.html',
                    ~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component NavmenuComponent.


Error: src/app/testimonial/testimonial-page/testimonial-page.component.html:8:42 - error TS2339: Property 'tagline' does not exist on type 'Testimonial[]'.

8     <h1 class="pull-down">{{ testimonial.tagline }}</h1>
                                           ~~~~~~~

  src/app/testimonial/testimonial-page/testimonial-page.component.ts:29:15
    29  templateUrl: './testimonial-page.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component TestimonialPageComponent.


Error: src/app/testimonial/testimonial-page/testimonial-page.component.html:9:46 - error TS2339: Property 'title' does not exist on type 'Testimonial[]'.

9     <h2 class="section-title">{{ testimonial.title }}</h2>
                                               ~~~~~

  src/app/testimonial/testimonial-page/testimonial-page.component.ts:29:15
    29  templateUrl: './testimonial-page.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component TestimonialPageComponent.




```

---
*Relatório gerado automaticamente por [Codex Morpheus](https://github.com/codex-morpheus) - Build Validator*
