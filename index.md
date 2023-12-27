<html>
    <body>

<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DAz000001QeNp',
				'Test',
				'https://autel--poc.sandbox.my.site.com/ESWTest1703655776310',
				{
					scrt2URL: 'https://autel--poc.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://autel--poc.sandbox.my.site.com/ESWTest1703655776310/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>



</body>


</html>