<template>
    <div class="index">
        <RoadMap></RoadMap>
        <Announcement></Announcement>
        <NavigatorBar></NavigatorBar>
        <GoodList></GoodList>
    </div>
</template>

<script>
    import RoadMap from './roadMap.vue';
    import NavigatorBar from './navigatorBar.vue';
    import GoodList from './goodList.vue';
    import Announcement from './announcement.vue';

    export default {
        name: 'index',
        components: {
            RoadMap,
            NavigatorBar,
            GoodList,
            Announcement,
        },
    };
</script>

<style lang="scss">
    .index {
        width: 100%;
        height: 100%;
        overflow-y: scroll;
        background-color: #f1f1f1;
    }
</style>