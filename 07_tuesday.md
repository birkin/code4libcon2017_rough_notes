### Andreas Orphanides

right kind of wrongness is what makes a model useful (re g.box)

systems are models of reality

'things are what they are reported to be' - gall

shane snow on prisons

gossamer condor, british prize -- key: quick iteration

lessons

- ensure system's framing... addresses correct issues?

    - take care in what's measured; it may improve, but possibly in isolation from overall goals

- assess system goals against real-world outcomes

- data is a model, too (it too is a model for what it represents)

    - compass system

Make systems introspective -- build in assessment

---
---

- hyrax
    - [sufia](http://sufia.io/about/managers/) ([code](https://github.com/projecthydra/sufia)) &
    - [curationconcerns](https://github.com/projecthydra-labs/hydra-vagrant/wiki/Dive-Into-Curation-Concerns) gems

- [Hyku](https://github.com/projecthydra-labs/hyku): the hydra-in-a-box repository
    - aws or ilk, or local install
    - multi-tenant

- [ArchiveSpace](http://archivesspace.org) -- opensource archives managent system (from archivist toolkin and Archon)
    - rails-based
    - me: what's the difference (in space or technically) between AS & [archivematica](https://www.archivematica.org/en/) ([archivematica code](https://github.com/artefactual/archivematica))
        - archivematica is a tool for making packages (metadata re object, rights, etc) for ingestion into whatever

- Archivematica -- connecting to hydra and archivespace
    - archivematica first -- then passed (archivespace)
    - archivematica last -- first into repo then enhanced (islandora)

    - projects
        - hydra york/hull
            - METS reader/Writer (mets to json for processing, and allowing the data to be reused in hydra)
            - DIP can be more easily used as the basis for a repository object which will be ingested for discovery & delivery (not hydra specific)
        - archivespace integration -- appraisal tab in archivematica
            - archivists can make appraisal decisions within archivematica before sending it to archivespace
            - can specify that certain images should be associated with specific archivespace 'collection?'
            - can add descriptive and rights metadata
        - rockefeller archive center
            - to apply premis rights to individual objects by including a csv file in the transfer, rather than having all the objects in the transfer inherit the same specified rights

