---
id: evmscript_EVMScriptRegistry
title: EVMScriptRegistry
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> EVMScriptRegistry</h2><p class="base-contracts"><span>is</span> <a href="evmscript_IEVMScriptRegistry.html">IEVMScriptRegistry</a><span>, </span><a href="evmscript_IEVMScriptRegistry_EVMScriptRegistryConstants.html">EVMScriptRegistryConstants</a><span>, </span><a href="apps_AragonApp.html">AragonApp</a></p><div class="source">Source: <a href="https://github.com/aragon/aragonOS//blob/v3.1.4/contracts/evmscript/EVMScriptRegistry.sol" target="_blank">evmscript/EVMScriptRegistry.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="evmscript_EVMScriptRegistry.html#addScriptExecutor">addScriptExecutor</a></li><li><a href="evmscript_EVMScriptRegistry.html#disableScriptExecutor">disableScriptExecutor</a></li><li><a href="evmscript_EVMScriptRegistry.html#getScriptExecutor">getScriptExecutor</a></li><li><a href="evmscript_EVMScriptRegistry.html#initialize">initialize</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="addScriptExecutor" class="anchor-marker"></span><h4 class="name">addScriptExecutor</h4><div class="body"><code class="signature">function <strong>addScriptExecutor</strong><span>(address _executor) </span><span>external </span><span>returns  (uint) </span></code><hr/><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd><a href="apps_AragonApp.html#auth">auth </a></dd><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_executor</code> - address</div></dd><dt><span class="label-return">Returns:</span></dt><dd>uint</dd></dl></div></div></li><li><div class="item function"><span id="disableScriptExecutor" class="anchor-marker"></span><h4 class="name">disableScriptExecutor</h4><div class="body"><code class="signature">function <strong>disableScriptExecutor</strong><span>(uint256 _executorId) </span><span>external </span></code><hr/><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd><a href="apps_AragonApp.html#auth">auth </a></dd><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_executorId</code> - uint256</div></dd></dl></div></div></li><li><div class="item function"><span id="getScriptExecutor" class="anchor-marker"></span><h4 class="name">getScriptExecutor</h4><div class="body"><code class="signature">function <strong>getScriptExecutor</strong><span>(bytes _script) </span><span>public </span><span>view </span><span>returns  (address) </span></code><hr/><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_script</code> - bytes</div></dd><dt><span class="label-return">Returns:</span></dt><dd>address</dd></dl></div></div></li><li><div class="item function"><span id="initialize" class="anchor-marker"></span><h4 class="name">initialize</h4><div class="body"><code class="signature">function <strong>initialize</strong><span>() </span><span>public </span></code><hr/><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd><a href="common_Initializable.html#onlyInit">onlyInit </a></dd></dl></div></div></li></ul></div></div></div>