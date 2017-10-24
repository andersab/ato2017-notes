# Jack of all trades - Development with Vuejs
**Presenter**: Tirell Mckinnon
Skookum
**Slides**: https://goo.gl/N7V8Vt

* was just a library, now a progressive framework

## BLUF
* What is VUe
* Why Vue
* Components
* Build Tools
* Vue Ecosystem
* Vue APIs

**Users**: Alibaba, Github, Codeship

## What Problems are being solved
* Declarative Rendering
* Component System
* State Management -> single source of truth
* Build System

## Component Driven Architecture
* Module Based Development

### Single File Components (SFC)
```plantuml
object html
object Vue
object js
object css

html -down-> Vue
js -up-> Vue
css -up-> Vue
```

### Global Components
* user Vue -> for global component registry

### Component props
* Properties passed into components
    * Properties should be immutable
* Events will always be passed up

### Vue Rendering
* Options: templates or render funcs
    * End result -> declarative map state to output

## Vue API
* Global Config
* Options 
    * Data
    * Options DOM
    * Options Lifecycle Hooks
    * Options Assets
    * Options Misc
* Instance Propreties
    * Instance Methods
* Special Attributes
* Built in Comp

## Directives
* Core and Custom Directives are available

## Event Handling
* v-<event> tag
* @<event> tag
- @<event>.modifier

## Reactivity
* ES6 Getter/Setter
* Computed Property
* Watcccccher Instances
* Makes things simple
* Saves time

## Vue Ecosystem
* vue-router
* vuex
* vue-cli
* vueloader
* vuerx
* vue-devtools

## State Management - Vuex

### Core Concepts
* State
* Getters
* Mutators
* Actions
* Modules

## Vue Router
* Async components (splitting imports)
* Nested Component Routing
* Guarded Routes
* Router and state sync 

## Webpack + VUe
* use it, use it, use it

## Target your favorites
* Lang targets

## SFC Components
* Build tools break out to a split of files (css, html, js, etc)

## Server Side Rendering
* https://ssr.vuejs.org/en
* NUXT

## **AWESOME VUE** - Podcasts, etc

### Vue Dev Tools
* great help for Vue apps, UI, data, state, etc

