FullStack **Projekti 3: React & Next.JS** 


# Sisällysluettelo

[1	Yleistä tietoa projektista	3](#_toc157605484)

[2	Käytettyjä tekniikoita ja erikoisuuksia	3](#_toc157605485)

[3	Sivuston / ohjelmiston design ja rakenne	3](#_toc157605486)

[4	Linkit	3](#_toc157605489)

[**4.1**	Verkkosivuni osoite -	3](#_toc157605490)

[4.2	Linkki GitHub repositorioon	3](#_toc157605491)

[4.3	Linkki projektin videoesitykseen	3](#_toc157605492)



# <a name="_toc119942852"></a><a name="_toc157605484"></a>Yleistä tietoa projektista
Tämä projekti on rakennettu Vercelin tarjoaman opastuksen/kurssin (*Learn Next.js Course*) pohjalta. Projektissa tavoitteena oli luoda yksinkertainen, käyttäjäystävällinen ja toimiva taloushallinnon Full Stack Web-sovellus, joka mukailee taloushallintapaneelia, käyttäen Next.js framework:iä. Full Stack sovellusten kehittämiseen Next.js on ideaalinen, koska Next.js tarjoaa palvelinpuolen hallintaan ja renderöintiin sekä Web-sovellusten kehittämiseen tehokkaat työkalut. Tämän projektin koodi on pääasiassa koottu valmiiksi annetuista koodin pätkistä hyödyntäen erilaisia pohjia (templates) ja kirjastoja (libraries).

# <a name="_toc119942853"></a><a name="_toc157605485"></a>Käytettyjä tekniikoita ja erikoisuuksia
Projektissa ei ole erityisiä erikoisuuksia. Tekniikoista tai työkaluista yksi merkittävimpiä oli Next.js, joka toimi sovelluksen pohjana, tarjoten palvelinpuolen ja asiakaspuolen kehitykseen tarvittavat työkalut. Käyttöliittymän rakentamisessa oli käytössä React, jonka kirjaston komponentteja hyödynnettiin laajasti sovelluksen arkkitehtuurissa. NextAuth.js todennusratkaisua käytetään sovelluksessa autentikaation käsittelyssä. Web-sovelluksen tyylittely ja ulkoasu taas pohjautuu Tailwind CSS:ään. Projektissa käytetään PostgreSQL-tietokantaa tietojen säilömiseen sekä taustalla ja sovelluksessa. PostgreSQL-tietokannan käyttöönottamiseen käytettiin Vercel:iä. 

# <a name="_toc119942854"></a><a name="_toc157605486"></a>Sivuston / ohjelmiston design ja rakenne
Web-sovelluksessa komponentit (React) ja niiden tyylit oli määritelty etukäteen oppaan / kurssin puolesta. Täten sivuston graafiseen ulkoasuun tai rakenteeseen ei erityisemmin tehty muutoksia muuten kuin fontteihin. Sovelluksen rakenne koostuu noin viidestä sivusta, jotka on kuvattu seuraavaksi:
**


1. **Kotisivu / Landing page:** Kotisivulla käyttäjät näkevät lyhyen pätkän tietoa sivusta ja kirjautumiseen ohjaavan linkin.

   ![A screenshot of the LandingPage](media/Aspose.Words.18c97cf8-2efa-4306-99ad-e8c4844384da.001.png)

2. **Sisään kirjautuminen – sivu:** NextAuth.js-kirjastoa hyödyntävä kirjautuminen.

   ![A screenshot of a login form](media/Aspose.Words.18c97cf8-2efa-4306-99ad-e8c4844384da.002.png)
**


3. **Suojattu Dashboard-sivu:** Kirjautumalla sisään käyttäjät näkevät taloustiedot ja muut tärkeät toiminnot

   ![A screenshot of Dashboard](media/Aspose.Words.18c97cf8-2efa-4306-99ad-e8c4844384da.003.png)

4. **Laskut-sivu, laskujen lisäys, muokkaus ja poistaminen:** Käyttäjät pystyvät käsitellä laskuja.

   ![A screenshot of Invoices](media/Aspose.Words.18c97cf8-2efa-4306-99ad-e8c4844384da.004.png)

   ![A screenshot of Edit Invoice](media/Aspose.Words.18c97cf8-2efa-4306-99ad-e8c4844384da.005.png)

   ![A screenshot of Create Invoice](media/Aspose.Words.18c97cf8-2efa-4306-99ad-e8c4844384da.006.png)

5. **Asiakkaat-sivu:** Käyttäjä voi nähdä asiakkaat listattuna taulukkonäkymässä.

   ![A screenshot of Customers](media/Aspose.Words.18c97cf8-2efa-4306-99ad-e8c4844384da.007.png)

6. **Vercel PostgreSQL tietokanta:** Käyttäjä- ja laskutietojen tallentamiseen on käytetty PostgreSQL-tietokantaa.

   ![A screenshot of vercel database](media/Aspose.Words.18c97cf8-2efa-4306-99ad-e8c4844384da.008.png)


# <a name="_toc157605489"></a>Linkit
## <a name="_toc157605490"></a>Verkkosivuni osoite –** 
<https://project-3-fs-next.vercel.app/> 
## <a name="_toc157605491"></a>Linkki GitHub repositorioon
<https://github.com/AleMayry/Project-3-FS-next> 
## <a name="_toc157605492"></a>Linkki projektin videoesitykseen