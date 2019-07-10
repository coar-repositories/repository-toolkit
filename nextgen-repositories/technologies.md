# Technologies

## ResourceSync

ResourceSync is a specification based on Sitemaps that can be used by repository managers to provide information that allows third-party systems to remain in sync with the resources in their repository as they evolve, i.e. are created, updated, deleted. Whereas basic Sitemaps allow exposing a repository inventory and crawl-related metadata, ResourceSync adds ways to expose changes only, and to provide expressive synchronization-related metadata as well as typed links for further discovery. ResourceSync can be used for discovery and synchronization of both content and metadata and uses the Sitemaps XML format. [http://www.openarchives.org/rs/toc](http://www.openarchives.org/rs/toc)

{% embed url="https://blog.core.ac.uk/2018/03/17/increasing-the-speed-of-harvesting-with-on-demand-resource-dumps/" %}

Martin Klein presents "ResourceSync: A Modular Framework for Web-Based Resource Synchronization". Slides can be found at [this](http://doi.org/10.5281/zenodo.1433806) link. 

{% embed url="https://youtu.be/tfD-C\_LiQXw" %}

## Signposting

Signposting is an approach to inform machine agents about the nature of the resources that are linked from the resource they currently interact with. It uses typed links \(in the HTTP Link header, the HTML element, or the [rs:ln](rs:ln) ResourceSync element\) to reveal patterns that occur repeatedly in scholarly portals. Signposting can be used to support automatic discovery of a variety of resources that pertain to a scholarly object, including a bibliographic description, a persistent identifier, a license, authors, or various resources that are part of the object. [http://signposting.org](http://signposting.org/)

Martin Klein, Harihar Shankar and Herbert Van de Sompel introduce Signposting [in this article](https://osf.io/preprints/lissa/wzd89/), "a mechanism to show machines how to maneuver repositories' objects and how to interpret their relationships. Signpostingis based on standard and widely adopted web technologies typed links and HTTP link headers." You can also see the [poster](https://osf.io/68uxm/) at the same link as supplemental material. 

{% embed url="https://osf.io/preprints/lissa/wzd89/" %}

