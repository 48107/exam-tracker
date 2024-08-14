<div class="bg-slate-800 rounded-lg">
	<p class="text-3xl px-6 pt-4 text-center">Add an Exam</p>
	<form class="flex flex-row flex-center justify-center py-4 px-6">
		<div>
			<div class="basis-4 py-2">
				<label for="name">Exam Name:</label><input
					name="name"
					type="text"
					class="width-3rem bg-slate-700 border-slate-600 focus:outline-none focus:border-slate-400 border-2 focus:bg-slate-600 rounded-md px-2 ml-2"
				/>
			</div>
			<div class="basis-4 py-2">
				<label for="calcNoCalc">Exam Type (1/2):</label><input
					name="calcNoCalc"
					type="range"
					min="1"
					max="2"
					class="ml-2"
				/>
			</div>
			<div class="basis-4 py-2">
				<label for="hours">Hours:</label><input
					name="hours"
					type="number"
					min="1"
					max="4"
					class="width-3rem bg-slate-700 border-slate-600 focus:outline-none focus:border-slate-400 border-2 focus:bg-slate-600 rounded-md px-2 ml-2"
				/>
			</div>
			<div class="basis-4 py-2">
				<input
					name="sumbit"
					type="button"
					class="width-3rem bg-slate-700 border-slate-600 border-2 rounded-md px-2 ml-2"
                    value="Add Exam!"
				/>
			</div>
		</div>
	</form>
</div>
