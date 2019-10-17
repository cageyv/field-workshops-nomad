# HashiCorp Nomad Field Workshops
All HashiCorp field workshops focused on Nomad should be placed in this repository. Similar field workshop repositories exist for these HashiCorp solutions:
* [field-workshops-consul](https://github.com/hashicorp/field-workshops-consul)
* [field-workshops-terraform](https://github.com/hashicorp/field-workshops-terraform)
* [field-workshops-vault](https://github.com/hashicorp/field-workshops-terraform)

Additionally, field workshops focused on more than one HashiCorp solution can be found in the [field-workshops-hashistack](https://github.com/hashicorp/field-workshops-hashistack) repository.

## Slides
The slides for these workshops should be created using [Remark](https://remarkjs.com) and should be placed under the [docs/slides](./docs/slides) directory. This directory is organized by cloud and then by workshop.  If a workshop targets a single cloud, its slides should be placed in a directory under that cloud's directory ([aws](./docs/slides/aws), [azure](./docs/slides/azure), or [gcp](./docs/slides/gcp)). If a workshop can be used with multiple clouds, its slides should be placed in a directory under the [multi-cloud](./docs/slides/multi-cloud) directory.

## Instructor Guides
The instructor guides for these workshops should be created as Markdown files and should be placed in the [instructor-guides](./instructor-guides) directory and have names like `<cloud>_<workshop_name>_INSTRUCTOR_GUIDE.md` where `<cloud>` is the cloud the workshop targets and `<workshop_name>` is the name of the workshop. But if the workshop is intended for use with multiple clouds, `<cloud>` should be omitted.

## Labs (Instruqt Tracks)
The labs for these workshops should be created using [Instruqt Tracks](https://instruqt.com/hashicorp).  Each track should be placed in its own directory directly underneath the [instruqt-tracks](./instruqt-tracks) directory. Doing this allows each track to be used by multiple workshops within this repository.
