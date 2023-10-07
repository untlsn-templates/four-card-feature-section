<script>
  import 'untcss-reset';
</script>


<template>
  <main class="bg-[#FAFAFA] min-h-screen flex-(~ col) justify-evenly gap-8 p-8">
    <div class="mx-auto max-w-120 space-y-2">
      <h1 class="text-4xl text-center text-gray-600 font-200">Reliable, efficient delivery</h1>
      <h2 class="text-4xl text-center">Powered by Technology</h2>
      <p class="text-center text-gray-600">
        Our Artificial Intelligence powered tools use millions of project data points
        to ensure that your project is successful
      </p>
    </div>

    <div class="grid lg:grid-(cols-2 rows-4) xl:grid-cols-3 gap-4 max-w-400 mx-auto">
      <ArticleBlock
          src="/images/icon-supervisor.svg"
          class="xl:row-start-2"
          color="#43D3D2"
          title="Supervisor"
      >
        Monitors activity to identify project roadblocks
      </ArticleBlock>
      <ArticleBlock
          src="/images/icon-team-builder.svg"
          class="xl:row-start-1"
          color="#E49F9F"
          title="Team Builder"
      >
        Scans our talent network to create the optimal team for your project
      </ArticleBlock>
      <ArticleBlock
          src="/images/icon-karma.svg"
          class="xl:row-start-3"
          color="#FCAE4A"
          title="Karma"
      >
        Regularly evaluates our talent to ensure quality
      </ArticleBlock>
      <ArticleBlock
          src="/images/icon-calculator.svg"
          class="xl:row-start-2"
          color="#569CF2"
          title="Calculator"
      >
        Uses data from past projects to provide better delivery estimates
      </ArticleBlock>
    </div>
  </main>
</template>
