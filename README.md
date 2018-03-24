# Rubbix_BlocksPHP
A bunch of PHP methods to build and sign transactions

<h3>Overview</h3>
<p>
Some more tools for people building stuff around Rubbix_Blocks :)<br/>
This basically allows you to build transactions and sign them directly from your application, without the need of interacting with Rubbix_Blocks node. 
</p>


<h3>Dependencies</h3>
<p>
This library depends on a modified version of <a href="https://github.com/devi/Salt">Salt</a>, a NaCl library for PHP. The modification basically
consists on a change on the hash function used at the cryto_sign methods. You can find it <a href="https://github.com/jaimehgb/Salt">here</a>.
It's already included in this repo.
</p>
