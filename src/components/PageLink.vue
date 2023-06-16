<template>
  <q-page
    class="pink"
    style="background-color: white; min-height: 600px; width: 90%"
  >
    <div class="container" style="background: white">
      <div class="row">
        <div class="col">
            <div class="text-h4 text-black" style="text-align: center">
                Unlock your Potential with our <br />
                Online Learning Platform
            </div>
            <div class="text-h6 text-black" style="text-align: center">
                Explore a world with Knowledge and Advance <br />
                Your Career from Anywhere, Anytime.
            </div>
            <div class="row">
                <div class="col" style="margin-top: 200px">
                    <q-btn size="22px" class="q-px-xl q-py-xs" color="blue" label="100+ courses"/>
                </div>
                <div class="col" style="margin-top: 200px">
                    <q-btn size="22px" class="q-px-xl q-py-xs" color="blue" label="100+ courses"/> />
                </div>
                <div class="col" style="margin-top: 200px">
                <q-btn size="22px" class="q-px-xl q-py-xs" color="blue" label="100+ courses"/> />
                </div>
            </div>
        </div>
        <div class="col">
          <div class="q-pa-xs" style="padding: 80px;">
            <q-video :ratio="16/9" src="https://www.youtube.com/embed/k3_tw44QsZQ?rel=0" />
          </div>
          <div class="text-h6 text-black" style="text-align: justify; margin-left: 70px">
                Lorem ipsum dolor sit amet et delectus <br> accommodare  his consul copiosae legendos at vix ad <br> putent delectus delicata usu. Vidit dissentiet eos
          </div>
          <div>
            <q-btn size="22px" class="q-px-xl q-py-xs" style="margin-left: 80px" color="blue" label="Get Subscribed"/>
          </div>
        </div>
      </div>
    </div>
  </q-page>
</template>
<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "PageLink",
});
</script>
