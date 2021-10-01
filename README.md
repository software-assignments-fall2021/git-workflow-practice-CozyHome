
<h1> Functional Programming vs. OOP </h1>

- [Article Link](#article-link)
- [Comments - Anastasia](#comments---anastasia)

## Article Link
<p> https://web.archive.org/web/20130819160454/http://www.altdevblogaday.com/2012/04/26/functional-programming-in-c/ </p>

<p>
	If you're familiar with anything related to realtime computer graphics, John Carmack is a name that you may have heard. Without him and Michael Abrash, I don't believe realtime GFX would be as developed as it is today. computer nerds like myself have this unhealthy habit of worshipping id Software and its early developers. John Carmack is primarily the one who lead the charge in realtime computer graphics during the mid to late nineties with games like Doom and Quake pushing the limits of even the most efficient processors at the time.
</p>

<p>
	So, why is this article important to me? Well, let's get something out of the way. I fucking hate the Object Oriented Paradigm. Sure, it may have its benefits, but it completely hinders scalability when you have inheritance trees the size of the fucking empire state building. I much prefer a Component based design system mixed with Functional approaches. One reason I prefer this paradigm is simple: Functional programming seeks to treat objects more as bundles of data that are acted upon by a third party. This third party can be a static function if desired, or a 'Manager' object that can treat these bundles of data differently depending on the context/design required. I appreciate Carmack's wisdom in saying that you don't need to adhere completely to 'true' functional design. He covers the concept of the 'Pure Function.' Such that the function only has the ability to operate on the data that it can see is passed into it. By doing this, you completely eliminate hidden state in your execution! Goodbye global state you waste of fucking time! As well as this, unit testing works completely out of the box! Just pass your data in and see its results. You don't need to replicate anything outside of that execution. It's somewhat comparable to atomic operations in that sense, and it makes OOP much easier to work with. I've been programming under this paradigm for such a long time, and inheritance chains are so disgustingly frustrating to deal with. This is why I love C# and C++. I can either use delegates or func pointers to get the same functionality v-tables are replicating.  
</p>

<p>
	Side note: I'm reading this back and god damn I sound like Casey Muratori with the levels of salt in this text. Sorry if this is overly aggressive, this is just years of anger built up. Don't let it get this bad! 
</p>

<p>
	I guess I'm just frustrated with OOP, and this allowed me to just vent. I feel that OOP allows a programmer to develop state and execution pretty quickly. It makes the case for quantity over quality. This should never be okay! The problem is, these implementations don't scale very well when large amounts of state and interaction occur. I've felt the nightmare of spaghetti code in both personal and corporate codebases. It is not fun. This needs to change. Stop programming like an idiot. Think before you code! 
</p>

<h2> -Daniel James Cucuzza </h2>
<br/>

## Comments - Anastasia
Having a Computer Graphics course this semester as well as a minor in Game Design, I feel like I definitely should read this article. Although unexpectedly, the article is not talking about either CG or games, it is still interesting to read. I enjoy reading the insights that the arthor shared about pure functions and OOP. And the comments in README are thorough and insightful. Good job Daniel!



