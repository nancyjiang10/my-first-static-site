<!--
  This is you page!
-->
<script>
  // Import all the news furniture components
  import ArticleHeader from '$lib/components/ArticleHeader.svelte';
  import ArticleBody from '$lib/components/ArticleBody.svelte';
  import ImageWithCaption from '$lib/components/ImageWithCaption.svelte';
  import RelatedLinks from '$lib/components/RelatedLinks.svelte';

  // Article metadata
  let headline = 'Mayor Adams Pushes ‘After-School for All’ Plan, but Providers Cite Budget Shortfalls';
  let byline = 'Nancy Jiang';
  let pubDate = '2026-02-09';

  // Related stories
  const relatedStories = [
    { headline: 'How America\'s top news organizations escape rigid publishing systems to design beautiful data-driven stories on deadline.', href: 'https://palewi.re/docs/coding-the-news/' },
    { headline: 'How to install, configure and use Visual Studio Code, GitHub and Copilot', href: 'https://palewi.re/docs/coding-the-news/scripts/week-1/' },
  ];
</script>

<!-- This sets the page title in the browser tab -->
<svelte:head>
  <title>{headline} | NYCity News Service</title>
  <meta name="description" content="At the Craig Newmark Graduate School of Journalism at the City University of New York, change is in our DNA. That comes of being born in 2006, as the digital revolution was transforming our profession in ways none of us could have imagined." />
</svelte:head>

<!-- Your page content goes here -->
<div class="container">
  
  <!-- Article Header: Headline, byline, and publication date -->
  <ArticleHeader
    {headline}
    {byline}
    {pubDate}
  />

  <!-- Lead Image: CUNY Journalism School building -->
  <ImageWithCaption
    src="/example-photo.gif"
    alt="The Craig Newmark Graduate School of Journalism is at 219 West 40th Street in Midtown Manhattan."
    caption="The Craig Newmark Graduate School of Journalism is at 219 West 40th Street in Midtown Manhattan."
    credit="Craig Newmark Graduate School of Journalism"
  />

  <!-- Article Body: The main story text with proper typography -->
  <ArticleBody>
    <p>
      This fall, Mayor Eric Adams unrolled an ambitious plan for “universal” after-school programs in public schools. But some providers say the plan has hit unexpected snags.  
    </p>

    <p>
       But the plan so far hasn’t fully delivered on budget pledges. And providers said it has also excluded some high-need schools, where students come from lower-income families, or have special education or physical needs. The plan is also facing implementation hurdles as providers follow new laws and rules while trying to meet increasing demand for safe and educational after-school options. </p>

<p>The Chinese-American Planning Council, one such program, launched new efforts at P.S. 255 and P.S. 160 in Brooklyn as part of Adams’ expansion. </p>

<p> After city inspections to advance the licensing process, Mary Cheng, director of childhood development services for the Council, said the program faced budget constraints due to classroom-size restrictions that require 35 square feet per child. Cheng said the organization now has to open more classrooms and hire more teachers to staff them – stretching the budget beyond what it has. </p>

<p>“I think the number they gave us is really with the idea in mind that you have 20 kids per classroom,” she said. </p>

<p>The increased space-per-child requirement came from a law passed in 2021 that was intended to reduce classroom size for early childhood programs. Cheng said after-school programs started implementing the law in 2024. </p>

<p>Cheng applied for additional funds for the Council, but it’s unclear whether the request will be approved. </p>
<p>“They only gave us $2,100 per child because it’s a shorter year, and we’re like, oh, this is not working right now. We’re nervous,” she said.</p>

<p>Previously, each classroom held up to 23 students in the Chinese-American Planning Council’s programs. With the new restrictions, their classrooms might hold around 14 students, requiring more money for hires and space — funds they don’t have.</p>

<p>The situation mirrors that of Grand Street Settlement, a nonprofit provider that opened five new after-school programs through Adams’ initiative, located from Chinatown through the Lower East Side.</p>

<p>Robert Cordero, the CEO of Grand Street, which has an annual budget of $60 million, said the nonprofit subsidizes every contract signed with the city, most by 15%. While Grand Street is never able to cover the costs of its youth development programs entirely with city funds, Cordero says the after-school contracts are worse, exacerbated by rising health insurance costs, rent, and utilities.</p>

<p>“I imagine smaller community-based organizations have to put it together with Scotch tape and Elmer’s glue,” he said.</p>
<p>“It’s a broken system.”</p>

 <iframe title="CPC New After-School Program Budget Gaps" aria-label="Grouped Bars" id="datawrapper-chart-kpDSx" src="https://datawrapper.dwcdn.net/kpDSx/5/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="260" data-external="1"></iframe><script type="text/javascript">window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r,i=0;r=e[i];i++)if(r.contentWindow===a.source){var d=a.data["datawrapper-height"][t]+"px";r.style.height=d}}});</script>

<p> A case study of two New York City schools by The Finance Project, a nonprofit research center, found that every dollar invested in school programs over three years produced a return on investment of “social value” between $10.30 and $14.80, with increases in academic scores, health areas, and parent engagement. </p>

<p>The Adams administration announced its program by citing an Oklahoma study that found after-school and crime prevention programs yield between $8 and $12 in savings for each dollar invested by increasing a child’s earning potential, improving their academic performance, and reducing crime and juvenile delinquency.</p>
<p> Cheng, however, said funding for the Chinese-American Planning Council has remained stagnant over the last decade, with the program having received the same amount since 2015. With rising inflation increasing the cost of goods and services, the budget has been increasingly thin year after year.</p>
<p> Adams said his expanded program and its additional funding would give “providers their first pay raise in 10 years.” But some providers said they’re concerned the boost won’t be enough to cover operating expenses amid rising costs. </p>
<p> In a regular school year, the Chinese-American Planning Council receives between $2,800 and $3,200 per child enrolled in its programs. Should the vendor’s additional funds be approved, it could receive boosts of up to $5,000 per child per year. The increase, however, may still not be enough to close the gap between labor costs and inflation, Cheng said. </p>
<p> “It’s still a very small fee. It’s hard because if you want good quality after-school teachers, you can’t build a workforce at minimum wage,” Cheng said. </p>
<p> The budget constraints have forced the Chinese-American Planning Council to delay hiring staff and increase job responsibilities for some administrative spots, Cheng said. The organization is running at a roughly $58,000 deficit to provide the full 120 seats at P.S. 255 and a $44,800 deficit at P.S. 160— an issue Cheng says other programs in the rollout may face. 

<p> “The vendors have to service the seats; we have to eat the costs,” Cheng said. </p>

<p> Vendors like the Chinese-American Planning Council are contractually bound to meet the After-School For All requirements, leaving those with limited funds in a Catch-22, Cheng said. </p>

<p> “If you don’t enroll all the kids, then you may not get your full enrollment amount. If you enroll all the kids, you go into the red. If we’re under-enrolled, the city goes ‘well, nobody’s using your services,’” Cheng said. </p>

<p> “It’s not the services that’s the problem, it’s the regulation constraints.” </p>

<p> In a statement to NYCity News Service, the Adams administration said schools were chosen based on “where the need was greatest.” </p>

<p> “That means continuing support for schools that already have programs in place and adding 115 more elementary schools where many families face economic challenges. The city used the NYC Public School Economic Need Index to identify these schools, along with other important factors — such as the number of students with disabilities, children living in temporary housing, and areas of the city that don’t have a DYCD or similar city-funded programs,” said a Department of Youth & Community Development spokesperson. </p>

<p> Cordero, however, challenged Adams’ assertion that the new after-school sites were chosen based on economic need and service gaps. He cited two high-needs schools, P.S. 158 in East New York, Brooklyn, and P.S. 1 Alfred E. Smith Elementary School on the Lower East Side, as examples. 
Despite efforts from elected officials, such as City Council member Chris Marte and Assembly member Grace Lee, who “tried everything in their power” to ensure the schools were on the eligibility list, they were passed over for new after-school programs, Cordero said. </p>

<p> For P.S. 1, which serves children from pre-K through fifth grade, 90% of the school’s population is low-income, with 30% in unstable housing and limited English proficiency, he said. For P.S. 158, “closer to 100%” of students live below the federal poverty level, according to Cordero. </p>

<p> “For some reason we cannot understand, [these schools] were left off the list. I’m not sure what the city’s defense of that would be,” Cordero said. </p>

<p> The city’s Department of Youth and Community Development didn’t respond to questions from NYCity News Service about funding specifics, but in a statement, said the agency was excited to add the 5,000 new seats to 40 new elementary school programs in September. 
NYCity News Service also reached out to the Office of Child and Family Services, which approves program licensing, but the agency declined to comment. </p>


  </ArticleBody>

  <!-- Related Stories: Links to other articles -->
  <RelatedLinks
    title="Related Stories"
    links={relatedStories}
  />

</div>

<style>
  /* Styles here only apply to this page */
  .container {
    padding: var(--spacing-lg) var(--spacing-md);
  }
</style>