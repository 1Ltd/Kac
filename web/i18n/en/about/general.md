<script lang="ts">  
    import { t } from "$lib/i18n/translations";  
    import { contacts, docs } from "$lib/env";  
  
    import SectionHeading from "$components/misc/SectionHeading.svelte";  
</script>  
  
<section id="summary">  
<SectionHeading  
    title={$t("about.heading.summary")}  
    sectionId="summary"  
/>  
  
kac is a simple and secure tool that lets you download content from your favorite platforms —  
videos, music, photos, and more — all in one place.  
just paste the link, choose your format, and your content is ready to go.  
  
no ads, no tracking, no hidden fees.  
just a clean and efficient app designed to make downloading easy and private.  
</section>  
  
<section id="motivation">  
<SectionHeading  
    title={$t("about.heading.motivation")}  
    sectionId="motivation"  
/>  
  
kac was created to make content downloading safe, reliable, and accessible for everyone.  
many download tools on the internet are filled with ads, trackers, or unsafe scripts.  
kac removes all that — offering a clean, privacy-focused experience built for the user.  
  
our goal is simple: give people full control over their downloads without compromising privacy or safety.  
</section>  
  
<section id="privacy-efficiency">  
<SectionHeading  
    title={$t("about.heading.privacy_efficiency")}  
    sectionId="privacy-efficiency"  
/>  
  
all processing within kac is private and secure.  
requests are handled anonymously, and no personal data is ever collected or stored.  
  
when possible, kac processes media directly on your device for faster performance and complete privacy.  
if server-side processing is required, it is done live in memory only —  
nothing is written to disk, and everything is erased immediately after the task is complete.  
  
kac also supports enhanced privacy modes that route downloads through secure tunnels,  
keeping your online activity hidden from any external observers, including your internet provider.  
</section>  
  
<section id="community">  
<SectionHeading  
    title={$t("about.heading.community")}  
    sectionId="community"  
/>  
  
kac is built for people who value simplicity, safety, and freedom online.  
our community includes creators, students, and everyday users who believe in open, secure access to digital content.  
  
we continue improving kac with community feedback and ideas, ensuring it stays fast, private, and reliable.  
together, we aim to make kac the most trusted and user-friendly content downloader available.  
</section>
