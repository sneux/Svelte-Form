<script>
    import Card from './Card.svelte'
    export let item 
</script>

<Card>
    <div class="num-display">
        {item.rating}
    </div>
    <div class="close">X</div>
    <div class="text-display">
        {item.text}
    </div>
</Card>

<style>
    .num-display {
        position: absolute;
        top: -10px;
        left: -10px;
        width: 50px;
        height: 50px;
        background: #ff6a95;
        color: #fff;
        border: 1px #eee solid;
        border-radius: 50%;
        padding: 10px;
        text-align: center;
        font-size: 19px;
    }
</style>