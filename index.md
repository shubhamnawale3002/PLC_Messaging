<script type='text/javascript' src='https://service.force.com/embeddedservice/5.0/esw.min.js'></script>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DKj000008RfqZ',
				'Sonim_Chat_Support',
				'https://in1730818425694.my.site.com/ESWSonimChatSupport1730825057895',
				{
					scrt2URL: 'https://in1730818425694.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://in1730818425694.my.site.com/ESWSonimChatSupport1730825057895/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
