# GSoC'22 Project - [WIP]VueJS Simulator

## New Frontend Framework for Simulator UI.
- [Phase-1 Report](https://blog.circuitverse.org/posts/devjitchoudhury_gsoc22_phase1_report/)
- [Phase-2 Report](https://blog.circuitverse.org/posts/devjitchoudhury_gsoc22_phase2_report/)

### Project Goals - 
1. Replacing JqueryUI with a modern frontend framework.
2. Decoupling the Simulator from backend
3. Dividing into Components
4. State Management
5. Refactoring CSS
6. Internationalization using Vue-i18n


### To Dos -
1. **Vue Project Integration** into the Main Repository or finding a way for the simulators in two different repositories to work in sync.
2. **API Integration and Testing**
3. **Embed Feature** - Discuss and implement the embeding of circuits feature.
4. **Internationalization of Simulator** - Internationalization is already set up using Vue-i18n but progressive work needs to be done on it.
5. **Refactoring of Styles** - Refactor the global stylesheet to local stylesheets for individual components. There is also a scope of removing SASS using modern CSS features.
6. Few components - Verilog Module, Quick-Button, Testbench, and Timing-Diagram are yet to be converted to Vue. 
7. With the removal of jQuery-UI, there is also a scope of removing the use of jQuery from the project.

### Setting up CV-frontend-vue

Please go through the [Contribution Guidelines](CONTRIBUTING.md) before going forward with any development. This helps us keep the process streamlined and results in better PRs.

If you have any setup problems, please ensure you have read through all the instructions have all the required software installed before creating an issue.

### Manual Setup (Local Environment)
#### Dependencies
- [Git](https://git-scm.com/) - Vuetify
- [Vue Router](https://router.vuejs.org/) - Vue Router
- [Pinia](https://pinia.vuejs.org/)  - Pinia (State Management)
- [npm](https://www.npmjs.com/) - JavaScript package manager
- [Vue i18n](https://kazupon.github.io/vue-i18n/) - Vue i18n
- [ES Lint + Preetier](https://imagemagick.org/) -  ES Lint + Preetier (Code Linting & Fomatting)


#### Setup