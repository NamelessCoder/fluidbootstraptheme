# Fluid Theme for Twitter Bootstrap
===

[![Build Status](https://travis-ci.org/bootstraptheme-for-typo3/fluidbootstraptheme.png?branch=master)](https://travis-ci.org/bootstraptheme-for-typo3/fluidbootstraptheme)


## Please notice before you update to Version 2.0 

This Version contains breaking changes!!

## What is it

A collection of Twitter Bootstrap oriented Fluid Content Elements and Page Templates written and `EXT:fluidpages` using ViewHelpers from `EXT:vhs`.
It uses `EXT:flux`

===

## What does it do?

Provides the template files and TypoScript setup necessary to use the included elements and pages.

===

## How does it do it?

By leveraging the integration logic provided by `EXT:fluidpages` - enabling use of specially constructed Fluid templates as
content elements, much like the Flexible Content Elements concept from TemplaVoila.

===

## How to install it?

Download, install the extension and include the static TypoScript template in your Roottemplate. The included templates must be at least:

* CSS Styled Content (css_styled_content)
* Bootstrap Theme (fluidbootstraptheme)

===

## Dependencies

FluidBootstrapTheme now has a stable release on the TYPO3 Extension Repository (TER). If you use our Development branch FluidBootstrapTheme should also work with all the Development releases of the following dependencies.
<ul>
<li><code>EXT:flux</code></li>
<li><code>EXT:vhs</code></li>
<li><code>EXT:fluidpages</code></li>
</ul>

You can get extensions at http://www.github.com/FluidTypo3

===

## How is it used?

After installation and inclusion of the static TypoScript, the included content elements and will be available as new content element
types and page layouts when inserting new content or creating new pages.

When inserted, each content element contains a special panel with configuration specifying how to render the content element. So do the pages.
After installation and inclusion of the static TypoScript configuration, a new group of templates is added to the page template
selection boxes in page properties - configurable with a page template to use for all subpages, just like TemplaVoila.

===


## References

* https://github.com/FluidTYPO3/fluidpages is a dependency - it is the integration necessary to render Fluid Page Templates
* https://github.com/FluidTYPO3/vhs is dependency providing many ViewHelpers used in the Fluid Content Element and Page templates
* https://github.com/FluidTYPO3/flux is a dependency and is used to configure how the content template variable are defined.

===

## Some Screenshots
**Pagetemplates:**

![image](http://snag.gy/9FHKC.jpg)

===
**Content Elements:**

![image](http://snag.gy/CF1Ro.jpg)

===
**Grids:**
![image](http://snag.gy/CRPuk.jpg)
