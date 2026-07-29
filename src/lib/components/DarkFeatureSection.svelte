<script lang="ts">
	import FeatureRow from './FeatureRow.svelte';
</script>

<section class="bg-[#050505] py-32 px-6">
	<div class="max-w-7xl mx-auto">
		<div class="mb-32 max-w-4xl">
			<h2 class="font-serif-display text-4xl md:text-6xl text-white leading-tight mb-8">
				One advisory platform built to move your transaction forward. <span class="text-gray-500">Navigate every stage of your exit with purpose-built expertise.</span>
			</h2>
		</div>

		<div class="space-y-32">
			<FeatureRow 
				title="Deal Origination" 
				description="Identify the right buyers from our global network of institutional and strategic capital providers."
				imagePosition="right"
				imageType="assistant"
			/>
			<FeatureRow 
				title="Mandate Management" 
				description="Securely manage confidential mandates, key documents, and deal timelines in one place."
				imagePosition="left"
				imageType="vault"
			/>
			<FeatureRow 
				title="Transaction Workflows" 
				description="Run proven M&A processes or tailor them to your sector, deal size, and exit goals."
				imagePosition="right"
				imageType="workflows"
			/>
			<FeatureRow 
				title="Sector Intelligence" 
				description="Leverage deep sector knowledge to benchmark valuations, assess buyers, and sharpen your positioning."
				imagePosition="left"
				imageType="knowledge"
			/>
			<FeatureRow 
				title="Network" 
				description="Tap into Mariana Research's global reach of capital providers wherever your deal takes you."
				imagePosition="right"
				imageType="ecosystem"
			/>
		</div>
	</div>
</section>
