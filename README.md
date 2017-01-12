# Product Pages Template

> :rotating_light: This project is **unstable** and **in development**, and should not be used in a production-grade product. :rotating_light:

## Usage

### Dependencies

You'll need to include:

- GOV.UK Frontend Toolkit
- GOV.UK Template (specifically accessibility.scss and footer.scss)
- 

## Modules

### Breadcrumbs

```
<nav class="breadcrumbs" aria-label="Breadcrumbs">
  <ol itemscope itemtype="http://schema.org/BreadcrumbList">
    <li class="breadcrumbs__item" itemprop="child" itemprop="itemListElement" itemscope itemtype="http://schema.org/ListItem">
      <a href="https://www.gov.uk/service-toolkit" itemprop="item">
        <span itemprop="name">Service Toolkit</span>
      </a>
    </li>
    <li class="breadcrumbs__item breadcrumbs__item--active" itemprop="itemListElement" itemscope itemtype="http://schema.org/ListItem">
      <a href="#main" itemprop="item">
        <span itemprop="name">Product Page</span>
      </a>
    </li>
  </ol>
</nav>
```

Notes:
- By linking the active link to the same place as the skip link, the link is still
focussable and thus included by screenreaders, but is announced as 'Product
page, same page link'.

### Content Section

### GOV.UK Logo

### Header

This is a revised version of the header from GOV.UK with an 'inlined' product
name and an improved mobile experience.

### Hero Button

### Hero

### Masthead

### Phase Banner

### Related Items

### Sub Navigation
