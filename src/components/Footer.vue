<template>
    <div class="siteFooter">
        <div class="siteFooter-wrapper container">
            <div class="siteFooter-header">
                <div class="siteFooter-logo">
                    <router-link :to="{ name: 'home' }">
                        <img src="/assets/images/brand/vanillaos-logo-icon.svg" alt="Vanilla OS" />
                    </router-link>
                </div>
                <div class="siteFooter-navigation">
                    <ul>
                        <li><router-link :to="{ name: 'blog' }">Blog</router-link></li>
                        <li><router-link :to="{ name: 'help' }">Help</router-link></li>
                        <li><router-link :to="{ name: 'get-involved' }">Get Involved</router-link></li>
                        <li><router-link :to="{ name: 'download' }">Download</router-link></li>
                    </ul>
                </div>
            </div>
            <div class="siteFooter-sitemap">
                <ul>
                    <li><b>Legal</b></li>
                    <li><a href="//fabricators.ltd/">fabricators Ltd.</a></li>
                    <li><router-link :to="{ name: 'privacy-policy' }">Privacy Policy</router-link></li>
                    <li><router-link :to="{ name: 'cookies-policy' }">Use of Cookies</router-link></li>
                    <li><router-link :to="{ name: 'brand' }">Our Brand</router-link></li>
                    <li><router-link :to="{ name: 'get-involved-funding' }">Funding</router-link></li>
                    <li><router-link :to="{ name: 'licenses' }">Licenses</router-link></li>
                    <li><a href="//fabricators.ltd/en/contact">File a Complaint</a></li>
                    <li><a href="//status.vanillaos.org/">System Status</a></li>
                </ul>
                <ul>
                    <li><b>Community</b></li>
                    <li><router-link :to="{ name: 'team' }">Our Team</router-link></li>
                    <li><router-link :to="{ name: 'community' }">Community</router-link></li>
                    <li><router-link :to="{ name: 'get-involved' }">Get Involved</router-link></li>
                    <li><router-link :to="{ name: 'code-of-conduct' }">Code of Conduct</router-link></li>
                    <li class="spacer"></li>
                    <li><b>Support</b></li>
                    <li><a href="//documentation.vanillaos.org/">Documentation</a></li>
                    <li><a href="//handbook.vanillaos.org/">Handbook</a></li>
                    <li><router-link :to="{ name: 'enterprise-support' }">Enterprise Support</router-link></li>
                    <li><router-link :to="{ name: 'community' }">Community Support</router-link></li>
                </ul>
                <ul>
                    <li><b>Developers</b></li>
                    <li><router-link :to="{ name: 'developers-program' }">Join the Developers Program</router-link></li>
                    <li><a href="https://github.com/vanilla-os" target="_blank">Source Code</a></li>
                    <li><a href="https://github.com/vanilla-os" target="_blank">Report a Bug</a></li>
                    <li><router-link :to="{ name: 'technologies-and-credits' }">Technologies and Credits</router-link></li>
                    <li><router-link :to="{ name: 'roadmap' }">Roadmap</router-link></li>
                    <li><router-link :to="{ name: 'components-lifecycle' }">Components Lifecycle</router-link></li>
                    <li class="spacer"></li>
                    <li><b>Get Vanilla OS</b></li>
                    <li><router-link :to="{ name: 'download' }">Download</router-link></li>
                    <li><router-link :to="{ name: 'download' }">System Requirements</router-link></li>
                    <!--<li><router-link :to="{ name: 'download' }">Release Notes</router-link></li>-->
                </ul>
            </div>
        </div>
    </div>
</template>
  
<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
    name: 'SiteFooter',
});
</script>