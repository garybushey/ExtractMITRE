# ExtractMITRE
Extract MITRE ATT&amp;CK information

Export-AzSentinelMITREToCSV.ps1 will export a count of the rules that match tactic/techniques or a list of the rules.

Export-AzSentinelMITREIncidentsToCSV.ps1 will export a listing of the incidents that match the tactic/techniques.

Make sure you are logged into Azure and are in the correct subscription before running:

```
Connect-AZAccount
Select-AzSubscription -SubscriptionId <Subscription GUID>
```
