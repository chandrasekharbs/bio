<script lang="ts">
	import { Button, Card } from 'flowbite-svelte';
	import {
		GithubSolid,
		LinkedinSolid,
		CodeSolid,
		AnnotationSolid,
		BookSolid,
		PhoneSolid,
		MessageCaptionSolid,
		MapPinAltSolid
	} from 'flowbite-svelte-icons';
</script>

<div class="grid grid-cols-12">
	<!-- left section -->
	<main class="p-2 col-span-12 md:col-span-9">
		<div class="grid grid-flow-row grid-cols-12 gap-3">
			<Card class="col-span-12 max-w-max">
				<figure>
					<figcaption class="flex items-center space-x-3">
						<AnnotationSolid size="lg" />
						<p class="text-xl text-black font-bold">About</p>
					</figcaption>
					<br />
				</figure>
				<div class="font-normal text-gray leading-tight">
					Web Application Developer having proficient experience in designing, modifying and
					maintaining database driven web applications using C# and ASP.NET MVC technology, and also
					support and modernize web applications to SPA using ASP.NET MVC Web API & Angular.
					<ol type="1">
						<li>Total 12+ years of experience in building web applications.</li>
						<li>6+ years of experience in building web applications using ASP.NET MVC.</li>
						<li>1+ years of experience in Angular & Web API.</li>
						<li>Supported deployed systems by analyzing and fixing software related issues.</li>
						<li>
							Good communication skills, ability to interact with internal & external clients.
						</li>
						<li>Have experience in managing a team.</li>
						<li>Self-motivated and a quick learner.</li>
					</ol>
				</div>
			</Card>
			<Card class="col-span-12 max-w-max">
				<figure>
					<figcaption class="flex items-center space-x-3">
						<BookSolid size="lg" />
						<p class="text-xl text-black font-bold">Education</p>
					</figcaption>
					<br />
				</figure>
				<p class="font-bold text-black">Swami Vivekananda Institute of Technology</p>
				<p class="font-normal text-gray">
					Bachelor of Engineering (B.Tech) in Electrical, Electronics and Communications Engineering
				</p>
				<p class="italic text-sm">2006-2010</p>
			</Card>
			<Card class="col-span-12 max-w-max">
				<figure>
					<figcaption class="flex items-center space-x-3">
						<CodeSolid size="lg" />
						<p class="text-xl text-black font-bold">Experience</p>
					</figcaption>
					<br />
				</figure>
				<p class="font-normal text-gray-700 leading-tight">
					Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse
					chronological order.
				</p>
			</Card>
		</div>
	</main>
	<!-- right section -->
	<aside class="place-self-center col-span-12 md:place-self-end md:col-span-3 md:sticky md:top-20">
		<Card class="shadow-xl rounded-2xl shadow-blue-500">
			<div class="grid grid-flow-row grid-rows-1 grid-cols-12 gap-1">
				<div class="col-span-12 place-self-center">
					<img class="rounded-full" src="profile.jpg" alt="" height="250" width="250" />
				</div>
				<div class="col-span-12">
					<div class="grid grid-flow-row grid-rows-1 grid-cols-1 gap-4">
						<div class="self-end">
							<div class="text-xl">Hello, I'm</div>
							<div class="text-4xl text-black font-bold">Chandra Sekhar</div>
							<div class="text-2xl text-gray-400 font-semibold">Full Stack Developer</div>
							<br />
							<figure>
								<figcaption class="flex items-center space-x-1">
									<MessageCaptionSolid size="sm" />
									<a href="mailto:sekharchandrabs@gmail.com">sekharchandrabs@gmail.com</a>
								</figcaption>
							</figure>
							<figure>
								<figcaption class="flex items-center space-x-1">
									<PhoneSolid size="sm" />
									<a href="call:+14379890486">+1 (437) 989-0486</a>
								</figcaption>
							</figure>
							<figure>
								<figcaption class="flex items-center space-x-1">
									<MapPinAltSolid size="sm" />
									<p>Mississauga, Ontario, Canada</p>
								</figcaption>
							</figure>
						</div>
						<div class="place-self-center">
							<Button pill color="dark">Download Resume</Button>
						</div>
						<div class="justify-self-center">
							<div class="flex flex-wrap gap-4">
								<GithubSolid class="text-black" size="lg" role="button" />
								<LinkedinSolid class="text-blue-700" size="lg" role="button" />
							</div>
						</div>
					</div>
				</div>
			</div>
		</Card>
	</aside>
</div>
