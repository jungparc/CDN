## Content Delivery > CDN > Error Codes

| errorCode | errorMessage | Description |
| --- | --- | --- |
| 0 | SUCCESS | Successful |
| -1 | FAIL | Failed |
| -2 | ASSERT | Failed |
| 10000 | Domain does not exist. | Service does not exist. |
| 10001 | There is no path to purge. | Enter path to purge. |
| 10002 | The HTTP Method or url of Callback URL is not valid. | HTTP method or URL of callback URL is not entered. |
| 10003 | Callback url format is not valid. | Callback url format is not valid. |
| 10004 | Exist a creating service. Please retry after it is finished. | Cannot execute requested task. Try again after previous request is completed. |
| 10006 | Not found resource | Resource is not found as requested, or the request is invalid. |
| 10007 | Already exists domain alias. | Domain Alias is already registered in another CDN service domain. |
| 10008 | Origin path must starts with a slash('/). | Start with '/' to enter origin path. |
| 10009 | Origin path must not end with a slash('/). | '/' is not allowed as the last character of the origin path. |
| 10010 | Origin domain is required. | Origin server is required. |
| 10011 | Please enter origin domain without scheme. | Origin server cannot have scheme information, such as http://. |
| 10012 | Please enter the origin domain in public IP or domain format. | The origin server format is not valid: enter in domain or IP. |
| 10013 | Domain alias is invalid. | The Domain Alias format is not valid. |
| 10014 | Referrers is invalid. Enter referrers regular expression. | The referrer format is not valid: check if it is valid regular expression. |
| 10015 | Please enter use origin 'Y' or 'N'. | Enter 'Y' or 'N'  regarding whether to use origins for cache expiration setting. |
| 10016 | Please enter origin. | Origin server setting is not available or invalid. |
| 10017 | Invalid Purge Type. Please enter purge type 'ITEM' or 'ALL' | The purge type is not valid: enter 'ITEM' or 'ALL'. |
| 10018 | Invalid Origin Port. Please enter a number between 0 and 65,536. | The origin server port is not valid: enter a number between 0 and 64, or 536. |
| 10019 | Up to three domain aliases can be registered. | Up to three domain aliases can be registered. |
| 10020 | The requested domain alias has duplicated values. | This is a domain alias that has already been registered, and new registration is not available. |
| 10021 | Already deleted distribution. | This is CDN service that has already been deleted. |
| 10023 | The port field cannot be set with either httpPort or httpsPort. | Port, httpPort and httpsPort cannot be entered at the same time. Please enter port, or enter httpPort and httpsPort.  |
| 10024 | The origin server port is not set. | origin server port is the required input value. Please enter the origin server port in the port or httpPort or httpsPort. |
| 10025 | Invalid origin port. The httpPort equals httpsPort. | Please enter a different input value for httpPort and httpsPort. |
| 10027 | The description's maximum length is limited to 255 characters. | Maximum of 255 characters can be entered for CDN service description. |
| 10028 | The Root Path Control 'controlType' is not set. Please enter type 'DENY' or 'REDIRECT' | controlType is a required input value. Please enter either "DENY" or "REDIRECT." |
| 10029 | The Root Path Control 'redirectPath' is not set. | If the controlType is "REDIRECT," the redirectPath is a required input value. |
| 10030 | 'redirectPath' must starts with a slash('/). | redirectPath must be entered starting with a "/." |
| 10031 | The Root Path Control 'redirectStatusCode' is not set. Please enter Code 301 or 302 or 303 or 307 | If the controlType is "REDIRECT," redirectStatusCode is a required input value. Please enter one of 301, 302, 303, or 307. |
| 10032 | Invalid 'redirectStatusCode'. Please enter Code 301 or 302 or 303 or 307 | The input value of redirectStatusCode is not correct. Please enter one of 301, 302, 303 or 307.  |
| 10033 | Auth Token 'encryptKey' is not set. | encryptKey is a required input. Enter the [Access Control for Auth Token Authentication > Token Encryption Key] value displayed on the NHN Cloud CDN console. |
| 10034 | Auth Token 'durationSeconds' is not set. | durationSeconds is a required input. Enter the value to set as the token expiration time in seconds. |
| 10035 | Invalid 'sessionId'. Please enter smaller than 36 bytes for the length of character string. | The length of the sessionId string cannot exceed 36 bytes. |
| 10036 | There is no path to generate token. Please enter 'singlePath' or 'singleWildcardPath' or 'multipleWildcardPath'. | At least one of singlePath, singleWildcardPath, or multipleWildcardPath must exist. |
| 10037 | Auth token paths ('singlePath', 'singleWildcardPath', 'multipleWildcardPath') must start with a slash(/). | singlePath, singleWildcardPath, and multipleWildcardPath must start with '/'. |
| 10038 | Invalid character exists. Since ! and ~ are used as reserved characters, do not include them in path or session ID. | The !, ~ characters are used as reserved characters, so they cannot be included in a path or session ID. |
| 20001 | Failed to authenticate with AppKey. | Appkey is not valid. |
| 20002 | Failed to authenticate with the secret key. | SecretKey is not valid. |
| 30000 | Failed to process request. Please try again later. | Failed to process request. |
| 30001 | Purge usage has exceeded. Please try again later. | Purge volume has been exceeded. |
| 30002 | Data not created or does not exist. Please try again later. | Data has not been created or is not available. |
| 30003 | Request not processed in current service status. | Cannot process the request under the current service status. |
| 30004 | The status of the service is unknown. | The service status is unknown. |
| 30005 | Resource not found. | Resource cannot be found. |
| 80500 | An unknown error occurred during processing. Please contact the service provider. | Unknown error has occurred while processed. Contact service provider. |