<template>
<ul></ul>

</template>

<script>
export default {
    data(){
        return {
            storedResourses:[
                {id : 'official-guide', title :'Official Guide', description : 'The Official Vue.js documentation.',
                link: 'https://vuejs.org'
                },
                 {id : 'google', title :'Google', description : 'Learn To Google..',
                link: 'https://google.org'
                },
                
            ]
        };
    }
}
</script>