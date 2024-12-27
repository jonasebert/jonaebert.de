<script lang="ts">
    import RoundedIcon from "$lib/components/button/RoundedIcon.svelte"
    import { faInstagram, faThreads, faYoutube, faTiktok, faLinkedinIn, faGithub } from "@fortawesome/free-brands-svg-icons"; // For new Icons: https://fontawesome.com/search
</script>

<div class="space-y-2">
    <RoundedIcon href="https://www.instagram.com/jonaebertbs" icon={faInstagram} target="_blank" />
    <RoundedIcon href="https://www.threads.net/@jonaebertbs" icon={faThreads} target="_blank" />
    <RoundedIcon href="https://www.youtube.com/@jonaebert" icon={faYoutube} target="_blank" />
    <RoundedIcon href="https://www.tiktok.com/@jona_ebert" icon={faTiktok} target="_blank" />
    <RoundedIcon href="https://www.linkedin.com/in/jonaebert" icon={faLinkedinIn} target="_blank" />
    <RoundedIcon href="https://github.com/jonaebert" icon={faGithub} target="_blank" />
</div>