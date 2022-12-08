<template>
  <div class="escaperoom-owner">
    <BreadCrumb />
    <section class="escaperoom-owner__headsection g-section--structure">
      <div class="headsection-main body-container">
				<div class="headsection-main__text">
					<h2>Unlock The Potential Of Your Escape Room Business Growth</h2>
					<p>Lorem Ipsum is simply dummy text of the text a Lorem Ipsum is simply dummy text.</p>
					<div class="btn">
						<button class="g--page-button">Partner Request Form <span class="material-symbols-outlined"> arrow_right_alt </span></button>
					</div>
				</div>
				<div class="headsection-main__image">
					<img src="@/assets/img/escaperoom__owners.jpg" alt="" />
				</div>
			</div>
    </section>
  </div>
</template>


<script>
import BreadCrumb from "@/components/BreadCrumb.vue";
import FrequentlyAskedQuestion from "@/components/FrequentlyAskedQuestion.vue";
export default {
	components: {
		BreadCrumb,
		FrequentlyAskedQuestion,
	},
};
</script>

<style lang="scss" src="@/assets/css/views/EscaperoomOwners.scss">

</style>