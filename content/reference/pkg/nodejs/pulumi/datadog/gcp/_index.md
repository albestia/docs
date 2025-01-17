---
title: Module gcp
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

<a href="../">@pulumi/datadog</a> &gt; gcp

<div class="toggleVisible">
<div class="collapsed">
<h2 class="pdoc-module-header toggleButton" title="Click to show Index">Index ▹</h2>
</div>
<div class="expanded">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Index">Index ▾</h2>
<div class="pdoc-module-contents">
<ul>
<li><a href="#Integration">class Integration</a></li>
<li><a href="#IntegrationArgs">interface IntegrationArgs</a></li>
<li><a href="#IntegrationState">interface IntegrationState</a></li>
</ul>

<a href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts">gcp/integration.ts</a> 
</div>
</div>
</div>


<h2 class="pdoc-module-header" id="Integration">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L30">class <b>Integration</b></a>
</h2>
<div class="pdoc-module-contents">
<pre class="highlight"><span class='kd'>extends</span> <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></pre>
{{% md %}}

Provides a Datadog - Google Cloud Platform integration resource. This can be used to create and manage Datadog - Google Cloud Platform integration.

## Example Usage

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as datadog from "@pulumi/datadog";

// Create a new Datadog - Google Cloud Platform integration
const awesomeGcpProjectIntegration = new datadog.gcp.Integration("awesome_gcp_project_integration", {
    clientEmail: "awesome-service-account@awesome-project-id.iam.gserviceaccount.com",
    clientId: "123456789012345678901",
    hostFilters: "foo:bar,buzz:lightyear",
    privateKey: `-----BEGIN PRIVATE KEY-----
...
-----END PRIVATE KEY-----
`,
    privateKeyId: "1234567890123456789012345678901234567890",
    projectId: "awesome-project-id",
});
```

{{% /md %}}
<h3 class="pdoc-member-header" id="Integration-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L80"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> Integration(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#IntegrationArgs'>IntegrationArgs</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a Integration resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Integration-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L39">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#IntegrationState'>IntegrationState</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Integration'>Integration</a></pre>


Get an existing Integration resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Integration-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L19">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Integration-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L50">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>public static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of Integration.  This is designed to work even
when multiple copies of the Pulumi SDK have been loaded into the same process.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Integration-clientEmail">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L60">property <b>clientEmail</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>clientEmail: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your email found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Integration-clientId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L64">property <b>clientId</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>clientId: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your ID found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Integration-hostFilters">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L68">property <b>hostFilters</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>hostFilters: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span>&gt;;</pre>
{{% md %}}

Limit the GCE instances that are pulled into Datadog by using tags. Only hosts that match one of the defined tags are imported into Datadog.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Integration-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L187">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</pre>
{{% md %}}

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Integration-privateKey">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L72">property <b>privateKey</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>privateKey: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your private key name found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Integration-privateKeyId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L76">property <b>privateKeyId</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>privateKeyId: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your private key ID found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Integration-projectId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L80">property <b>projectId</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>projectId: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your Google Cloud project ID found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Integration-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L17">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>urn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</pre>
{{% md %}}

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="IntegrationArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L161">interface <b>IntegrationArgs</b></a>
</h2>
<div class="pdoc-module-contents">
{{% md %}}

The set of arguments for constructing a Integration resource.

{{% /md %}}
<h3 class="pdoc-member-header" id="IntegrationArgs-clientEmail">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L165">property <b>clientEmail</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>clientEmail: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your email found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="IntegrationArgs-clientId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L169">property <b>clientId</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>clientId: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your ID found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="IntegrationArgs-hostFilters">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L173">property <b>hostFilters</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>hostFilters?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Limit the GCE instances that are pulled into Datadog by using tags. Only hosts that match one of the defined tags are imported into Datadog.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="IntegrationArgs-privateKey">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L177">property <b>privateKey</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>privateKey: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your private key name found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="IntegrationArgs-privateKeyId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L181">property <b>privateKeyId</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>privateKeyId: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your private key ID found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="IntegrationArgs-projectId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L185">property <b>projectId</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>projectId: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your Google Cloud project ID found in your JSON service account key.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="IntegrationState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L131">interface <b>IntegrationState</b></a>
</h2>
<div class="pdoc-module-contents">
{{% md %}}

Input properties used for looking up and filtering Integration resources.

{{% /md %}}
<h3 class="pdoc-member-header" id="IntegrationState-clientEmail">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L135">property <b>clientEmail</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>clientEmail?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your email found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="IntegrationState-clientId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L139">property <b>clientId</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>clientId?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your ID found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="IntegrationState-hostFilters">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L143">property <b>hostFilters</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>hostFilters?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Limit the GCE instances that are pulled into Datadog by using tags. Only hosts that match one of the defined tags are imported into Datadog.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="IntegrationState-privateKey">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L147">property <b>privateKey</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>privateKey?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your private key name found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="IntegrationState-privateKeyId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L151">property <b>privateKeyId</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>privateKeyId?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your private key ID found in your JSON service account key.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="IntegrationState-projectId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-datadog/blob/ee0b22ff3ee86cb0297490ffcfa8073a78a90062/sdk/nodejs/gcp/integration.ts#L155">property <b>projectId</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>projectId?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

Your Google Cloud project ID found in your JSON service account key.

{{% /md %}}
</div>
</div>
