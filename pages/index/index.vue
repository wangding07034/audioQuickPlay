<template>
	<view class="content">
		<audioQuickPlay url="https://media.lycheer.net/lecture/90258602/5e32624d521b272b49b1ff61_transcoded.m4a?0.1"></audioQuickPlay>
	</view>
</template>

<script>
	import audioQuickPlay from '@/components/wangding-audioQuickPlay/index.vue'
	export default {
		components: { audioQuickPlay },
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
