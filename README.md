<h1>InstaStream</h1>

View a quick demo live here : <a href="http://instastream.exibit.be/">http://instastream.exibit.be/</a>

<h2>Before to use the plugin</h2>
<p>Before to go further be sure you have an Instagram account and an Instagram API Key.</p>
<p>For how you can have one, please visit the official <a href="http://instagram.com/developer/">Instagram Developer center</a> and tutorials like <a href="https://github.com/macuenca/Instagram-PHP-API">this one</a>.</p>

Once you have your Token you can start using this jQuery plugin.
<h2>Installation</h2>
<ol>
	<li>Unzip the folder</li>
	<li>Add the js file to your website </li>
	<li>Add css styles to your website </li>
	<li>Add 'img' folder to your website </li>
</ol>
<h2>Configuration</h2>
To call the plugin, you need to write a little javascript/jQuery code

<code>jQuery(document).ready(function ($) {

	/* INSTASTREAM DEMO 1 */
  $("#demo1").instastream({
		instaToken: '1011689.764d34f.25312ac794bf41f5b7c3d2f3385ce17e',
		instaUser: '1011689',
		instaResults: 3,
		instaMenu: 'yes'
	});
	
	
	
});</code>

