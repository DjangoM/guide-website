<template>
  <v-layout wrap pa-2>
    <h1>Ethereum Network - The Hitchhiker's Guide to the Ethereum Blockchain</h1>
    <p>Ethereum Network is a guide to better understand, use and explore Ethereum, the decentralized smart contracts platform.</br>This is not the official website of the <a href="https://ethereum.org/" target="_blank">Ethereum</a> project, it is rather a guide for and by the community to foster the Ethereum ecosystem.</p>

    <p>The <b>learn</b> page is a curated, up-to-date list of links to show users and developers first steps into Ethereum.<br>
    <p>The <b>project</b> list gives an overview of all projects using Ethereum in some way, searchable by their keywords, technologies, developers and other criteria. URLs can link directly to the <router-link to="/project/AKASHA">project details</router-link> or <router-link to="/?q=prediction market">search queries</router-link>.</br>It's more a tool to find ideas and people with similar interests to form connections and work together, rather than a list to brag how many projects exist on Ethereum. So you will also find <router-link to="/?q=abandoned">abandoned</router-link> projects and the ones which never made it past the idea stage.</p>
    <p>Through the <b>explorer</b> you can analyze the Ethereum blockchain in detail, see transactions coming in in real time, verify smart contract code and view statistics (coming soon).</p>
    <p>As there are already many quality news websites reporting about Ethereum, we just gather the 24 most important ones of the day and post them via our social media accounts, but in our <b>blog</b> we report from Ethereum meetups around the world.</p>
    <br>
    <h1>Team</h1>
    <p>Unitl now this project is built in spare time and paid by ether appreciation, but will turn into a fully decentralized community project with the help of Colony, Aragon or alike. Help is always appreciated, either by <a href="https://github.com/EthereumNetwork/guide-website/issues">finding bugs</a>, <router-link to="/address/0x720AD841f4B0ffB8aB8EEe4Ed1Bd5d84DD282450">donating</router-link> a little bit, or <router-link to="/form">adding projects</router-link>.<br>All <a href="https://blog.ethereum.network/latest" target="_blank">code</a> and the project database is open source and can be edited (via the little edit symbol) or <a href="/download/projects" target="_blank">downloaded</a>.</p>
    <v-flex xs12 sm6>
      <h2>Dang Du</h2>
      <img src="/ddu.jpg" class="profilePic">
      <p>Dang’s projects have evolved from public policy to central banking before moving on to the financial sector. Now his time is devoted to decentralized finance and the digital economy.</p>
      <p>As community manager, he manages the main <a href="https://t.me/EthereumNetwork" target="_blank">Telegram</a> and <a href="https://www.facebook.com/groups/112915296053162/" target="_blank">Facebook</a> groups, and writes news summaries and Ethereum meetup reports on our <a href="https://blog.ethereum.network/latest" target="_blank">blog</a></p>
      <a href="https://www.linkedin.com/in/dang-du-330068106/" target="_blank"> <i class="icon-linkedin-squared contact-link"></i></a>
      <a href="https://twitter.com/DDeconomics" target="_blank"> <i class="icon-twitter-squared contact-link"></i></a>
      <a href="https://medium.com/@DDeconomics" target="_blank"> <i class="icon-newspaper contact-link"></i></a>
    </v-flex>
    <br>
    <v-flex xs12 sm6>
      <h2>Juan José Domínguez</h2>
      <img src="/jjd.jpg" class="profilePic">
      <p>in Mexico City, is a marketing consultant who knew the blockchain by accident (or not).</p>
      <p>As manager for the Spanish speaking community, he manages our Spanish <a href="https://t.me/ReddeEthereum" target="_blank">Telegram</a> and <a href="https://facebook.com/groups/113343209354983" target="_blank">Facebook</a> groups, and translates important Ethereum news and summaries.</a></p>
      <a href="https://www.linkedin.com/in/juanjosedominguezochoa/" target="_blank"> <i class="icon-linkedin-squared contact-link"></i></a>
      <a href="https://twitter.com/jjthink" target="_blank"> <i class="icon-twitter-squared contact-link"></i></a>
      <a href="https://blockchainmarketing.org/" target="_blank"> <i class="icon-link contact-link"></i></a>
    </v-flex>
    <br>
    <v-flex xs12 sm6>
      <h2>Michael Ilg</h2>
      <img src="/milg.jpg" class="profilePic">
      <p>in Berlin, started out with programming on the Bitcoin blockchain before moving on to Ethereum to decentralize all the things.</p>
      <p>As founder and developer, he keeps the <router-link to="/">website</router-link> running by fixing bugs and adding features, as well as assisting the community managers.</p>
      <a href="https://www.linkedin.com/in/michaelilg/" target="_blank"> <i class="icon-linkedin-squared contact-link"></i></a>
      <a href="https://twitter.com/misterigl" target="_blank"> <i class="icon-twitter-squared contact-link"></i></a>
      <a href="https://github.com/misterigl" target="_blank"> <i class="icon-github-squared contact-link"></i></a>
    </v-flex>
  </v-layout>
</template>

<script>
export default {
  name: 'about',
  props: ['searchField'],
  data () {
    return {
      msg: 'the network explorer is in the works...'
    }
  }
}
</script>

<style>
.profilePic {
  padding: 5px;
}
</style>
