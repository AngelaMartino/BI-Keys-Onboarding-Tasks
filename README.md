# BI-Keys-Onboarding-Tasks
SELECT  P.[Name],P.[ID] FROM  [dbo].[Property] as P 
inner join[dbo].[OwnerProperty] AS Op on P.Id = Op.Id
where op.OwnerId = 1426
