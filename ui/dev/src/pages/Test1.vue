<template>
  <q-page padding class="q-pa-md q-gutter-sm">
    <div style="max-width: 400px;">
      Basic
      <q-sliding-btn-group
        v-model="model"
        unelevated
      >
        <q-sliding-btn
          name="1"
          icon="bookmark"
          label="Bookmark"
          text-color="teal-8"
        />
        <q-sliding-btn
          name="2"
          icon="event"
          label="Calendar"
          text-color="blue-grey-8"
        />
        <q-sliding-btn
          name="3"
          icon="alarm"
          label="Alarm"
          text-color="orange-8"
        />
        <q-sliding-btn
          name="4"
          icon="directions"
          label="Directions"
        />
      </q-sliding-btn-group>
    </div>

    <div style="max-width: 400px;">
      Outline
      <q-sliding-btn-group
        v-model="model"
        outline
        unelevated
      >
        <q-sliding-btn
          name="1"
          icon="bookmark"
          label="Bookmark"
          text-color="teal-8"
        />
        <q-sliding-btn
          name="2"
          icon="event"
          label="Calendar"
          text-color="blue-grey-8"
        />
        <q-sliding-btn
          name="3"
          icon="alarm"
          label="Alarm"
          text-color="orange-8"
        />
        <q-sliding-btn
          name="4"
          icon="directions"
          label="Directions"
        />
      </q-sliding-btn-group>
    </div>

    <div style="max-width: 400px;">
      Push
      <q-sliding-btn-group
        v-model="model"
        push
        unelevated
      >
        <q-sliding-btn
          name="1"
          icon="bookmark"
          label="Bookmark"
          text-color="teal-8"
        />
        <q-sliding-btn
          name="2"
          icon="event"
          label="Calendar"
          text-color="blue-grey-8"
        />
        <q-sliding-btn
          name="3"
          icon="alarm"
          label="Alarm"
          text-color="orange-8"
        />
        <q-sliding-btn
          name="4"
          icon="directions"
          label="Directions"
        />
      </q-sliding-btn-group>
    </div>

    <div style="max-width: 400px;">
      Flat
      <q-sliding-btn-group
        v-model="model"
        flat
        unelevated
      >
        <q-sliding-btn
          name="1"
          icon="bookmark"
          label="Bookmark"
          text-color="teal-8"
        />
        <q-sliding-btn
          name="2"
          icon="event"
          label="Calendar"
          text-color="blue-grey-8"
        />
        <q-sliding-btn
          name="3"
          icon="alarm"
          label="Alarm"
          text-color="orange-8"
        />
        <q-sliding-btn
          name="4"
          icon="directions"
          label="Directions"
        />
      </q-sliding-btn-group>
    </div>

    <div style="max-width: 400px;">
      Glossy
      <q-sliding-btn-group
        v-model="model"
        glossy
        unelevated
      >
        <q-sliding-btn
          name="1"
          icon="bookmark"
          label="Bookmark"
          color="teal-8"
        />
        <q-sliding-btn
          name="2"
          icon="event"
          label="Calendar"
          color="blue-grey-8"
        />
        <q-sliding-btn
          name="3"
          icon="alarm"
          label="Alarm"
          color="orange-8"
        />
        <q-sliding-btn
          name="4"
          icon="directions"
          label="Directions"
          color="black"
        />
      </q-sliding-btn-group>
    </div>

    <div style="max-width: 400px;">
      Square
      <q-sliding-btn-group
        v-model="model"
        square
        unelevated
      >
        <q-sliding-btn
          name="1"
          icon="bookmark"
          label="Bookmark"
          text-color="teal-8"
        />
        <q-sliding-btn
          name="2"
          icon="event"
          label="Calendar"
          text-color="blue-grey-8"
        />
        <q-sliding-btn
          name="3"
          icon="alarm"
          label="Alarm"
          text-color="orange-8"
        />
        <q-sliding-btn
          name="4"
          icon="directions"
          label="Directions"
        />
      </q-sliding-btn-group>
    </div>

    <div style="max-width: 400px;">
      Padding
      <q-sliding-btn-group
        v-model="model"
        padding="2px"
        unelevated
      >
        <q-sliding-btn
          name="1"
          icon="bookmark"
          label="Bookmark"
          text-color="teal-8"
        />
        <q-sliding-btn
          name="2"
          icon="event"
          label="Calendar"
          text-color="blue-grey-8"
        />
        <q-sliding-btn
          name="3"
          icon="alarm"
          label="Alarm"
          text-color="orange-8"
        />
        <q-sliding-btn
          name="4"
          icon="directions"
          label="Directions"
        />
      </q-sliding-btn-group>
    </div>

    <div style="max-width: 400px;">
      Disabled
      <q-sliding-btn-group
        v-model="model"
        unelevated
      >
        <q-sliding-btn
          name="1"
          icon="bookmark"
          label="Bookmark"
          text-color="teal-8"
          disable
        />
        <q-sliding-btn
          name="2"
          icon="event"
          label="Calendar"
          text-color="blue-grey-8"
          disable
        />
        <q-sliding-btn
          name="3"
          icon="alarm"
          label="Alarm"
          text-color="orange-8"
        />
        <q-sliding-btn
          name="4"
          icon="directions"
          label="Directions"
        />
      </q-sliding-btn-group>
    </div>

    <div style="max-width: 400px;">
      Justify Between
      <q-sliding-btn-group
        v-model="model"
        flat
        unelevated
        class="justify-between align-items"
      >
        <q-sliding-btn
          name="1"
          icon="bookmark"
          label="Bookmark"
          text-color="teal-8"
        />
        <q-sliding-btn
          name="2"
          icon="event"
          label="Calendar"
          text-color="blue-grey-8"
        />
        <q-sliding-btn
          name="3"
          icon="alarm"
          label="Alarm"
          text-color="orange-8"
        />
        <q-sliding-btn
          name="4"
          icon="directions"
          label="Directions"
        />
      </q-sliding-btn-group>
    </div>

    <div style="max-width: 400px;">
      Justify Evenly
      <q-sliding-btn-group
        v-model="model"
        flat
        unelevated
        class="justify-evenly align-items"
      >
        <q-sliding-btn
          name="1"
          icon="bookmark"
          label="Bookmark"
          text-color="teal-8"
        />
        <q-sliding-btn
          name="2"
          icon="event"
          label="Calendar"
          text-color="blue-grey-8"
        />
        <q-sliding-btn
          name="3"
          icon="alarm"
          label="Alarm"
          text-color="orange-8"
        />
        <q-sliding-btn
          name="4"
          icon="directions"
          label="Directions"
        />
      </q-sliding-btn-group>
    </div>

    <div style="max-width: 400px;">
      Justify Evenly w/Padding
      <q-sliding-btn-group
        v-model="model"
        flat
        unelevated
        padding="2px"
        class="justify-evenly align-items"
      >
        <q-sliding-btn
          name="1"
          icon="bookmark"
          label="Bookmark"
          text-color="teal-8"
        />
        <q-sliding-btn
          name="2"
          icon="event"
          label="Calendar"
          text-color="blue-grey-8"
        />
        <q-sliding-btn
          name="3"
          icon="alarm"
          label="Alarm"
          text-color="orange-8"
        />
        <q-sliding-btn
          name="4"
          icon="directions"
          label="Directions"
        />
      </q-sliding-btn-group>
    </div>

    <div style="max-width: 400px;">
      Multiple w/Justify Evenly + Padding
      <q-sliding-btn-group
        v-model="model"
        multiple
        flat
        unelevated
        padding="2px"
        class="justify-evenly align-items"
      >
        <q-sliding-btn
          name="1"
          icon="bookmark"
          label="Bookmark"
          text-color="teal-8"
        />
        <q-sliding-btn
          name="2"
          icon="event"
          label="Calendar"
          text-color="blue-grey-8"
        />
        <q-sliding-btn
          name="3"
          icon="alarm"
          label="Alarm"
          text-color="orange-8"
        />
        <q-sliding-btn
          name="4"
          icon="directions"
          label="Directions"
        />
      </q-sliding-btn-group>
    </div>

  </q-page>
</template>

<script>
export default {
  data () {
    return {
      model: '1'
    }
  },

  watch: {
    model (val) {
      console.log('model changed:', val)
    }
  }
}
</script>

<style lang="sass" scoped>
.directive-target
  width: 50px
  height: 50px
</style>
