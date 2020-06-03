Node Id: DNC
Type: HTTP Post
URL: https://engage.ringcentral.com/api/v1/admin/accounts/{accountId}/dncLists
Concurrent Audio: dnc_or_q_bye
Timeout: 30
Format: JSON

{
    "dncTag":
      {
        "dncTagId":0,
        "dncTagLabel":"GLOBAL"
      },
    "countryCode":
      {
        "id":"USA"
      },
    "phone":"$ani",
    "tag":"GLOBAL",
    "dncTagId":0
}
