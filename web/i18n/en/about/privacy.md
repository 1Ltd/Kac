<script lang="ts">
    import env from "$lib/env";
    import { t } from "$lib/i18n/translations";

    import SectionHeading from "$components/misc/SectionHeading.svelte";
</script>

<section id="general">
<SectionHeading
    title={$t("about.heading.general")}
    sectionId="general"
/>

KAC respects your privacy completely. We do not collect, store, track, or share any personal information about you or your usage.  
Everything you do within KAC stays on your device and under your control.  
These terms apply only to the official KAC app and website. For unofficial or modified versions, please contact the provider directly.
</section>

<section id="local">
<SectionHeading
    title={$t("about.heading.local")}
    sectionId="local"
/>

Most KAC tools operate locally on your device.  
When using such tools, no data leaves your device and nothing is transmitted to any server.  
Local tools are designed to work offline whenever possible to ensure your full privacy.
</section>

<section id="saving">
<SectionHeading
    title={$t("about.heading.saving")}
    sectionId="saving"
/>

When you download or save content through KAC, the app may temporarily process media files to generate the required output.  
During this process, only minimal technical data is used for file handling.  
No personal data, browsing history, or user identity is ever stored or logged.  
Temporary data is automatically removed after the process completes and never reused for any other purpose.
</section>

<section id="encryption">
<SectionHeading
    title={$t("about.heading.encryption")}
    sectionId="encryption"
/>

KAC uses strong encryption methods to protect all temporary data handled during downloads or transfers.  
This ensures that any data processed remains secure and inaccessible to anyone else.  
All encryption keys are generated dynamically and are never stored or shared.
</section>

{#if env.PLAUSIBLE_ENABLED}
<section id="plausible">
<SectionHeading
    title={$t("about.heading.plausible")}
    sectionId="plausible"
/>

KAC may include optional anonymous usage statistics to help improve stability and performance.  
These analytics do not include any personal or identifiable information.  
You can disable analytics anytime in the app’s privacy settings.
</section>
{/if}

<section id="cloudflare">
<SectionHeading
    title={$t("about.heading.cloudflare")}
    sectionId="cloudflare"
/>

KAC uses secure hosting and protection services to ensure safe and reliable operation.  
These services are used only to prevent abuse, protect against attacks, and maintain app availability.  
No personal user data is ever shared with these services beyond what is technically necessary for protection.
</section>
