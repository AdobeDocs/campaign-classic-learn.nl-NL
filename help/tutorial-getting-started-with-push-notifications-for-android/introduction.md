---
title: Aan de slag met pushmeldingen voor Android - Inleiding
description: Deze tutorial begeleidt u door de stappen voor het verzenden van pushmeldingen vanuit Adobe Campaign en het ontvangen van deze meldingen in uw Android-app.
feature: Push
jira: KT-5951
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noDisplay
exl-id: 291c2e3a-c126-439d-9753-06a4091bbda0
source-git-commit: b56c0af81ed73fa06fe4846d0794167d35a26305
workflow-type: ht
source-wordcount: '355'
ht-degree: 100%

---

# Aan de slag met pushmeldingen voor Android - Inleiding

Met Adobe Campaign kunt u gepersonaliseerde en gesegmenteerde [!DNL push]-meldingen verzenden naar mobiele [!DNL iOS]- en [!DNL Android]-apparaten. Deze tutorial begeleidt u door de stappen voor het verzenden van [!DNL push]-meldingen vanuit Adobe Campaign naar een [!DNL Android]-app.

## Vereisten

Voordat u kunt beginnen, hebt u het volgende nodig:

1) **Mobiele Android-applicatie**

   In deze tutorial worden niet de gedetailleerde stappen behandeld die nodig zijn om de mobiele applicatie in te stellen. U hebt een mobiele **[!DNL Android]-applicatie nodig met [!DNL Campaign SDK]-integratie**.

   U vindt een gedetailleerde beschrijving van de vereiste stappen in de productdocumentatie:

   [De Campaign-SDK integreren in de mobiele applicatie](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=nl)

   U kunt ook de Experience Platform Mobile SDK gebruiken. Bekijk de videotutorial voor meer informatie:

   [Pushkanaal configureren met de Experience Platform Mobile SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html?lang=nl)

2) **[!DNL Mobile App channel]-pakket geïnstalleerd**

   Het [!DNL Mobile App channel]-pakket moet op uw [!DNL Campaign]-instantie zijn geïnstalleerd. In de volgende video wordt uitgelegd hoe u kunt controleren of het [!DNL Mobile App channel] op uw installatie is geïnstalleerd en, indien dit niet het geval is, hoe u dit installeert.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12&learn=on){transcript=true}

## Overzicht van tutorial

We willen een gepersonaliseerde [!DNL push]-reclamemelding sturen naar de abonnees van de mobiele [!DNL Android]-app [!DNL Neotrip]. De app [!DNL Neotrip] is geconfigureerd met de [!DNL Campaign SDK] en we hebben ervoor gezorgd dat het [!DNL Mobile App channel] op onze [!DNL Campaign]-instantie is geactiveerd.

De volgende configuratiestappen zijn vereist:

### Stap 1: Het schema voor app-abonnementen voor het personaliseren van [!DNL push]-meldingen uitbreiden

Omdat we de [!DNL push]-melding willen personaliseren, gaan we eerst het [app-abonnementschema uitbreiden](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md), zodat we de personalisatiewaarden kunnen opslaan die we van de app ontvangen wanneer de gebruiker zich inschrijft voor de service.

### Stap 2: De Android-service configureren en de mobiele applicatie maken in Campaign

Vervolgens moeten we de [Android-service configureren en de mobiele applicatie maken in Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). In deze stap definiëren we de app [!DNL Neotrip] als de target voor de pushmelding.

### Stap 3: De pushmelding configureren en verzenden

Vervolgens zijn we gereed om [de pushmelding te configureren en te verzenden](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## Tutorial starten

Stap 1: [Het schema voor app-abonnementen uitbreiden](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
