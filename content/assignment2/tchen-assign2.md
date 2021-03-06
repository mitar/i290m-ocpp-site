Title: PeerLibrary Development Community Reflection
Date: 2013-10-7 04:20
Category: assignment
Tags: peerlibrary, open access, peer collaboration
Slug: tchen-assign2
Author: Tony Chen
Summary: History, infrastructure and culture @ PeerLibrary

The initial vision for PeerLibrary was to create a platform for open and transparent academic publication. For these reasons, the project has been open source primarily for ideological reasons since its early roots. In the early days, Rodrigo and I had conversations about the failures of journal print culture to meet the pace with technological innovation. We noticed a crippling property of the existing publication models is largely due to closed access bureaucratic machinery. In early 2013, Rodrigo and I started the Open Access Initiative to address this problem with political advocacy. Even though, in our time a system wide open access policy was passed in the UCs, we strongly felt that was no sufficient to the promotion of open access culture. We realized the technical infrastructure for open access scholarship was not there, so we decided to build it. Today, there is a great intersection in the set of members of the Open Access Initiative and the set of contributors to the PeerLibrary project. In this respect, I believe the ideological foundations for this project will continue to influence the development in the future.

The infrastructure of the project was built on top of open source web technologies (node.js, mongo doc store, etc.). There were both practical and ideological reasons for this. There is a large and growing community of web developers that actively contribute to these frameworks and libraries which means extended software support and increased stability of our application. We also felt like it was necessary to provide solidarity to support the ecosystem of open source apps being built. For example, Meteor, a budding real-time web framework that is slowly slipping into the consciousness of agile web development, was missing a lot of dependencies that were in node.js. In building infrastructure for PeerLibrary we also published Meteor packages to their ecosystem to provide these tools to other developers.

The project was initially created under the [BSD 2-clause license](http://directory.fsf.org/wiki?title=License:FreeBSD), a permissive free software license. We didn't spend that much time deliberating on what software licenses  we were going to use so this decision was just made under ideological assumptions that PeerLibrary will be free and opensource forever. Knowing the scope of this project, I still feel that it does not matter who implements this concept - it just needs to be out there. (So fork PeerLibrary and do what you may with it :-))

In the recent summer, Mitar prudently suggested the potential misuse of PeerLibrary as open source software - that subscription based journals could potentially integrate PeerLibrary's features behind a paywall. This was another avenue for ideological debate. Do we want to use a license that would aid in the advancement of PeerLibrary's technical features without corporate competition? or do we want to commit to open access? The answer was obvious. As a result, we switched to a copyleft license: [GNU Affero General Public License](http://www.gnu.org/licenses/agpl-3.0.html)


added Comments Thomas 11/6/2013 (see commit description)
