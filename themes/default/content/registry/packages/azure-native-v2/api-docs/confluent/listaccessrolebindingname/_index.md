
---
title: "listAccessRoleBindingName"
title_tag: "azure-native.confluent.listAccessRoleBindingName"
meta_desc: "Documentation for the azure-native.confluent.listAccessRoleBindingName function with examples, input properties, output properties, and supporting types."
layout: api
no_edit_this_page: true
---



<!-- WARNING: this file was generated by Pulumi Docs Generator. -->
<!-- Do not edit by hand unless you're certain you know what you are doing! -->

Details of the role binding names returned on successful response

Azure REST API version: 2024-07-01.

Other available API versions: 2024-02-13.

These versions are not included in the SDK but you can generate them as a local SDK package; see the [version guide](../../../version-guide/#accessing-any-api-version-via-local-packages) for details.




## Using listAccessRoleBindingName {#using}

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
><span class="k">function </span>listAccessRoleBindingName<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx">ListAccessRoleBindingNameArgs</span><span class="p">,</span> <span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Promise&lt;<span class="nx"><a href="#result">ListAccessRoleBindingNameResult</a></span>></span
><span class="k">
function </span>listAccessRoleBindingNameOutput<span class="p">(</span><span class="nx">args</span><span class="p">:</span> <span class="nx">ListAccessRoleBindingNameOutputArgs</span><span class="p">,</span> <span class="nx">opts</span><span class="p">?:</span> <span class="nx"><a href="/docs/reference/pkg/nodejs/pulumi/pulumi/#InvokeOptions">InvokeOptions</a></span><span class="p">): Output&lt;<span class="nx"><a href="#result">ListAccessRoleBindingNameResult</a></span>></span
></code></pre></div>
</pulumi-choosable>
</div>


<div>
<pulumi-choosable type="language" values="python">
<div class="highlight"><pre class="chroma"><code class="language-python" data-lang="python"
><span class="k">def </span>list_access_role_binding_name<span class="p">(</span><span class="nx">organization_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">,</span>
                                  <span class="nx">resource_group_name</span><span class="p">:</span> <span class="nx">Optional[str]</span> = None<span class="p">,</span>
                                  <span class="nx">search_filters</span><span class="p">:</span> <span class="nx">Optional[Mapping[str, str]]</span> = None<span class="p">,</span>
                                  <span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> <span>ListAccessRoleBindingNameResult</span
><span class="k">
def </span>list_access_role_binding_name_output<span class="p">(</span><span class="nx">organization_name</span><span class="p">:</span> <span class="nx">Optional[pulumi.Input[str]]</span> = None<span class="p">,</span>
                                  <span class="nx">resource_group_name</span><span class="p">:</span> <span class="nx">Optional[pulumi.Input[str]]</span> = None<span class="p">,</span>
                                  <span class="nx">search_filters</span><span class="p">:</span> <span class="nx">Optional[pulumi.Input[Mapping[str, pulumi.Input[str]]]]</span> = None<span class="p">,</span>
                                  <span class="nx">opts</span><span class="p">:</span> <span class="nx"><a href="/docs/reference/pkg/python/pulumi/#pulumi.InvokeOptions">Optional[InvokeOptions]</a></span> = None<span class="p">) -&gt;</span> <span>Output[ListAccessRoleBindingNameResult]</span
></code></pre></div>
</pulumi-choosable>
</div>


<div>
<pulumi-choosable type="language" values="go">
<div class="highlight"><pre class="chroma"><code class="language-go" data-lang="go"
><span class="k">func </span>ListAccessRoleBindingName<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#Context">Context</a></span><span class="p">,</span> <span class="nx">args</span><span class="p"> *</span><span class="nx">ListAccessRoleBindingNameArgs</span><span class="p">,</span> <span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) (*<span class="nx"><a href="#result">ListAccessRoleBindingNameResult</a></span>, error)</span
><span class="k">
func </span>ListAccessRoleBindingNameOutput<span class="p">(</span><span class="nx">ctx</span><span class="p"> *</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#Context">Context</a></span><span class="p">,</span> <span class="nx">args</span><span class="p"> *</span><span class="nx">ListAccessRoleBindingNameOutputArgs</span><span class="p">,</span> <span class="nx">opts</span><span class="p"> ...</span><span class="nx"><a href="https://pkg.go.dev/github.com/pulumi/pulumi/sdk/v3/go/pulumi?tab=doc#InvokeOption">InvokeOption</a></span><span class="p">) ListAccessRoleBindingNameResultOutput</span
></code></pre></div>

&gt; Note: This function is named `ListAccessRoleBindingName` in the Go SDK.

</pulumi-choosable>
</div>


<div>
<pulumi-choosable type="language" values="csharp">
<div class="highlight"><pre class="chroma"><code class="language-csharp" data-lang="csharp"><span class="k">public static class </span><span class="nx">ListAccessRoleBindingName </span><span class="p">
{</span><span class="k">
    public static </span>Task&lt;<span class="nx"><a href="#result">ListAccessRoleBindingNameResult</a></span>> <span class="p">InvokeAsync(</span><span class="nx">ListAccessRoleBindingNameArgs</span><span class="p"> </span><span class="nx">args<span class="p">,</span> <span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="k">
    public static </span>Output&lt;<span class="nx"><a href="#result">ListAccessRoleBindingNameResult</a></span>> <span class="p">Invoke(</span><span class="nx">ListAccessRoleBindingNameInvokeArgs</span><span class="p"> </span><span class="nx">args<span class="p">,</span> <span class="nx"><a href="/docs/reference/pkg/dotnet/Pulumi/Pulumi.InvokeOptions.html">InvokeOptions</a></span><span class="p">? </span><span class="nx">opts = null<span class="p">)</span><span class="p">
}</span></code></pre></div>
</pulumi-choosable>
</div>


<div>
<pulumi-choosable type="language" values="java">
<div class="highlight"><pre class="chroma"><code class="language-java" data-lang="java"><span class="k">public static CompletableFuture&lt;<span class="nx"><a href="#result">ListAccessRoleBindingNameResult</a></span>> </span>listAccessRoleBindingName<span class="p">(</span><span class="nx">ListAccessRoleBindingNameArgs</span><span class="p"> </span><span class="nx">args<span class="p">,</span> <span class="nx">InvokeOptions</span><span class="p"> </span><span class="nx">options<span class="p">)</span>
<span class="k">public static Output&lt;<span class="nx"><a href="#result">ListAccessRoleBindingNameResult</a></span>> </span>listAccessRoleBindingName<span class="p">(</span><span class="nx">ListAccessRoleBindingNameArgs</span><span class="p"> </span><span class="nx">args<span class="p">,</span> <span class="nx">InvokeOptions</span><span class="p"> </span><span class="nx">options<span class="p">)</span>
</code></pre></div>
</pulumi-choosable>
</div>


<div>
<pulumi-choosable type="language" values="yaml">
<div class="highlight"><pre class="chroma"><code class="language-yaml" data-lang="yaml"><span class="k">fn::invoke:</span>
<span class="k">&nbsp;&nbsp;function:</span> azure-native:confluent:listAccessRoleBindingName
<span class="k">&nbsp;&nbsp;arguments:</span>
<span class="c">&nbsp;&nbsp;&nbsp;&nbsp;# arguments dictionary</span></code></pre></div>
</pulumi-choosable>
</div>



The following arguments are supported:


<div>
<pulumi-choosable type="language" values="csharp">
<dl class="resources-properties"><dt class="property-required property-replacement"
            title="Required">
        <span id="organizationname_csharp">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#organizationname_csharp" style="color: inherit; text-decoration: inherit;">Organization<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Organization resource name</dd><dt class="property-required property-replacement"
            title="Required">
        <span id="resourcegroupname_csharp">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#resourcegroupname_csharp" style="color: inherit; text-decoration: inherit;">Resource<wbr>Group<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>The name of the resource group. The name is case insensitive.</dd><dt class="property-optional"
            title="Optional">
        <span id="searchfilters_csharp">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#searchfilters_csharp" style="color: inherit; text-decoration: inherit;">Search<wbr>Filters</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Dictionary&lt;string, string&gt;</span>
    </dt>
    <dd>Search filters for the request</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="go">
<dl class="resources-properties"><dt class="property-required property-replacement"
            title="Required">
        <span id="organizationname_go">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#organizationname_go" style="color: inherit; text-decoration: inherit;">Organization<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Organization resource name</dd><dt class="property-required property-replacement"
            title="Required">
        <span id="resourcegroupname_go">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#resourcegroupname_go" style="color: inherit; text-decoration: inherit;">Resource<wbr>Group<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>The name of the resource group. The name is case insensitive.</dd><dt class="property-optional"
            title="Optional">
        <span id="searchfilters_go">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#searchfilters_go" style="color: inherit; text-decoration: inherit;">Search<wbr>Filters</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">map[string]string</span>
    </dt>
    <dd>Search filters for the request</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="java">
<dl class="resources-properties"><dt class="property-required property-replacement"
            title="Required">
        <span id="organizationname_java">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#organizationname_java" style="color: inherit; text-decoration: inherit;">organization<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>Organization resource name</dd><dt class="property-required property-replacement"
            title="Required">
        <span id="resourcegroupname_java">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#resourcegroupname_java" style="color: inherit; text-decoration: inherit;">resource<wbr>Group<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>The name of the resource group. The name is case insensitive.</dd><dt class="property-optional"
            title="Optional">
        <span id="searchfilters_java">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#searchfilters_java" style="color: inherit; text-decoration: inherit;">search<wbr>Filters</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Map&lt;String,String&gt;</span>
    </dt>
    <dd>Search filters for the request</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="javascript,typescript">
<dl class="resources-properties"><dt class="property-required property-replacement"
            title="Required">
        <span id="organizationname_nodejs">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#organizationname_nodejs" style="color: inherit; text-decoration: inherit;">organization<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Organization resource name</dd><dt class="property-required property-replacement"
            title="Required">
        <span id="resourcegroupname_nodejs">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#resourcegroupname_nodejs" style="color: inherit; text-decoration: inherit;">resource<wbr>Group<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>The name of the resource group. The name is case insensitive.</dd><dt class="property-optional"
            title="Optional">
        <span id="searchfilters_nodejs">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#searchfilters_nodejs" style="color: inherit; text-decoration: inherit;">search<wbr>Filters</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">{[key: string]: string}</span>
    </dt>
    <dd>Search filters for the request</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="python">
<dl class="resources-properties"><dt class="property-required property-replacement"
            title="Required">
        <span id="organization_name_python">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#organization_name_python" style="color: inherit; text-decoration: inherit;">organization_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>Organization resource name</dd><dt class="property-required property-replacement"
            title="Required">
        <span id="resource_group_name_python">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#resource_group_name_python" style="color: inherit; text-decoration: inherit;">resource_<wbr>group_<wbr>name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>The name of the resource group. The name is case insensitive.</dd><dt class="property-optional"
            title="Optional">
        <span id="search_filters_python">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#search_filters_python" style="color: inherit; text-decoration: inherit;">search_<wbr>filters</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Mapping[str, str]</span>
    </dt>
    <dd>Search filters for the request</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="yaml">
<dl class="resources-properties"><dt class="property-required property-replacement"
            title="Required">
        <span id="organizationname_yaml">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#organizationname_yaml" style="color: inherit; text-decoration: inherit;">organization<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>Organization resource name</dd><dt class="property-required property-replacement"
            title="Required">
        <span id="resourcegroupname_yaml">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#resourcegroupname_yaml" style="color: inherit; text-decoration: inherit;">resource<wbr>Group<wbr>Name</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>The name of the resource group. The name is case insensitive.</dd><dt class="property-optional"
            title="Optional">
        <span id="searchfilters_yaml">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#searchfilters_yaml" style="color: inherit; text-decoration: inherit;">search<wbr>Filters</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Map&lt;String&gt;</span>
    </dt>
    <dd>Search filters for the request</dd></dl>
</pulumi-choosable>
</div>




## listAccessRoleBindingName Result {#result}

The following output properties are available:



<div>
<pulumi-choosable type="language" values="csharp">
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="data_csharp">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#data_csharp" style="color: inherit; text-decoration: inherit;">Data</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">List&lt;string&gt;</span>
    </dt>
    <dd>List of role binding names</dd><dt class="property-"
            title="">
        <span id="kind_csharp">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#kind_csharp" style="color: inherit; text-decoration: inherit;">Kind</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Type of response</dd><dt class="property-"
            title="">
        <span id="metadata_csharp">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#metadata_csharp" style="color: inherit; text-decoration: inherit;">Metadata</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#confluentlistmetadataresponse">Pulumi.<wbr>Azure<wbr>Native.<wbr>Confluent.<wbr>Outputs.<wbr>Confluent<wbr>List<wbr>Metadata<wbr>Response</a></span>
    </dt>
    <dd>Metadata of the list</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="go">
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="data_go">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#data_go" style="color: inherit; text-decoration: inherit;">Data</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">[]string</span>
    </dt>
    <dd>List of role binding names</dd><dt class="property-"
            title="">
        <span id="kind_go">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#kind_go" style="color: inherit; text-decoration: inherit;">Kind</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Type of response</dd><dt class="property-"
            title="">
        <span id="metadata_go">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#metadata_go" style="color: inherit; text-decoration: inherit;">Metadata</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#confluentlistmetadataresponse">Confluent<wbr>List<wbr>Metadata<wbr>Response</a></span>
    </dt>
    <dd>Metadata of the list</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="java">
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="data_java">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#data_java" style="color: inherit; text-decoration: inherit;">data</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">List&lt;String&gt;</span>
    </dt>
    <dd>List of role binding names</dd><dt class="property-"
            title="">
        <span id="kind_java">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#kind_java" style="color: inherit; text-decoration: inherit;">kind</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>Type of response</dd><dt class="property-"
            title="">
        <span id="metadata_java">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#metadata_java" style="color: inherit; text-decoration: inherit;">metadata</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#confluentlistmetadataresponse">Confluent<wbr>List<wbr>Metadata<wbr>Response</a></span>
    </dt>
    <dd>Metadata of the list</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="javascript,typescript">
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="data_nodejs">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#data_nodejs" style="color: inherit; text-decoration: inherit;">data</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string[]</span>
    </dt>
    <dd>List of role binding names</dd><dt class="property-"
            title="">
        <span id="kind_nodejs">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#kind_nodejs" style="color: inherit; text-decoration: inherit;">kind</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Type of response</dd><dt class="property-"
            title="">
        <span id="metadata_nodejs">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#metadata_nodejs" style="color: inherit; text-decoration: inherit;">metadata</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#confluentlistmetadataresponse">Confluent<wbr>List<wbr>Metadata<wbr>Response</a></span>
    </dt>
    <dd>Metadata of the list</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="python">
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="data_python">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#data_python" style="color: inherit; text-decoration: inherit;">data</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Sequence[str]</span>
    </dt>
    <dd>List of role binding names</dd><dt class="property-"
            title="">
        <span id="kind_python">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#kind_python" style="color: inherit; text-decoration: inherit;">kind</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>Type of response</dd><dt class="property-"
            title="">
        <span id="metadata_python">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#metadata_python" style="color: inherit; text-decoration: inherit;">metadata</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#confluentlistmetadataresponse">Confluent<wbr>List<wbr>Metadata<wbr>Response</a></span>
    </dt>
    <dd>Metadata of the list</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="yaml">
<dl class="resources-properties"><dt class="property-"
            title="">
        <span id="data_yaml">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#data_yaml" style="color: inherit; text-decoration: inherit;">data</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">List&lt;String&gt;</span>
    </dt>
    <dd>List of role binding names</dd><dt class="property-"
            title="">
        <span id="kind_yaml">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#kind_yaml" style="color: inherit; text-decoration: inherit;">kind</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>Type of response</dd><dt class="property-"
            title="">
        <span id="metadata_yaml">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#metadata_yaml" style="color: inherit; text-decoration: inherit;">metadata</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type"><a href="#confluentlistmetadataresponse">Property Map</a></span>
    </dt>
    <dd>Metadata of the list</dd></dl>
</pulumi-choosable>
</div>




## Supporting Types


<h4 id="confluentlistmetadataresponse">Confluent<wbr>List<wbr>Metadata<wbr>Response</h4>



<div>
<pulumi-choosable type="language" values="csharp">
<dl class="resources-properties"><dt class="property-optional"
            title="Optional">
        <span id="first_csharp">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#first_csharp" style="color: inherit; text-decoration: inherit;">First</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>First page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="last_csharp">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#last_csharp" style="color: inherit; text-decoration: inherit;">Last</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Last page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="next_csharp">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#next_csharp" style="color: inherit; text-decoration: inherit;">Next</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Next page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="prev_csharp">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#prev_csharp" style="color: inherit; text-decoration: inherit;">Prev</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Previous page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="totalsize_csharp">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#totalsize_csharp" style="color: inherit; text-decoration: inherit;">Total<wbr>Size</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>Total size of the list</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="go">
<dl class="resources-properties"><dt class="property-optional"
            title="Optional">
        <span id="first_go">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#first_go" style="color: inherit; text-decoration: inherit;">First</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>First page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="last_go">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#last_go" style="color: inherit; text-decoration: inherit;">Last</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Last page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="next_go">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#next_go" style="color: inherit; text-decoration: inherit;">Next</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Next page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="prev_go">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#prev_go" style="color: inherit; text-decoration: inherit;">Prev</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Previous page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="totalsize_go">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#totalsize_go" style="color: inherit; text-decoration: inherit;">Total<wbr>Size</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>Total size of the list</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="java">
<dl class="resources-properties"><dt class="property-optional"
            title="Optional">
        <span id="first_java">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#first_java" style="color: inherit; text-decoration: inherit;">first</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>First page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="last_java">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#last_java" style="color: inherit; text-decoration: inherit;">last</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>Last page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="next_java">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#next_java" style="color: inherit; text-decoration: inherit;">next</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>Next page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="prev_java">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#prev_java" style="color: inherit; text-decoration: inherit;">prev</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>Previous page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="totalsize_java">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#totalsize_java" style="color: inherit; text-decoration: inherit;">total<wbr>Size</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Integer</span>
    </dt>
    <dd>Total size of the list</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="javascript,typescript">
<dl class="resources-properties"><dt class="property-optional"
            title="Optional">
        <span id="first_nodejs">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#first_nodejs" style="color: inherit; text-decoration: inherit;">first</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>First page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="last_nodejs">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#last_nodejs" style="color: inherit; text-decoration: inherit;">last</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Last page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="next_nodejs">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#next_nodejs" style="color: inherit; text-decoration: inherit;">next</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Next page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="prev_nodejs">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#prev_nodejs" style="color: inherit; text-decoration: inherit;">prev</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">string</span>
    </dt>
    <dd>Previous page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="totalsize_nodejs">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#totalsize_nodejs" style="color: inherit; text-decoration: inherit;">total<wbr>Size</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">number</span>
    </dt>
    <dd>Total size of the list</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="python">
<dl class="resources-properties"><dt class="property-optional"
            title="Optional">
        <span id="first_python">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#first_python" style="color: inherit; text-decoration: inherit;">first</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>First page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="last_python">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#last_python" style="color: inherit; text-decoration: inherit;">last</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>Last page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="next_python">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#next_python" style="color: inherit; text-decoration: inherit;">next</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>Next page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="prev_python">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#prev_python" style="color: inherit; text-decoration: inherit;">prev</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">str</span>
    </dt>
    <dd>Previous page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="total_size_python">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#total_size_python" style="color: inherit; text-decoration: inherit;">total_<wbr>size</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">int</span>
    </dt>
    <dd>Total size of the list</dd></dl>
</pulumi-choosable>
</div>

<div>
<pulumi-choosable type="language" values="yaml">
<dl class="resources-properties"><dt class="property-optional"
            title="Optional">
        <span id="first_yaml">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#first_yaml" style="color: inherit; text-decoration: inherit;">first</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>First page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="last_yaml">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#last_yaml" style="color: inherit; text-decoration: inherit;">last</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>Last page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="next_yaml">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#next_yaml" style="color: inherit; text-decoration: inherit;">next</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>Next page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="prev_yaml">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#prev_yaml" style="color: inherit; text-decoration: inherit;">prev</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">String</span>
    </dt>
    <dd>Previous page of the list</dd><dt class="property-optional"
            title="Optional">
        <span id="totalsize_yaml">
<a data-swiftype-name="resource-property" data-swiftype-type="text" href="#totalsize_yaml" style="color: inherit; text-decoration: inherit;">total<wbr>Size</a>
</span>
        <span class="property-indicator"></span>
        <span class="property-type">Number</span>
    </dt>
    <dd>Total size of the list</dd></dl>
</pulumi-choosable>
</div>





<h2 id="package-details">Package Details</h2>
<dl class="package-details">
	<dt>Repository</dt>
	<dd><a href="https://github.com/pulumi/pulumi-azure-native">Azure Native pulumi/pulumi-azure-native</a></dd>
	<dt>License</dt>
	<dd>Apache-2.0</dd>
</dl>

