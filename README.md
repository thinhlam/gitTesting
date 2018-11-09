# gitTesting
gittest

Read me
ITransReceiverService __transType: 220801 - server_channel_system_id: DANA22 - client_channel_system_id: IFINFLUX_MERCHANT__
|
| sgw_parser_template
|
#public class IFINFLUX_MERCHANTDispatcherParser extends InnerWsRequestMessageDispatcherParser
|
| sgw_transtype_channel_map edited same place
|
parser : channel_system_id: Ifinflux_merchant, transactionType: 2200801, out_trans_code: IFINFLUX_DANA02, Gateway_mode: Server
|
| sgw_parser_template
|

Change 1 line
DANA220801ApplyTokenRequestParser parse request
|
| sgw_assemble_template (out_trans_code : DANA02, MessageType: CallMessage)
|
assembler
|
| send
|
