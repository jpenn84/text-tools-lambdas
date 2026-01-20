# Text Tools Lambdas

Text Tools Lambdas are lambda functions that perform the text alteration as defined by their individual functional areas.
While it would make more sense to use a local JS function, an API-based approach allows integration into other products.
Additioally, this is an academic exercise aimed at gaining more experience working with AWS Lambdas and serverless infrastructure in general.

## Explanation of tools

### Sarcastic Text

Sarcastic text comes from a meme of SpongeBob SquarePants scene, acting like a chicken due to hypnosis, where the still frame looks like SpongeBob is mocking someone.
The text is transformed to alternate the letter case of each letter. Punctuation and numbers are ignored. The limitations on what characters' case can be changed is limited by the Unicode Standard, as described in section 3.13 "Default Case Folding." (https://www.unicode.org/versions/Unicode15.0.0/ch03.pdf#page=86)

**Example**

Input: ` Money can't buy happiness.`

Output: `MoNeY cAn'T bUy HaPpInEsS.`


## Authors

- [@jpenn84](https://www.github.com/jpenn84)


## Badges

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-limegreen.svg)](https://opensource.org/licenses/)
