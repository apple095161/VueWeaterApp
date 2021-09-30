<template>
  <div class="home">Weater</div>
</template>

<script>
import { ref, reactive, onMounted } from "vue";
export default {
  name: "Home",
  setup() {
    const array = ref([0, 1, 2, 3, 4]);
    const array2 = reactive({});
    onMounted(() => {
      console.log("123");
    });
    // onMounted(() => {
    //   array.value.forEach((item) => {
    //     console.log(item);
    //   });
    // });
    return {
      array,
      array2,
    };
  },
};
</script>
