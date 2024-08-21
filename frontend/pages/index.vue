<template>
  <div class="flex flex-col items-center">
    <div class="w-full h-28 flex items-center justify-center border-b shadow-md gap-3">
      <font-awesome :icon="['fas', 'bolt']" class="size-12 text-sky-400" />
      <h1 class="text-6xl font-bold tracking-wide text-neutral-700">Chat rooms</h1>
    </div>
    
    <div class="grid grid-cols-4 gap-6 p-16">
      <Chat title="Epic chat" description="Interesting stuff here" />
      <Chat title="good chat" description="some good stuff!" />
      <Chat title="Educational chat" description="Learn here" />
      <Chat title="Spam spam spam" description="spam spam spam" />
      <Chat title="Intellectual chat" description="pretentious stuff here!" />
      <Chat title="bad chat" description="don't join" />
      <Chat title="Sports" description="self-explanatory" />
      <Chat title="good chat" description="some good stuff!" />
      <Chat title="good chat" description="some good stuff!" />
      <Chat title="good chat" description="some good stuff!" />
      <Chat title="good chat" description="some good stuff!" />
      <Chat title="good chat" description="some good stuff!" />
      <Chat title="good chat" description="some good stuff!" />
    </div>
    
  </div>
</template>
