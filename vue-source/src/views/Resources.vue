
<template>
  <div class="id">    
            <div class="about-text" style="word-wrap: break-word;">
                <h1 style="padding-left: 4rem; padding-right: 4rem; font-weight: bolder; ">Tools</h1>
                <h3 style="padding-left: 4rem; padding-right: 4rem; padding-top: 4rem; font-weight: 600; ">
                    SDK’S </h3>

                <p style="padding-left: 4rem; padding-right: 8rem; ">
                    VitaSDK: <a style="color:#fff; " href="https://vitasdk.org">ttps://vitasdk.org</a>
                    <br>DolceSDK: <a style="color:#fff; " href="https://github.com/DolceSDK">https://github.com/DolceSDK</a>
                    <br>How to setup Unity for the PS Vita: <a style="color:#fff; " href="https://www.patreon.com/posts/guide-how-to-to-24906451">https://www.patreon.com/posts/guide-how-to-to-24906451</a>
                    <br>Gamemaker Studio PSVita export tool: <a style="color:#fff; " href="https://github.com/KuromeSan/GayMaker">https://github.com/KuromeSan/GayMaker</a></p>

                <h3 style="padding-left: 4rem; padding-right: 4rem; padding-top: 4rem; font-weight: 600; ">
                    Tools that make your life just a bit easier </h3>
                <p style="padding-left: 4rem; padding-right: 8rem;">
                    Vitacompanion: <a style="color:#fff; " href="https://github.com/devnoname120/vitacompanion">https://github.com/devnoname120/vitacompanion</a>
                    <br>PSVshell: <a style="color:#fff; " href="https://github.com/Electry/PSVshell">https://github.com/Electry/PSVshell</a>
                </p>


                <h3 style="padding-left: 4rem; padding-right: 4rem; padding-top: 4rem; font-weight: 600; ">
                    Useful debugging tools </h3>
                <p style="padding-left: 4rem; padding-right: 8rem;">
                    Vitashell: <a style="color:#fff; " href="https://github.com/TheOfficialFloW/VitaShell/releases l">https://github.com/TheOfficialFloW/VitaShell/releases </a>
                    <br> Core dump reader : <a style="color:#fff; " href="https://github.com/xyzz/vita-parse-core ">https://github.com/xyzz/vita-parse-core </a>
                    <br> PrincessLog : <a style="color:#fff; " href="https://forum.devchroma.nl/index.php?topic=80.0">https://forum.devchroma.nl/index.php?topic=80.0 </a>
                    <br> GDB for vita : <a style="color:#fff; " href="https://github.com/DaveeFTW/kvdb">https://github.com/DaveeFTW/kvdb</a> (not convenient)

                </p>
            </div>
            <div class="contact">
                <h1 style="padding-left: 4rem; padding-right: 4rem; font-weight: bolder; ">Useful discord servers</h1>
                <p style="padding-left: 4rem; padding-right: 8rem;">
                    <br>Henkaku : <a style="color:#fff; " href="https://discord.gg/m7MwpKA">https://discord.gg/m7MwpKA</a> (mainly vitasdk)
                    <br>Vita Nuova : <a style="color:#fff; " href="https://discord.gg/PyCaBx9">https://discord.gg/PyCaBx9</a> (mainly vitasdk)
                    <br>CBPS : <a style="color:#fff; " href="http://discord.cbps.xyz/">http://discord.cbps.xyz/</a> (mainly dolce sdk/unity/gamemaker)

                </p>
            </div></div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
<style>
    .content {
        width: 85vw;
    }
    
    @media (max-width: 1000px) {
        .content {
            width: 100vw;
        }
    }
</style>