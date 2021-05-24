<template>
  <nav>
    <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
      <div class="relative flex items-center justify-between h-24">
        <div class="flex-shrink-0 flex items-center">
          <img
            class="d-inline h-8 w-auto"
            src="https://tailwindui.com/img/logos/workflow-mark-indigo-500.svg"
            alt="Workflow"
          />
          <span class="pl-2 text-xl font-bold">logoipsum•</span>
        </div>
        <div class="hidden sm:block sm:ml-6">
          <div class="flex space-x-4">
            <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
            <a
              href="#"
              class="bg-gray-900 text-white px-3 py-2 rounded-md text-sm font-medium"
              aria-current="page"
              >Dashboard</a
            >

            <a
              href="#"
              class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium"
              >Team</a
            >

            <a
              href="#"
              class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium"
              >Projects</a
            >

            <a
              href="#"
              class="text-gray-300 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium"
              >Calendar</a
            >
          </div>
        </div>
        <div
          class="rounded-md bg-red-400 px-3 py-2 cursor-pointer font-semibold	 text-white"
        >
          Get Started
        </div>
      </div>
    </div>
  </nav>
</template>
<script type="text/javascript">
export default {};
</script>
