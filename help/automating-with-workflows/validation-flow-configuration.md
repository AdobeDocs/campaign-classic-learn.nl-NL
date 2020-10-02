---
title: Validatieworkflows configureren in Adobe Campaign Classic
seo-title: Validatieworkflows configureren in Adobe Campaign Classic
description: Adobe Campaign biedt verschillende mogelijkheden voor marketers om inhoud, campagnedoel, gegevensextractie en begrotingsgoedkeuring te beoordelen en te leveren. In deze zelfstudie wordt uitgelegd hoe u verschillende workflows voor goedkeuringsvalidatie kunt configureren.
seo-description: In deze video wordt uitgelegd hoe u een leveringssjabloon kunt configureren en gebruiken in ACCAdobe Campaign. Deze video biedt verschillende opties voor marketers om de leveringsinhoud, het campagnedoel, de gegevensextractie en begrotingsgoedkeuringen te beoordelen en te leveren. In deze zelfstudie wordt uitgelegd hoe u verschillende workflows voor goedkeuringsvalidatie kunt configureren.
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: Workflow
topics: Validation
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 838c617ca163a09fcb57b7b4706433e98869bc3d
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Validatieworkflows configureren in Adobe Campaign Classic

Adobe Campaign biedt verschillende mogelijkheden voor marketers om inhoud, campagnedoel, gegevensextractie en begrotingsgoedkeuring te beoordelen en te leveren.

In deze zelfstudie wordt uitgelegd hoe u verschillende workflows voor goedkeuringsvalidatie kunt configureren.

## Vereiste {#prerequisite}

Voordat het marketingteam goedkeuringsstappen kan uitvoeren, moet het afzonderlijke controleurs definiëren:

* De rol van Adobe Campaign-revisor binnen een goedkeuringsactiviteit kan één revisor (operator) of een groep revisoren (rol van operator) zijn.
* De revisoren en revisorgroepen moeten eerder in Adobe Campaign zijn geconfigureerd met een beheerdersrol. Op deze manier kunnen ontwikkelaars van campagnes de controleurs selecteren als fiatteurs in een campagne of levering.

## Goedkeuringen voor campagnes configureren  {#configuring-approvals-for-campaigns}

Als u dezelfde set controleurs voor alle leveringen in uw campagneworkflow hebt, gebruikt u de [!DNL Campaign] goedkeuringsfuncties. Door goedkeuringen en revisoren op campagnereniveau in te stellen, worden de goedkeuringstaken en controleurs naar elke leveringsactiviteit van uw werkstroom verschoven zodra de werkstroom wordt uitgevoerd.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Goedkeuringen voor leveringen configureren  {#configuring-approvals-for-deliveries}

U kunt goedkeuringen ook instellen op leveringsniveau. Als de stappen voor de goedkeuring van de levering en de controleurs afwijken van de stappen voor de goedkeuring van de campagne en de controleurs, hebben de leveringsinstellingen voorrang op de instellingen voor de campagne.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Een goedkeuringsactiviteit configureren  {#configuring-an-approval-activity}

In tegenstelling tot de levering of campagnegoedkeuringen, staat de goedkeuringsactiviteit toe om een goedkeuringsproces binnen een werkschema tot stand te brengen. Op deze manier kan de doelgerichte selectielogica worden goedgekeurd voordat de levering wordt gestart. Het staat ook goedkeuring op veelvoudige niveaus binnen het werkschema toe, indien nodig.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

For more information, refer to the [Approval Documentation](https://docs.adobe.com/help/en/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)