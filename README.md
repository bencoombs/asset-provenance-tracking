Note: All icons, images, and logos are © 2024 Global Open Source Quality Assurance System. All rights reserved.
We are committed to keeping our code open source, but all GOSQAS and GDT 
branding, including logos, is subject to the copyright above.

## A Live MVP

We are developing a Minimal Viable Product. Although still a work in progress, you can try it out here:

[https://gosqas.org/](https://gosqas.org/)

# GOSQAS Demo

This is experimental code for the [GOSQAS project](https://github.com/gosqas/home/blob/main/README.md).

GOSQAS is grateful to @devhawk (Harry Pierson) for rapidly prototyping this demo.

# News

[Distributed Medical Device Manufacturing](https://dmdm.icu/) (DMDM) has made a small number of Glia tourniquest wwhich will be tracked with the GDT QR codes
and sent to Sudan where they are desperately needed. We thank Alex Barton for being an early user.


![DMDMwithTourniquetBoxes](https://github.com/user-attachments/assets/d0a15ae4-d2d6-4bf0-b69e-2e19ee9caf0b)



## Installation

1. Clone the repo
2. Install dependencies
```
npm install
```
3. Run development environment
```
npm run dev
```
4. Then point your browser at [http://localhost:8000](http://localhost:8000) for example

> Note, as of v0.2, the demo server listens on *all* networks the server is connected to.
> While exposing server ports is always a security risk, exposing the demo server on the local network
> allows other devices - mobile devices in particular - to access the demo server.
> On startup, the server prints out a list of the IP addresses it is listening on.

## Video of Operation

We have made a [short video](https://youtu.be/E5_YQV72NyY) of [v0.1](https://github.com/gosqas/asset-provenance-tracking/releases/tag/v0.1) operation.

## batch-shell.sh

The file batch-shell.sh can be used to produce any number of keys and QR codes at at time.
It takes a single argument, the number N of keys and QR codes to create. It will
populate the current directory directly with N files, each of which has the name of a device key, and whose
body a .png file of the QR code that resolves to that key. An internal variable defines the full URL.
The name in the start record is currently hard-coded to "MakerFaireBayArea" but can of course be changed.

For example, to generate 300 valid QR codes run the following:
```
batch-shell.sh 300
```

## License
As mentioned in the [Licences section](https://github.com/gosqasorg/home#licenses) of the Home repository, as this repository is software the license is under a GNU Affero GPL v3 License. See the [License](https://github.com/gosqasorg/asset-provenance-tracking/blob/main/LICENSE) file for more details.

## A Note on Our Trademarks

Although all of our code is open-source, you may not use our trademarks without written permission.
Our trademarks include:
1. The word GOSQAS
2. The term "Global Open Source Quality Assurance System"
3. The "purple hands" logo
4. The word-ard GOSQAS with the "purple hands" symbol in the letter O.

## Contributing

Global Distributed Tracking is being built by volunteers, and we need and appreciate your help. In addition to coders, we need 
artists, writers, tests, UX experts, supply chain experts and more. The best way to contribute is to email [read.robert@pubinv.org](mailto:gosqasystem@gmail.com) directly,
where he will likely schedule a private meeting with you before introducing you to the team.

But, you are welcome to enter issues and create pull requests as well. We recommend you full read our associated technical papers
before expending significant time on this unless you have spoken to us first.

Contributors will be expected to sign our [Contributors License Agreement ](https://github.com/gosqasorg/asset-provenance-tracking/blob/main/CONTRIBUTOR%20LICENSE%20AGREEMENT.md) designed to keep your contribution forever free.



