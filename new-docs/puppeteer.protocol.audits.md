<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Audits](./puppeteer.protocol.audits.md)

## Protocol.Audits namespace

Audits domain allows investigation of page violations and possible improvements.

<b>Signature:</b>

```typescript
export namespace Audits 
```

## Enumerations

|  Enumeration | Description |
|  --- | --- |
|  [GetEncodedResponseRequestEncoding](./puppeteer.protocol.audits.getencodedresponserequestencoding.md) |  |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [AffectedCookie](./puppeteer.protocol.audits.affectedcookie.md) | Information about a cookie that is affected by an inspector issue. |
|  [AffectedFrame](./puppeteer.protocol.audits.affectedframe.md) | Information about the frame affected by an inspector issue. |
|  [AffectedRequest](./puppeteer.protocol.audits.affectedrequest.md) | Information about a request that is affected by an inspector issue. |
|  [BlockedByResponseIssueDetails](./puppeteer.protocol.audits.blockedbyresponseissuedetails.md) | Details for a request that has been blocked with the BLOCKED\_BY\_RESPONSE code. Currently only used for COEP/COOP, but may be extended to include some CSP errors in the future. |
|  [GetEncodedResponseRequest](./puppeteer.protocol.audits.getencodedresponserequest.md) |  |
|  [GetEncodedResponseResponse](./puppeteer.protocol.audits.getencodedresponseresponse.md) |  |
|  [HeavyAdIssueDetails](./puppeteer.protocol.audits.heavyadissuedetails.md) |  |
|  [InspectorIssue](./puppeteer.protocol.audits.inspectorissue.md) | An inspector issue reported from the back-end. |
|  [InspectorIssueDetails](./puppeteer.protocol.audits.inspectorissuedetails.md) | This struct holds a list of optional fields with additional information specific to the kind of issue. When adding a new issue code, please also add a new optional field to this type. |
|  [IssueAddedEvent](./puppeteer.protocol.audits.issueaddedevent.md) |  |
|  [MixedContentIssueDetails](./puppeteer.protocol.audits.mixedcontentissuedetails.md) |  |
|  [SameSiteCookieIssueDetails](./puppeteer.protocol.audits.samesitecookieissuedetails.md) | This information is currently necessary, as the front-end has a difficult time finding a specific cookie. With this, we can convey specific error information without the cookie. |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [BlockedByResponseReason](./puppeteer.protocol.audits.blockedbyresponsereason.md) | Enum indicating the reason a response has been blocked. These reasons are refinements of the net error BLOCKED\_BY\_RESPONSE. |
|  [HeavyAdReason](./puppeteer.protocol.audits.heavyadreason.md) |  |
|  [HeavyAdResolutionStatus](./puppeteer.protocol.audits.heavyadresolutionstatus.md) |  |
|  [InspectorIssueCode](./puppeteer.protocol.audits.inspectorissuecode.md) | A unique identifier for the type of issue. Each type may use one of the optional fields in InspectorIssueDetails to convey more specific information about the kind of issue. |
|  [MixedContentResolutionStatus](./puppeteer.protocol.audits.mixedcontentresolutionstatus.md) |  |
|  [MixedContentResourceType](./puppeteer.protocol.audits.mixedcontentresourcetype.md) |  |
|  [SameSiteCookieExclusionReason](./puppeteer.protocol.audits.samesitecookieexclusionreason.md) |  |
|  [SameSiteCookieOperation](./puppeteer.protocol.audits.samesitecookieoperation.md) |  |
|  [SameSiteCookieWarningReason](./puppeteer.protocol.audits.samesitecookiewarningreason.md) |  |

