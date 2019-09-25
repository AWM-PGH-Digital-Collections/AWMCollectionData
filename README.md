# AWMCollectionData - A public, downloadable csv file of The Andy Warhol Museum's collection data.

## Welcome to the Andy Warhol Musuem's Collection Data Set! In an attempt to make our collection accessible, to adhere to current trends regarding Open Access, and to aid researchers and art enthusiasts who are interested in our collection, we are making our collection data public and downloadable as a csv file.

## In this repository, you will find data that pertains to all accessioned objects in our collection, a description of the data, and some guidelines on using the data. Please take a minute to familiarize yourself with the structure and guidelines below.

Your feedback and input is always welcome. If you’ve got questions or suggestions, please send them to us with “AWM Dataset” in the subject header of your [email](mailto:womackb@warhol.org).

# Data Structure
This data release includes nearly all accessioned works in our database. It contains basic data for each work.

The data is released as a CSV dump. Please note that both the CSV may contain newlines (\n) within any text field, and they often appear within the provenance, medium and credit_line fields.

| Header |   Type   |   Description   |   Example    |
|----------|:---------:|:----------:|:----------:|
| Title | String | The main title that identifies the object or artwork. | Judith Green |
| Dated | String | The human readable date of creation for the object. Note that this is a string and may not be a valid date. | 1963 |
| Medium | Memo | Material of which this object/artwork is made. | acrylic and silkscreen ink on linen |
| Object Number | String | This is the number assigned by the museum when it takes official ownership of an object. | 1998.1.72 |
| Object ID | Number | A unique string that identifies the record of the object in the collections database. | 4825 |
| Credit Line | Memo | Identifies and gives credit to the person, foundation, or method by which the object was acquired. | The Andy Warhol Museum, Pittsburgh; Founding Collection, Contribution The Andy Warhol Foundation for the Visual Arts, Inc. |
| On View | Number | 0 = no, 1 = yes | 0 |
| Description | Memo | A physcial description of the object. | Painting. Black silkscreen ink on bright orange acrylic paint on linen. Portrait of a woman (Judith Green) with dark hair, facing the viewer, smiling, mouth open, head tilted to the right, wearing a turtleneck. Not signed or dated on recto.  Verso unexamined (backing board). |
| Provenance | Memo | The ownership history of an object/artwork.  | Estate of Andy Warhol; The Andy Warhol Foundation for the Visual Arts |
| Classification | String | The name of a group to which the work belongs within the museum's classification scheme, based on similar characteristics. | Paintings |
| Constituents | String | Describes a person’s association with this object | Andy Warhol (artist), Judith Green (depicted) |
| Last Name | String | Last Name of the artist/creator. | Warhol |
| First Name| String | First Name of the artist/creator. | Andy |
| Role | String | Describes a person’s involvement with this object. | Primary Maker|
| Culture Group | String | The nationality of the artist/creator.| American |
| CatRais | String | Warhol catalogue raisonné number| 497 |

# Usage Guidelines
The dataset contains the data and metadata of approximately ???? objects in the collection of The Andy Warhol Museum in Pittsburgh, PA, USA. We are providing this data without restrictions for all to enjoy. We've got a few guidelines, but we've worked hard to make this dataset as open and explorable as possible. There are a few limitations: At present, primary artist birth and death dates are not included. These dates are not seperate data fields in our collections management system. Warhol's Time Capsules are not included in this data set.

Please contact us if you have any questions.

# Lack of Images in the Data Set
Images are not covered under the same license as the dataset.

If you would like to license images of artworks in AWM’s collection, please contact the [Rights and Reproduction Department](mailto:rights@warhol.org).

# Dataset Integrity
Collections data is provided for the purposes of exploration, education, experimentation, and fun, but it is to be used at your own risk.

Please be aware that the dataset may contain incomplete data and/or errors. AWM staff does not guarantee or provide curatorial approval for these records.

At AWM, research is always ongoing, and so our understanding of these objects and their metadata are subject to change. This dataset will be updated on a regular basis to reflect our current best understanding of the objects. You are advised to use, or update to, the most current version of the dataset for best accuracy.

If you have identified errors in the dataset, or have additional information to add, we welcome your feedback! [Please contact us](mailto:womackb@warhol.org).

Thanks!

# Pull Requests
Please note that we will not accept pull requests for the data in this repository. If you have corrections, please [email](mailto:womackb@warhol.org) them to us and we will forward them to the appropriate department for correction and inclusion in a future release. 

# Attribution
Our dataset is being offered under [CC0 1.0 Universal license](https://creativecommons.org/publicdomain/zero/1.0/).

We respectfully ask that you acknowledge AWM as a source wherever possible, in order to preserve a link to the dataset. By providing acknowledgement or citation, you enable others to verify, replicate, and further explore your presentation and interpretation of our data.

# No Endorsement/Representation
Use of this dataset does not grant or imply AWM’s approval, commission, or support of your work. AWM retains the rights to all of its trademarks, and they are not part of the dataset. If you transform or modify the dataset, you must clearly distinguish the resulting work as having been modified from the AWM dataset. If you create a derivative dataset from the AWM dataset, we ask that you consider releasing the derivative under a CC0 license, which mirrors the licensing of the AWM dataset.

# Acknowledgement
The Warhol owes a debt to our sister institution, [CMOA](https://cmoa.org/), and to the [MoMA](https://www.moma.org/), [Tate](https://www.tate.org.uk/), and [Cooper Hewitt Museum](https://www.cooperhewitt.org/) for setting the example of how to make a large data collection open and accessible to the public in the most straightforward way possible.
