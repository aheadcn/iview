<template>
    <ColorPicker v-model="color1" style="width: 100px;height: 50px;" :recommend="true" @on-active-change="test" @add-recomment-color="test" transfer/>
</template>
<script>
export default {
    methods:{
      test(val){
          // eslint-disable-next-line no-console
          console.log(val);
      }
    },
    data() {
        return {
            color1: '#19be6b',
            color2: ''
        };
    }
};
</script>
