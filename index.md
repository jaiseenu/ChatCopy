<html>
	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
	</head>
<body>

<script type='text/javascript'>
	function initEmbeddedMessaging() {
		console.log('::%::', embeddedservice_bootstrap);
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00Dce000001LoFm',
				'Copy_Web_Chat',
				'https://pflms--qa.sandbox.my.site.com/ESWCopyWebChat1745250621922',
				{
					scrt2URL: 'https://pflms--qa.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://pflms--qa.sandbox.my.site.com/ESWCopyWebChat1745250621922/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>



</body>
</html>
