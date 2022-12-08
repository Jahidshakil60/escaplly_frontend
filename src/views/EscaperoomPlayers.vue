<template>
	<div class="escaperoom-player">
		<BreadCrumb />
		<section class="escaperoom-player__headersection g-section--structure">
			<div class="headsection-main body-container">
				<div class="headsection-main__text">
					<h2>Fun, Activities, Games, Escape The Real Life Through Fun!</h2>
					<p>Lorem Ipsum is simply dummy text of the text a Lorem Ipsum is simply dummy text.</p>
					<div class="btn">
						<button class="g--page-button">View All Escape Games <span class="material-symbols-outlined"> arrow_right_alt </span></button>
					</div>
				</div>
				<div class="headsection-main__image">
					<img src="@/assets/img/hero_escaperoom_players.jpg" alt="" />
				</div>
			</div>
		</section>
		<section class="escaperoom-player__escaplly-best g-section--structure">
			<div class="escaplly-best-main body-container">
				<div class="escaplly-best-wrapper">
					<div class="escaplly-best-wrapper__text">
						<h3>Why Escaplly Best For All Escape Room Players!</h3>
						<p>
							Lorem Ipsum is simply dummy text of the text a Lorem Ipsum is simply dummy text of the text a lpsum simply text for dummy only. simply
							dummy text of the text a lpsum simply text for dummy only. Lorem Ipsum is simply dummy text of the text a Lorem Ipsum is simply dummy
							text of the text a lpsum simply text for dummy only.
						</p>
						<div class="btn">
							<button class="g--page-button">View All Escape Games</button>
						</div>
					</div>
					<div class="escaplly-best-wrapper__items">
						<div class="item-popular item">
							<h6>Inlisted Most Popular Companies</h6>
							<p>To move forward and open certain doors or chests, you will need to find physical keys or digital.</p>
						</div>
						<div class="item-booking item">
							<h6>Easy Booking System</h6>
							<p>To move forward and open certain doors or chests, you will need to find physical keys or digital.</p>
						</div>
						<div class="item-coupon item">
							<h6>Deals And Coupon Code!</h6>
							<p>To move forward and open certain doors or chests, you will need to find physical keys or digital.</p>
						</div>
						<div class="item-review item">
							<h6>Most Advance Review System</h6>
							<p>To move forward and open certain doors or chests, you will need to find physical keys or digital.</p>
						</div>
					</div>
				</div>
				<div class="escaplly-main__details">
					<h3>
						We Are The Most Advanced And Leading Escape Room Directory. Every Day, Thousand Of Escape Room Enthusiasts Visit Our Website For Book
						Their Next Escape Room Experience. You are one of them!
					</h3>
					<div class="btn">
						<button class="g--page-button">View All Escape Games</button>
					</div>
				</div>
			</div>
		</section>
		<section class="escaplly-support-system g-section--structure">
			<div class="g--support-system__main body-container">
				<div class="g--support-system-text">
					<h3>We Have Support System For Escape Room Players.</h3>
					<p>
						Lorem Ipsum is simply dummy text of the text a Lorem Ipsum is simply dummy text of the text a lpsum simply text for dummy only. simply
						dummy text of the text a lpsum simply text for dummy only. Lorem Ipsum is simply dummy text of the text a Lorem Ipsum is simply dummy text
						of the text a lpsum simply text for dummy only. Lorem Ipsum is simply dummy text of the text a Lorem Ipsum is simply dummy text of the
						text.
					</p>
					<div class="btn">
						<button class="g--page-button">Contact Us</button>
					</div>
				</div>
				<div class="g--support-system-img">
					<img src="@/assets/img/support_system.jpg" alt="" />
				</div>
			</div>
		</section>
		<section class="escaplly-discount-facility g-section--structure">
			<div class="g--support-system__main special-discount__main body-container">
				<div class="g--support-system-img">
					<img src="@/assets/img/discount_facility.jpg" alt="" />
				</div>
				<div class="g--support-system-text">
					<h3>Special Discount Facility From Our Platform!</h3>
					<p>
						Lorem Ipsum is simply dummy text of the text a Lorem Ipsum is simply dummy text of the text a lpsum simply text for dummy only. simply
						dummy text of the text a lpsum simply text for dummy only. Lorem Ipsum is simply dummy text of the text a Lorem Ipsum is simply dummy text
						of the text a lpsum simply text for dummy only. Lorem Ipsum is simply dummy text of the text a Lorem Ipsum is simply dummy text of the
						text.
					</p>
					<div class="btn">
						<button class="g--page-button">View All Escape Companies</button>
					</div>
				</div>
			</div>
		</section>
		<section class="escapelly-frequently-asked g-section--structure">
			<FrequentlyAskedQuestion />
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

<style lang="scss" src="@/assets/css/views/EscaperoomPlayers.scss"></style>
