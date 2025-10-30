<script lang="ts">
    import { t } from "$lib/i18n/translations";
    import SectionHeading from "$components/misc/SectionHeading.svelte";
</script>

<section id="general">
<SectionHeading
    title={$t("about.heading.general")}
    sectionId="general"
/>

these terms apply only when using the official kac app or service.  
if you are using an unofficial or modified version, please contact the provider or maintainer directly for accurate information.  
the official kac instance follows strict privacy and ethical guidelines as described here.
</section>

<section id="saving">
<SectionHeading
    title={$t("about.heading.saving")}
    sectionId="saving"
/>

kac provides tools to help users download and save content from various online platforms.  
we do not host or store any downloaded files, nor do we track what users download.  
all processing happens securely and temporarily in memory, and all temporary data is cleared automatically after completion.  

users are fully responsible for the content they choose to download, store, or share using kac.  
kac does not claim ownership of any media processed through its services.
</section>

<section id="responsibility">
<SectionHeading
    title={$t("about.heading.responsibility")}
    sectionId="responsibility"
/>

you, the end user, are solely responsible for how you use kac and the content you obtain through it.  
always respect copyright laws, creator rights, and platform policies when downloading or redistributing any material.  

if you use kac for educational or informational purposes, always credit original creators and cite your sources.  
kac encourages ethical use and respect for digital content ownership.
</section>

<section id="abuse">
<SectionHeading
    title={$t("about.heading.abuse")}
    sectionId="abuse"
/>

kac operates with user privacy in mind and does not include any automatic tracking or behavior detection systems.  
if you encounter misuse, illegal activity, or content violations involving kac, please report it through the official kac contact channels.  

reports are reviewed manually to ensure fairness and prevent abuse of the reporting system.  
support-related questions should be directed only to official kac support channels, not to the abuse reporting contacts.
</section>
