# MCMinelab Web — engineering notes

## Platform domains

The application separates public studio / product content, editorial documentation, authenticated accounts, product access and private administration. Next.js and React provide the web layer, with TypeScript across the application.

## Content and product journey

Public product pages connect the catalogue to edition information, checkout, documentation and downloads. MDX supports guides and documentation. Prisma / MySQL stores application data, Better Auth handles account workflows, Stripe provides checkout and R2 holds digital files delivered through controlled access.

## Migration context

The second-generation application replaces a former WordPress website. The migration work covers the site's content and routes as well as product and account workflows. This case study describes the replacement platform rather than publishing the old site archive or internal migration runbooks.

## Design implementation

Self-hosted typography and reusable interface components keep the studio identity consistent across editorial pages, product information and account flows. Creator credits remain part of the portfolio presentation.

## Contribution scope

Public issues can document website defects, navigation problems or feature proposals. ModernHDV plugin behavior belongs in the product's tracker. Source changes, private administration and customer account investigations are handled outside this public repository.

<p><a href="../README.md"><img src="../assets/link-overview.svg" width="160" alt="Back to project overview" /></a></p>
