<template>
  <Layout>
    <h1>About us</h1>
        <div class="inner">
            <span>i</span>
            <h1>Hey</h1>
            <p>This is an informative card that will tell you something that's... well, important!</p> <p>This is an informative card that will tell you something that's... well, important!</p> <p>This is an informative card that will tell you something that's... well, important!</p> <p>This is an informative card that will tell you something that's... well, important!</p>
        
    </div>  
    
    </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'About us'
  }
}
</script>

<style scoped>
.inner {
    background: rgb(9, 201, 153);
    padding: 1em;
    border-radius: 10px;
    width: 250px;
    clip-path: circle(8% at 90% 29px);
    transition: all .5s ease-in-out;
    cursor: pointer;
}
    .inner:hover {
        clip-path: circle(75%);
        background: #00B6FF;
    }

   .inner h1 {
        color: white;
        margin: 0;
    }

   .inner p {
        color: white;
        font-size: .8rem;
    }
    .inner span {
        float: right;
        color: white;
        font-weight: bold;
        transition: color .5s;
        position: relative;
        margin-right: 4%;
    }
    .inner:hover span {
        color: rgba(255,255,255,0)
    }

</style>