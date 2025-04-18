
---
title: "getGetPrivateDnsZoneSuffixExecute"
title_tag: "azure-native.dbformysql.getGetPrivateDnsZoneSuffixExecute"
meta_desc: "Documentation for the azure-native.dbformysql.getGetPrivateDnsZoneSuffixExecute function with examples, input properties, output properties, and supporting types."
layout: api
no_edit_this_page: true
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

Get private DNS zone suffix in the cloud.

Azure REST API version: 2024-10-01-preview.

Other available API versions: 2022-01-01, 2022-09-30-preview, 2023-06-01-preview, 2023-06-30, 2023-12-01-preview, 2023-12-30.

These versions are not included in the SDK but you can generate them as a local SDK package; see the [version guide](../../../version-guide/#accessing-any-api-version-via-local-packages) for details.




## Using getGetPrivateDnsZoneSuffixExecute {#using}

Two invocation forms are available. The direct form accepts plain
arguments and either blocks until the result value is available, or
returns a Promise-wrapped result. The output form accepts
Input-wrapped arguments and returns an Output-wrapped result.

<div>
<pulumi-chooser type="language" options="csharp,go,typescript,python,yaml,java"></pulumi-chooser>
</div>


<div>
<pulumi-choosable type="language" values="javascript,typescript">
<div class="highlight"
><pre class="chroma"><code class="language-typescript" data-lang="typescript"
><span class="k">function </span>getGetPrivateDnsZoneSuffixExecute<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx">GetGetPrivateDnsZoneSuffixExecuteArgs</span><span class="p">,</span> <span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx"><a href="#result">GetGetPrivateDnsZoneSuffixExecuteResult</a></span>></span
><span class="k">
function </span>getGetPrivateDnsZoneSuffixExecuteOutput<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx">GetGetPrivateDnsZoneSuffixExecuteOutputArgs</span><span class="p">,</span> <span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Output&lt;<span class="nx"><a href="#result">GetGetPrivateDnsZoneSuffixExecuteResult</a></span>></span
></code></pre></div>
</pulumi-choosable>
</div>


<div>
<pulumi-choosable type="language" values="python">
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"
><span class="k">def </span>get_get_private_dns_zone_suffix_execute<span class="p">(</span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> <span>GetGetPrivateDnsZoneSuffixExecuteResult</span
><span class="k">
def </span>get_get_private_dns_zone_suffix_execute_output<span class="p">(</span><span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> <span>Output[GetGetPrivateDnsZoneSuffixExecuteResult]</span
></code></pre></div>
</pulumi-choosable>
</div>


<div>
<pulumi-choosable type="language" values="go">
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"
><span class="k">func </span>GetGetPrivateDnsZoneSuffixExecute<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#Context">Context</a></span><span class="p">,</span> <span class="nx">args</span><span class="p"> *</span><span class="nx">GetGetPrivateDnsZoneSuffixExecuteArgs</span><span class="p">,</span> <span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx"><a href="#result">GetGetPrivateDnsZoneSuffixExecuteResult</a></span>, error)</span
><span class="k">
func </span>GetGetPrivateDnsZoneSuffixExecuteOutput<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#Context">Context</a></span><span class="p">,</span> <span class="nx">args</span><span class="p"> *</span><span class="nx">GetGetPrivateDnsZoneSuffixExecuteOutputArgs</span><span class="p">,</span> <span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) GetGetPrivateDnsZoneSuffixExecuteResultOutput</span
></code></pre></div>

&gt; Note: This function is named `GetGetPrivateDnsZoneSuffixExecute` in the Go SDK.

</pulumi-choosable>
</div>


<div>
<pulumi-choosable type="language" values="csharp">
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">GetGetPrivateDnsZoneSuffixExecute </span><span class="p">
{</span><span class="k">
    public static </span>Task&lt;<span class="nx"><a href="#result">GetGetPrivateDnsZoneSuffixExecuteResult</a></span>> <span class="p">InvokeAsync(</span><span class="nx">GetGetPrivateDnsZoneSuffixExecuteArgs</span><span class="p"> </span><span class="nx">args<span class="p">,</span> <span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="k">
    public static </span>Output&lt;<span class="nx"><a href="#result">GetGetPrivateDnsZoneSuffixExecuteResult</a></span>> <span class="p">Invoke(</span><span class="nx">GetGetPrivateDnsZoneSuffixExecuteInvokeArgs</span><span class="p"> </span><span class="nx">args<span class="p">,</span> <span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
</pulumi-choosable>
</div>


<div>
<pulumi-choosable type="language" values="java">
<div class="highlight"><pre class="chroma"><code class="language-java" data-lang="java"><span class="k">public static CompletableFuture&lt;<span class="nx"><a href="#result">GetGetPrivateDnsZoneSuffixExecuteResult</a></span>> </span>getGetPrivateDnsZoneSuffixExecute<span class="p">(</span><span class="nx">GetGetPrivateDnsZoneSuffixExecuteArgs</span><span class="p"> </span><span class="nx">args<span class="p">,</span> <span class="nx">InvokeOptions</span><span class="p"> </span><span class="nx">options<span class="p">)</span>
<span class="k">public static Output&lt;<span class="nx"><a href="#result">GetGetPrivateDnsZoneSuffixExecuteResult</a></span>> </span>getGetPrivateDnsZoneSuffixExecute<span class="p">(</span><span class="nx">GetGetPrivateDnsZoneSuffixExecuteArgs</span><span class="p"> </span><span class="nx">args<span class="p">,</span> <span class="nx">InvokeOptions</span><span class="p"> </span><span class="nx">options<span class="p">)</span>
</code></pre></div>
</pulumi-choosable>
</div>


<div>
<pulumi-choosable type="language" values="yaml">
<div class="highlight"><pre class="chroma"><code class="language-yaml" data-lang="yaml"><span class="k">fn::invoke:</span>
<span class="k">&nbsp;&nbsp;function:</span> azure-native:dbformysql:getGetPrivateDnsZoneSuffixExecute
<span class="k">&nbsp;&nbsp;arguments:</span>
<span class="c">&nbsp;&nbsp;&nbsp;&nbsp;# arguments dictionary</span></code></pre></div>
</pulumi-choosable>
</div>



The following arguments are supported:


<div>
<pulumi-choosable type="language" values="csharp">
<dl class="resources-properties"></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="go">
<dl class="resources-properties"></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="java">
<dl class="resources-properties"></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="javascript,typescript">
<dl class="resources-properties"></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="python">
<dl class="resources-properties"></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="yaml">
<dl class="resources-properties"></dl>
</pulumi-choosable>
</div>




## getGetPrivateDnsZoneSuffixExecute Result {#result}

The following output properties are available:



<div>
<pulumi-choosable type="language" values="csharp">
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="privatednszonesuffix_csharp">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#privatednszonesuffix_csharp" style="color: inherit; text-decoration: inherit;">Private<wbr>Dns<wbr>Zone<wbr>Suffix</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Represents the private DNS zone suffix.</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="go">
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="privatednszonesuffix_go">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#privatednszonesuffix_go" style="color: inherit; text-decoration: inherit;">Private<wbr>Dns<wbr>Zone<wbr>Suffix</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Represents the private DNS zone suffix.</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="java">
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="privatednszonesuffix_java">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#privatednszonesuffix_java" style="color: inherit; text-decoration: inherit;">private<wbr>Dns<wbr>Zone<wbr>Suffix</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>Represents the private DNS zone suffix.</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="javascript,typescript">
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="privatednszonesuffix_nodejs">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#privatednszonesuffix_nodejs" style="color: inherit; text-decoration: inherit;">private<wbr>Dns<wbr>Zone<wbr>Suffix</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Represents the private DNS zone suffix.</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="python">
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="private_dns_zone_suffix_python">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#private_dns_zone_suffix_python" style="color: inherit; text-decoration: inherit;">private_<wbr>dns_<wbr>zone_<wbr>suffix</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>Represents the private DNS zone suffix.</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="yaml">
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="privatednszonesuffix_yaml">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#privatednszonesuffix_yaml" style="color: inherit; text-decoration: inherit;">private<wbr>Dns<wbr>Zone<wbr>Suffix</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>Represents the private DNS zone suffix.</dd></dl>
</pulumi-choosable>
</div>





<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-azure-native">Azure Native pulumi/pulumi-azure-native</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
</dl>

