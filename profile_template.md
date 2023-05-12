
# Profile Templates (Markdown)

<br>

--------------

<h1 align="center">
  <!--<img src="xcbuild_logo.jpg" alt="Facebook xcbuild" />-->
  xcbuild
</h1>

https://github.com/facebookarchive/xcbuild

**xcbuild** is an Xcode-compatible build tool with the goal of providing faster builds, better documentation of the build process and running on multiple platforms (macOS, Linux, and Windows)

### Why xcbuild?

<table>
  <tr>
    <th colspan="2">Features</th>
    <th rowspan="10"></th>
    <th colspan="3">Performance</th>
  </tr>
  <tr><td>:rocket:</td><td>Blazing fast incremental builds</td><th rowspan="3"></th><th rowspan="3"><code>xcodebuild</code></th><th rowspan="3">xcbuild + Ninja</th></tr>
  <tr><td>:book:</td><td>Documents the Xcode build process</td></tr>
  <tr><td>:link:</td><td>Builds Xcode projects and workspaces</td></tr>
  <tr><td>:hatching_chick:</td><td>Supports Swift apps and frameworks</td><th rowspan="3">Clean Build</th><td rowspan="3">30.103s</td><td rowspan="3">25.122s</td></tr>
  <tr><td>:sparkles:</td><td>Tools and libraries for Xcode projects</td></tr>
  <tr><td>:gift_heart:</td><td>Fully compatible with <a href="https://github.com/supermarin/xcpretty">xcpretty</a></td></tr>
  <tr><td>:tophat:</td><td>Uses <a href="https://ninja-build.org/">Ninja</a> and <a href="https://github.com/apple/swift-llbuild">llbuild</a></td><th rowspan="3">Incremental Build</th><td rowspan="3">2.190s</td><td rowspan="3">0.046s :zap:</td></tr>
  <tr><td>:octocat:</td><td>Open source under the BSD license</td></tr>
  <tr><td>:penguin:</td><td>Builds on Linux and Windows</td></tr>
</table>

### xcbuild and other build tools

[xctool](https://github.com/facebook/xctool) | [Buck](https://github.com/facebook/buck) | [xcpretty](https://github.com/supermarin/xcpretty)
----|----|---
xcbuild and [xctool](https://github.com/facebook/xctool) are both Xcode-compatible build systems. We plan on slowly deprecating xctool's build support but keep it as a great way to run tests. | Facebook's main build system is [Buck](https://buckbuild.com). Buck has a stronger architecture and advanced features like artifact caching while having a much simpler build format. If you have a new project, it's highly recommended. | xcbuild works great with [xcpretty](https://github.com/supermarin/xcpretty). Pipe the output from xcbuild to xcpretty the same way as you would from `xcodebuild`.

-----------

<br>


<div align="center">
	<div>
		<sub>Check out my latest app</sub>
		<br>
		<h2>
			<a href="https://github.com/UFund-Me/Qbot">Qbot</a>
			<br><br>
			<sup>运行量化策略自动化完成股票和基金交易的机器人</sup>
		</h2>
	</div>
	<br>
	<br>
	<br>
	<br>
	<br>
	<br>
	<hr>
	<p>
		<p>
			<sup>
				<a href="https://github.com/sponsors/sindresorhus">My open source work is supported by the community</a>
			</sup>
		</p>
		<sup>Special thanks to:</sup>
		<br>
		<br>
		<a href="https://standardresume.co/tech">
			<img src="https://sindresorhus.com/assets/thanks/standard-resume-logo.svg" width="160"/>
		</a>
		<br>
		<br>
		<a href="https://retool.com/?utm_campaign=sindresorhus">
			<img src="https://sindresorhus.com/assets/thanks/retool-logo.svg" width="210"/>
		</a>
    <br>
		<br>
		<a href="https://github.com/UFund-Me/Qbot">
			<div>
				<img src="https://raw.githubusercontent.com/UFund-Me/UFund/main/img/UFund.png" width="120" alt="Qbot">
			</div>
			<b>AI autonomous trading bot</b>
			<div>
				<sub>AI-oriented quantitative investment platform, </sub>
				<br>
				<sup>which aims to realize the potential, empower AI technologies in quantitative investment.</sup>
			</div>
		</a>
		<br>
		<br>
		<a href="https://workos.com/?utm_campaign=github_repo&utm_medium=referral&utm_content=awesome&utm_source=github">
			<div>
				<img src="https://sindresorhus.com/assets/thanks/workos-logo-white-bg.svg" width="200" alt="WorkOS">
			</div>
			<b>Your app, enterprise-ready.</b>
			<div>
				<sub>Start selling to enterprise customers with just a few lines of code.</sub>
				<br>
				<sup>Add Single Sign-On (and more) in minutes instead of months.</sup>
			</div>
		</a>
		<br>
		<a href="https://strapi.io/?ref=sindresorhus">
			<div>
				<img src="https://sindresorhus.com/assets/thanks/strapi-logo-white-bg.png" width="200" alt="Strapi">
			</div>
			<b>Strapi is the leading open-source headless CMS.</b>
			<div>
				<sup>It’s 100% JavaScript, fully customizable, and developer-first.</sup>
			</div>
		</a>
		<br>
		<br>
		<a href="https://bit.io/?utm_campaign=github_repo&utm_medium=referral&utm_content=awesome&utm_source=github">
			<div>
				<img src="https://sindresorhus.com/assets/thanks/bitio-logo.svg" width="190" alt="bit.io">
			</div>
			<b>Instant, shareable cloud PostgreSQL database</b>
			<div>
				<sup>Import any dataset in seconds, share with anyone with a click, try without signing up</sup>
			</div>
		</a>
		<br>
		<br>
		<br>
		<a href="https://getstream.io/chat/sdk/ios/?utm_source=Github&utm_medium=Github_Repo_Content_Ad&utm_content=Developer&utm_campaign=Github_Jan2022_iOSChatSDK&utm_term=Sindresorhus#gh-light-mode-only">
			<div>
				<img src="https://sindresorhus.com/assets/thanks/stream-logo.svg" width="220" alt="Stream">
			</div>
			<br>
			<div>
				<b>Build Scalable Feeds & Chat Applications with Powerful APIs and Front End Components</b>
			</div>
		</a>
		<a href="https://getstream.io/chat/sdk/ios/?utm_source=Github&utm_medium=Github_Repo_Content_Ad&utm_content=Developer&utm_campaign=Github_Jan2022_iOSChatSDK&utm_term=Sindresorhus#gh-dark-mode-only">
			<div>
				<img src="https://sindresorhus.com/assets/thanks/stream-logo-dark.svg" width="220" alt="Stream">
			</div>
			<br>
			<div>
				<b>Build Scalable Feeds & Chat Applications with Powerful APIs and Front End Components</b>
			</div>
		</a>
		<br>
		<br>
		<br>
		<a href="https://www.useanvil.com/?utm_source=sindresorhus#gh-light-mode-only">
			<div>
				<img src="https://sindresorhus.com/assets/thanks/anvil-logo-light.svg" width="200" alt="Anvil">
			</div>
			<br>
			<b>Paperwork that makes the data work.</b>
			<div>
				<sub>
				Easy APIs for paperwork. PDF generation, e-signature and embeddable no-code webforms.
				<br>
				The easiest way to build paperwork automation into your product.
				</sub>
			</div>
		</a>
		<a href="https://www.useanvil.com/?utm_source=sindresorhus#gh-dark-mode-only">
			<div>
				<img src="https://sindresorhus.com/assets/thanks/anvil-logo-dark.svg" width="200" alt="Anvil">
			</div>
			<br>
			<b>Paperwork that makes the data work.</b>
			<div>
				<sub>
				Easy APIs for paperwork. PDF generation, e-signature and embeddable no-code webforms.
				<br>
				The easiest way to build paperwork automation into your product.
				</sub>
			</div>
		</a>
		<br>
		<br>
		<br>
		<a href="https://serpapi.com#gh-light-mode-only">
			<div>
				<img src="https://sindresorhus.com/assets/thanks/serpapi-logo-light.svg" width="140" alt="SerpApi">
			</div>
			<b>API to get search engine results with ease.</b>
		</a>
		<a href="https://serpapi.com#gh-dark-mode-only">
			<div>
				<img src="https://sindresorhus.com/assets/thanks/serpapi-logo-dark.svg" width="140" alt="SerpApi">
			</div>
			<b>API to get search engine results with ease.</b>
		</a>
		<br>
		<br>
		<br>
	</p>
	<hr>
	<br>
	<br>
	<br>
	<br>
</div>

<p align="center">
	<a href="awesome.md">What is an awesome list?</a>&nbsp;&nbsp;&nbsp;
	<a href="contributing.md">Contribution guide</a>&nbsp;&nbsp;&nbsp;
	<a href="create-list.md">Creating a list</a>&nbsp;&nbsp;&nbsp;
	<a href="https://twitter.com/awesome__re">Twitter</a>&nbsp;&nbsp;&nbsp;
	<a href="https://www.redbubble.com/people/sindresorhus/works/30364188-awesome-logo">Stickers & t-shirts</a>
</p>

<br>

<div align="center">
	<b>Follow the <a href="https://twitter.com/awesome__re">Awesome Twitter account</a> for updates on new list additions.</b>
</div>

<br>

<p align="center">
	<sub>Just type <a href="https://awesome.re"><code>awesome.re</code></a> to go here. Check out my <a href="https://sindresorhus.com/apps">apps</a> and follow me on <a href="https://twitter.com/sindresorhus">Twitter</a>.</sub>
</p>
<br>

-----------

<br>

-----------

<br>
