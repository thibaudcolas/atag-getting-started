# [Your project] vX.Y ATAG 2.0 audit

- Author: [Your name]
- Created: [Date]
- Last Modified: [Date]
- Product: [Your project] vX.Y

## Audit findings overview

At the success criteria level as per the [W3C ATAG report tool](https://www.w3.org/WAI/atag/report-tool/), pass/fail:

| Conformance Level | Total | Part A | Part B |
| ----------------- | ----- | ------ | ------ |
| Pass              |       |        |        |
| Fail              |       |        |        |
| Not applicable    |       |        |        |

### [A. Make the authoring tool user interface accessible](#a-make-the-authoring-tool-user-interface-accessible)

- [A.1. Authoring tool user interfaces follow applicable accessibility guidelines](#a1-authoring-tool-user-interfaces-follow-applicable-accessibility-guidelines)
  - **\[Conformance\]**: [A.1.1. (For the authoring tool user interface) Ensure that web-based functionality is accessible](#a11-for-the-authoring-tool-user-interface-ensure-that-web-based-functionality-is-accessible)
    - **\[Conformance\]**: [A.1.1.1 Web-Based Accessible (WCAG)](#a111-web-based-accessible-wcag) (Level A / AA / AAA)
  - **\[Conformance\]**: [A.1.2. (For the authoring tool user interface) Ensure that non-web-based functionality is accessible](#a12-for-the-authoring-tool-user-interface-ensure-that-non-web-based-functionality-is-accessible)
    - **\[Conformance\]**: [A.1.2.1 Accessibility Guidelines](#a121-accessibility-guidelines) (Level A)
    - **\[Conformance\]**: [A.1.2.2 Platform Accessibility Services](#a122-platform-accessibility-services) (Level A)
- [A.2. Editing-views are perceivable](#a2-editing-views-are-perceivable)
  - **\[Conformance\]**: [A.2.1. (For the authoring tool user interface) Make alternative content available to authors](#a21-for-the-authoring-tool-user-interface-make-alternative-content-available-to-authors)
    - **\[Conformance\]**: [A.2.1.1 Text Alternatives for Rendered Non-Text Content](#a211-text-alternatives-for-rendered-non-text-content) (Level A)
    - **\[Conformance\]**: [A.2.1.2 Alternatives for Rendered Time-Based Media](#a212-alternatives-for-rendered-time-based-media) (Level A)
  - **\[Conformance\]**: [A.2.2. (For the authoring tool user interface) Ensure that editing-view presentation can be programmatically determined](#a22-for-the-authoring-tool-user-interface-ensure-that-editing-view-presentation-can-be-programmatically-determined)
    - **\[Conformance\]**: [A.2.2.1 Editing-View Status Indicators](#a221-editing-view-status-indicators) (Level A)
    - **\[Conformance\]**: [A.2.2.2 Access to Rendered Text Properties](#a222-access-to-rendered-text-properties) (Level AA)
- [A.3. Editing-views are operable](#a3-editing-views-are-operable)
  - **\[Conformance\]**: [A.3.1. (For the authoring tool user interface) Provide keyboard access to authoring features](#a31-for-the-authoring-tool-user-interface-provide-keyboard-access-to-authoring-features)
    - **\[Conformance\]**: [A.3.1.1 Keyboard Access (Minimum)](#a311-keyboard-access-minimum) (Level A)
    - **\[Conformance\]**: [A.3.1.2 No Keyboard Traps](#a312-no-keyboard-traps) (Level A)
    - **\[Conformance\]**: [A.3.1.3 Efficient Keyboard Access](#a313-efficient-keyboard-access) (Level AA)
    - **\[Conformance\]**: [A.3.1.4 Keyboard Access (Enhanced)](#a314-keyboard-access-enhanced) (Level AAA)
    - **\[Conformance\]**: [A.3.1.5 Customize Keyboard Access](#a315-customize-keyboard-access) (Level AAA)
    - **\[Conformance\]**: [A.3.1.6 Present Keyboard Commands](#a316-present-keyboard-commands) (Level AAA)
  - **\[Conformance\]**: [A.3.2. (For the authoring tool user interface) Provide authors with enough time](#a32-for-the-authoring-tool-user-interface-provide-authors-with-enough-time)
    - **\[Conformance\]**: [A.3.2.1 Auto-Save (Minimum)](#a321-auto-save-minimum) (Level A)
    - **\[Conformance\]**: [A.3.2.2 Timing Adjustable](#a322-timing-adjustable) (Level A)
    - **\[Conformance\]**: [A.3.2.3 Static Input Components](#a323-static-input-components) (Level A)
    - **\[Conformance\]**: [A.3.2.4 Content Edits Saved (Extended)](#a324-content-edits-saved-extended) (Level AAA)
  - **\[Conformance\]**: [A.3.3. (For the authoring tool user interface) Help authors avoid flashing that could cause seizures](#a33-for-the-authoring-tool-user-interface-help-authors-avoid-flashing-that-could-cause-seizures)
    - **\[Conformance\]**: [A.3.3.1 Static View Option](#a331-static-view-option) (Level A)
  - **\[Conformance\]**: [A.3.4. (For the authoring tool user interface) Enhance navigation and editing via content structure](#a34-for-the-authoring-tool-user-interface-enhance-navigation-and-editing-via-content-structure)
    - **\[Conformance\]**: [A.3.4.1 Navigate By Structure](#a341-navigate-by-structure) (Level AA)
    - **\[Conformance\]**: [A.3.4.2 Navigate by Programmatic Relationships](#a342-navigate-by-programmatic-relationships) (Level AAA)
  - **\[Conformance\]**: [A.3.5. (For the authoring tool user interface) Provide text search of the content](#a35-for-the-authoring-tool-user-interface-provide-text-search-of-the-content)
    - **\[Conformance\]**: [A.3.5.1 Text Search](#a351-text-search) (Level AA)
  - **\[Conformance\]**: [A.3.6. (For the authoring tool user interface) Manage preference settings](#a36-for-the-authoring-tool-user-interface-manage-preference-settings)
    - **\[Conformance\]**: [A.3.6.1 Independence of Display](#a361-independence-of-display) (Level A)
    - **\[Conformance\]**: [A.3.6.2 Save Settings](#a362-save-settings) (Level AA)
    - **\[Conformance\]**: [A.3.6.3 Apply Platform Settings](#a363-apply-platform-settings) (Level AA)
  - **\[Conformance\]**: [A.3.7. (For the authoring tool user interface) Ensure that previews are at least as accessible as in-market user agents](#a37-for-the-authoring-tool-user-interface-ensure-that-previews-are-at-least-as-accessible-as-in-market-user-agents)
    - **\[Conformance\]**: [A.3.7.1 Preview (Minimum)](#a371-preview-minimum) (Level A)
    - **\[Conformance\]**: [A.3.7.2 Preview (Enhanced)](#a372-preview-enhanced) (Level AAA)
- [A.4. Editing-views are understandable](#a4-editing-views-are-understandable)
  - **\[Conformance\]**: [A.4.1. (For the authoring tool user interface) Help authors avoid and correct mistakes](#a41-for-the-authoring-tool-user-interface-help-authors-avoid-and-correct-mistakes)
    - **\[Conformance\]**: [A.4.1.1 Content Changes Reversible (Minimum)](#a411-content-changes-reversible-minimum) (Level A)
    - **\[Conformance\]**: [A.4.1.2 Settings Change Confirmation](#a412-settings-change-confirmation) (Level A)
    - **\[Conformance\]**: [A.4.1.3 Content Changes Reversible (Enhanced)](#a413-content-changes-reversible-enhanced) (Level AAA)
  - **\[Conformance\]**: [A.4.2. (For the authoring tool user interface) Document the user interface, including all accessibility features](#a42-for-the-authoring-tool-user-interface-document-the-user-interface-including-all-accessibility-features)
    - **\[Conformance\]**: [A.4.2.1 Describe Accessibility Features](#a421-describe-accessibility-features) (Level A)
    - **\[Conformance\]**: [A.4.2.2 Document All Features](#a422-document-all-features) (Level AA)

### [B. Support the production of accessible content](#b-support-the-production-of-accessible-content)

- [B.1. Fully automatic processes produce accessible content](#b1-fully-automatic-processes-produce-accessible-content)
  - **\[Conformance\]**: [B.1.1. Ensure that automatically-specified content is accessible](#b11-ensure-that-automatically-specified-content-is-accessible)
    - **\[Conformance\]**: [B.1.1.1 Content Auto-Generation After Authoring Sessions (WCAG)](#b111-content-auto-generation-after-authoring-sessions-wcag) (Level A / AA / AAA)
    - **\[Conformance\]**: [B.1.1.2 Content Auto-Generation During Authoring Sessions (WCAG)](#b112-content-auto-generation-during-authoring-sessions-wcag) (Level A / AA / AAA)
  - **\[Conformance\]**: [B.1.2. Ensure that accessibility information is preserved](#b12-ensure-that-accessibility-information-is-preserved)
    - **\[Conformance\]**: [B.1.2.1 Restructuring and Recoding Transformations (WCAG)](#b121-restructuring-and-recoding-transformations-wcag) (Level A / AA / AAA)
    - **\[Conformance\]**: [B.1.2.2 Copy-Paste Inside Authoring Tool (WCAG)](#b122-copy-paste-inside-authoring-tool-wcag) (Level A / AA / AAA)
    - **\[Conformance\]**: [B.1.2.3 Optimizations Preserve Accessibility](#b123-optimizations-preserve-accessibility) (Level A)
    - **\[Conformance\]**: [B.1.2.4 Text Alternatives for Non-Text Content are Preserved](#b124-text-alternatives-for-non-text-content-are-preserved) (Level A)
- [B.2. Authors are supported in producing accessible content](#b2-authors-are-supported-in-producing-accessible-content)
  - **\[Conformance\]**: [B.2.1. Ensure that accessible content production is possible](#b21-ensure-that-accessible-content-production-is-possible)
    - **\[Conformance\]**: [B.2.1.1 Accessible Content Possible (WCAG)](#b211-accessible-content-possible-wcag) (Level A / AA / AAA)
  - **\[Conformance\]**: [B.2.2. Guide authors to produce accessible content](#b22-guide-authors-to-produce-accessible-content)
    - **\[Conformance\]**: [B.2.2.1 Accessible Option Prominence (WCAG)](#b221-accessible-option-prominence-wcag) (Level A / AA / AAA)
    - **\[Conformance\]**: [B.2.2.2 Setting Accessibility Properties (WCAG)](#b222-setting-accessibility-properties-wcag) (Level A / AA / AAA)
  - **\[Conformance\]**: [B.2.3. Assist authors with managing alternative content for non-text content](#b23-assist-authors-with-managing-alternative-content-for-non-text-content)
    - **\[Conformance\]**: [B.2.3.1 Alternative Content is Editable (WCAG)](#b231-alternative-content-is-editable-wcag) (Level A / AA / AAA)
    - **\[Conformance\]**: [B.2.3.2 Automating Repair of Text Alternatives](#b232-automating-repair-of-text-alternatives) (Level A)
    - **\[Conformance\]**: [B.2.3.3 Save for Reuse](#b233-save-for-reuse) (Level AAA)
  - **\[Conformance\]**: [B.2.4. Assist authors with accessible templates](#b24-assist-authors-with-accessible-templates)
    - **\[Conformance\]**: [B.2.4.1 Accessible Template Options (WCAG)](#b241-accessible-template-options-wcag) (Level A / AA / AAA)
    - **\[Conformance\]**: [B.2.4.2 Identify Template Accessibility](#b242-identify-template-accessibility) (Level AA)
    - **\[Conformance\]**: [B.2.4.3 Author-Created Templates](#b243-author-created-templates) (Level AA)
    - **\[Conformance\]**: [B.2.4.4 Accessible Template Options (Enhanced)](#b244-accessible-template-options-enhanced) (Level AAA)
  - **\[Conformance\]**: [B.2.5. Assist authors with accessible pre-authored content](#b25-assist-authors-with-accessible-pre-authored-content)
    - **\[Conformance\]**: [B.2.5.1 Accessible Pre-Authored Content Options](#b251-accessible-pre-authored-content-options) (Level AA)
    - **\[Conformance\]**: [B.2.5.2 Identify Pre-Authored Content Accessibility](#b252-identify-pre-authored-content-accessibility) (Level AA)
- [B.3. Authors are supported in improving the accessibility of existing content](#b3-authors-are-supported-in-improving-the-accessibility-of-existing-content)
  - **\[Conformance\]**: [B.3.1. Assist authors in checking for accessibility problems](#b31-assist-authors-in-checking-for-accessibility-problems)
    - **\[Conformance\]**: [B.3.1.1 Checking Assistance (WCAG)](#b311-checking-assistance-wcag) (Level A / AA / AAA)
    - **\[Conformance\]**: [B.3.1.2 Help Authors Decide](#b312-help-authors-decide) (Level A)
    - **\[Conformance\]**: [B.3.1.3 Help Authors Locate](#b313-help-authors-locate) (Level A)
    - **\[Conformance\]**: [B.3.1.4 Status Report](#b314-status-report) (Level AA)
    - **\[Conformance\]**: [B.3.1.5 Programmatic Association of Results](#b315-programmatic-association-of-results) (Level AA)
  - **\[Conformance\]**: [B.3.2. Assist authors in repairing accessibility problems](#b32-assist-authors-in-repairing-accessibility-problems)
    - **\[Conformance\]**: [B.3.2.1 Repair Assistance (WCAG)](#b321-repair-assistance-wcag) (Level A / AA / AAA)
- [B.4. Authoring tools promote and integrate their accessibility features](#b4-authoring-tools-promote-and-integrate-their-accessibility-features)
  - **\[Conformance\]**: [B.4.1. Ensure the availability of features that support the production of accessible content](#b41-ensure-the-availability-of-features-that-support-the-production-of-accessible-content)
    - **\[Conformance\]**: [B.4.1.1 Features Active by Default](#b411-features-active-by-default) (Level A)
    - **\[Conformance\]**: [B.4.1.2 Option to Reactivate Features](#b412-option-to-reactivate-features) (Level A)
    - **\[Conformance\]**: [B.4.1.3 Feature Deactivation Warning](#b413-feature-deactivation-warning) (Level AA)
    - **\[Conformance\]**: [B.4.1.4 Feature Prominence](#b414-feature-prominence) (Level AA)
  - **\[Conformance\]**: [B.4.2. Ensure that documentation promotes the production of accessible content](#b42-ensure-that-documentation-promotes-the-production-of-accessible-content)
    - **\[Conformance\]**: [B.4.2.1 Model Practice (WCAG)](#b421-model-practice-wcag) (Level A / AA / AAA)
    - **\[Conformance\]**: [B.4.2.2 Feature Instructions](#b422-feature-instructions) (Level A)
    - **\[Conformance\]**: [B.4.2.3 Tutorial](#b423-tutorial) (Level AAA)
    - **\[Conformance\]**: [B.4.2.4 Instruction Index](#b424-instruction-index) (Level AAA)

## [A. Make the authoring tool user interface accessible](https://www.w3.org/TR/ATAG20/#part_a)

### [A.1. Authoring tool user interfaces follow applicable accessibility guidelines](https://www.w3.org/TR/ATAG20/#principle_a1)

#### [A.1.1. (For the authoring tool user interface) Ensure that web-based functionality is accessible](https://www.w3.org/TR/ATAG20/#gl_a11)

See [Implementing A.1.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a11).

##### A.1.1.1 Web-Based Accessible (WCAG)

> (Level A / AA / AAA). See [Implementing A.1.1.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a111).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

Suggested next steps:

References:

#### [A.1.2. (For the authoring tool user interface) Ensure that non-web-based functionality is accessible](https://www.w3.org/TR/ATAG20/#gl_a12)

See [Implementing A.1.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a12).

##### A.1.2.1 Accessibility Guidelines

> (Level A). See [Implementing A.1.2.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a121).

**\[Conformance\]**.

##### A.1.2.2 Platform Accessibility Services

> (Level A). See [Implementing A.1.2.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a122).

**\[Conformance\]**.

### [A.2. Editing-views are perceivable](https://www.w3.org/TR/ATAG20/#principle_a2)

#### [A.2.1. (For the authoring tool user interface) Make alternative content available to authors](https://www.w3.org/TR/ATAG20/#gl_a21)

See [Implementing A.2.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a21).

##### A.2.1.1 Text Alternatives for Rendered Non-Text Content

> (Level A). See [Implementing A.2.1.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a211).

**\[Conformance\]**.

##### A.2.1.2 Alternatives for Rendered Time-Based Media

> (Level A). See [Implementing A.2.1.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a212).

**\[Conformance\]**.

#### [A.2.2. (For the authoring tool user interface) Ensure that editing-view presentation can be programmatically determined](https://www.w3.org/TR/ATAG20/#gl_a22)

See [Implementing A.2.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a22).

##### A.2.2.1 Editing-View Status Indicators

> (Level A). See [Implementing A.2.2.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a221).

**\[Conformance\]**.

##### A.2.2.2 Access to Rendered Text Properties

> (Level AA). See [Implementing A.2.2.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a222).

**\[Conformance\]**.

### [A.3. Editing-views are operable](https://www.w3.org/TR/ATAG20/#principle_a3)

#### [A.3.1. (For the authoring tool user interface) Provide keyboard access to authoring features](https://www.w3.org/TR/ATAG20/#gl_a31)

See [Implementing A.3.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a31).

##### A.3.1.1 Keyboard Access (Minimum)

> (Level A). See [Implementing A.3.1.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a311).

**\[Conformance\]**.

##### A.3.1.2 No Keyboard Traps

> (Level A). See [Implementing A.3.1.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a312).

**\[Conformance\]**.

##### A.3.1.3 Efficient Keyboard Access

> (Level AA). See [Implementing A.3.1.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a313).

**\[Conformance\]**.

##### A.3.1.4 Keyboard Access (Enhanced)

> (Level AAA). See [Implementing A.3.1.4](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a314).

**\[Conformance\]**.

##### A.3.1.5 Customize Keyboard Access

> (Level AAA). See [Implementing A.3.1.5](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a315).

**\[Conformance\]**.

Proposed actions:

##### A.3.1.6 Present Keyboard Commands

> (Level AAA). See [Implementing A.3.1.6](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a316).

**\[Conformance\]**.

Proposed actions:

#### [A.3.2. (For the authoring tool user interface) Provide authors with enough time](https://www.w3.org/TR/ATAG20/#gl_a32)

See [Implementing A.3.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a32).

##### A.3.2.1 Auto-Save (Minimum)

> (Level A). See [Implementing A.3.2.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a321).

**\[Conformance\]**.

##### A.3.2.2 Timing Adjustable

> (Level A). See [Implementing A.3.2.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a322).

**\[Conformance\]**.

##### A.3.2.3 Static Input Components

> (Level A). See [Implementing A.3.2.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a323).

**\[Conformance\]**.

##### A.3.2.4 Content Edits Saved (Extended)

> (Level AAA). See [Implementing A.3.2.4](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a324).

**\[Conformance\]**.

#### [A.3.3. (For the authoring tool user interface) Help authors avoid flashing that could cause seizures](https://www.w3.org/TR/ATAG20/#gl_a33)

See [Implementing A.3.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a33).

##### A.3.3.1 Static View Option

> (Level A). See [Implementing A.3.3.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a331).

**\[Conformance\]**.

Proposed actions:

#### [A.3.4. (For the authoring tool user interface) Enhance navigation and editing via content structure](https://www.w3.org/TR/ATAG20/#gl_a34)

See [Implementing A.3.4](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a34).

##### A.3.4.1 Navigate By Structure

> (Level AA). See [Implementing A.3.4.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a341).

**\[Conformance\]**.

##### A.3.4.2 Navigate by Programmatic Relationships

> (Level AAA). See [Implementing A.3.4.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a342).

**\[Conformance\]**.

#### [A.3.5. (For the authoring tool user interface) Provide text search of the content](https://www.w3.org/TR/ATAG20/#gl_a35)

See [Implementing A.3.5](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a35).

##### A.3.5.1 Text Search

> (Level AA). See [Implementing A.3.5.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a351).

**\[Conformance\]**.

Proposed actions:

#### [A.3.6. (For the authoring tool user interface) Manage preference settings](https://www.w3.org/TR/ATAG20/#gl_a36)

See [Implementing A.3.6](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a36).

##### A.3.6.1 Independence of Display

> (Level A). See [Implementing A.3.6.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a361).

**\[Conformance\]**.

##### A.3.6.2 Save Settings

> (Level AA). See [Implementing A.3.6.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a362).

**\[Conformance\]**.

##### A.3.6.3 Apply Platform Settings

> (Level AA). See [Implementing A.3.6.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a363).

**\[Conformance\]**.

#### [A.3.7. (For the authoring tool user interface) Ensure that previews are at least as accessible as in-market user agents](https://www.w3.org/TR/ATAG20/#gl_a37)

See [Implementing A.3.7](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a37).

##### A.3.7.1 Preview (Minimum)

> (Level A). See [Implementing A.3.7.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a371).

**\[Conformance\]**.

##### A.3.7.2 Preview (Enhanced)

> (Level AAA). See [Implementing A.3.7.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a372).

**\[Conformance\]**.

### [A.4. Editing-views are understandable](https://www.w3.org/TR/ATAG20/#principle_a4)

#### [A.4.1. (For the authoring tool user interface) Help authors avoid and correct mistakes](https://www.w3.org/TR/ATAG20/#gl_a41)

See [Implementing A.4.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a41).

##### A.4.1.1 Content Changes Reversible (Minimum)

> (Level A). See [Implementing A.4.1.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a411).

**\[Conformance\]**.

The following actions are not reversible but do require confirmation to proceed:

The following actions are not reversible and do not require confirmation to proceed:

##### A.4.1.2 Settings Change Confirmation

> (Level A). See [Implementing A.4.1.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a412).

**\[Conformance\]**.

Recommendations:

##### A.4.1.3 Content Changes Reversible (Enhanced)

> (Level AAA). See [Implementing A.4.1.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a413).

**\[Conformance\]**.

#### [A.4.2. (For the authoring tool user interface) Document the user interface, including all accessibility features](https://www.w3.org/TR/ATAG20/#gl_a42)

See [Implementing A.4.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_a42).

##### A.4.2.1 Describe Accessibility Features

> (Level A). See [Implementing A.4.2.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a421).

**\[Conformance\]**.

The following functionality is described in the user interface:

The following functionality is described in the documentation:

The following functionality is provided by the underlying platform:

##### A.4.2.2 Document All Features

> (Level AA). See [Implementing A.4.2.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_a422).

**\[Conformance\]**.

| Functionality | Documented? |
| ------------- | ----------- |
|               | Partial     |
|               | Yes         |
|               | No          |

## [B. Support the production of accessible content](https://www.w3.org/TR/ATAG20/#part_b)

### [B.1. Fully automatic processes produce accessible content](https://www.w3.org/TR/ATAG20/#principle_b1)

#### [B.1.1. Ensure that automatically-specified content is accessible](https://www.w3.org/TR/ATAG20/#gl_b11)

See [Implementing B.1.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_b11).

##### B.1.1.1 Content Auto-Generation After Authoring Sessions (WCAG)

> (Level A / AA / AAA). See [Implementing B.1.1.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b111).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

##### B.1.1.2 Content Auto-Generation During Authoring Sessions (WCAG)

> (Level A / AA / AAA). See [Implementing B.1.1.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b112).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

Proposed actions:

#### [B.1.2. Ensure that accessibility information is preserved](https://www.w3.org/TR/ATAG20/#gl_b12)

See [Implementing B.1.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_b12).

##### B.1.2.1 Restructuring and Recoding Transformations (WCAG)

> (Level A / AA / AAA). See [Implementing B.1.2.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b121).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

##### B.1.2.2 Copy-Paste Inside Authoring Tool (WCAG)

> (Level A / AA / AAA). See [Implementing B.1.2.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b122).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

##### B.1.2.3 Optimizations Preserve Accessibility

> (Level A). See [Implementing B.1.2.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b123).

**\[Conformance\]**.

##### B.1.2.4 Text Alternatives for Non-Text Content are Preserved

> (Level A). See [Implementing B.1.2.4](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b124).

**\[Conformance\]**.

### [B.2. Authors are supported in producing accessible content](https://www.w3.org/TR/ATAG20/#principle_b2)

#### [B.2.1. Ensure that accessible content production is possible](https://www.w3.org/TR/ATAG20/#gl_b21)

See [Implementing B.2.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_b21).

##### B.2.1.1 Accessible Content Possible (WCAG)

> (Level A / AA / AAA). See [Implementing B.2.1.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b211).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

Proposed actions:

#### [B.2.2. Guide authors to produce accessible content](https://www.w3.org/TR/ATAG20/#gl_b22)

See [Implementing B.2.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_b22).

##### B.2.2.1 Accessible Option Prominence (WCAG)

> (Level A / AA / AAA). See [Implementing B.2.2.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b221).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

##### B.2.2.2 Setting Accessibility Properties (WCAG)

> (Level A / AA / AAA). See [Implementing B.2.2.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b222).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

#### [B.2.3. Assist authors with managing alternative content for non-text content](https://www.w3.org/TR/ATAG20/#gl_b23)

See [Implementing B.2.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_b23).

##### B.2.3.1 Alternative Content is Editable (WCAG)

> (Level A / AA / AAA). See [Implementing B.2.3.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b231).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

##### B.2.3.2 Automating Repair of Text Alternatives

> (Level A). See [Implementing B.2.3.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b232).

**\[Conformance\]**.

##### B.2.3.3 Save for Reuse

> (Level AAA). See [Implementing B.2.3.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b233).

**\[Conformance\]**.

Suggested action:

#### [B.2.4. Assist authors with accessible templates](https://www.w3.org/TR/ATAG20/#gl_b24)

See [Implementing B.2.4](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_b24).

##### B.2.4.1 Accessible Template Options (WCAG)

> (Level A / AA / AAA). See [Implementing B.2.4.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b241).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

| Template | Accessibility issues |
| -------- | -------------------- |
|          |                      |

Proposed actions:

##### B.2.4.2 Identify Template Accessibility

> (Level AA). See [Implementing B.2.4.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b242).

**\[Conformance\]**.

##### B.2.4.3 Author-Created Templates

> (Level AA). See [Implementing B.2.4.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b243).

**\[Conformance\]**.

##### B.2.4.4 Accessible Template Options (Enhanced)

> (Level AAA). See [Implementing B.2.4.4](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b244).

**\[Conformance\]**.

#### [B.2.5. Assist authors with accessible pre-authored content](https://www.w3.org/TR/ATAG20/#gl_b25)

See [Implementing B.2.5](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_b25).

##### B.2.5.1 Accessible Pre-Authored Content Options

> (Level AA). See [Implementing B.2.5.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b251).

**\[Conformance\]**.

##### B.2.5.2 Identify Pre-Authored Content Accessibility

> (Level AA). See [Implementing B.2.5.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b252).

**\[Conformance\]**.

### [B.3. Authors are supported in improving the accessibility of existing content](https://www.w3.org/TR/ATAG20/#principle_b3)

#### [B.3.1. Assist authors in checking for accessibility problems](https://www.w3.org/TR/ATAG20/#gl_b31)

See [Implementing B.3.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_b31).

##### B.3.1.1 Checking Assistance (WCAG)

> (Level A / AA / AAA). See [Implementing B.3.1.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b311).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

Proposed actions:

##### B.3.1.2 Help Authors Decide

> (Level A). See [Implementing B.3.1.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b312).

**\[Conformance\]**.

##### B.3.1.3 Help Authors Locate

> (Level A). See [Implementing B.3.1.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b313).

**\[Conformance\]**.

##### B.3.1.4 Status Report

> (Level AA). See [Implementing B.3.1.4](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b314).

**\[Conformance\]**.

Possible improvements:

##### B.3.1.5 Programmatic Association of Results

> (Level AA). See [Implementing B.3.1.5](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b315).

**\[Conformance\]**.

Possible resolution:

#### [B.3.2. Assist authors in repairing accessibility problems](https://www.w3.org/TR/ATAG20/#gl_b32)

See [Implementing B.2.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_b32).

##### B.3.2.1 Repair Assistance (WCAG)

> (Level A / AA / AAA). See [Implementing B.3.2.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b321).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

Proposed improvements:

### [B.4. Authoring tools promote and integrate their accessibility features](https://www.w3.org/TR/ATAG20/#principle_b4)

#### [B.4.1. Ensure the availability of features that support the production of accessible content](https://www.w3.org/TR/ATAG20/#gl_b41)

See [Implementing B.4.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_b41).

##### B.4.1.1 Features Active by Default

> (Level A). See [Implementing B.4.1.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b411).

**\[Conformance\]**.

##### B.4.1.2 Option to Reactivate Features

> (Level A). See [Implementing B.4.1.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b412).

**\[Conformance\]**.

##### B.4.1.3 Feature Deactivation Warning

> (Level AA). See [Implementing B.4.1.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b413).

**\[Conformance\]**.

##### B.4.1.4 Feature Prominence

> (Level AA). See [Implementing B.4.1.4](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b414).

**\[Conformance\]**.

#### [B.4.2. Ensure that documentation promotes the production of accessible content](https://www.w3.org/TR/ATAG20/#gl_b42)

See [Implementing B.4.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#gl_b42).

##### B.4.2.1 Model Practice (WCAG)

> (Level A / AA / AAA). See [Implementing B.4.2.1](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b421).

**\[Conformance\]**. Evaluated as: **Level \[A/AA/AAA\]**.

Proposed actions:

##### B.4.2.2 Feature Instructions

> (Level A). See [Implementing B.4.2.2](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b422).

**\[Conformance\]**.

Proposed actions:

##### B.4.2.3 Tutorial

> (Level AAA). See [Implementing B.4.2.3](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b423).

**\[Conformance\]**.

Proposed actions:

##### B.4.2.4 Instruction Index

> (Level AAA). See [Implementing B.4.2.4](http://www.w3.org/TR/2015/NOTE-IMPLEMENTING-ATAG20-20150924/#sc_b424).

**\[Conformance\]**.

Proposed actions:

---

[ATAG Wagtail template](https://github.com/thibaudcolas/atag-getting-started/blob/main/atag_wagtail_template.md) by [Thibaud Colas](https://thib.me/) is marked with [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/?ref=chooser-v1).
