<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Drive more. Spend less."
	subtitle="Electric vehicles built to cut operating costs."
	imageSrc="/generated/image-a-fleet-operations-manager-standing-conf.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://logo.clearbit.com/fedex.com',
		'https://logo.clearbit.com/ups.com',
		'https://logo.clearbit.com/dhl.com',
		'https://logo.clearbit.com/amazon.com'
	]}
/>

<Summary
	title="What we do"
	text="Planetelectric delivers 70% lighter electric commercial vehicles with 47% lower total cost of ownership through proprietary aerospace-grade composite materials. Our lightweight technology dramatically reduces battery requirements and operating expenses for logistics fleets."
/>

<Testimonials
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image:
				"https://images.unsplash.com/photo-1571513722275-4b41940f54b8?q=80&w=3687&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image:
				"https://images.unsplash.com/photo-1600603405959-6d623e92445c?q=80&w=3687&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image:
				"https://images.unsplash.com/photo-1531123897727-8f129e1688ce?q=80&w=3687&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
		}
	]}
/>

<Features
	title="Why Planetelectric leads the market"
	subtitle="Breakthrough technology that delivers real results"
	features={[
		{
			title: "70% lighter vehicles",
			description:
				"Proprietary multi-material composite structures reduce vehicle weight by 70%, dramatically cutting battery requirements and operating costs."
		},
		{
			title: "47% lower total cost of ownership",
			description:
				"Advanced lightweighting technology delivers guaranteed 47% lower TCO compared to traditional electric commercial vehicles."
		},
		{
			title: "Aerospace-grade materials",
			description:
				"ISRO-proven composite expertise brings space-grade engineering to commercial vehicles with unmatched durability and performance."
		},
		{
			title: "Pre-certified systems",
			description:
				"All sub-systems undergo EMI/EMC certification before integration, ensuring reliable operation and faster deployment."
		},
		{
			title: "Real-time fleet intelligence",
			description:
				"Advanced telematics provide real-time range monitoring, remote diagnostics, and predictive health analytics for optimal fleet management."
		},
		{
			title: "Scalable architecture",
			description:
				"Modular design supports 4X load capacity with flexible powertrain options, growing with your business needs."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
