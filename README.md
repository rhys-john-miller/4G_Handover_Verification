<!DOCTYPE html>
<html lang="en">
    <head>
        <!-- Required meta tags -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

        <!-- Bootstrap CSS -->
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/css/bootstrap.min.css" integrity="sha384-/Y6pD6FV/Vv2HJnA6t+vslU6fwYXjCFtcEpHbNJ0lyAFsXTsjBbfaDjzALeQsN6M" crossorigin="anonymous">

        <link href="https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/2.8.0/github-markdown.min.css" rel="stylesheet" type="text/css" />

        <link href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/9.12.0/styles/github.min.css" rel="stylesheet" type="text/css" />
        <link href="https://use.fontawesome.com/releases/v5.0.6/css/all.css" rel="stylesheet">
<script data-ad-client="ca-pub-3773134145653736" async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
        <link href="/static/css/style.css" rel="stylesheet" type="text/css" />
    </head>
    <body>
        <div class="main">
            <div class="container-fluid">
                <div class="paths">
                    
                    
                    <span class="path"><a href="/repository/6162390d-f50b-4716-ada1-4c519d400067">Root</a></span>
                
                </div>
                <div class="files">
                    
                    <div class="tree ">
                        <a href="/repository/6162390d-f50b-4716-ada1-4c519d400067/Figures/">
                            Figures
                        </a>
                    </div>
                    
                    <div class="blob active">
                        <a href="/repository/6162390d-f50b-4716-ada1-4c519d400067/README.md">
                            README.md
                        </a>
                    </div>
                    
                    <div class="tree ">
                        <a href="/repository/6162390d-f50b-4716-ada1-4c519d400067/S1/">
                            S1
                        </a>
                    </div>
                    
                    <div class="tree ">
                        <a href="/repository/6162390d-f50b-4716-ada1-4c519d400067/X2/">
                            X2
                        </a>
                    </div>
                    
               </div>
                
                <div class='markdown-body'><h1>
<a id="user-content-4g_handover_verification" class="anchor" href="#4g_handover_verification" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>4G_Handover_Verification</h1>
<p>This repository is a for the formal verification files of the 4G handover procedures of X2 and S1.</p>
<h2>
<a id="user-content-x2-file-structure" class="anchor" href="#x2-file-structure" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>X2 File Structure</h2>
<p>The X2 folder contains the following proverif files:</p>
<ul>
<li>X2.pv</li>
<li>X2patched.pv</li>
</ul>
<p>The files above contain a main process with just one session of the following entities: UE, source Node, target Node and MME. The "X2.pv" file encodes the original X2 protocol and the "X2patched.pv" file encodes our new, secure version of X2. </p>
<ul>
<li>X2_ndevices.pv</li>
<li>X2_ndevices_patched.pv</li>
</ul>
<p>The files above contain a main process with multiple entities UE, source Node, target Node and MME, adn/or multiple sessions thereof. The "X2_ndevices.pv" file encodes the original X2 protocol and the "X2_ndevices_patched.pv" file encodes our new, secure version of X2, in this setting. </p>
<ul>
<li>X2_forwardSecrecy.pv</li>
</ul>
<h2>
<a id="user-content-s1-file-structure" class="anchor" href="#s1-file-structure" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>S1 File Structure</h2>
<p>The S1 folder contains the following proverif files:</p>
<ul>
<li>S1.pv</li>
<li>S1patched.pv</li>
</ul>
<p>The files above contain a main process with just one session of the following entities: UE, source Node, target Node and MME. The "S1.pv" file encodes the original S1 protocol and the "S1patched.pv" file encodes our new, secure version of S1. </p>
<ul>
<li>S1_ndevices.pv</li>
<li>S1_ndevices_patched.pv</li>
</ul>
<p>The files above contain a main process with multiple entities UE, source Node, target Node and MME, adn/or multiple sessions thereof. The "S1_ndevices.pv" file encodes the original S1 protocol and the "S1_ndevices_patched.pv" file encodes our new, secure version of S1, in this setting. </p>
<h2>
<a id="user-content-traces" class="anchor" href="#traces" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Traces</h2>
<p>This folder contains some exemple of  traces for the attacks we found on these LTE handover protocols.</p>
<h2>
<a id="user-content-submission" class="anchor" href="#submission" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Submission</h2>
<p>These files are in support of a paper being submitted to a conference.</p>
</div>
                
            </div>
        </div>

        <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js" integrity="sha384-b/U6ypiBEHpOf/4+1nzFpr53nxSS+GLCkfwBdFNTxtclqqenISfwAzpKaMNFNmj4" crossorigin="anonymous"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/js/bootstrap.min.js" integrity="sha384-h0AbiXch4ZDo7tp9hKZ4TsHbi047NrKGLO3SEJAg45jXxnGIfYzk4Si90RDIqNm1" crossorigin="anonymous"></script>

        <script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/9.12.0/highlight.min.js" crossorigin="anonymous"></script>
        <script>hljs.initHighlightingOnLoad();</script>
        <script>
        (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script','//ana.durieux.me/analytics.js','ga');
ga('provide', 'adblockTracker', function(tracker, opts) {

  var xhr = new XMLHttpRequest(),
      method = "GET",
      url = "//ana.durieux.me/advertisement.js";
  try {
    xhr.open(method, url, false);
    xhr.send();
    ga('set', 'dimension' + opts.dimensionIndex, xhr.responseText != "var canRunAds=true;");
  } catch {
    ga('set', 'dimension' + opts.dimensionIndex, xhr.responseText != "var canRunAds=true;");
  }
});
ga('create', 'UA-5954162-28', 'auto');
ga('require', 'adblockTracker', {dimensionIndex: 1});
ga('require', 'ipMeta', {
      apiKey: '24dfe248bf92983106e37a0e5faeeb70f45bbd8891f8d94c23b59365d5f2b269',
      serviceProvider: 'dimension2',
      networkDomain: 'dimension3',
      networkType: 'dimension4',
  });
  ga('ipMeta:loadNetworkFields');
ga('send', 'pageview');
        </script>
	<script async src="https://ipmeta.io/plugin.js"></script>
    </body>
</html>
