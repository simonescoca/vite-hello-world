<script>
	export default {
		data () {
			return {
				jumboText: "JUMBO"
			}
		}
	}
</script>

<template>
    <div class="jumbo">
        <p>
            {{jumboText}}
        </p>
    </div>
</template>

<style scoped>
    .jumbo {
        width: 500px;
        height: 300px;
        background-color: rgb(0, 153, 255);
        border-radius: 15px;
        display: flex;
    }

    p {
        margin: auto;
        color: white;
        font-size: 2.5rem;
    }
</style>