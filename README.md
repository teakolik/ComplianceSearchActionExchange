# ComplianceSearchActionExchange
# Exchange Compliance Search And Delete Mails

Install-Module ExchangeOnlineManagement

Import-Module ExchangeOnlineManagement

Connect-ExchangeOnline

Connect-IPPSSession -UserPrincipalName teakolik@teakolik.com

New-ComplianceSearchAction -SearchName "Eski Grup Mailleri Sil" -Purge -PurgeType HardDelete
New-ComplianceSearchAction -SearchName "Eski Grup Mailleri Sil" -Purge -PurgeType HardDelete -Force  // Force


