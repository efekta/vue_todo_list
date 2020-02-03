<template>
    <div>
        <h1>Список групп</h1>
        <AddGroup></AddGroup>
    </div>
</template>

<script>
    import AddGroup from './AddGroup'

    export default {
        name: 'GroupList',
        component: {
            AddGroup
        }
    }
</script>