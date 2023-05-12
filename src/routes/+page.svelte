<script>
	import compressed1 from '$lib/images/compressed1.png';
	import compressed2 from '$lib/images/compressed2.png';
	import graduation from '$lib/images/graduation2.png';
	import abroad from '$lib/images/knowledge1.png';
	import logo from '$lib/images/logo.png';
	import school from '$lib/images/school1.png';
	import cover from '$lib/images/cover.png';
    import Icon from '@iconify/svelte';
</script>

<div>
	<div
		class="bg-cover pb-24"
		style="background-image: url('{cover}') "
	>
		<div class="pl-16 pt-8">
			<img class="w-20" src={logo} alt="" />
		</div>
		<h1 class="font-medium lg:text-[61px] pl-16 pt-4 text-[20px]">STUDENT RESOURCE PORTAL</h1>

        <div class="lg:w-[43%] w-8/12 lg:h-[370px] h-[482px] ml-16 mt-12 shadow-lg bg-gradient-to-t from-[#CE99919C] to-[#D9D9D9] rounded-lg">
            <div class="grid grid-cols-2 gap-9 pt-8 ml-8 mr-8 mb-[20px]">
                <div class="bg-gradient-to-l from-[#D9D9D9] to-[#CE99919C] rounded-md  text-center py-2 font-medium  shadow-xl">
                    <h1>Updates</h1>
                </div>
                <div class="bg-gradient-to-l from-[#D9D9D987] to-[#FBFAF5C2] rounded-md   text-center py-2 font-medium  shadow-xl">
                    <h1>Grants</h1>
                </div>
            </div>

            <div class="ml-8 mr-8 py-3 pl-4 mb-[20px] bg-[#FBFAF5] rounded-xl">
				University A open for admission
			</div>
			<div class="ml-8 mr-8 py-3 pl-4 mb-[20px] bg-[#FBFAF5] rounded-xl">
				Dhaka University Circular Out
			</div>
			<div class="ml-8 mr-8 py-3 pl-4 mb-[20px] bg-[#FBFAF5] rounded-xl">
				University B arranges career fair
			</div>
			<div class="ml-8 mr-8 py-3 pl-4 bg-[#FBFAF5] rounded-xl">
				University A open for admission
			</div>
            <Icon icon="material-symbols:keyboard-arrow-down" width="30" height="30" class="lg:ml-[50%] ml-32"/>
        </div>
	</div>

	<div class="bg-[#D9D9D9] mt-[25px] ml-[65px] mb-[25px] mr-[65px]">
		<h1 class="font-semibold lg:text-[42px] text-[30px] text-center py-7">Ad</h1>
	</div>

	<div class="bg-[#EDD7CF] mt-[25px] ml-[65px] mb-[15px] mr-[65px] rounded-lg">
		<h1 class="text-center font-semibold lg:text-[42px] text-[20px] pt-5 pb-10">What are you preparing for?</h1>
		<div class="grid lg:grid-cols-3 grid-cols-1 gap-4 justify-items-center pb-[35px]">
			<div>
				<img class="w-[85px]" src={school} alt="" />
				<h1 class="text-center font-medium">High School</h1>
			</div>
			<div>
				<img class="w-[85px]" src={abroad} alt="" />
				<h1 class="text-center font-medium">Study Abroad</h1>
			</div>
			<div>
				<img class="w-[85px]" src={graduation} alt="" />
				<h1 class="text-center font-medium">University</h1>
			</div>
		</div>
	</div>

	<div class="grid grid-cols-1 lg:grid-cols-3 gap-4 ml-[65px] mb-[25px] mr-[65px]">
		<div class="bg-[#EDD7CF] col-span-2 rounded-lg">
			<h1 class="lg:font-semibold lg:text-[30px] pt-5 pl-6 pb-5">Latest Reads</h1>

			<div class="bg-[#FBFAF5] ml-6 mb-5 mr-6 rounded-lg flex flex-row">
				<img class="w-[150px] p-2" src={compressed1} alt="" />
				<h1 class="pt-6 font-medium">Most Popular Olympiads in Bangladesh</h1>
			</div>
			<div class="bg-[#FBFAF5] ml-6 mb-5 mr-6 rounded-lg flex flex-row">
				<img class="w-[150px] p-2" src={compressed2} alt="" />
				<h1 class="pt-6 font-medium">
					President asks UGC to hold single admission test at all public universities for 2023-24
					session
				</h1>
			</div>
            <Icon icon="material-symbols:keyboard-arrow-down" width="30" height="30" class="lg:ml-[50%] ml-32"/>
		</div>
		<div class="bg-[#EDD7CF] rounded-lg">
			<h1 class="font-bold text-[25px] text-center pt-5">Free Mock Test</h1>
			<p class="font-light text-[15px] text-center pb-4">powered by StudyAbroadSponsor</p>

			<div>
				<div class="bg-gradient-to-l from-[#D9D9D987] to-[#FBFAF5C2] rounded-md ml-4 mr-4 text-center py-2 font-extrabold mb-4 shadow-xl">IELTS</div>

				<div class="bg-gradient-to-l from-[#D9D9D987] to-[#FBFAF5C2] rounded-md ml-4 mr-4 text-center py-2 font-extrabold mb-4 shadow-xl">Admission</div>

				<div class="bg-gradient-to-l from-[#D9D9D987] to-[#FBFAF5C2] rounded-md ml-4 mr-4 text-center py-2 font-extrabold mb-4 shadow-xl">SAT</div>

				<div class="bg-gradient-to-l from-[#D9D9D987] to-[#FBFAF5C2] rounded-md ml-4 mr-4 text-center py-2 font-extrabold mb-4 shadow-xl">Vocabulary</div>
			</div>
		</div>
	</div>
</div>
