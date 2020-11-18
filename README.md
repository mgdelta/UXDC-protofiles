UXDC-protofiles

eCAL topic names for UXDC_Halo.proto:

follows 'rule' 	UXDC_<application>_<message>

UXDC::Halo::HALO_Status  	publisher 	topicname: "UXDC_Halo_Status"
	
UXDC::Halo::SetColor_Strip	subscriber	topicname: "UXDC_Halo_SetColor"
UXDC::Halo::Clear_Strip		subscriber	topicname: "UXDC_Halo_ClearStrip"
UXDC::Halo::Cmd_FadeIn		subscriber	topicname: "UXDC_Halo_FadeIn"
UXDC::Halo::Cmd_FadeOut		subscriber	topicname: "UXDC_Halo_FadeOut"
UXDC::Halo::SetEvent		subscriber	topicname: "UXDC_Halo_TriggerEvent"
