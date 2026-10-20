---
permalink: /v0.5.13/controlplane/v1alpha3/talosControlPlane/
---

# controlplane.v1alpha3.talosControlPlane

"TalosControlPlane is the Schema for the taloscontrolplanes API"

## Index

* [`fn new(name)`](#fn-new)
* [`obj metadata`](#obj-metadata)
  * [`fn withAnnotations(annotations)`](#fn-metadatawithannotations)
  * [`fn withAnnotationsMixin(annotations)`](#fn-metadatawithannotationsmixin)
  * [`fn withClusterName(clusterName)`](#fn-metadatawithclustername)
  * [`fn withCreationTimestamp(creationTimestamp)`](#fn-metadatawithcreationtimestamp)
  * [`fn withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)`](#fn-metadatawithdeletiongraceperiodseconds)
  * [`fn withDeletionTimestamp(deletionTimestamp)`](#fn-metadatawithdeletiontimestamp)
  * [`fn withFinalizers(finalizers)`](#fn-metadatawithfinalizers)
  * [`fn withFinalizersMixin(finalizers)`](#fn-metadatawithfinalizersmixin)
  * [`fn withGenerateName(generateName)`](#fn-metadatawithgeneratename)
  * [`fn withGeneration(generation)`](#fn-metadatawithgeneration)
  * [`fn withLabels(labels)`](#fn-metadatawithlabels)
  * [`fn withLabelsMixin(labels)`](#fn-metadatawithlabelsmixin)
  * [`fn withName(name)`](#fn-metadatawithname)
  * [`fn withNamespace(namespace)`](#fn-metadatawithnamespace)
  * [`fn withOwnerReferences(ownerReferences)`](#fn-metadatawithownerreferences)
  * [`fn withOwnerReferencesMixin(ownerReferences)`](#fn-metadatawithownerreferencesmixin)
  * [`fn withResourceVersion(resourceVersion)`](#fn-metadatawithresourceversion)
  * [`fn withSelfLink(selfLink)`](#fn-metadatawithselflink)
  * [`fn withUid(uid)`](#fn-metadatawithuid)
* [`obj spec`](#obj-spec)
  * [`fn withReplicas(replicas)`](#fn-specwithreplicas)
  * [`fn withVersion(version)`](#fn-specwithversion)
  * [`obj spec.controlPlaneConfig`](#obj-speccontrolplaneconfig)
    * [`obj spec.controlPlaneConfig.controlplane`](#obj-speccontrolplaneconfigcontrolplane)
      * [`fn withConfigPatches(configPatches)`](#fn-speccontrolplaneconfigcontrolplanewithconfigpatches)
      * [`fn withConfigPatchesMixin(configPatches)`](#fn-speccontrolplaneconfigcontrolplanewithconfigpatchesmixin)
      * [`fn withData(data)`](#fn-speccontrolplaneconfigcontrolplanewithdata)
      * [`fn withGenerateType(generateType)`](#fn-speccontrolplaneconfigcontrolplanewithgeneratetype)
      * [`fn withStrategicPatches(strategicPatches)`](#fn-speccontrolplaneconfigcontrolplanewithstrategicpatches)
      * [`fn withStrategicPatchesMixin(strategicPatches)`](#fn-speccontrolplaneconfigcontrolplanewithstrategicpatchesmixin)
      * [`fn withTalosVersion(talosVersion)`](#fn-speccontrolplaneconfigcontrolplanewithtalosversion)
      * [`obj spec.controlPlaneConfig.controlplane.configPatches`](#obj-speccontrolplaneconfigcontrolplaneconfigpatches)
        * [`fn withOp(op)`](#fn-speccontrolplaneconfigcontrolplaneconfigpatcheswithop)
        * [`fn withPath(path)`](#fn-speccontrolplaneconfigcontrolplaneconfigpatcheswithpath)
        * [`fn withValue(value)`](#fn-speccontrolplaneconfigcontrolplaneconfigpatcheswithvalue)
      * [`obj spec.controlPlaneConfig.controlplane.hostname`](#obj-speccontrolplaneconfigcontrolplanehostname)
        * [`fn withSource(source)`](#fn-speccontrolplaneconfigcontrolplanehostnamewithsource)
    * [`obj spec.controlPlaneConfig.init`](#obj-speccontrolplaneconfiginit)
      * [`fn withConfigPatches(configPatches)`](#fn-speccontrolplaneconfiginitwithconfigpatches)
      * [`fn withConfigPatchesMixin(configPatches)`](#fn-speccontrolplaneconfiginitwithconfigpatchesmixin)
      * [`fn withData(data)`](#fn-speccontrolplaneconfiginitwithdata)
      * [`fn withGenerateType(generateType)`](#fn-speccontrolplaneconfiginitwithgeneratetype)
      * [`fn withStrategicPatches(strategicPatches)`](#fn-speccontrolplaneconfiginitwithstrategicpatches)
      * [`fn withStrategicPatchesMixin(strategicPatches)`](#fn-speccontrolplaneconfiginitwithstrategicpatchesmixin)
      * [`fn withTalosVersion(talosVersion)`](#fn-speccontrolplaneconfiginitwithtalosversion)
      * [`obj spec.controlPlaneConfig.init.configPatches`](#obj-speccontrolplaneconfiginitconfigpatches)
        * [`fn withOp(op)`](#fn-speccontrolplaneconfiginitconfigpatcheswithop)
        * [`fn withPath(path)`](#fn-speccontrolplaneconfiginitconfigpatcheswithpath)
        * [`fn withValue(value)`](#fn-speccontrolplaneconfiginitconfigpatcheswithvalue)
      * [`obj spec.controlPlaneConfig.init.hostname`](#obj-speccontrolplaneconfiginithostname)
        * [`fn withSource(source)`](#fn-speccontrolplaneconfiginithostnamewithsource)
  * [`obj spec.infrastructureTemplate`](#obj-specinfrastructuretemplate)
    * [`fn withApiVersion(apiVersion)`](#fn-specinfrastructuretemplatewithapiversion)
    * [`fn withFieldPath(fieldPath)`](#fn-specinfrastructuretemplatewithfieldpath)
    * [`fn withKind(kind)`](#fn-specinfrastructuretemplatewithkind)
    * [`fn withName(name)`](#fn-specinfrastructuretemplatewithname)
    * [`fn withNamespace(namespace)`](#fn-specinfrastructuretemplatewithnamespace)
    * [`fn withResourceVersion(resourceVersion)`](#fn-specinfrastructuretemplatewithresourceversion)
    * [`fn withUid(uid)`](#fn-specinfrastructuretemplatewithuid)
  * [`obj spec.rolloutStrategy`](#obj-specrolloutstrategy)
    * [`fn withType(type)`](#fn-specrolloutstrategywithtype)
    * [`obj spec.rolloutStrategy.rollingUpdate`](#obj-specrolloutstrategyrollingupdate)
      * [`fn withMaxSurge(maxSurge)`](#fn-specrolloutstrategyrollingupdatewithmaxsurge)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of TalosControlPlane

## obj metadata

"ObjectMeta is metadata that all persisted resources must have, which includes all objects users must create."

### fn metadata.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

### fn metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

**Note:** This function appends passed data to existing values

### fn metadata.withClusterName

```ts
withClusterName(clusterName)
```

"The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request."

### fn metadata.withCreationTimestamp

```ts
withCreationTimestamp(creationTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withDeletionGracePeriodSeconds

```ts
withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)
```

"Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only."

### fn metadata.withDeletionTimestamp

```ts
withDeletionTimestamp(deletionTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withFinalizers

```ts
withFinalizers(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

### fn metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

**Note:** This function appends passed data to existing values

### fn metadata.withGenerateName

```ts
withGenerateName(generateName)
```

"GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server.\n\nIf this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header).\n\nApplied only if Name is not specified. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#idempotency"

### fn metadata.withGeneration

```ts
withGeneration(generation)
```

"A sequence number representing a specific generation of the desired state. Populated by the system. Read-only."

### fn metadata.withLabels

```ts
withLabels(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

### fn metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

**Note:** This function appends passed data to existing values

### fn metadata.withName

```ts
withName(name)
```

"Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/identifiers#names"

### fn metadata.withNamespace

```ts
withNamespace(namespace)
```

"Namespace defines the space within which each name must be unique. An empty namespace is equivalent to the \"default\" namespace, but \"default\" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty.\n\nMust be a DNS_LABEL. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/namespaces"

### fn metadata.withOwnerReferences

```ts
withOwnerReferences(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

### fn metadata.withOwnerReferencesMixin

```ts
withOwnerReferencesMixin(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

**Note:** This function appends passed data to existing values

### fn metadata.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```

"An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources.\n\nPopulated by the system. Read-only. Value must be treated as opaque by clients and . More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency"

### fn metadata.withSelfLink

```ts
withSelfLink(selfLink)
```

"SelfLink is a URL representing this object. Populated by the system. Read-only.\n\nDEPRECATED Kubernetes will stop propagating this field in 1.20 release and the field is planned to be removed in 1.21 release."

### fn metadata.withUid

```ts
withUid(uid)
```

"UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations.\n\nPopulated by the system. Read-only. More info: http://kubernetes.io/docs/user-guide/identifiers#uids"

## obj spec

"TalosControlPlaneSpec defines the desired state of TalosControlPlane"

### fn spec.withReplicas

```ts
withReplicas(replicas)
```

"Number of desired machines. Defaults to 1. When stacked etcd is used only\nodd numbers are permitted, as per [etcd best practice](https://etcd.io/docs/v3.3.12/faq/#why-an-odd-number-of-cluster-members).\nThis is a pointer to distinguish between explicit zero and not specified."

### fn spec.withVersion

```ts
withVersion(version)
```

"Version defines the desired Kubernetes version."

## obj spec.controlPlaneConfig

"ControlPlaneConfig is a two TalosConfigSpecs\nto use for initializing and joining machines to the control plane."

## obj spec.controlPlaneConfig.controlplane

"TalosConfigSpec defines the desired state of TalosConfig"

### fn spec.controlPlaneConfig.controlplane.withConfigPatches

```ts
withConfigPatches(configPatches)
```



### fn spec.controlPlaneConfig.controlplane.withConfigPatchesMixin

```ts
withConfigPatchesMixin(configPatches)
```



**Note:** This function appends passed data to existing values

### fn spec.controlPlaneConfig.controlplane.withData

```ts
withData(data)
```



### fn spec.controlPlaneConfig.controlplane.withGenerateType

```ts
withGenerateType(generateType)
```



### fn spec.controlPlaneConfig.controlplane.withStrategicPatches

```ts
withStrategicPatches(strategicPatches)
```

"Talos Linux machine configuration strategic merge patch list."

### fn spec.controlPlaneConfig.controlplane.withStrategicPatchesMixin

```ts
withStrategicPatchesMixin(strategicPatches)
```

"Talos Linux machine configuration strategic merge patch list."

**Note:** This function appends passed data to existing values

### fn spec.controlPlaneConfig.controlplane.withTalosVersion

```ts
withTalosVersion(talosVersion)
```



## obj spec.controlPlaneConfig.controlplane.configPatches



### fn spec.controlPlaneConfig.controlplane.configPatches.withOp

```ts
withOp(op)
```



### fn spec.controlPlaneConfig.controlplane.configPatches.withPath

```ts
withPath(path)
```



### fn spec.controlPlaneConfig.controlplane.configPatches.withValue

```ts
withValue(value)
```



## obj spec.controlPlaneConfig.controlplane.hostname

"Set hostname in the machine configuration to some value."

### fn spec.controlPlaneConfig.controlplane.hostname.withSource

```ts
withSource(source)
```

"Source of the hostname.\n\nAllowed values:\n\"MachineName\" (use linked Machine's Name).\n\"InfrastructureName\" (use linked Machine's infrastructure's name)."

## obj spec.controlPlaneConfig.init

"Deprecated: starting from cacppt v0.4.0 provider doesn't use init configs."

### fn spec.controlPlaneConfig.init.withConfigPatches

```ts
withConfigPatches(configPatches)
```



### fn spec.controlPlaneConfig.init.withConfigPatchesMixin

```ts
withConfigPatchesMixin(configPatches)
```



**Note:** This function appends passed data to existing values

### fn spec.controlPlaneConfig.init.withData

```ts
withData(data)
```



### fn spec.controlPlaneConfig.init.withGenerateType

```ts
withGenerateType(generateType)
```



### fn spec.controlPlaneConfig.init.withStrategicPatches

```ts
withStrategicPatches(strategicPatches)
```

"Talos Linux machine configuration strategic merge patch list."

### fn spec.controlPlaneConfig.init.withStrategicPatchesMixin

```ts
withStrategicPatchesMixin(strategicPatches)
```

"Talos Linux machine configuration strategic merge patch list."

**Note:** This function appends passed data to existing values

### fn spec.controlPlaneConfig.init.withTalosVersion

```ts
withTalosVersion(talosVersion)
```



## obj spec.controlPlaneConfig.init.configPatches



### fn spec.controlPlaneConfig.init.configPatches.withOp

```ts
withOp(op)
```



### fn spec.controlPlaneConfig.init.configPatches.withPath

```ts
withPath(path)
```



### fn spec.controlPlaneConfig.init.configPatches.withValue

```ts
withValue(value)
```



## obj spec.controlPlaneConfig.init.hostname

"Set hostname in the machine configuration to some value."

### fn spec.controlPlaneConfig.init.hostname.withSource

```ts
withSource(source)
```

"Source of the hostname.\n\nAllowed values:\n\"MachineName\" (use linked Machine's Name).\n\"InfrastructureName\" (use linked Machine's infrastructure's name)."

## obj spec.infrastructureTemplate

"InfrastructureTemplate is a required reference to a custom resource\noffered by an infrastructure provider."

### fn spec.infrastructureTemplate.withApiVersion

```ts
withApiVersion(apiVersion)
```

"API version of the referent."

### fn spec.infrastructureTemplate.withFieldPath

```ts
withFieldPath(fieldPath)
```

"If referring to a piece of an object instead of an entire object, this string\nshould contain a valid JSON/Go field access statement, such as desiredState.manifest.containers[2].\nFor example, if the object reference is to a container within a pod, this would take on a value like:\n\"spec.containers{name}\" (where \"name\" refers to the name of the container that triggered\nthe event) or if no container name is specified \"spec.containers[2]\" (container with\nindex 2 in this pod). This syntax is chosen only to have some well-defined way of\nreferencing a part of an object."

### fn spec.infrastructureTemplate.withKind

```ts
withKind(kind)
```

"Kind of the referent.\nMore info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#types-kinds"

### fn spec.infrastructureTemplate.withName

```ts
withName(name)
```

"Name of the referent.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.infrastructureTemplate.withNamespace

```ts
withNamespace(namespace)
```

"Namespace of the referent.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/"

### fn spec.infrastructureTemplate.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```

"Specific resourceVersion to which this reference is made, if any.\nMore info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency"

### fn spec.infrastructureTemplate.withUid

```ts
withUid(uid)
```

"UID of the referent.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#uids"

## obj spec.rolloutStrategy

"The RolloutStrategy to use to replace control plane machines with\nnew ones."

### fn spec.rolloutStrategy.withType

```ts
withType(type)
```

"Change rollout strategy.\n\nSupported strategies:\n * \"RollingUpdate\".\n * \"OnDelete\"\n\nDefault is RollingUpdate."

## obj spec.rolloutStrategy.rollingUpdate

"Rolling update config params. Present only if\nRolloutStrategyType = RollingUpdate."

### fn spec.rolloutStrategy.rollingUpdate.withMaxSurge

```ts
withMaxSurge(maxSurge)
```

"The maximum number of control planes that can be scheduled above or under the\ndesired number of control planes.\nValue can be an absolute number 1 or 0.\nDefaults to 1.\nExample: when this is set to 1, the control plane can be scaled\nup immediately when the rolling update starts."