<template>
  <div class="card">
      <Splitter style="height: 100vw;background: #c00808;">
          <SplitterPanel class="flex align-items-center justify-content-center" :size="20" :minSize="10"> Panel 1 </SplitterPanel>
          <SplitterPanel :size="80">
              <Splitter layout="vertical">
                  <SplitterPanel class="flex align-items-center justify-content-center" :size="15"> Panel 2 </SplitterPanel>
                  <SplitterPanel :size="85">
                      <Splitter>
                          <SplitterPanel class="flex align-items-center justify-content-center" :size="20"> Panel 3 </SplitterPanel>
                          <SplitterPanel class="flex align-items-center justify-content-center" :size="80"> Panel 4 </SplitterPanel>
                      </Splitter>
                  </SplitterPanel>
              </Splitter>
          </SplitterPanel>
      </Splitter>
  </div>
</template>
<script setup>
import Splitter from 'primevue/splitter';
import SplitterPanel from 'primevue/splitterpanel';
</script>

<style lang="scss" scoped>

</style>