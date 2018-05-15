---
id: version-0.0.4-application_management_PackagedAppManager
title: PackagedAppManager
original_id: application_management_PackagedAppManager
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> PackagedAppManager</h2><p class="base-contracts"><span>is</span> <a href="application_management_BaseAppManager.html">BaseAppManager</a></p><p class="description">Standard entry point for an upgradeable user app.</p><div class="source">Source: <a href="git+https://github.com/zeppelinos/zos-lib/blob/v0.1.12/contracts/application/management/PackagedAppManager.sol" target="_blank">application/management/PackagedAppManager.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="application_management_PackagedAppManager.html#PackagedAppManager">PackagedAppManager</a></li><li><a href="application_management_PackagedAppManager.html#getProvider">getProvider</a></li><li><a href="application_management_PackagedAppManager.html#setVersion">setVersion</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="PackagedAppManager" class="anchor-marker"></span><h4 class="name">PackagedAppManager</h4><div class="body"><code class="signature">function <strong>PackagedAppManager</strong><span>(Package _package, string _version, UpgradeabilityProxyFactory _factory) </span><span>public </span></code><hr/><div class="description"><p>Constructor function.</p></div><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd></dd><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>_package</code> - Package that stores the contract implementation addresses</div><div><code>_version</code> - string</div><div><code>_factory</code> - Proxy factory</div></dd></dl></div></div></li><li><div class="item function"><span id="getProvider" class="anchor-marker"></span><h4 class="name">getProvider</h4><div class="body"><code class="signature">function <strong>getProvider</strong><span>() </span><span>internal </span><span>view </span><span>returns  (ImplementationProvider) </span></code><hr/><dl><dt><span class="label-return">Returns:</span></dt><dd>Implementation provider for the current version</dd></dl></div></div></li><li><div class="item function"><span id="setVersion" class="anchor-marker"></span><h4 class="name">setVersion</h4><div class="body"><code class="signature">function <strong>setVersion</strong><span>(string newVersion) </span><span>public </span></code><hr/><div class="description"><p>Contract implementations for the given version must already be registered in the package.</p></div><dl><dt><span class="label-modifiers">Modifiers:</span></dt><dd><a href="ity_contracts_ownership_Ownable.html#onlyOwner">onlyOwner </a></dd><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>newVersion</code> - Name of the new version</div></dd></dl></div></div></li></ul></div></div></div>