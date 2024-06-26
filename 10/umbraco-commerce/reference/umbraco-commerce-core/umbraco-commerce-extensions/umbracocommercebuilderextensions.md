---
title: UmbracoCommerceBuilderExtensions
description: API reference for UmbracoCommerceBuilderExtensions in Umbraco Commerce
---
## UmbracoCommerceBuilderExtensions

```csharp
public static class UmbracoCommerceBuilderExtensions
```

**Namespace**
* [Umbraco.Commerce.Extensions](README.md)

### Methods

#### WithAmountAdjusters

```csharp
public static AmountAdjusterCollectionBuilder WithAmountAdjusters(
    this IUmbracoCommerceBuilder builder)
```


---

#### WithDomainEvent&lt;TEvent&gt;

```csharp
public static UmbracoCommerceEventHandlerComposer<TEvent, IDomainEvent> WithDomainEvent<TEvent>(
    this IUmbracoCommerceBuilder builder)
    where TEvent : IDomainEvent
```


---

#### WithNotificationEvent&lt;TEvent&gt;

```csharp
public static UmbracoCommerceEventHandlerComposer<TEvent, INotificationEvent> 
    WithNotificationEvent<TEvent>(this IUmbracoCommerceBuilder builder)
    where TEvent : INotificationEvent
```


---

#### WithOrderFinders

```csharp
public static OrderFinderCollectionBuilder WithOrderFinders(this IUmbracoCommerceBuilder builder)
```


---

#### WithPipeline&lt;TCollection,TItem&gt;

```csharp
public static PipelineTaskCollectionBuilder<TCollection, TItem> WithPipeline<TCollection, TItem>(
    this IUmbracoCommerceBuilder builder)
    where TCollection : class, IPipelineTaskCollection<TItem>
```


---

#### WithPriceAdjusters

```csharp
public static PriceAdjusterCollectionBuilder WithPriceAdjusters(
    this IUmbracoCommerceBuilder builder)
```


---

#### WithRegisteredCustomerInfoProviders

```csharp
public static RegisteredCustomerInfoProviderCollectionBuilder WithRegisteredCustomerInfoProviders(
    this IUmbracoCommerceBuilder builder)
```


---

#### WithValidationEvent&lt;TEvent&gt;

```csharp
public static UmbracoCommerceEventHandlerComposer<TEvent, IValidationEvent> 
    WithValidationEvent<TEvent>(this IUmbracoCommerceBuilder builder)
    where TEvent : IValidationEvent
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
