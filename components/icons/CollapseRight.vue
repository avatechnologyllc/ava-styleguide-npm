<template>
  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="16" fill="none"><path d="M1.5 1.389v-.75a.75.75 0 0 0-.75.75h.75Zm17 0h.75a.75.75 0 0 0-.75-.75v.75Zm0 13.222v.75a.75.75 0 0 0 .75-.75h-.75Zm-17 0H.75c0 .414.336.75.75.75v-.75ZM3.653 7.25a.75.75 0 0 0 0 1.5v-1.5Zm6.659.75.46.592a.75.75 0 0 0 0-1.185l-.46.593ZM8.023 5.273a.75.75 0 1 0-.92 1.185l.92-1.185Zm-.92 4.269a.75.75 0 0 0 .92 1.185l-.92-1.185Zm6.49-8.153a.75.75 0 0 0-1.5 0h1.5Zm-1.5 13.222a.75.75 0 0 0 1.5 0h-1.5ZM1.5 2.139h17v-1.5h-17v1.5Zm16.25-.75V14.61h1.5V1.389h-1.5Zm.75 12.472h-17v1.5h17v-1.5Zm-16.25.75V1.389H.75V14.61h1.5ZM3.653 8.75h6.659v-1.5H3.653v1.5Zm3.45-2.292 2.749 2.134.92-1.185-2.749-2.134-.92 1.185Zm.92 4.269 2.749-2.135-.92-1.185-2.749 2.135.92 1.185Zm4.07-9.338V14.61h1.5V1.389h-1.5Z" :fill="fillColor"/></svg>
</template>
<script>
export default {
	props: {
		fillColor: {
			type: String,
			default: '#A7A9AC'
		},
		strokeColor: {
			type: String,
			default: '#fff'
		},
	}
}
</script>
