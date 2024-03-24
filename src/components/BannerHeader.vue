<template>
    <div class="relative isolate overflow-hidden bg-gray-900 py-24 sm:py-32">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div class=" flex justify-center">
          <div>
            <h2 class="text-4xl font-bold tracking-tight text-white sm:text-6xl">Iván Cuadrado</h2>
            <h4 class="mt-6 text-4xl leading-8 text-gray-300">{{ titleCareer }}</h4>
          </div>     
        </div>
        <div class="mx-auto mt-10 max-w-2xl lg:mx-0 lg:max-w-none">
          <dl class="mt-16 grid grid-cols-1 gap-8 sm:mt-20 sm:grid-cols-2 lg:grid-cols-4">
            <div v-for="skill in skills" :key="skill.name" class="flex flex-col">
              <dd class="text-xl font-bold leading-9 tracking-tight text-white"> {{ skill.name }}  <font-awesome-icon :icon="['fab', skill.icon]" /></dd>
              <dt class="text-base leading-7 text-gray-300">{{ skill.experience }} years  </dt>
            </div>
          </dl>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  const skills = [
    { name: 'Javascript', icon: 'js', experience: 5 },
    { name: 'Typescript', icon: 'ts', experience: 2 },
    { name: 'React', icon: 'react', experience: 2 },
    { name: 'Vue', icon: 'vuejs', experience: 4 },
    { name: 'Angular', icon: 'angular', experience: 1 },
    { name: 'Git', icon: 'git', experience: 5 },
    { name: 'Gitlab', icon: 'gitlab', experience: 3 },
    { name: 'Node', icon: 'node', experience: 3 },
    
    
    // { name: 'Projects', value: '7' },
    // { name: 'Hours per week', value: '40' },
    // { name: 'Paid time off', value: 'Unlimited' },
  ]

  const titleCareer = '< Software Developer />'
  </script>