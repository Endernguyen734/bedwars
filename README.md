
<?php
echo "PocketMine-MP plugin BedWars v1
This file has been generated using DevTools v1.13.0 at Thu, 03 Sep 2020 05:09:51 +0000
----------------
";

if(extension_loaded("phar")){
	$phar = new \Phar(__FILE__);
	foreach($phar->getMetadata() as $key => $value){
		echo ucfirst($key) . ": " . (is_array($value) ? implode(", ", $value) : $value) . "\n";
	}
}

__HALT_COMPILER(); ?>
9             �   a:9:{s:4:"name";s:7:"BedWars";s:7:"version";d:1;s:4:"main";s:15:"BedWars\BedWars";s:3:"api";s:5:"3.5.9";s:6:"depend";s:0:"";s:11:"description";s:0:"";s:7:"authors";s:0:"";s:7:"website";s:0:"";s:12:"creationDate";i:1599109791;}   LICENSEM�  �zP_M�   =g��      	   README.mdo  �zP_o  ���]�      
   plugin.ymlK   �zP_K   �	 ��         resources/config.yml�   �zP_�   �;䛶         resources/skins/264.png�  �zP_�  Γ��         resources/skins/388.png�  �zP_�  ;�)|�         src/BedWars/BedWars.php$  �zP_$  ��E/�         src/BedWars/SignUpdater.php�  �zP_�  }^l�      &   src/BedWars/command/DefaultCommand.phpvc  �zP_vc  ņs�         src/BedWars/game/Game.phpy  �zP_y  Tr�f�      !   src/BedWars/game/GameListener.php�B  �zP_�B  &��x�         src/BedWars/game/GameTick.php�  �zP_�  �Ke��         src/BedWars/game/Generator.php�  �zP_�  G#��         src/BedWars/game/Team.php�
  �zP_�
  �}x�      *   src/BedWars/game/entity/FakeItemEntity.php^  �zP_^  �
�      '   src/BedWars/game/player/PlayerCache.php5  �zP_5  8���      "   src/BedWars/game/shop/ItemShop.php/B  �zP_/B  U���      %   src/BedWars/game/shop/UpgradeShop.php�  �zP_�  �'r�          src/BedWars/utils/Scoreboard.phpZ
  �zP_Z
  �v�1�         src/BedWars/utils/Utils.phpQ  �zP_Q  i��@�                          GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007

 Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.

                            Preamble

  The GNU General Public License is a free, copyleft license for
software and other kinds of works.

  The licenses for most software and other practical works are designed
to take away your freedom to share and change the works.  By contrast,
the GNU General Public License is intended to guarantee your freedom to
share and change all versions of a program--to make sure it remains free
software for all its users.  We, the Free Software Foundation, use the
GNU General Public License for most of our software; it applies also to
any other work released this way by its authors.  You can apply it to
your programs, too.

  When we speak of free software, we are referring to freedom, not
price.  Our General Public Licenses are designed to make sure that you
have the freedom to distribute copies of free software (and charge for
them if you wish), that you receive source code or can get it if you
want it, that you can change the software or use pieces of it in new
free programs, and that you know you can do these things.

  To protect your rights, we need to prevent others from denying you
these rights or asking you to surrender the rights.  Therefore, you have
certain responsibilities if you distribute copies of the software, or if
you modify it: responsibilities to respect the freedom of others.

  For example, if you distribute copies of such a program, whether
gratis or for a fee, you must pass on to the recipients the same
freedoms that you received.  You must make sure that they, too, receive
or can get the source code.  And you must show them these terms so they
know their rights.

  Developers that use the GNU GPL protect your rights with two steps:
(1) assert copyright on the software, and (2) offer you this License
giving you legal permission to copy, distribute and/or modify it.

  For the developers' and authors' protection, the GPL clearly explains
that there is no warranty for this free software.  For both users' and
authors' sake, the GPL requires that modified versions be marked as
changed, so that their problems will not be attributed erroneously to
authors of previous versions.

  Some devices are designed to deny users access to install or run
modified versions of the software inside them, although the manufacturer
can do so.  This is fundamentally incompatible with the aim of
protecting users' freedom to change the software.  The systematic
pattern of such abuse occurs in the area of products for individuals to
use, which is precisely where it is most unacceptable.  Therefore, we
have designed this version of the GPL to prohibit the practice for those
products.  If such problems arise substantially in other domains, we
stand ready to extend this provision to those domains in future versions
of the GPL, as needed to protect the freedom of users.

  Finally, every program is threatened constantly by software patents.
States should not allow patents to restrict development and use of
software on general-purpose computers, but in those that do, we wish to
avoid the special danger that patents applied to a free program could
make it effectively proprietary.  To prevent this, the GPL assures that
patents cannot be used to render the program non-free.

  The precise terms and conditions for copying, distribution and
modification follow.

                       TERMS AND CONDITIONS

  0. Definitions.

  "This License" refers to version 3 of the GNU General Public License.

  "Copyright" also means copyright-like laws that apply to other kinds of
works, such as semiconductor masks.

  "The Program" refers to any copyrightable work licensed under this
License.  Each licensee is addressed as "you".  "Licensees" and
"recipients" may be individuals or organizations.

  To "modify" a work means to copy from or adapt all or part of the work
in a fashion requiring copyright permission, other than the making of an
exact copy.  The resulting work is called a "modified version" of the
earlier work or a work "based on" the earlier work.

  A "covered work" means either the unmodified Program or a work based
on the Program.

  To "propagate" a work means to do anything with it that, without
permission, would make you directly or secondarily liable for
infringement under applicable copyright law, except executing it on a
computer or modifying a private copy.  Propagation includes copying,
distribution (with or without modification), making available to the
public, and in some countries other activities as well.

  To "convey" a work means any kind of propagation that enables other
parties to make or receive copies.  Mere interaction with a user through
a computer network, with no transfer of a copy, is not conveying.

  An interactive user interface displays "Appropriate Legal Notices"
to the extent that it includes a convenient and prominently visible
feature that (1) displays an appropriate copyright notice, and (2)
tells the user that there is no warranty for the work (except to the
extent that warranties are provided), that licensees may convey the
work under this License, and how to view a copy of this License.  If
the interface presents a list of user commands or options, such as a
menu, a prominent item in the list meets this criterion.

  1. Source Code.

  The "source code" for a work means the preferred form of the work
for making modifications to it.  "Object code" means any non-source
form of a work.

  A "Standard Interface" means an interface that either is an official
standard defined by a recognized standards body, or, in the case of
interfaces specified for a particular programming language, one that
is widely used among developers working in that language.

  The "System Libraries" of an executable work include anything, other
than the work as a whole, that (a) is included in the normal form of
packaging a Major Component, but which is not part of that Major
Component, and (b) serves only to enable use of the work with that
Major Component, or to implement a Standard Interface for which an
implementation is available to the public in source code form.  A
"Major Component", in this context, means a major essential component
(kernel, window system, and so on) of the specific operating system
(if any) on which the executable work runs, or a compiler used to
produce the work, or an object code interpreter used to run it.

  The "Corresponding Source" for a work in object code form means all
the source code needed to generate, install, and (for an executable
work) run the object code and to modify the work, including scripts to
control those activities.  However, it does not include the work's
System Libraries, or general-purpose tools or generally available free
programs which are used unmodified in performing those activities but
which are not part of the work.  For example, Corresponding Source
includes interface definition files associated with source files for
the work, and the source code for shared libraries and dynamically
linked subprograms that the work is specifically designed to require,
such as by intimate data communication or control flow between those
subprograms and other parts of the work.

  The Corresponding Source need not include anything that users
can regenerate automatically from other parts of the Corresponding
Source.

  The Corresponding Source for a work in source code form is that
same work.

  2. Basic Permissions.

  All rights granted under this License are granted for the term of
copyright on the Program, and are irrevocable provided the stated
conditions are met.  This License explicitly affirms your unlimited
permission to run the unmodified Program.  The output from running a
covered work is covered by this License only if the output, given its
content, constitutes a covered work.  This License acknowledges your
rights of fair use or other equivalent, as provided by copyright law.

  You may make, run and propagate covered works that you do not
convey, without conditions so long as your license otherwise remains
in force.  You may convey covered works to others for the sole purpose
of having them make modifications exclusively for you, or provide you
with facilities for running those works, provided that you comply with
the terms of this License in conveying all material for which you do
not control copyright.  Those thus making or running the covered works
for you must do so exclusively on your behalf, under your direction
and control, on terms that prohibit them from making any copies of
your copyrighted material outside their relationship with you.

  Conveying under any other circumstances is permitted solely under
the conditions stated below.  Sublicensing is not allowed; section 10
makes it unnecessary.

  3. Protecting Users' Legal Rights From Anti-Circumvention Law.

  No covered work shall be deemed part of an effective technological
measure under any applicable law fulfilling obligations under article
11 of the WIPO copyright treaty adopted on 20 December 1996, or
similar laws prohibiting or restricting circumvention of such
measures.

  When you convey a covered work, you waive any legal power to forbid
circumvention of technological measures to the extent such circumvention
is effected by exercising rights under this License with respect to
the covered work, and you disclaim any intention to limit operation or
modification of the work as a means of enforcing, against the work's
users, your or third parties' legal rights to forbid circumvention of
technological measures.

  4. Conveying Verbatim Copies.

  You may convey verbatim copies of the Program's source code as you
receive it, in any medium, provided that you conspicuously and
appropriately publish on each copy an appropriate copyright notice;
keep intact all notices stating that this License and any
non-permissive terms added in accord with section 7 apply to the code;
keep intact all notices of the absence of any warranty; and give all
recipients a copy of this License along with the Program.

  You may charge any price or no price for each copy that you convey,
and you may offer support or warranty protection for a fee.

  5. Conveying Modified Source Versions.

  You may convey a work based on the Program, or the modifications to
produce it from the Program, in the form of source code under the
terms of section 4, provided that you also meet all of these conditions:

    a) The work must carry prominent notices stating that you modified
    it, and giving a relevant date.

    b) The work must carry prominent notices stating that it is
    released under this License and any conditions added under section
    7.  This requirement modifies the requirement in section 4 to
    "keep intact all notices".

    c) You must license the entire work, as a whole, under this
    License to anyone who comes into possession of a copy.  This
    License will therefore apply, along with any applicable section 7
    additional terms, to the whole of the work, and all its parts,
    regardless of how they are packaged.  This License gives no
    permission to license the work in any other way, but it does not
    invalidate such permission if you have separately received it.

    d) If the work has interactive user interfaces, each must display
    Appropriate Legal Notices; however, if the Program has interactive
    interfaces that do not display Appropriate Legal Notices, your
    work need not make them do so.

  A compilation of a covered work with other separate and independent
works, which are not by their nature extensions of the covered work,
and which are not combined with it such as to form a larger program,
in or on a volume of a storage or distribution medium, is called an
"aggregate" if the compilation and its resulting copyright are not
used to limit the access or legal rights of the compilation's users
beyond what the individual works permit.  Inclusion of a covered work
in an aggregate does not cause this License to apply to the other
parts of the aggregate.

  6. Conveying Non-Source Forms.

  You may convey a covered work in object code form under the terms
of sections 4 and 5, provided that you also convey the
machine-readable Corresponding Source under the terms of this License,
in one of these ways:

    a) Convey the object code in, or embodied in, a physical product
    (including a physical distribution medium), accompanied by the
    Corresponding Source fixed on a durable physical medium
    customarily used for software interchange.

    b) Convey the object code in, or embodied in, a physical product
    (including a physical distribution medium), accompanied by a
    written offer, valid for at least three years and valid for as
    long as you offer spare parts or customer support for that product
    model, to give anyone who possesses the object code either (1) a
    copy of the Corresponding Source for all the software in the
    product that is covered by this License, on a durable physical
    medium customarily used for software interchange, for a price no
    more than your reasonable cost of physically performing this
    conveying of source, or (2) access to copy the
    Corresponding Source from a network server at no charge.

    c) Convey individual copies of the object code with a copy of the
    written offer to provide the Corresponding Source.  This
    alternative is allowed only occasionally and noncommercially, and
    only if you received the object code with such an offer, in accord
    with subsection 6b.

    d) Convey the object code by offering access from a designated
    place (gratis or for a charge), and offer equivalent access to the
    Corresponding Source in the same way through the same place at no
    further charge.  You need not require recipients to copy the
    Corresponding Source along with the object code.  If the place to
    copy the object code is a network server, the Corresponding Source
    may be on a different server (operated by you or a third party)
    that supports equivalent copying facilities, provided you maintain
    clear directions next to the object code saying where to find the
    Corresponding Source.  Regardless of what server hosts the
    Corresponding Source, you remain obligated to ensure that it is
    available for as long as needed to satisfy these requirements.

    e) Convey the object code using peer-to-peer transmission, provided
    you inform other peers where the object code and Corresponding
    Source of the work are being offered to the general public at no
    charge under subsection 6d.

  A separable portion of the object code, whose source code is excluded
from the Corresponding Source as a System Library, need not be
included in conveying the object code work.

  A "User Product" is either (1) a "consumer product", which means any
tangible personal property which is normally used for personal, family,
or household purposes, or (2) anything designed or sold for incorporation
into a dwelling.  In determining whether a product is a consumer product,
doubtful cases shall be resolved in favor of coverage.  For a particular
product received by a particular user, "normally used" refers to a
typical or common use of that class of product, regardless of the status
of the particular user or of the way in which the particular user
actually uses, or expects or is expected to use, the product.  A product
is a consumer product regardless of whether the product has substantial
commercial, industrial or non-consumer uses, unless such uses represent
the only significant mode of use of the product.

  "Installation Information" for a User Product means any methods,
procedures, authorization keys, or other information required to install
and execute modified versions of a covered work in that User Product from
a modified version of its Corresponding Source.  The information must
suffice to ensure that the continued functioning of the modified object
code is in no case prevented or interfered with solely because
modification has been made.

  If you convey an object code work under this section in, or with, or
specifically for use in, a User Product, and the conveying occurs as
part of a transaction in which the right of possession and use of the
User Product is transferred to the recipient in perpetuity or for a
fixed term (regardless of how the transaction is characterized), the
Corresponding Source conveyed under this section must be accompanied
by the Installation Information.  But this requirement does not apply
if neither you nor any third party retains the ability to install
modified object code on the User Product (for example, the work has
been installed in ROM).

  The requirement to provide Installation Information does not include a
requirement to continue to provide support service, warranty, or updates
for a work that has been modified or installed by the recipient, or for
the User Product in which it has been modified or installed.  Access to a
network may be denied when the modification itself materially and
adversely affects the operation of the network or violates the rules and
protocols for communication across the network.

  Corresponding Source conveyed, and Installation Information provided,
in accord with this section must be in a format that is publicly
documented (and with an implementation available to the public in
source code form), and must require no special password or key for
unpacking, reading or copying.

  7. Additional Terms.

  "Additional permissions" are terms that supplement the terms of this
License by making exceptions from one or more of its conditions.
Additional permissions that are applicable to the entire Program shall
be treated as though they were included in this License, to the extent
that they are valid under applicable law.  If additional permissions
apply only to part of the Program, that part may be used separately
under those permissions, but the entire Program remains governed by
this License without regard to the additional permissions.

  When you convey a copy of a covered work, you may at your option
remove any additional permissions from that copy, or from any part of
it.  (Additional permissions may be written to require their own
removal in certain cases when you modify the work.)  You may place
additional permissions on material, added by you to a covered work,
for which you have or can give appropriate copyright permission.

  Notwithstanding any other provision of this License, for material you
add to a covered work, you may (if authorized by the copyright holders of
that material) supplement the terms of this License with terms:

    a) Disclaiming warranty or limiting liability differently from the
    terms of sections 15 and 16 of this License; or

    b) Requiring preservation of specified reasonable legal notices or
    author attributions in that material or in the Appropriate Legal
    Notices displayed by works containing it; or

    c) Prohibiting misrepresentation of the origin of that material, or
    requiring that modified versions of such material be marked in
    reasonable ways as different from the original version; or

    d) Limiting the use for publicity purposes of names of licensors or
    authors of the material; or

    e) Declining to grant rights under trademark law for use of some
    trade names, trademarks, or service marks; or

    f) Requiring indemnification of licensors and authors of that
    material by anyone who conveys the material (or modified versions of
    it) with contractual assumptions of liability to the recipient, for
    any liability that these contractual assumptions directly impose on
    those licensors and authors.

  All other non-permissive additional terms are considered "further
restrictions" within the meaning of section 10.  If the Program as you
received it, or any part of it, contains a notice stating that it is
governed by this License along with a term that is a further
restriction, you may remove that term.  If a license document contains
a further restriction but permits relicensing or conveying under this
License, you may add to a covered work material governed by the terms
of that license document, provided that the further restriction does
not survive such relicensing or conveying.

  If you add terms to a covered work in accord with this section, you
must place, in the relevant source files, a statement of the
additional terms that apply to those files, or a notice indicating
where to find the applicable terms.

  Additional terms, permissive or non-permissive, may be stated in the
form of a separately written license, or stated as exceptions;
the above requirements apply either way.

  8. Termination.

  You may not propagate or modify a covered work except as expressly
provided under this License.  Any attempt otherwise to propagate or
modify it is void, and will automatically terminate your rights under
this License (including any patent licenses granted under the third
paragraph of section 11).

  However, if you cease all violation of this License, then your
license from a particular copyright holder is reinstated (a)
provisionally, unless and until the copyright holder explicitly and
finally terminates your license, and (b) permanently, if the copyright
holder fails to notify you of the violation by some reasonable means
prior to 60 days after the cessation.

  Moreover, your license from a particular copyright holder is
reinstated permanently if the copyright holder notifies you of the
violation by some reasonable means, this is the first time you have
received notice of violation of this License (for any work) from that
copyright holder, and you cure the violation prior to 30 days after
your receipt of the notice.

  Termination of your rights under this section does not terminate the
licenses of parties who have received copies or rights from you under
this License.  If your rights have been terminated and not permanently
reinstated, you do not qualify to receive new licenses for the same
material under section 10.

  9. Acceptance Not Required for Having Copies.

  You are not required to accept this License in order to receive or
run a copy of the Program.  Ancillary propagation of a covered work
occurring solely as a consequence of using peer-to-peer transmission
to receive a copy likewise does not require acceptance.  However,
nothing other than this License grants you permission to propagate or
modify any covered work.  These actions infringe copyright if you do
not accept this License.  Therefore, by modifying or propagating a
covered work, you indicate your acceptance of this License to do so.

  10. Automatic Licensing of Downstream Recipients.

  Each time you convey a covered work, the recipient automatically
receives a license from the original licensors, to run, modify and
propagate that work, subject to this License.  You are not responsible
for enforcing compliance by third parties with this License.

  An "entity transaction" is a transaction transferring control of an
organization, or substantially all assets of one, or subdividing an
organization, or merging organizations.  If propagation of a covered
work results from an entity transaction, each party to that
transaction who receives a copy of the work also receives whatever
licenses to the work the party's predecessor in interest had or could
give under the previous paragraph, plus a right to possession of the
Corresponding Source of the work from the predecessor in interest, if
the predecessor has it or can get it with reasonable efforts.

  You may not impose any further restrictions on the exercise of the
rights granted or affirmed under this License.  For example, you may
not impose a license fee, royalty, or other charge for exercise of
rights granted under this License, and you may not initiate litigation
(including a cross-claim or counterclaim in a lawsuit) alleging that
any patent claim is infringed by making, using, selling, offering for
sale, or importing the Program or any portion of it.

  11. Patents.

  A "contributor" is a copyright holder who authorizes use under this
License of the Program or a work on which the Program is based.  The
work thus licensed is called the contributor's "contributor version".

  A contributor's "essential patent claims" are all patent claims
owned or controlled by the contributor, whether already acquired or
hereafter acquired, that would be infringed by some manner, permitted
by this License, of making, using, or selling its contributor version,
but do not include claims that would be infringed only as a
consequence of further modification of the contributor version.  For
purposes of this definition, "control" includes the right to grant
patent sublicenses in a manner consistent with the requirements of
this License.

  Each contributor grants you a non-exclusive, worldwide, royalty-free
patent license under the contributor's essential patent claims, to
make, use, sell, offer for sale, import and otherwise run, modify and
propagate the contents of its contributor version.

  In the following three paragraphs, a "patent license" is any express
agreement or commitment, however denominated, not to enforce a patent
(such as an express permission to practice a patent or covenant not to
sue for patent infringement).  To "grant" such a patent license to a
party means to make such an agreement or commitment not to enforce a
patent against the party.

  If you convey a covered work, knowingly relying on a patent license,
and the Corresponding Source of the work is not available for anyone
to copy, free of charge and under the terms of this License, through a
publicly available network server or other readily accessible means,
then you must either (1) cause the Corresponding Source to be so
available, or (2) arrange to deprive yourself of the benefit of the
patent license for this particular work, or (3) arrange, in a manner
consistent with the requirements of this License, to extend the patent
license to downstream recipients.  "Knowingly relying" means you have
actual knowledge that, but for the patent license, your conveying the
covered work in a country, or your recipient's use of the covered work
in a country, would infringe one or more identifiable patents in that
country that you have reason to believe are valid.

  If, pursuant to or in connection with a single transaction or
arrangement, you convey, or propagate by procuring conveyance of, a
covered work, and grant a patent license to some of the parties
receiving the covered work authorizing them to use, propagate, modify
or convey a specific copy of the covered work, then the patent license
you grant is automatically extended to all recipients of the covered
work and works based on it.

  A patent license is "discriminatory" if it does not include within
the scope of its coverage, prohibits the exercise of, or is
conditioned on the non-exercise of one or more of the rights that are
specifically granted under this License.  You may not convey a covered
work if you are a party to an arrangement with a third party that is
in the business of distributing software, under which you make payment
to the third party based on the extent of your activity of conveying
the work, and under which the third party grants, to any of the
parties who would receive the covered work from you, a discriminatory
patent license (a) in connection with copies of the covered work
conveyed by you (or copies made from those copies), or (b) primarily
for and in connection with specific products or compilations that
contain the covered work, unless you entered into that arrangement,
or that patent license was granted, prior to 28 March 2007.

  Nothing in this License shall be construed as excluding or limiting
any implied license or other defenses to infringement that may
otherwise be available to you under applicable patent law.

  12. No Surrender of Others' Freedom.

  If conditions are imposed on you (whether by court order, agreement or
otherwise) that contradict the conditions of this License, they do not
excuse you from the conditions of this License.  If you cannot convey a
covered work so as to satisfy simultaneously your obligations under this
License and any other pertinent obligations, then as a consequence you may
not convey it at all.  For example, if you agree to terms that obligate you
to collect a royalty for further conveying from those to whom you convey
the Program, the only way you could satisfy both those terms and this
License would be to refrain entirely from conveying the Program.

  13. Use with the GNU Affero General Public License.

  Notwithstanding any other provision of this License, you have
permission to link or combine any covered work with a work licensed
under version 3 of the GNU Affero General Public License into a single
combined work, and to convey the resulting work.  The terms of this
License will continue to apply to the part which is the covered work,
but the special requirements of the GNU Affero General Public License,
section 13, concerning interaction through a network will apply to the
combination as such.

  14. Revised Versions of this License.

  The Free Software Foundation may publish revised and/or new versions of
the GNU General Public License from time to time.  Such new versions will
be similar in spirit to the present version, but may differ in detail to
address new problems or concerns.

  Each version is given a distinguishing version number.  If the
Program specifies that a certain numbered version of the GNU General
Public License "or any later version" applies to it, you have the
option of following the terms and conditions either of that numbered
version or of any later version published by the Free Software
Foundation.  If the Program does not specify a version number of the
GNU General Public License, you may choose any version ever published
by the Free Software Foundation.

  If the Program specifies that a proxy can decide which future
versions of the GNU General Public License can be used, that proxy's
public statement of acceptance of a version permanently authorizes you
to choose that version for the Program.

  Later license versions may give you additional or different
permissions.  However, no additional obligations are imposed on any
author or copyright holder as a result of your choosing to follow a
later version.

  15. Disclaimer of Warranty.

  THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY
APPLICABLE LAW.  EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT
HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY
OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO,
THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE.  THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM
IS WITH YOU.  SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF
ALL NECESSARY SERVICING, REPAIR OR CORRECTION.

  16. Limitation of Liability.

  IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING
WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS
THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY
GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE
USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED TO LOSS OF
DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD
PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS),
EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF
SUCH DAMAGES.

  17. Interpretation of Sections 15 and 16.

  If the disclaimer of warranty and limitation of liability provided
above cannot be given local legal effect according to their terms,
reviewing courts shall apply local law that most closely approximates
an absolute waiver of all civil liability in connection with the
Program, unless a warranty or assumption of liability accompanies a
copy of the Program in return for a fee.

                     END OF TERMS AND CONDITIONS

            How to Apply These Terms to Your New Programs

  If you develop a new program, and you want it to be of the greatest
possible use to the public, the best way to achieve this is to make it
free software which everyone can redistribute and change under these terms.

  To do so, attach the following notices to the program.  It is safest
to attach them to the start of each source file to most effectively
state the exclusion of warranty; and each file should have at least
the "copyright" line and a pointer to where the full notice is found.

    <one line to give the program's name and a brief idea of what it does.>
    Copyright (C) <year>  <name of author>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

Also add information on how to contact you by electronic and paper mail.

  If the program does terminal interaction, make it output a short
notice like this when it starts in an interactive mode:

    <program>  Copyright (C) <year>  <name of author>
    This program comes with ABSOLUTELY NO WARRANTY; for details type `show w'.
    This is free software, and you are welcome to redistribute it
    under certain conditions; type `show c' for details.

The hypothetical commands `show w' and `show c' should show the appropriate
parts of the General Public License.  Of course, your program's commands
might be different; for a GUI interface, you would use an "about box".

  You should also get your employer (if you work as a programmer) or school,
if any, to sign a "copyright disclaimer" for the program, if necessary.
For more information on this, and how to apply and follow the GNU GPL, see
<https://www.gnu.org/licenses/>.

  The GNU General Public License does not permit incorporating your program
into proprietary programs.  If your program is a subroutine library, you
may consider it more useful to permit linking proprietary applications with
the library.  If this is what you want to do, use the GNU Lesser General
Public License instead of this License.  But first, please read
<https://www.gnu.org/licenses/why-not-lgpl.html>.
# BedWars - PocketMine Plugin
Ultimate BedWars plugin for PocketMine<br>
**Warning:** DO NOT TRUST OTHER PEOPLE SELLING FIXED VERSION OF THIS PLUGIN AS THEIR OWN, I AM ORIGINAL AUTHOR.<br>

This plugin was originally designed for Hyperlands, but as it got leaked I decided to make it public.

![Image from game](https://i.imgur.com/X9zSs1u.png)</br>
Please note that this plugin is not ready for being used on production servers as it's still in development. I'm not aware of any damage caused to your server by this plugin.

## Features
- All basics of BedWars game
- Spectator mode
- In-Game scoreboard
- Team upgrades 
- Custom generators (like Hypixel's)

## TODO
- [ ] Customizable messages and scoreboard 
- [ ] Custom team upgrades & shop prices
- [ ] Use random as arena identifier
- [ ] Rewrite arena setup

## Contact
**Discord** boi#1485 or https://discord.gg/XKaXcE4
name: BedWars
version: 1.0
api: 3.5.9
main: BedWars\BedWars
author: boi#Website of your server displayed on scoreboard in-game
website: www.example.net
#Time of countdown before game starts
start-time: 60
#Time of countdown before game is restarted
restart-time: 15�PNG

   
IHDR   @   @   �iq�  �IDATx^�[[lU�fg��XXhi)�,m��\M��b��c�$`BP�!x+�D�"� ��	&4Qy��,h3¥�B[�ڥ-K��۝�c��]Z���0�م�$��o�s���w��s����rT5�%aE2'f3�(5�k�eX�	�v�D�U��:u���͂��J��Kxe?t�CljBm��]���U��HnZɆ�rHD������$�sȇ��[���~B`�8v��+�=��>Iꬥ��h�ڇ����pS����q_��_�yY�Cr���a'�Y[X�~Imܹ�w�Q@��6�)*aט|0(����#A@u^!Z��^��2����rBt��zzQT9>}<`qn>Nz��{�C�"��{!^���i8}��\����?�`��u�pJ Ų��B$z�����&�	�U>�[����@#�\��xʟ-�qh�K�VV�!�tT�2�r\$	q�?�j�	8����z~��̙�����ϋ��=<����,L0��mesX�ӆ�z��zq��
��E\�o,I0�d�m��Ɵ��f��'���5q�'�֙���nY�[��G��;���U��;���Յ%����ޅ{�ǆ76���@^�*_�4������F��q��z=?6q���V�	5ʳ�?s�,S�}��C�������#=0��0��x��������<���ƪ�A�=�	k���ZKY����k��QĿt]UMp���g�X�Y� ���o��v_~!Tf���اN@K#y;7��}�uC<s�r���y]���F�����IQX=<�Է��9H
�'ע_�}��m"�����������}��&�1v�c����~=��@cK��9����^�FF{�'�,���ڱ�k-?f{���b�ڲ�l⳥�Kt��u���4���_kyM��[��'��	Ў�v@�o*������-ˁ�U�Z�k�O��cI�����W. i�Ћ7����2��Eӯ��&�T	� 5E����qЋ��9�M��p�X����d߳�����н���Y�o-�=�A����S�7p� �J*���̉Ћ�+���_��_kyM�������YS�o+���_��_kyM�����$f�<�g�B/�\Z=�A����S%�x��ӆ���<�ŵ�%���k-��>�|��
��e(�Ϸ��:��|k��B�Z�k�O%����o����y!��Kܞہ�H����G�/D����&{T�
	MF�/8%E��'�S�\�a�5)0���c���?��&��s�\wLy@r���֤<�xΓ�)�����y�&���g	�#1�}{���Z�3�P�l'��`���;� �����b���3�
:�'��c���o=�O��d�x�����8�4ۉ���'��?<���G�2y�zElt�7����Ě5�.��LΆ�xa���XWe���?HMi�f�����C��5������#*�^7���B@���^�ty}�C�3/��D]�Y���'5�
[:�؊��x�˺ڠ�2#���[�lL�y|F�/�e�N��]dYy%l�X�~	��P�p~�Al�RL7����b����� �N|mBW�{{`(N�Kpϯ�B����t�儡�����c�*�V��N���v�ѩ/�GF���n���� Н&�=��k0Z>���tu���8��*�%    IEND�B`��PNG

   
IHDR   @       ��~�   gAMA  ���a   	pHYs  �  ��o�d   tEXtSoftware Paint.NET v3.5.100�r�  #IDAThC�YkSSW�Oj#��@ZP�RMmBB���ARІ ����
蔱uj�u��O��@i��"*����M��/������͌{���$��=kg�:랜�Ͼ*�I�����L�����@����Cؾ
���,޸1�x�W��8���mE������#��1��H	�<�����ГGW�{[�h��3��3>�S�
�G�?�]��U��p�|�Yt���[������s�`?��^���K�p�W�O�К�fP8����H�&Ng"�l����(�W8�̆�E#�_�A�
�@J``�-|�o�е1 m��##�e��{)��)���M�Q�S>h�;вlǑ'f�L���?�[A�
�@�����AT�5^w�:^k��Pu��x�
��x��@��Z�u7�����n U�k��� ��S�;�_n����Q�cJ�w�
tn�c�� �]��q|���7{ѱ�S�J�Q����a��&�<�B�k��C(� ,^��0��wa����z�
�����U�l��e����"0mÙ��5��so��~ڤ�?�h~l�S�J�Q��3�:���~�F?�1E�؝�W�(Z���
���Y_�±7���p��)~����l��ߞ�mkQ�'6�S��s��M���P���N !��x�6"{U�����(CUԡS����7�Wi@�� ;��ة? m]���0wfÇ���N�D�_�}=������7�Wi@��qF*{�UJcK&&m�p���CԎ�~4�ec����7�Wi UVxq����x�y����mȍ�%}J����!N�x0����)^e�>���\�ϛϫ�4���ݕ�w�N�����k��,N X���п	����)���7�Wi �X��T�#�����C`e��'7�s7z��@i<]��� ,ٸ4F�O�O�����X?o>�>ҀJ����[�N�Y�4>_\��#t��k�t���%3<k�п�U�����#
�ZK^�ju�|���zHZ�n�M�,Zмdc;AYlXd�(�,�B��>�o�~�Ͳꇖ*~�|^}��z.���&�    IEND�B`�<?php


namespace BedWars;


use pocketmine\block\utils\SignText;
use pocketmine\item\Item;
use pocketmine\level\Level;
use pocketmine\Player;
use pocketmine\scheduler\Task;
use pocketmine\tile\Sign;
use pocketmine\utils\TextFormat;
use pocketmine\math\Vector3;
use pocketmine\plugin\Plugin;
use pocketmine\plugin\PluginBase;
use BedWars\command\DefaultCommand;
use BedWars\game\Game;
use BedWars\game\GameListener;
use BedWars\game\Team;


class BedWars extends PluginBase
{

    const PREFIX = TextFormat::BOLD . TextFormat::DARK_RED . "BedWars " . TextFormat::RESET;

    /** @var Game[] $games */
    public $games = array();

    /** @var array $signs */
    public $signs = array();

    /** @var array $bedSetup */
    public $bedSetup = array();

    /** @var string $serverWebsite */
    public $serverWebsite;

    /** @var int $staticStartTime */
    public $staticStartTime;

    /** @var int $staticRestartTime */
    public $staticRestartTime;

    const TEAMS = [
        'blue' => "§1",
        'red' => "§c",
        'yellow' => "§e",
        "green" => "§a",
        "aqua" => "§b",
        "gold" => "§6",
        "white" => "§f"
    ];

    const GENERATOR_PRIORITIES = [
        'gold' => ['item' => Item::GOLD_INGOT, 'spawnText' => false, 'spawnBlock' => false, 'refreshRate' => 10],
        'iron' => ['item' => Item::IRON_INGOT, 'spawnText' => false, 'spawnBlock' => false, 'refreshRate' => 3],
        'diamond' => ['item' => Item::DIAMOND, 'spawnText' => true, 'spawnBlock' => true, 'refreshRate' => 30],
        'emerald' => ['item' => Item::EMERALD, 'spawnText' => true, 'spawnBlock' => true, 'refreshRate' => 60]
    ];

    public function onEnable() : void
    {
        $formAPI = $this->getServer()->getPluginManager()->getPlugin('FormAPI');
        if($formAPI->getDescription()->getAuthors()[0] !== "jojoe77777"){
                $this->getLogger()->error("Invalid dependency author | FormAPI");
                $this->setEnabled(false);
        }

        $this->saveDefaultConfig();
        $this->serverWebsite = $this->getConfig()->get('website');

        @mkdir($this->getDataFolder() . "games");
        @mkdir($this->getDataFolder() . "skins");
        $this->saveResource("skins/264.png");
        $this->saveResource("skins/388.png");

        $this->getScheduler()->scheduleRepeatingTask(
            new SignUpdater($this), 20
        );
        $this->getServer()->getPluginManager()->registerEvents(new GameListener($this), $this);

        foreach(glob($this->getDataFolder() . "games/*.json") as $location){
            $fileContents = file_get_contents($location);
            $jsonData = json_decode($fileContents, true);

            if(!$this->validateGame($jsonData)){
                continue;
            }

            if(count($jsonData['signs']) > 0){
                $this->signs[$jsonData['name']] = $jsonData['signs'];
            }

            $this->games[$jsonData['name']] = $game = new Game($this, $jsonData);
        }

        $this->getServer()->getCommandMap()->register("bedwars", new DefaultCommand($this));
    }

    /**
     * @param string $id
     * @return array|null
     */
    public function getGameData(string $id) : ?array{
        if(!$this->gameExists($id))return null;

        $location = $this->gamePath($id);

        $file = file_get_contents($location);
        return json_decode($file, true);
    }

    /**
     * @param string $id
     * @param int $minPlayers
     * @param int $playersPerTeam
     * @param int $startTime
     */
    public function createGame(string $id, int $minPlayers, int $playersPerTeam, int $startTime, string $world) : void{
        $dataStructure = [
            'name' => $id,
            'minPlayers' => $minPlayers,
            'playersPerTeam' => $playersPerTeam,
            'world' => $world,
            'startTime' => $startTime,
            'signs' => [],
            'teamInfo' => [],
            'generatorInfo' => []
        ];
        file_put_contents($this->gamePath($id), json_encode($dataStructure));
    }

    /**
     * @param string $id
     */
    public function deleteGame(string $id) : void{
        unlink($this->gamePath($id));
    }

    /**
     * @param string $id
     * @param int $x
     * @param int $y
     * @param int $z
     * @param string $levelName
     */
    public function setLobby(string $id, int $x, int $y, int $z, string $levelName, int $voidY) : void{
        $file = file_get_contents($path = $this->gamePath($id));
        $json = json_decode($file, true);

        $json['lobby'] = implode(":", [$x, ($y + 1.5), $z,$levelName]);
        $json['void_y'] = $voidY;
        file_put_contents($path, json_encode($json));
    }

    /**
     * @param string $id
     * @param string $team
     * @param string $keyPos
     * @param int $x
     * @param int $y
     * @param int $z
     */
    public function setTeamPosition(string $id, string $team, string $keyPos, int $x, int $y, int $z, float $yaw, float $pitch) : void{
        $file = file_get_contents($path = $this->gamePath($id));
        $json = json_decode($file, true);
        $key = ['shop', 'upgrade', 'spawn'];

        $json['teamInfo'][$team][$key[$keyPos] . "Pos"] = implode(":", [$x, $y, $z, $yaw, $pitch]);
        file_put_contents($path, json_encode($json));
    }

    /**
     * @param string $id
     * @return array
     */
    public function getTeams(string $id) : array{
        $file = file_get_contents($this->gamePath($id));
        $json = json_decode($file, true);

        $teams = array();
        foreach($json['teamInfo'] as $name => $data){
            $teams[] = $name;
        }
        return $teams;
    }

    /**
     * @param string $id
     * @param string $team
     */
    public function addTeam(string $id, string $team){
        $file = file_get_contents($path = $this->gamePath($id));
        $json = json_decode($file, true);
        $json['teamInfo'][$team] = ['spawnPos' => '', 'bedPos' => '', 'shopPos'];
        file_put_contents($path, json_encode($json));
    }

    /**
     * @param string $id
     * @param string $team
     * @return bool
     */
    public function teamExists(string $id, string $team) : bool{
        $file = file_get_contents($this->gamePath($id));
        if($file == null){
            foreach($this->getServer()->getOnlinePlayers() as $p){
         $p->sendMessage("null file");
        }
            return false;
        }
        foreach($this->getServer()->getOnlinePlayers() as $p){
         $p->sendMessage(strtolower($team));
        }
        $json = json_decode($file, true);
        return isset($json['teamInfo'][strtolower($team)]);
    }

    /**
     * @param string $gameID
     * @return bool
     */
    public function gameExists(string $gameID) : bool {
        if(!is_file($this->gamePath($gameID))){
            return false;
        }
        return true;
    }

    /**
     * @param string $gameName
     * @return bool
     */
    public function isGameLoaded(string $gameName) : bool{
        return isset($this->games[$gameName]);
    }

    /**
     * @param string $id
     * @return string
     */
    public function gamePath(string $id) : string{
        return $this->getDataFolder() . "games/" . $id . ".json";
    }

    /**
     * @param array $arenaData
     * @return bool
     */
    public function validateGame(array $arenaData) : bool{
        $requiredParams = [
            'name',
            'minPlayers',
            'playersPerTeam',
            'lobby',
            'world',
            'teamInfo',
            'generatorInfo',
            'void_y'
        ];

        $error = 0;
        foreach($requiredParams as $param){
            if(!in_array($param, array_keys($arenaData))){
                $error ++;
            }
        }

        return !$error > 0;
    }

    /**
     * @param Player $player
     * @param bool $isSpectator
     * @return Game|null
     */
    public function getPlayerGame(Player $player, bool $isSpectator = false) : ?Game{
        $isSpectator = false;
        foreach($this->games as $game){
            if(isset($game->players[$player->getRawUniqueId()]))return $game;
            if(isset($game->spectators[$player->getRawUniqueId()]))return $game;
        }
        return null;
    }

    /**
     * @param Player $player
     * @return Team|null
     */
    public function getPlayerTeam(Player $player) : ?Team{
        $game = $this->getPlayerGame($player);
        if($game == null)return null;

        foreach($game->teams as $team){
            if(in_array($player->getRawUniqueId(), array_keys($team->getPlayers()))){
                return $team;
            }
        }
        return null;
    }

    public function writeGameData(string $gameName, array $gameData) : void{
        $location = $this->getDataFolder() . "games/" . $gameName . ".json";

        file_put_contents($location, json_encode($gameData));
    }
}<?php


namespace BedWars;

use pocketmine\scheduler\Task;
use pocketmine\level\Level;
use pocketmine\math\Vector3;
use pocketmine\tile\Sign;
use pocketmine\utils\TextFormat;

class SignUpdater extends Task
{

    /** @var BedWars $plugin */
    private $plugin;

    public function __construct(BedWars $plugin)
    {
        $this->plugin = $plugin;
    }

    /**
     * @param int $currentTick
     */
    public function onRun(int $currentTick) : void
    {
        foreach ($this->plugin->signs as $arena => $positions) {
            foreach ($positions as $position) {
                $pos = explode(":", $position);
                $vector = new Vector3(intval($pos[0]), intval($pos[1]), intval($pos[2]));

                $level = $this->plugin->getServer()->getLevelByName($pos[3]);

                if (!$level instanceof Level) {
                    continue;
                }

                if (!in_array($arena, array_keys($this->plugin->games))) {
                    continue;
                }

                $game = $this->plugin->games[$arena];
                $tile = $level->getTile($vector);
                if (!$tile instanceof Sign) {
                    continue;
                }

                $tile->setText(TextFormat::BOLD . TextFormat::DARK_RED . "BedWars",
                    TextFormat::AQUA . "[" . count($game->players) . "/" . $game->getMaxPlayers() . "]",
                    TextFormat::BOLD . TextFormat::GOLD . $game->getName(),
                    $this->getStatus($game->getState()));


            }
        }
    }

    /**
     * @param int $state
     * @return string
     */
    public function getStatus(int $state) : string{
        switch($state){
            case 0;
                return TextFormat::YELLOW . "Touch Me";
            case 1;
                return TextFormat::RED . "InGame";
        }
        return "";
    }

}<?php


namespace BedWars\command;


use BedWars\BedWars;
use BedWars\game\Game;
use BedWars\utils\Utils;
use pocketmine\block\Block;
use pocketmine\block\TNT;
use pocketmine\command\CommandSender;
use pocketmine\command\PluginCommand;
use pocketmine\item\Bed;
use pocketmine\level\Level;
use pocketmine\Player;
use pocketmine\plugin\Plugin;
use pocketmine\utils\Config;
use pocketmine\utils\TextFormat;
use pocketmine\math\Vector3;
use pocketmine\Server;

//form api
use jojoe77777\FormAPI\CustomForm;
use jojoe77777\FormAPI\SimpleForm;
use jojoe77777\FormAPI\Form;


class DefaultCommand extends PluginCommand
{

    /** @var array $errors */
    private $cachedCommandResponse = array();
    /** @var array $cachedResponses */
    private $cachedFormResponse = array();

    /**
     * DefaultCommand constructor.
     * @param BedWars $owner
     */
    public function __construct(BedWars $owner)
    {
        parent::__construct("bedwars", $owner);
        parent::setDescription("BedWars command");
        parent::setPermission("bedwars.command");
    }

    /**
     * @param Player $player
     * @param string $command
     * @return array|null
     */
    public function getErrorsForCommand(Player $player, string $command) : ?array{
        if(!isset($this->cachedCommandResponse[$player->getRawUniqueId()]))return null;
        $errors = $this->cachedCommandResponse[$player->getRawUniqueId()];
        if($errors['command'] == $command && count($errors['errors']) > 0){
                return $errors['errors'];
        }
        return null;
    }

    /**
     * @param Player $player
     * @param string $command
     * @return array|null
     */
    public function getValuesForCommand(Player $player, string $command) : ?array{
        if(!isset($this->cachedCommandResponse[$player->getRawUniqueId()]))return null;
        $values = $this->cachedCommandResponse[$player->getRawUniqueId()];
        if($values['command'] == $command && count($values['values']) > 0){
            return $values['values'];
        }
        return null;
    }

    public function sendFormCustom(Player $player, CustomForm $form, string $command) : void{
        $errors = $this->getErrorsForCommand($player, $command);
        $values = $this->getValuesForCommand($player, $command);

        $form->setTitle("BedWars: Setup Manager");
        switch ($command){
            case "create";
            $form->addInput(isset($errors[0]) ? "GameID: " . $errors[0] : "Game ID", "String/Integer", isset($values[0]) ? $values[0] : "");
            $form->addInput(isset($errors[1]) ? "Minimum players: " . $errors[1] : "Minimum players", "Integer", isset($values[1]) ? $values[1] : "");
            $form->addInput(isset($errors[2]) ? "Players per team: " . $errors[2] : "Players per team", "Integer", isset($values[2]) ? $values[2] : "");
            $form->addInput(isset($errors[3]) ? "Start time: " . $errors[3] : "Start time", "Integer", isset($values[3]) ? $values[3] : "");
            $form->addInput(isset($errors[4]) ? "Map name: " . $errors[4] : "Map name", "String", isset($values[4]) ? $values[4] : "");
          
            $form->sendToPlayer($player);
            break;
            case 'addteam';
            $form->addInput(isset($errors[0]) ? "GameID: " . $errors[0] : "Game ID", "String/Integer", isset($values[0]) ? $values[0] : "");
            $form->addDropdown(isset($errors[1]) ? "Team: " . $errors[1] : "Team", array_keys(BedWars::TEAMS), isset($values[1]) ? $values[1] : null);
            $form->sendToPlayer($player);
            break;
            case "delete";
            $form->addInput(isset($errors[0]) ? "GameID: " . $errors[0] : "Game ID", "String/Integer", isset($values[0]) ? $values[0] : "");
            $form->sendToPlayer($player);
            break;
            case "setlobby";
            $form->addInput(isset($errors[0]) ? "GameID: " . $errors[0] : "Game ID", "String/Integer", isset($values[0]) ? $values[0] : "");
            $form->addInput(isset($errors[1]) ? "Coord X: " . $errors[0] : "Coord X", "Integer/Float", isset($values[1]) ? $values[1] : $player->getX());
            $form->addInput(isset($errors[2]) ? "Coord Y: " . $errors[0] : "Coord Y", "Integer/Float", isset($values[2]) ? $values[2] : $player->getY());
            $form->addInput(isset($errors[3]) ? "Coord Z: " . $errors[0] : "Coord Z", "Integer/Float", isset($values[3]) ? $values[3] : $player->getZ());
            $form->addInput(isset($errors[4]) ? "Level name: " . $errors[4] : "Level name", "String", isset($values[4]) ? $values[4] : "");
            $form->sendToPlayer($player);
            break;
            case "setposition";
            $form->addInput(isset($errors[0]) ? "GameID: " . $errors[0] : "Game ID", "String/Integer", isset($values[0]) ? $values[0] : "");
            $form->addDropdown(isset($errors[1]) ? "Team: " . $errors[1] : "Team", array_keys(BedWars::TEAMS), isset($values[1]) ? $values[1] : null);
            $form->addDropdown("Position", array('ShopClassic', 'ShopUpgrades', 'Spawn'), isset($values[2]) ? $values[2] : null);
            $form->addInput(isset($errors[0]) ? "Coord X: " . $errors[0] : "Coord X", "Integer/Float", isset($values[1]) ? $values[1] : $player->getX());
            $form->addInput(isset($errors[0]) ? "Coord Y: " . $errors[0] : "Coord Y", "Integer/Float", isset($values[2]) ? $values[2] : $player->getY());
            $form->addInput(isset($errors[0]) ? "Coord Z: " . $errors[0] : "Coord Z", "Integer/Float", isset($values[3]) ? $values[3] : $player->getZ());
            $form->sendToPlayer($player);
            break;
            case "setbed";
            $form->addInput(isset($errors[0]) ? "GameID: " . $errors[0] : "Game ID", "String/Integer", isset($values[0]) ? $values[0] : "");
            $form->addDropdown(isset($errors[1]) ? "Team: " . $errors[1] : "Team", array_keys(BedWars::TEAMS), isset($values[1]) ? $values[1] : null);
            $form->sendToPlayer($player);
            break;
            case "setgenerator";
            $form->addInput(isset($errors[0]) ? "GameID: " . $errors[0] : "Game ID", "String/Integer", isset($values[0]) ? $values[0] : "");
            $form->addDropdown(isset($errors[2]) ? "Type: " . $errors[2] : "Type", array("Diamond", "Emerald", "Gold", "Iron"), isset($values[2]) ? $values[2] : null);
            $form->sendToPlayer($player);
            break;
        }

        if($errors !== null) {
            unset($this->cachedCommandResponse[$player->getRawUniqueId()]);
        }
        $this->cachedFormResponse[$command] = $form;
        $refOb = new \ReflectionObject($this->cachedFormResponse[$command]);
        $property = $refOb->getProperty('data');
        $property->setAccessible(true);
        $clonedData = $property->getValue($this->cachedFormResponse[$command]);
        $clonedData['content'] = [];
        $property->setValue($this->cachedFormResponse[$command], $clonedData);
    }

    /**
     * @param CommandSender $sender
     * @param string $commandLabel
     * @param array $args
     * @return bool|mixed|void
     */
    public function execute(CommandSender $sender, string $commandLabel, array $args)
    {
        if(empty($args[0])){

            return;
        }

        switch(strtolower($args[0])){
            case "list";
            commandList:
            $listForm = new SimpleForm(function (Player $player, ?array $data){
                if($data === null) {
                    return;
                }

                $gameClicked = $this->getPlugin()->games((int)$data);

            });

            foreach($this->getPlugin()->games as $game){
                $listForm->addButton(TextFormat::YELLOW . $game->getName() . "\n" . TextFormat::RESET . "Click to edit");
            }
            break;
            case "create";
            if(!$sender instanceof Player){
                $sender->sendMessage(TextFormat::RED . "This command can be executed only in game");
                return;
            }

            commandCreate:

            $createForm = new CustomForm(function(Player $player, ?array $data){
                if($data === null) {
                    return;
                }

                $error = array();

                if(isset($data[0]) && $data[0] !== ""){
                    if(strlen($data[0]) < 5){
                        $error[0] = TextFormat::RED . "Too short";
                        goto b;
                    }

                    if($this->getPlugin()->gameExists($data[0])){
                        $error[0] = TextFormat::RED . "Already exists";
                    }
                }else{
                    $error[0] = TextFormat::RED . "Column can't be blank";
                }
                b:

                if(isset($data[1]) && $data[1] !== ""){
                    if(!is_int((int)$data[1])){
                        $error[1] = TextFormat::RED . "Must be an Integer";
                        goto c;
                    }

                    if((int)$data[1] < 1){
                        $error[1] = TextFormat::RED . "Must be higher than 0";
                    }
                }else{
                    $error[1] = TextFormat::RED . "Column can't be blank";
                }
                c:

                if(isset($data[2]) && $data[2] !== ""){
                    if(!is_int((int)$data[2])){
                        $error[2] = TextFormat::RED . "Must be an Integer";
                        goto d;
                    }

                    if((int)$data[2] < 1){
                        $error[2] = TextFormat::RED . "Must be higher than 0";
                    }
                }else{
                    $error[2] = TextFormat::RED . "Column can't be blank";
                }
                d:

                if(isset($data[3]) && $data[3] !== ""){
                    if(!is_int((int)$data[3])){
                        $error[3] = TextFormat::RED . "Must be an Integer";
                        goto e;
                    }

                    if((int)$data[3] < 1){
                        $error[3] = TextFormat::RED . "Must be higher than 0";
                    }

                }else{
                    $error[3] = TextFormat::RED . "Column can't be blank";
                }

                if(isset($data[4]) && $data[4] !== ""){
                    if(strlen($data[4]) <= 1){
                        $error[4] = TextFormat::RED . "Too short";
                    }
                    if(!Server::getInstance()->loadLevel($data[4])){
                        $error[4] = TextFormat::RED . "Level not found or corrupt";
                    }
                    if(!Server::getInstance()->isLevelLoaded($data[4])){
                        $error[4] = TextFormat::RED . "Level not loaded";
                    }
                }else{
                    $error[4] = TextFormat::RED . "Column can't be blank";
                }
                e:

                if(count($error) > 0){
                    $this->cachedCommandResponse[$player->getRawUniqueId()] = array('command' => 'create', 'errors' => $error, 'values' => $data);
                    $this->sendFormCustom($player, $this->cachedFormResponse['create'], 'create');
                }else{
                    $this->getPlugin()->createGame($data[0], $data[1], $data[2], $data[3], $data[4]);
                    $player->sendMessage(TextFormat::GREEN . "Game created");
                }
            });
            $this->sendFormCustom($sender, $createForm, 'create');
            break;
            case "addteam";
            if(!$sender instanceof Player){
                $sender->sendMessage(TextFormat::RED . "This command can be executed only in game");
                return;
            }

            commandAddteam:

            $addteamForm = new CustomForm(function(Player $player, ?array $data){
                if($data === null){
                    return;
                }

                $error = array();
                if(isset($data[0]) && $data[0] !== ""){
                    if(!$this->getPlugin()->gameExists($data[0])){
                        $error[0] = TextFormat::RED . "Doesn't exist";
                    }
                }else{
                    $error[0] = TextFormat::RED . "Column can't be blank";
                }
                if(isset($data[1]) && $data[1] !== ""){
                $find = false;
                    foreach(BedWars::TEAMS as $team2 => $color){
                        if($team2 === strtolower(array_keys(BedWars::TEAMS)[$data[1]])){
                            $find = true;
                        }
                    }
                    if(!$find){
                        $error[1] = TextFormat::RED . "Invalid team";
                    }

                    if($this->getPlugin()->teamExists($data[0], array_keys(BedWars::TEAMS)[$data[1]])){
                        $error[1] = TextFormat::RED . "Already exists for " . $data[0];
                    }
                }else{
                    $error[1] = TextFormat::RED . "Column can't be blank";
                }

                if(count($error) > 0){
                    $this->cachedCommandResponse[$player->getRawUniqueId()] = array('command' => 'addteam', 'errors' => $error, 'values' => $data);
                    $this->sendFormCustom($player, $this->cachedFormResponse['addteam'], 'addteam');
                }else{
                    $this->getPlugin()->addTeam($data[0], array_keys(BedWars::TEAMS)[$data[1]]);
                    $player->sendMessage(TextFormat::GREEN . "Team added");
                }
            });
            $this->sendFormCustom($sender, $addteamForm, 'addteam');
            break;
            case "delete";
            if(!$sender instanceof Player){
                $sender->sendMessage(TextFormat::RED . "This command can be executed only in game");
                return;
            }

            commandDelete:

            $deleteForm = new CustomForm(function(Player $player, ?array $data){
                if($data === null){
                    return;
                }

                $error = array();

                if(isset($data[0]) && $data[0] !== ""){
                    if(!$this->getPlugin()->gameExists($data[0])){
                        $error[0] = TextFormat::RED . "Doesn't exist";
                    }
                }else{
                    $error[0] = TextFormat::RED . "Column can't be blank";
                }

                if(count($error) > 0){
                    $this->cachedCommandResponse[$player->getRawUniqueId()] = array('command' => 'delete', 'errors' => $error, 'values' => $data);
                    $this->sendFormCustom($player, $this->cachedFormResponse['delete'], 'delete');
                }else{
                    $this->getPlugin()->deleteGame($data[0]);
                    $player->sendMessage(TextFormat::GREEN . "Game deleted");
                }
            });
            $this->sendFormCustom($sender, $deleteForm, 'delete');
            break;
            case "setlobby";
            if(!$sender instanceof Player){
                $sender->sendMessage(TextFormat::RED . "This command can be executed only in game");
                return;
            }

            $setlobbyForm = new CustomForm(function(Player $player, ?array $data){
                if($data === null){
                    return;
                }

                $error = array();

                if(isset($data[0]) && $data[0] !== ""){
                    if(!$this->getPlugin()->gameExists($data[0])){
                        $error[0] = TextFormat::RED . "Doesn't exist";
                    }
                }else{
                    $error[0] = TextFormat::RED . "Column can't be blank";
                }
                if(isset($data[1]) && $data[1] !== ""){
                    if(!is_numeric($data[1])){
                        $error[1] = TextFormat::RED . "Must be numeric";
                    }
                }else{
                    $error[1] = TextFormat::RED . "Column can't be blank";
                }
                if(isset($data[2]) && $data[2] !== ""){
                    if(!is_numeric($data[2])){
                        $error[2] = TextFormat::RED . "Must be numeric";
                    }
                }else{
                    $error[2] = TextFormat::RED . "Column can't be blank";
                }
                if(isset($data[3]) && $data[3] !== ""){
                    if(!is_numeric($data[3])){
                        $error[3] = TextFormat::RED . "Must be numeric";
                    }
                }else {
                    $error[3] = TextFormat::RED . "Column can't be blank";
                }

                if(isset($data[4]) && $data[4] !== ""){
                    if(!Server::getInstance()->isLevelLoaded($data[4])){
                        $error[4] = TextFormat::RED . "Level not loaded";
                    }
                }else {
                    $error[4] = TextFormat::RED . "Column can't be blank";
                }

                if(count($error) > 0){
                    $this->cachedCommandResponse[$player->getRawUniqueId()] = array('command' => 'setlobby', 'errors' => $error, 'values' => $data);
                    $this->sendFormCustom($player, $this->cachedFormResponse['setlobby'], 'setlobby');
                }else{
                    $level = $player->level;
                    $void_y = Level::Y_MAX;
                     foreach ($level->getChunks() as $chunk) {
                         for ($x = 0; $x < 16; ++$x) {
                             for ($z = 0; $z < 16; ++$z) {
                                 for ($y = 0; $y < $void_y; ++$y) {
                                      $block = $chunk->getBlockId($x, $y, $z);
                                      if ($block !== Block::AIR) {
                                           $void_y = $y;
                                          break;
                                      }
                                  }
                              }
                          }
                      }
                     --$void_y;

                    $this->getPlugin()->setLobby($data[0], $data[1], $data[2], $data[3], $data[4], $void_y);
                    $player->sendMessage(TextFormat::GREEN . "Lobby set");
                }
            });
            $this->sendFormCustom($sender, $setlobbyForm, 'setlobby');
            break;
            case "setposition";
            if(!$sender instanceof Player){
                $sender->sendMessage(TextFormat::RED . "This command can be executed only in game");
                return;
            }

            $setpositionForm = new CustomForm(function(Player $player, ?array $data){
                if($data === null){
                    return;
                }

                $error = array();

                if(isset($data[0]) && $data[0] !== ""){
                    if(!$this->getPlugin()->gameExists($data[0])){
                        $error[0] = TextFormat::RED . "Doesn't exist";
                    }
                }else{
                    $error[0] = TextFormat::RED . "Column can't be blank";
                }

                if(isset($data[1]) && $data[1] !== ""){
                    if(!$this->getPlugin()->teamExists($data[0], strtolower(array_keys(BedWars::TEAMS)[$data[1]]))){
                        $error[1] = TextFormat::RED . "Doesn't exist";
                    }
                }else{
                    $error[1] = TextFormat::RED . "Column can't be blank";
                }

                if(isset($data[2]) && $data[2] !== ""){
                    if(!is_numeric($data[2])){
                        $error[2] = TextFormat::RED . "Must be numeric";
                    }
                }else{
                    $error[2] = TextFormat::RED . "Column can't be blank";
                }

                if(isset($data[3]) && $data[3] !== ""){
                    if(!is_numeric($data[3])){
                        $error[3] = TextFormat::RED . "Must be numeric";
                    }
                }else{
                    $error[3] = TextFormat::RED . "Column can't be blank";
                }
                if(isset($data[4]) && $data[4] !== ""){
                    if(!is_numeric($data[4])){
                        $error[4] = TextFormat::RED . "Must be numeric";
                    }
                }else {
                    $error[4] = TextFormat::RED . "Column can't be blank";
                }

                if(count($error) > 0){
                    $this->cachedCommandResponse[$player->getRawUniqueId()] = array('command' => 'setposition', 'errors' => $error, 'values' => $data);
                    $this->sendFormCustom($player, $this->cachedFormResponse['setposition'], 'setposition');
                }else{
                    $this->getPlugin()->setTeamPosition($data[0], array_keys(BedWars::TEAMS)[$data[1]], $data[2], (int)$data[3], (int)$data[4], (int)$data[5], (float) $player->getYaw(), (float) $player->getPitch());
                    $player->sendMessage(TextFormat::GREEN . "Position set");
                }
            });

            $this->sendFormCustom($sender, $setpositionForm, 'setposition');
            break;
            case "setbed";
            if(!$sender instanceof Player){
                $sender->sendMessage(TextFormat::RED . "This command can be executed only in game");
                return;
            }

            $setbedForm = new CustomForm(function(Player $player, ?array $data){

                if($data === null){
                    return;
                }

                $error = array();

                if(isset($data[0]) && $data[0] !== ""){
                    if(!$this->getPlugin()->gameExists($data[0])){
                        $error[0] = TextFormat::RED . "Doesn't exist";
                    }
                }else{
                    $error[0] = TextFormat::RED . "Column can't be blank";
                }
                if(isset($data[1]) && $data[1] !== ""){
                    if(!$this->getPlugin()->teamExists($data[0], strtolower(array_keys(BedWars::TEAMS)[$data[1]]))){
                        $error[1] = TextFormat::RED . "Doesn't exist";
                    }
                }else{
                    $error[1] = TextFormat::RED . "Column can't be blank";
                }

                if(count($error) > 0){
                    $this->cachedCommandResponse[$player->getRawUniqueId()] = array('command' => 'setbed', 'errors' => $error, 'values' => $data);
                    $this->sendFormCustom($player, $this->cachedFormResponse['setbed'], 'setbed');
                }else{
                    $this->getPlugin()->bedSetup[$player->getRawUniqueId()] = ['game' => $data[0], 'team' => array_keys(BedWars::TEAMS)[$data[1]], 'step' => 1];
                    $player->sendMessage(TextFormat::RED . "Break the bed");
                }
            });

            $this->sendFormCustom($sender, $setbedForm, 'setbed');
            break;
            case "setgenerator";
            $setgeneratorForm = new CustomForm(function(Player $player, ?array $data) {
                if($data === null){
                    return;
                }

                $error = array();

                if(isset($data[0]) && $data[0] !== ""){
                    if(!$this->getPlugin()->gameExists($data[0])){
                        $error[0] = TextFormat::RED . "Doesn't exist";
                    }
                }else{
                    $error[0] = TextFormat::RED . "Column can't be blank";
                }
                $gens = array("Diamond", "Emerald", "Gold", "Iron");
                $generator = null;
                if(isset($data[1]) && $data[1] !== ""){
                    $generator = strtolower($gens[$data[1]]);
                }else{
                    $error[0] = TextFormat::RED . "Column can't be blank";
                }

                if(count($error) > 0){
                    $this->cachedCommandResponse[$player->getRawUniqueId()] = array('command' => 'setgenerator', 'errors' => $error, 'values' => $data);
                    $this->sendFormCustom($player, $this->cachedFormResponse['setgenerator'], 'setgenerator');
                }else if($generator !== null){
                    $arenaData = $this->getPlugin()->getGameData($data[0]);
                    $arenaData['generatorInfo'][$data[0]][] = ['type' => $generator, 'position' => Utils::vectorToString("", $player), 'game'];
                    $this->getPlugin()->writeGameData($data[0], $arenaData);
                    $player->sendMessage(TextFormat::GREEN . "Generator added ".$generator);
                }
            });
            $this->sendFormCustom($sender, $setgeneratorForm, 'setgenerator');
            break;
        }
    }
}<?php


namespace BedWars\game;

use BedWars\game\player\PlayerCache;
use BedWars\utils\Utils;
use pocketmine\entity\Entity;
use pocketmine\event\entity\EntityDamageByChildEntityEvent;
use pocketmine\event\entity\EntityDamageEvent;
use pocketmine\item\Compass;
use pocketmine\item\enchantment\Enchantment;
use pocketmine\item\enchantment\EnchantmentInstance;
use pocketmine\item\Item;
use pocketmine\level\Level;
use pocketmine\level\Position;
use pocketmine\Player;
use pocketmine\plugin\Plugin;
use pocketmine\scheduler\Task;
use pocketmine\utils\TextFormat;
use pocketmine\math\Vector3;
use pocketmine\nbt\tag\CompoundTag;
use pocketmine\nbt\tag\IntTag;
use pocketmine\Server;
use BedWars\BedWars;

class Game
{

    const STATE_LOBBY = 0;
    const STATE_RUNNING = 1;
    const STATE_REBOOT = 2;

    /** @var BedWars $plugin */
    private $plugin;

    /** @var string $gameName */
    private $gameName;

    /** @var int $minPlayers */
    private $minPlayers;

    /** @var int $maxPlayers */
    private $maxPlayers;

    /** @var int $playersPerTeam */
    public $playersPerTeam;

    /** @var string $worldName */
    public $worldName;

    /** @var string $lobbyName */
    private $lobbyName;

    /** @var int $state */
    private $state = self::STATE_LOBBY;

    /** @var array $players */
    public $players = array();

    /** @var array $spectators */
    public $spectators = array();

    /** @var bool $starting */
    private $starting = false;

    /** @var Vector3 $lobby */
    private $lobby;

    /** @var int $startTime */
    private $startTime;
    private $startTimeSaver;

    /** @var int $rebootTime */
    private $rebootTime;

    /** @var int $voidY */
    private $voidY ;

    /** @var array $teamInfo */
    public $teamInfo = array();

    /** @var array $teams */
    public $teams = array();

    /** @var array $deadQueue */
    public $deadQueue = [];

    /** @var string $winnerTeam */
    private $winnerTeam = '';

    /** @var Entity[] $npcs */
    public $npcs = [];

    /** @var array $trackingPositions */
    private $trackingPositions = [];

    /** @var Generator[] $generators */
    public $generators = array();

    /** @var array $generatorInfo */
    private $generatorInfo = array();

    /** @var float|int $tierUpdate */
    private $tierUpdate = 60 * 10;

    /** @var string $tierUpdateGen */
    private $tierUpdateGen = "diamond";

    /** @var array $placedBlocks */
    public $placedBlocks = array();

    /** @var PlayerCache[] $cachedPlayers */
    private $cachedPlayers = array();

    /**
     * Game constructor.
     * @param BedWars $plugin
     * @param array $data
     */
    public function __construct(BedWars $plugin, array $data)
    {
        $this->plugin = $plugin;
        $this->startTime = $data['startTime'];
        $this->startTimeSaver = $data['startTime'];
        $this->rebootTime = 10;
        $this->gameName = $data['name'];
        $this->minPlayers = $data['minPlayers'];
        $this->playersPerTeam = $data['playersPerTeam'];
        $this->worldName = $data['world'];
        $this->teamInfo = $data['teamInfo'];
        $this->voidY = $data['void_y'];
        $lobby = explode(":", $data['lobby']);
        $this->lobbyName = $lobby[3];
        $this->lobby = Utils::stringToVector(":", $data['lobby']); 
        #echo "&&".$lobby[0]."&&++-+++++".$this->lobbyName."+----";
  
        $this->generatorInfo = !isset($data['generatorInfo'][$this->gameName]) ? [] : $data['generatorInfo'][$this->gameName];

        foreach($this->teamInfo as $teamName => $data){
            $this->teams[$teamName] = new Team($teamName, BedWars::TEAMS[strtolower($teamName)]);
        }

        $this->maxPlayers = count($this->teams) * $this->playersPerTeam;
        $this->reload();
        $this->plugin->getScheduler()->scheduleRepeatingTask(new GameTick($this), 20);
    }

    /**
     * @param int $limit
     */
    public function setVoidLimit(int $limit) : void{
        $this->voidY = $limit;
    }

    /**
     * @param Vector3 $lobby
     * @param string $worldName
     */
    public function setLobby(Vector3 $lobby, string $worldName) : void{
        $this->lobby = new Position($lobby->x, $lobby->y, $lobby->z, $this->plugin->getServer()->getLevelByName($worldName));
    }

    /**
     * @return int
     */
    public function getVoidLimit() : int{
        return $this->voidY;
    }

    /**
     * @return int
     */
    public function getState() : int{
        return $this->state;
    }

    /**
     * @return string
     */
    public function getName() : string{
        return $this->gameName;
    }

    /**
     * @return string
     */
    public function getMaxPlayers() : int{
        return $this->maxPlayers;
    }

    public function reload() : void{
        $this->plugin->getServer()->loadLevel($this->worldName);
        $world = $this->plugin->getServer()->getLevelByName($this->worldName);
        if(!$world instanceof Level){
            $this->plugin->getLogger()->info(BedWars::PREFIX . TextFormat::YELLOW . "Failed to load arena " . $this->gameName . " because it's world does not exist!");
            return;
        }
        $world->setAutoSave(false);
    }

    /**
     * @param string $message
     */
    public function broadcastMessage(string $message) : void{
        foreach(array_merge($this->spectators, $this->players) as $player){
            $player->sendMessage(BedWars::PREFIX . $message);
        }
    }

    /**
     * @return array
     */
    public function getAliveTeams() : array{
        $teams = [];
        foreach($this->teams as $team){
            if(count($team->getPlayers()) <= 0 || !$team->hasBed())continue;
            $players = [];

            foreach($team->getPlayers() as $player){
                if(!$player->isOnline())continue;
                if($player->isAlive() && $player->getLevel()->getFolderName() == $this->worldName){
                    $players[] = $player;
                }
            }

            if(count($players) >= 1){
                $teams[] = $team->getName();
            }
        }
        return $teams;
    }

    public function stop() : void{
        foreach(array_merge($this->players, $this->spectators) as $player){
            $this->cachedPlayers[$player->getRawUniqueId()]->load();
            \BedWars\utils\Scoreboard::remove($player);
        }

        foreach($this->teams as $team){
            $team->reset();
        }

        foreach($this->generators as $generator){
            if($generator->getBlockEntity() !== null){
                $generator->getBlockEntity()->flagForDespawn();
            }

            if($generator->getFloatingText() !== null){
                $generator->getFloatingText()->setInvisible(true);
                foreach($this->plugin->getServer()->getOnlinePlayers() as $player){
                    foreach($generator->getFloatingText()->encode() as $packet){
                        $player->dataPacket($packet);
                    }
                }
            }
        }

        $this->spectators = array();
        $this->players = array();
        $this->winnerTeam = '';
        $this->startTime = $this->startTimeSaver;
        $this->rebootTime = 10;
        $this->generators = array();
        $this->cachedPlayers = array();
        $this->state = self::STATE_LOBBY;
        $this->starting = false;
        $this->plugin->getServer()->unloadLevel($this->plugin->getServer()->getLevelByName($this->worldName));
        $this->reload();

        $this->setLobby(new Vector3($this->lobby->x, $this->lobby->y, $this->lobby->z), $this->lobbyName);

    }

    public function start() : void{
         $this->broadcastMessage(TextFormat::GREEN . "Game has started! ");
         $this->state = self::STATE_RUNNING;

         foreach($this->players as $player){
             $playerTeam = $this->plugin->getPlayerTeam($player);

             if($playerTeam == null){
                 $players = array();
                 foreach($this->teams as $name => $object){
                     $players[$name] = count($object->getPlayers());
                 }

                 $lowest = min($players);
                 $teamName = array_search($lowest, $players);

                 $team = $this->teams[$teamName];
                 $team->add($player);
                 $playerTeam = $team;
             }

             $playerTeam->setArmor($player, 'leather');

             $this->respawnPlayer($player);
             $player->setNameTag(TextFormat::BOLD . $playerTeam->getColor() . strtoupper($playerTeam->getName()[0]) . " " .  TextFormat::RESET . $playerTeam->getColor() . $player->getName());

             $this->trackingPositions[$player->getRawUniqueId()] = $playerTeam->getName();
             $player->setSpawn(Utils::stringToVector(":",  $spawnPos = $this->teamInfo[$playerTeam->getName()]['spawnPos']));
         }

         $this->initShops();
         $this->initGenerators();
         $this->initTeams();
    }

    private function initTeams() : void{
        foreach($this->teams as $team){
            if(count($team->getPlayers()) === 0){
                $team->updateBedState(false);
            }
        }
    }

    private function initGenerators() : void{
        foreach($this->generatorInfo as $generator){
            $generatorData = BedWars::GENERATOR_PRIORITIES[$generator['type']];
            $item = $generatorData['item'];
            $spawnText = $generatorData['spawnText'];
            $spawnBlock = $generatorData['spawnBlock'];
            $delay = $generatorData['refreshRate'];

            $vector = Utils::stringToVector(":", $generator['position']);
            $position = new Position($vector->x, $vector->y, $vector->z,$this->plugin->getServer()->getLevelByName($this->worldName));

            $this->generators[] = new Generator($item, $delay,$position, $spawnText, $spawnBlock);

        }
    }

    private function initShops() : void{
        foreach($this->teamInfo as $team => $info){
            $shopPos = Utils::stringToVector(":", $info['shopPos']);
            $rotation = explode(":", $info['shopPos']);

            $nbt = Entity::createBaseNBT($shopPos->add(0.5, 0, 0.5), null, $rotation[3], $rotation[4]);
            $entity = Entity::createEntity("Villager", $this->plugin->getServer()->getLevelByName($this->worldName), $nbt);
            $entity->setNameTag(TextFormat::AQUA . "ITEM SHOP\n" . TextFormat::BOLD . TextFormat::YELLOW . "TAP TO USE");
            $entity->setNameTagAlwaysVisible(true);
            $entity->spawnToAll();

            $this->npcs[$entity->getId()] = [$team, 'shop'];

            $upgradePos = Utils::stringToVector(":", $info['upgradePos']);
            $rotation = explode(":", $info['upgradePos']);
            

            $nbt = Entity::createBaseNBT($upgradePos, null, $rotation[3], $rotation[4]);
            $entity = Entity::createEntity("Villager", $this->plugin->getServer()->getLevelByName($this->worldName), $nbt);
            $entity->setNameTag(TextFormat::AQUA . "TEAM UPGRADES\n" . TextFormat::BOLD . TextFormat::YELLOW . "TAP TO USE");
            $entity->setNameTagAlwaysVisible(true);
            $entity->spawnToAll();

            $this->npcs[$entity->getId()] = [$team, 'upgrade'];
        }
    }

    /**
     * @param Player $player
     */
    public function join(Player $player) : void{
         if($this->state !== self::STATE_LOBBY){
             $player->sendMessage(BedWars::PREFIX . TextFormat::YELLOW . "Arena is full!");
             return;
         }

         $this->cachedPlayers[$player->getRawUniqueId()] = new PlayerCache($player);
         $this->plugin->getServer()->loadLevel($this->worldName);
        
         
         $player->teleport(Server::getInstance()->getLevelByName($this->worldName)->getSafeSpawn()); 
         $player->teleport($this->lobby);
         $this->players[$player->getRawUniqueId()] = $player;

         $this->broadcastMessage(TextFormat::GRAY . $player->getName() . " " . TextFormat::YELLOW . "has joined the game " . TextFormat::GOLD . "(" . TextFormat::AQUA .  count($this->players) . TextFormat::YELLOW . "/" . TextFormat::AQUA .  $this->maxPlayers . TextFormat::YELLOW .  ")");
         $player->getInventory()->clearAll();
         $a = 0;
         $items = array_fill(0, count($this->teams), Item::get(Item::WOOL));
         foreach($this->teams as $team){
             $items[$a]->setDamage(Utils::colorIntoWool($team->getColor()));
             $player->getInventory()->addItem($items[$a]);
             $a++;
         }

         $player->getInventory()->setItem(8, Item::get(Item::COMPASS)->setCustomName(TextFormat::YELLOW . "Leave"));
         $this->checkLobby();

        \BedWars\utils\Scoreboard::new($player, 'bedwars', TextFormat::BOLD . TextFormat::YELLOW . "Bed Wars");

        \BedWars\utils\Scoreboard::setLine($player, 1, " ");
        \BedWars\utils\Scoreboard::setLine($player, 2, " " . TextFormat::WHITE ."Map: " . TextFormat::GREEN .  $this->gameName . str_repeat(" ", 3));
        \BedWars\utils\Scoreboard::setLine($player, 3, " " . TextFormat::WHITE . "Players: " . TextFormat::GREEN . count($this->players) . "/" . $this->maxPlayers . str_repeat(" ", 3));
        \BedWars\utils\Scoreboard::setLine($player, 4, "  ");
        \BedWars\utils\Scoreboard::setLine($player, 5, " " . $this->starting ? TextFormat::WHITE . "Starting in " . TextFormat::GREEN .  $this->startTime . str_repeat(" ", 3) : TextFormat::GREEN . "Waiting for players..." . str_repeat(" ", 3));
        \BedWars\utils\Scoreboard::setLine($player, 6, "   ");
        \BedWars\utils\Scoreboard::setLine($player, 7, " " . TextFormat::WHITE . "Mode: " . TextFormat::GREEN . substr(str_repeat($this->playersPerTeam . "v", count($this->teams)), 0, -1) . str_repeat(" ", 3));
        \BedWars\utils\Scoreboard::setLine($player, 8, " " . TextFormat::WHITE . "Version: " . TextFormat::GRAY . "v1.0" . str_repeat(" ", 3));
        \BedWars\utils\Scoreboard::setLine($player, 9, "    ");
        \BedWars\utils\Scoreboard::setLine($player, 10, " " . TextFormat::YELLOW . "www.example.net");
    }

    /**
     * @param Player $player
     */
    public function trackCompass(Player $player) : void{
        $currentTeam = $this->trackingPositions[$player->getRawUniqueId()];
        $arrayTeam = $this->teams;
        $position = array_search($currentTeam, array_keys($arrayTeam));
        $teams = array_values($this->teams);
        $team = null;

        if(isset($teams[$position+1])){
            $team = $teams[$position+1]->getName();
        }else{
            $team = $teams[0]->getName();
        }

        $this->trackingPositions[$player->getRawUniqueId()] = $team;

        $player->setSpawn(Utils::stringToVector(":",  $spawnPos = $this->teamInfo[$team]['spawnPos']));
        $player->setSpawn(Utils::stringToVector(":",  $spawnPos = $this->teamInfo[$team]['spawnPos']));

        foreach($player->getInventory()->getContents() as $slot => $item){
            if($item instanceof Compass){
                $player->getInventory()->removeItem($item);
                $player->getInventory()->setItem($slot, Item::get(Item::COMPASS)->setCustomName(TextFormat::GREEN . "Tap to switch"));
            }
        }
    }

    /**
     * @param Team $team
     * @param Player $player
     */
    public function breakBed(Team $team, Player $player) : void{
        $team->updateBedState(false);

        $playerTeam = $this->plugin->getPlayerTeam($player);

        $this->broadcastMessage($team->getColor() . $team->getName() . "'s '" . TextFormat::GRAY . "bed was destroyed by " . $playerTeam->getColor() . $player->getName());
        foreach($team->getPlayers() as $player){
            $player->addTitle(TextFormat::RED . "Bed Destroyed!", TextFormat::GRAY . "You will no longer respawn");
        }
    }

    /**
     * @param Player $player
     */
    public function quit(Player $player) : void{
         if(isset($this->players[$player->getRawUniqueId()])){
             $team = $this->plugin->getPlayerTeam($player);
             if($team instanceof Team){
                 $team->remove($player);
             }
             unset($this->players[$player->getRawUniqueId()]);
         }
         if(isset($this->spectators[$player->getRawUniqueId()])){
             unset($this->spectators[$player->getRawUniqueId()]);
         }



         \BedWars\utils\Scoreboard::remove($player);
    }

    private function checkLobby() : void{
        if(!$this->starting && count($this->players) >= $this->minPlayers) {
            $this->starting = true;
            $this->broadcastMessage(TextFormat::GREEN . "Countdown started");
        }
    }

    /**
     * @param Player $player
     */
    public function killPlayer(Player $player) : void{
        $playerTeam = $this->plugin->getPlayerTeam($player);
        if($player->isSpectator())return;

        if(!$playerTeam->hasBed()){
            $playerTeam->dead++;
            $this->spectators[$player->getRawUniqueId()] = $player;
            unset($this->players[$player->getRawUniqueId()]);
            $player->setGamemode(Player::SPECTATOR);
            $player->addTitle(TextFormat::BOLD . TextFormat::RED . "Bed Destroyed!", TextFormat::GRAY . "You will no longer respawn");
        }else{
            $player->setGamemode(Player::SPECTATOR);
            $this->deadQueue[$player->getRawUniqueId()] = 5;
         }

        $cause = $player->getLastDamageCause();
        if($cause == null)return; //probadly handled the event itself
        switch($cause->getCause()){
            case EntityDamageEvent::CAUSE_ENTITY_ATTACK;
            $damager = $cause->getDamager();
            $this->broadcastMessage($this->plugin->getPlayerTeam($player)->getColor() . $player->getName() . " " . TextFormat::GRAY . "was killed by " . $this->plugin->getPlayerTeam($damager)->getColor() . $damager->getName());
            break;
            case EntityDamageEvent::CAUSE_PROJECTILE;
            if($cause instanceof EntityDamageByChildEntityEvent){
                $damager = $cause->getDamager();
                $this->broadcastMessage($this->plugin->getPlayerTeam($player)->getColor() . $player->getName() . " " . TextFormat::GRAY . "was shot by " . $this->plugin->getPlayerTeam($damager)->getColor() . $damager->getName());
            }
            break;
            case EntityDamageEvent::CAUSE_FIRE;
            $this->broadcastMessage($this->plugin->getPlayerTeam($player)->getColor() . $player->getName() . " " . TextFormat::GRAY . "went up in flame");
            break;
            case EntityDamageEvent::CAUSE_VOID;
            $player->teleport($player->add(0, $this->voidY + 5, 0));
            break;
        }

    }



    /**
     * @param Player $player
     */
    public function respawnPlayer(Player $player) : void{
        $team = $this->plugin->getPlayerTeam($player);
        if($team == null)return;

        $spawnPos = $this->teamInfo[$team->getName()]['spawnPos'];

        $player->setGamemode(Player::SURVIVAL);
        $player->setFood($player->getMaxFood());
        $player->setHealth($player->getMaxHealth());
        $player->getInventory()->clearAll();

        $player->teleport($this->plugin->getServer()->getLevelByName($this->worldName)->getSafeSpawn());
        $player->teleport(Utils::stringToVector(":", $spawnPos));

        //inventory
        $helmet = Item::get(Item::LEATHER_CAP);
        $chestplate = Item::get(Item::LEATHER_CHESTPLATE);
        $leggings = Item::get(Item::LEATHER_LEGGINGS);
        $boots = Item::get(Item::LEATHER_BOOTS);

        $hasArmorUpdated = true;

        switch($team->getArmor($player)){
            case "iron";
            $leggings = Item::get(Item::IRON_LEGGINGS);
            break;
            case "diamond";
            $boots = Item::get(Item::IRON_BOOTS);
            break;
            default;
            $hasArmorUpdated = false;
            break;
        }


        foreach(array_merge([$helmet, $chestplate], !$hasArmorUpdated ? [$leggings, $boots] : []) as $armor){
            $armor->setCustomColor(Utils::colorIntoObject($team->getColor()));
        }

        $armorUpgrade = $team->getUpgrade('armorProtection');
        if($armorUpgrade > 0){
            foreach([$helmet, $chestplate, $leggings, $boots] as $armor){
                $armor->addEnchantment(new EnchantmentInstance(Enchantment::getEnchantment(Enchantment::PROTECTION)), $armorUpgrade);
            }
        }

        $player->getArmorInventory()->setHelmet($helmet);
        $player->getArmorInventory()->setChestplate($chestplate);
        $player->getArmorInventory()->setLeggings($leggings);
        $player->getArmorInventory()->setBoots($boots);

        $sword = Item::get(Item::WOODEN_SWORD);

        $swordUpgrade = $team->getUpgrade('sharpenedSwords');
        if($swordUpgrade > 0){
            $sword->addEnchantment(new EnchantmentInstance(Enchantment::getEnchantment(Enchantment::SHARPNESS)), $swordUpgrade);
        }

        $player->getInventory()->setItem(0, $sword);
        $player->getInventory()->setItem(8, Item::get(Item::COMPASS)->setCustomName(TextFormat::GREEN . "Tap to switch"));

    }


    public function tick() : void{

         switch($this->state) {
             case self::STATE_LOBBY;
                 if ($this->starting) {
                     if($this->starting && count($this->players) < $this->minPlayers) {
                         $this->startTime = $this->startTimeSaver;
                         $this->starting = false;
                         $this->broadcastMessage(TextFormat::YELLOW . "Countdown stopped");
                     }

                     $this->startTime--;

                     foreach ($this->players as $player) {
                         $player->sendTip(TextFormat::YELLOW . "Starting in " . TextFormat::AQUA . gmdate("i:s", $this->startTime));
                     }

                     switch ($this->startTime) {
                         case 30;
                             $this->broadcastMessage(TextFormat::YELLOW . "Starting in " . TextFormat::RED . "30");
                             break;
                         case 15;
                             $this->broadcastMessage(TextFormat::YELLOW . "Starting in " . TextFormat::GOLD . "15");
                             break;
                         case 5;
                         case 4;
                         case 3;
                         case 2;
                         case 1;
                             foreach ($this->players as $player) {
                                 $player->addTitle(TextFormat::RED . $this->startTime);
                             }
                             break;
                     }

                     if ($this->startTime == 0) {
                         $this->start();
                     }
                     
                 } else {
                     foreach ($this->players as $player) {
                         $player->sendTip(TextFormat::YELLOW . "Waiting for players (" . TextFormat::AQUA . ($this->minPlayers - count($this->players)) . TextFormat::YELLOW . ")");
                     }
                 }

                 foreach (array_merge($this->players, $this->spectators) as $player) {
                     \BedWars\utils\Scoreboard::remove($player);
                     \BedWars\utils\Scoreboard::new($player, 'bedwars', TextFormat::BOLD . TextFormat::YELLOW . "Bed Wars");
                     \BedWars\utils\Scoreboard::setLine($player, 1, " ");
                     \BedWars\utils\Scoreboard::setLine($player, 2, " " . TextFormat::WHITE . "Map: " . TextFormat::GREEN . $this->gameName . str_repeat(" ", 3));
                     \BedWars\utils\Scoreboard::setLine($player, 3, " " . TextFormat::WHITE . "Players: " . TextFormat::GREEN . count($this->players) . "/" . $this->maxPlayers . str_repeat(" ", 3));
                     \BedWars\utils\Scoreboard::setLine($player, 4, "  ");
                     \BedWars\utils\Scoreboard::setLine($player, 5, " " . ($this->starting ? TextFormat::WHITE . "Starting in " . TextFormat::GREEN . $this->startTime . str_repeat(" ", 3) : TextFormat::GREEN . "Waiting for players..." . str_repeat(" ", 3)));
                     \BedWars\utils\Scoreboard::setLine($player, 6, "   ");
                     \BedWars\utils\Scoreboard::setLine($player, 7, " " . TextFormat::WHITE . "Mode: " . TextFormat::GREEN . substr(str_repeat($this->playersPerTeam . "v", count($this->teams)), 0, -1) . str_repeat(" ", 3));
                     \BedWars\utils\Scoreboard::setLine($player, 8, " " . TextFormat::WHITE . "Version: " . TextFormat::GRAY . "v1.0" . str_repeat(" ", 3));
                     \BedWars\utils\Scoreboard::setLine($player, 9, "    ");
                     \BedWars\utils\Scoreboard::setLine($player, 10, " " . TextFormat::YELLOW . "www.example.net");
                 }

                 break;
             case self::STATE_RUNNING;

                 foreach ($this->players as $player) {
                     if ($player->getInventory()->contains(Item::get(Item::COMPASS))) {
                         $trackIndex = $this->trackingPositions[$player->getRawUniqueId()];
                         $team = $this->teams[$trackIndex];
                         $player->sendTip(TextFormat::WHITE . "Tracking: " . TextFormat::BOLD . $team->getColor() . ucfirst($team->getName()) . " " . TextFormat::RESET . TextFormat::WHITE . "- Distance: " . TextFormat::BOLD . $team->getColor() . round(Utils::stringToVector(":", $this->teamInfo[$trackIndex]['spawnPos'])->distance($player)) . "m");
                     }

                     if (isset($this->deadQueue[$player->getRawUniqueId()])) {

                         $player->addTitle(TextFormat::RED . "You died!", TextFormat::YELLOW . "You will respawn in " . TextFormat::RED . $this->deadQueue[$player->getRawUniqueId()] . " " . TextFormat::YELLOW . "seconds!");
                         $player->sendMessage(TextFormat::YELLOW . "You will respawn in " . TextFormat::RED . $this->deadQueue[$player->getRawUniqueId()] . " " . TextFormat::YELLOW . "seconds!");

                         $this->deadQueue[$player->getRawUniqueId()] -= 1;
                         if ($this->deadQueue[$player->getRawUniqueId()] == 0) {
                             unset($this->deadQueue[$player->getRawUniqueId()]);

                             $this->respawnPlayer($player);
                             $player->addTitle(TextFormat::GREEN . "RESPAWNED!");
                             $player->sendMessage(TextFormat::YELLOW . "You have respawned!");
                         }
                     }
                 }

                 foreach (array_merge($this->players, $this->spectators) as $player) {

                     \BedWars\utils\Scoreboard::remove($player);
                     \BedWars\utils\Scoreboard::new($player, 'bedwars', TextFormat::BOLD . TextFormat::YELLOW . "Bed Wars");

                     \BedWars\utils\Scoreboard::setLine($player, 1, " ");
                     \BedWars\utils\Scoreboard::setLine($player, 2, " " . TextFormat::WHITE . ucfirst($this->tierUpdateGen) . " Upgrade: " . TextFormat::GREEN . gmdate("i:s", $this->tierUpdate));
                     \BedWars\utils\Scoreboard::setLine($player, 3, "  ");

                     $currentLine = 4;
                     $playerTeam = $this->plugin->getPlayerTeam($player);
                     foreach ($this->teams as $team) {
                         $status = "";
                         if ($team->hasBed()) {
                             $status = TextFormat::GREEN . "[+]";
                         } elseif(count($team->getPlayers()) < $team->dead) {
                             $status = count($team->getPlayers()) === 0 ? TextFormat::DARK_RED . "[-]" : TextFormat::GRAY . "[" . count($team->getPlayers()) . "]";
                         }elseif(count($team->getPlayers()) >= $team->dead){
                             $status = TextFormat::DARK_RED . "[-]";
                         }
                         $isPlayerTeam = $team->getName() == $playerTeam->getName() ? TextFormat::GRAY . "(YOU)" : "";
                         $stringFormat = TextFormat::BOLD . $team->getColor() . ucfirst($team->getName()[0]) . " " . TextFormat::RESET . TextFormat::WHITE . ucfirst($team->getName()) . ": " . $status . " " . $isPlayerTeam;
                         \BedWars\utils\Scoreboard::setLine($player, " " . $currentLine, $stringFormat);
                         $currentLine++;
                     }
                     \BedWars\utils\Scoreboard::setLine($player, " " . $currentLine, "   ");
                     \BedWars\utils\Scoreboard::setLine($player, " " . $currentLine++, " " . TextFormat::YELLOW . "www.example.net");
                 }


             if(count($team = $this->getAliveTeams()) === 1){
                 $this->winnerTeam = $team[0];

                 $this->state = self::STATE_REBOOT;
             }

             foreach($this->generators as $generator){
                 $generator->tick();
             }

             $this->tierUpdate --;

             if($this->tierUpdate == 0){
                 $this->tierUpdate = 60 * 10;
                 foreach($this->generators as $generator){
                     if($generator->itemID == Item::DIAMOND && $this->tierUpdateGen == "diamond") {
                          $generator->updateTier();
                     }elseif($generator->itemID == Item::EMERALD && $this->tierUpdateGen == "emerald"){
                          $generator->updateTier();
                     }
                 }
                 $this->tierUpdateGen = $this->tierUpdateGen == 'diamond' ? 'emerald' : 'diamond';
             }
             break;
             case Game::STATE_REBOOT;
             $team = $this->teams[$this->winnerTeam];
             if($this->rebootTime == 10){
                 foreach($team->getPlayers() as $player){
                     $player->addTitle(TextFormat::BOLD . TextFormat::GOLD . "VICTORY!");
                 }
             }

             --$this->rebootTime;
             if($this->rebootTime == 0){
                 $this->stop();
             }
             break;
         }
    }







}<?php


namespace BedWars\game;

use BedWars\BedWars;
use BedWars\game\shop\ItemShop;
use BedWars\game\shop\UpgradeShop;
use BedWars\utils\Utils;
use pocketmine\block\Bed;
use pocketmine\block\Block;
use pocketmine\event\block\BlockBreakEvent;
use pocketmine\event\block\BlockPlaceEvent;
use pocketmine\event\block\SignChangeEvent;
use pocketmine\event\player\PlayerJoinEvent;
use pocketmine\event\entity\EntityDamageByEntityEvent;
use pocketmine\event\entity\EntityDamageEvent;
use pocketmine\event\entity\EntityLevelChangeEvent;
use pocketmine\event\Listener;
use pocketmine\event\player\PlayerInteractEvent;
use pocketmine\event\player\PlayerMoveEvent;
use pocketmine\event\player\PlayerQuitEvent;
use pocketmine\event\server\DataPacketReceiveEvent;
use pocketmine\event\entity\EntityExplodeEvent;
use pocketmine\item\Item;
use pocketmine\entity\object\PrimedTNT;
use pocketmine\network\mcpe\protocol\ModalFormResponsePacket;
use pocketmine\Player;
use pocketmine\utils\TextFormat;
use pocketmine\math\Vector3;
use pocketmine\event\player\PlayerCommandPreprocessEvent;


class GameListener implements Listener
{

    /** @var BedWars $plugin */
    private $plugin;

    /**
     * GameListener constructor.
     * @param BedWars $plugin
     */
    public function __construct(BedWars $plugin)
    {
        $this->plugin = $plugin;
    }

    /**
     * @param SignChangeEvent $event
     */
    public function onPlayerJoin(PlayerJoinEvent $e){
     $p = $e->getPlayer();
     foreach(glob($this->plugin->getDataFolder() . "games/*.json") as $location){
            $fileContents = file_get_contents($location);
            $jsonData = json_decode($fileContents, true);

            if(!$this->plugin->validateGame($jsonData)){
                continue;
            }
            if($p->getLevel()->getFolderName() === $jsonData['world']){
                $p->teleport($this->plugin->getServer()->getDefaultLevel()->getSafeSpawn());
            }
       }
    }
     
    public function onSignChange(SignChangeEvent $event) : void{
        $player = $event->getPlayer();
        $sign = $event->getBlock();

        if($event->getLine(0) == "[bedwars]" && $event->getLine(1) !== ""){
            if(!in_array($event->getLine(1), array_keys($this->plugin->games))){
                $player->sendMessage(BedWars::PREFIX . TextFormat::YELLOW . "Arena doesn't exist!");
                return;
            }

            $dataFormat = $sign->getX() . ":" . $sign->getY() . ":" . $sign->getZ() . ":" . $player->level->getFolderName();
            $this->plugin->signs[$event->getLine(1)][] = $dataFormat;

            $location = $this->plugin->getDataFolder() . "games/" . $event->getLine(1) . ".json";
            if(!is_file($location)){
                //wtf ??
                return;
            }

            $fileContent = file_get_contents($location);
            $jsonData = json_decode($fileContent, true);
            $positionData = [
                "signs" => $this->plugin->signs[$event->getLine(1)]
            ];

            file_put_contents($location, json_encode(array_merge($jsonData, $positionData)));
            $player->sendMessage(BedWars::PREFIX . TextFormat::GREEN . "Sign created");

        }
    }

    public function onExplode(EntityExplodeEvent $ev) : void{
        $entity = $ev->getEntity();
        if(!$entity instanceof PrimedTNT)return;
        $level = $entity->level;
        $game = null;
        foreach ($level->getPlayers() as $player) {
            if($g = $this->plugin->getPlayerGame($player) !== null){
                $game = $g;
            }
        }
        if($game == null)return;

        $newList = array();

        foreach($ev->getBlockList() as $block){
            if(in_array(Utils::vectorToString(":", $block->asVector3()), $game->placedBlocks)){
                $newList[] = $block;
            }
        }
        $ev->setBlockList($newList);
    }

    /**
     * @param PlayerInteractEvent $event
     */
    public function onInteract(PlayerInteractEvent $event) : void{
        $player = $event->getPlayer();
        $block = $event->getBlock();

        foreach($this->plugin->signs as $arena => $positions){
            foreach($positions as $position) {
                $pos = explode(":", $position);
                if ($block->getX() == $pos[0] && $block->getY() == $pos[1] && $block->getZ() == $pos[2] && $player->level->getFolderName() == $pos[3]) {
                    $game = $this->plugin->games[$arena];
                    $game->join($player);
                    return;
                }
            }
        }

        $item = $event->getItem();

        if($item->getId() == Item::WOOL){
            $teamColor = Utils::woolIntoColor($item->getDamage());

            $playerGame = $this->plugin->getPlayerGame($player);
            if($playerGame == null || $playerGame->getState() !== Game::STATE_LOBBY)return;

            if(!$player->hasPermission('lobby.ranked')){
                $player->sendMessage(BedWars::PREFIX . TextFormat::YELLOW . "You don't have permission to use this");
                return;
            }

            $playerTeam = $this->plugin->getPlayerTeam($player);
            if($playerTeam !== null){
                $player->sendMessage(BedWars::PREFIX . TextFormat::YELLOW . "You are already in a team!");
                return;
            }

            foreach($playerGame->teams as $team){
                if($team->getColor() == $teamColor){

                    if(count($team->getPlayers()) >= $playerGame->playersPerTeam){
                        $player->sendMessage(BedWars::PREFIX . TextFormat::RED . "Team is full");
                        return;
                    }
                    $team->add($player);
                    $player->sendMessage(BedWars::PREFIX . TextFormat::GRAY . "You've joined team " . $teamColor . $team->getName());
                }
            }
        }elseif($item->getId() == Item::COMPASS){
            $playerGame = $this->plugin->getPlayerGame($player);
            if($playerGame == null)return;

            if($playerGame->getState() == Game::STATE_RUNNING){
                 $playerGame->trackCompass($player);
            }elseif($playerGame->getState() == Game::STATE_LOBBY){
                $playerGame->quit($player);
                $player->teleport($this->plugin->getServer()->getDefaultLevel()->getSafeSpawn());
                $player->getInventory()->clearAll();
            }
        }
    }

    /**
     * @param PlayerQuitEvent $event
     */
    public function onQuit(PlayerQuitEvent $event) : void{
        $player = $event->getPlayer();
        foreach($this->plugin->games as $game){
            if(in_array($player->getRawUniqueId(), array_keys(array_merge($game->players, $game->spectators)))){
                $game->quit($player);
            }
        }
    }

    /**
     * @param EntityLevelChangeEvent $event
     */
    public function onEntityLevelChange(EntityLevelChangeEvent $event) : void{
        $player = $event->getEntity();
        if(!$player instanceof Player){
            return;
        }

        $playerGame = $this->plugin->getPlayerGame($player);
        if($playerGame !== null && $event->getTarget()->getFolderName() !== $playerGame->worldName)$playerGame->quit($player);
    }

    /**
     * @param PlayerMoveEvent $event
     */
    public function onMove(PlayerMoveEvent $event) : void
    {
        $player = $event->getPlayer();
        foreach ($this->plugin->games as $game) {
            if (isset($game->players[$player->getRawUniqueId()])) {
                if ($game->getState() == Game::STATE_RUNNING) {
                    if($player->getY() < $game->getVoidLimit() && !$player->isSpectator()){
                        $game->killPlayer($player);
                        $playerTeam = $this->plugin->getPlayerTeam($player);
                        $game->broadcastMessage($playerTeam->getColor() . $player->getName() . " " . TextFormat::GRAY . "was killed by void");
                    }
                }
            }
        }
    }

    /**
     * @param BlockBreakEvent $event
     */
    public function onBreak(BlockBreakEvent $event) : void
    {
        $player = $event->getPlayer();
        $block = $event->getBlock();

        if(isset($this->plugin->bedSetup[$player->getRawUniqueId()])){
            if(!$event->getBlock() instanceof Bed){
                $player->sendMessage(BedWars::PREFIX . TextFormat::YELLOW . "The block is not bed!");
                return;
            }
            $setup = $this->plugin->bedSetup[$player->getRawUniqueId()];

            $step =  (int)$setup['step'];

            $location = $this->plugin->getDataFolder() . "games/" . $setup['game'] . ".json";
            $fileContent = file_get_contents($location);
            $jsonData = json_decode($fileContent, true);

            $jsonData['teamInfo'][$setup['team']]['bedPos' . $step] = $block->getX() . ":" . $block->getY() . ":" . $block->getZ();
            file_put_contents($location, json_encode($jsonData));

            $player->sendMessage(BedWars::PREFIX . TextFormat::GREEN . "Bed $step has been set!");

            if($step == 2){
                unset($this->plugin->bedSetup[$player->getRawUniqueId()]);
                return;
            }

            $this->plugin->bedSetup[$player->getRawUniqueId()]['step']+=1;

            return;
        }

        $playerGame = $this->plugin->getPlayerGame($player);
        if($playerGame !== null){
            if($playerGame->getState() == Game::STATE_LOBBY){
                $event->setCancelled();
            }elseif($event->getBlock() instanceof Bed){
                $blockPos = $event->getBlock()->asPosition();

                $game = $this->plugin->getPlayerGame($player);
                $team = $this->plugin->getPlayerTeam($player);
                if($team == null || $game == null)return;

                foreach($game->teamInfo as $name => $info){
                    $bedPos = Utils::stringToVector(":", $info['bedPos1']);
                    $teamName = "";

                    if($bedPos->x == $blockPos->x && $bedPos->y == $blockPos->y && $bedPos->z == $blockPos->z){
                        $teamName = $name;
                    }else{
                        $bedPos = Utils::stringToVector(":", $info['bedPos2']);
                        if($bedPos->x == $blockPos->x && $bedPos->y == $blockPos->y && $bedPos->z == $blockPos->z){
                            $teamName = $name;
                        }
                    }

                    if($teamName !== ""){
                        $teamObject = $game->teams[$name];
                        if($name == $this->plugin->getPlayerTeam($player)->getName()){
                            $player->sendMessage(TextFormat::RED . "You can't break your bed!");
                            $event->setCancelled();
                            return;
                        }
                        $event->setDrops([]);
                        $game->breakBed($teamObject, $player);

                    }
                }
            }else{
                if($playerGame->getState() == Game::STATE_RUNNING){
                    if(!in_array(Utils::vectorToString(":", $block->asVector3()), $playerGame->placedBlocks)){
                        $event->setCancelled();
                    }
                }
            }
        }
    }

    /**
     * @param BlockPlaceEvent $event
     */
    public function onPlace(BlockPlaceEvent $event) : void{
        $player = $event->getPlayer();
        $playerGame = $this->plugin->getPlayerGame($player);
        if($playerGame !== null){
            if($playerGame->getState() == Game::STATE_LOBBY){
                $event->setCancelled();
            }elseif($playerGame->getState() == Game::STATE_RUNNING){
                foreach($playerGame->teamInfo as $team => $data){
                    $spawn = Utils::stringToVector(":", $data['spawnPos']);
                    if($spawn->distance($event->getBlock()) < 6){
                        $event->setCancelled();
                    }else{
                        $playerGame->placedBlocks[] = Utils::vectorToString(":", $event->getBlock());
                    }
                }

                if($event->getBlock()->getId() == Block::TNT){
                    $event->getBlock()->ignite();
                }
            }
        }
    }

    /**
     * @param EntityDamageEvent $event
     */
    public function onDamage(EntityDamageEvent $event) : void{
        $entity = $event->getEntity();
        foreach ($this->plugin->games as $game) {
            if ($entity instanceof Player && isset($game->players[$entity->getRawUniqueId()])) {

                if($game->getState() == Game::STATE_LOBBY){
                     $event->setCancelled();
                     return;
                }

                if($event instanceof EntityDamageByEntityEvent){
                    $damager = $event->getDamager();

                    if(!$damager instanceof Player)return;

                    if(isset($game->players[$damager->getRawUniqueId()])){
                        $damagerTeam = $this->plugin->getPlayerTeam($damager);
                        $playerTeam = $this->plugin->getPlayerTeam($entity);

                        if($damagerTeam->getName() == $playerTeam->getName()){
                            $event->setCancelled();
                        }
                    }
                }

                if($event->getFinalDamage() >= $entity->getHealth()){
                    $game->killPlayer($entity);
                    $event->setCancelled();


                }

            }elseif(isset($game->npcs[$entity->getId()])){
                $event->setCancelled();

                if($event instanceof EntityDamageByEntityEvent){
                    $damager = $event->getDamager();

                    if($damager instanceof Player){
                        $npcTeam = $game->npcs[$entity->getId()][0];
                        $npcType = $game->npcs[$entity->getId()][1];

                        if(($game = $this->plugin->getPlayerGame($damager)) == null){
                            return;
                        }

                        if($game->getState() !== Game::STATE_RUNNING){
                            return;
                        }

                        $playerTeam = $this->plugin->getPlayerTeam($damager)->getName();
                        if($npcTeam !== $playerTeam && $npcType == "upgrade"){
                            $damager->sendMessage(TextFormat::RED . "You can upgrade only your base!");
                            return;
                        }

                        if($npcType == "upgrade"){
                            UpgradeShop::sendDefaultShop($damager);
                        }else{
                            ItemShop::sendDefaultShop($damager);
                        }
                    }
                }
            }
        }
    }

    public function onCommandPreprocess(PlayerCommandPreprocessEvent $event) : void{
          $player = $event->getPlayer();

          $game = $this->plugin->getPlayerGame($player);

          if($game == null)return;

          $args = explode(" ", $event->getMessage());

          if($args[0] == '/fly' || isset($args[1]) && $args[1] == 'join'){
              $player->sendMessage(TextFormat::RED . "You cannot run this in-game!");
              $event->setCancelled();
          }
    }



    /**
     * @param DataPacketReceiveEvent $event
     */
    public function handlePacket(DataPacketReceiveEvent $event) : void{
        $packet = $event->getPacket();
        $player = $event->getPlayer();



        if($packet instanceof ModalFormResponsePacket){
            $playerGame = $this->plugin->getPlayerGame($player);
            if($playerGame == null)return;
              $data = json_decode($packet->formData);
              if (is_null($data)) {
                return;
              }
                if($packet->formId == 50) {
                    ItemShop::sendPage($player, intval($data));

                }elseif($packet->formId < 100){
                    ItemShop::handleTransaction(($packet->formId), json_decode($packet->formData), $player, $this->plugin);
                }elseif($packet->formId == 100){
                    UpgradeShop::sendBuyPage(json_decode($packet->formData), $player, $this->plugin);
                }elseif($packet->formId > 100){
                    UpgradeShop::handleTransaction(($packet->formId), $player, $this->plugin);
                }
            }
    }
}<?php


namespace BedWars\game;

use pocketmine\scheduler\Task;

class GameTick extends Task
{

    private $plugin;

    /**
     *  constructor.
     * @param Game $plugin
     */
    public function __construct(Game $plugin)
    {
        $this->plugin = $plugin;
    }

    public function onRun(int $currentTick)
    {
        $this->plugin->tick();
    }

}<?php


namespace BedWars\game;

use BedWars\game\entity\FakeItemEntity;
use BedWars\utils\Utils;
use pocketmine\entity\Entity;
use pocketmine\item\Item;
use pocketmine\level\particle\FloatingTextParticle;
use pocketmine\level\Position;
use pocketmine\plugin\PluginBase;
use pocketmine\Server;
use pocketmine\utils\TextFormat;
use pocketmine\nbt\tag\CompoundTag;
use pocketmine\nbt\tag\StringTag;
use pocketmine\nbt\tag\ByteArrayTag;

class Generator
{

    /** @var int $repeatRate */
    private $repeatRate;

    /** @var int $itemID */
    public $itemID;

    /** @var Position $position */
    private $position;

    /** @var bool $spawnText */
    private $spawnText;

    /** @var bool $spawnBlock */
    private $spawnBlock;

    /** @var int $dynamicSpawnTime */
    private $dynamicSpawnTime;

    /** @var FloatingTextParticle $floatingText */
    private $floatingText;

    /** @var $blockEntity */
    private $blockEntity;

    /** @var int $tier */
    private $tier = 1;

    const TITLE = [
        Item::DIAMOND => TextFormat::BOLD . TextFormat::AQUA . "Diamond",
        Item::EMERALD => TextFormat::BOLD . TextFormat::GREEN . "Emerald"
    ];

    const FAKE_BLOCK = [
        Item::DIAMOND => Item::DIAMOND_BLOCK,
        Item::EMERALD => Item::EMERALD_BLOCK
    ];


    /**
     * Generator constructor.
     * @param int $itemID
     * @param int $repeatRate
     * @param Position $position
     * @param bool $spawnText
     * @param bool $spawnBlock
     * @param Team|null $team
     */
    public function __construct(int $itemID, int $repeatRate, Position $position, bool $spawnText, bool $spawnBlock, Team $team = null)
    {
        $this->itemID = $itemID;
        $this->repeatRate = $repeatRate;
        $this->position = $position;
        $this->spawnText = $spawnText;
        $this->spawnBlock = $spawnBlock;

        $this->dynamicSpawnTime = $repeatRate;

        if($this->spawnText){
            $text = TextFormat::YELLOW . "Tier " . TextFormat::RED . Utils::rome($this->tier) . "\n".
                self::TITLE[$itemID] . "\n\n".
                TextFormat::YELLOW . "Spawns in " . TextFormat::RED . $this->dynamicSpawnTime . "seconds";
            $this->floatingText = new FloatingTextParticle($position->add(0.5, 3, 0.5), $text, "");
        }

        if($this->spawnBlock){
           $path = Server::getInstance()->getDataPath() . "plugin_data/BedWars/skins/" . $itemID . ".png";
           $skin = Utils::getSkinFromFile($path);
           $nbt = Entity::createBaseNBT($position->add(0.5, 2.3, 0.5), null);
           $nbt->setTag(new CompoundTag('Skin', [
                new StringTag('Data', $skin->getSkinData()),
                new StringTag('Name', 'Standard_CustomSlim'),
                new StringTag('GeometryName', 'geometry.player_head'),
                new ByteArrayTag('GeometryData', FakeItemEntity::GEOMETRY)]));
           $fakeItem = new FakeItemEntity($position->level, $nbt);
           $fakeItem->setScale(1.4);
           $fakeItem->spawnToAll();
        }
    }


    /**
     * @param int $repeatRate
     */
    public function setRepeatRate(int $repeatRate) : void{
        $this->repeatRate = $repeatRate;
    }

    public function tick() : void{
        if($this->spawnText){
            $text = TextFormat::YELLOW . "Tier " . TextFormat::RED . Utils::rome($this->tier) . "\n".
                self::TITLE[$this->itemID] . "\n".
                TextFormat::YELLOW . "Spawn in " . TextFormat::RED . $this->dynamicSpawnTime;
            $this->floatingText->setText($text);
            foreach($this->floatingText->encode() as $packet){
                foreach($this->position->getLevel()->getPlayers() as $player){
                    $player->dataPacket($packet);
                }
            }
        }

        $this->dynamicSpawnTime--;

        if($this->dynamicSpawnTime == 0){
            $this->dynamicSpawnTime = $this->repeatRate;

            $this->position->getLevel()->dropItem($this->position->asVector3(), Item::get($this->itemID));

        }
    }

    public function getTier() : int{
        return $this->tier;
    }

    public function updateTier() : void{
        $this->tier++;
        //-20%
        $this->repeatRate = $this->repeatRate - ($this->repeatRate * 100 / 20);
    }

    /**
     * @return FakeItemEntity
     */
    public function getBlockEntity() : ?FakeItemEntity{
        return $this->blockEntity;
    }

    /**
     * @return FloatingTextParticle|null
     */
    public function getFloatingText() : ?FloatingTextParticle{
        return $this->floatingText;
    }




}<?php


namespace BedWars\game;


use pocketmine\Player;

class Team
{

    /** @var Player[] $players */
    protected $players = array();

    /** @var string $color */
    protected $color;

    /** @var string $name */
    protected $name;

    /** @var bool $hasBed */
    protected $hasBed = true;

    /** @var array $armorUpdates */
    private $armorUpdates = array();

    /** @var int $dead */
    public $dead = 0;

    /** @var array $upgrades */
    private $upgrades = array(
        'sharpenedSwords' => 0,
        'armorProtection' => 0
    );


    /**
     * Team constructor.
     * @param string $name
     * @param string $color
     */
    public function __construct(string $name, string $color)
    {
        $this->name = $name;
        $this->color = $color;
    }

    /**
     * @param Player $player
     */
    public function add(Player $player) : void{
        $this->players[$player->getRawUniqueId()] = $player;
    }

    public function remove(Player $player) : void{
        unset($this->players[$player->getRawUniqueId()]);
    }

    /**
     * @return string
     */
    public function getColor() : string{
        return $this->color;
    }

    /**
     * @return string
     */
    public function getName() : string{
        return $this->name;
    }

    /**
     * @return array
     */
    public function getPlayers() : array{
        return $this->players;
    }

    /**
     * @param bool $state
     */
    public function updateBedState(bool $state) : void{
        $this->hasBed = $state;
    }

    /**
     * @return bool
     */
    public function hasBed() : bool{
        return $this->hasBed;
    }

    /**
     * @param Player $player
     * @param string $armor
     */
    public function setArmor(Player $player, string $armor){
        $this->armorUpdates[$player->getRawUniqueId()] = $armor;
    }

    /**
     * @param Player $player
     * @return string|null
     */
    public function getArmor(Player $player) : ?string{
        return $this->armorUpdates[$player->getRawUniqueId()];
    }

    /**
     * @param string $property
     */
    public function upgrade(string $property) : void{
        $this->upgrades[$property] +=1;
    }

    /**
     * @param string $property
     * @return int
     */
    public function getUpgrade(string $property) : int{
        return $this->upgrades[$property];
    }

    public function reset() : void{
        $this->upgrades = array(
            'sharpenedSwords' => 0,
            'armorProtection' => 0
        );

        $this->hasBed = true;
        $this->armorUpdates = array();
        $this->players = array();
    }

}<?php


namespace BedWars\game\entity;


use pocketmine\entity\Human;
use pocketmine\entity\object\ItemEntity;
use pocketmine\entity\Skin;
use pocketmine\event\entity\EntityDamageEvent;
use pocketmine\level\Level;
use pocketmine\nbt\tag\CompoundTag;

class FakeItemEntity extends Human
{

    public const GEOMETRY = '{"geometry.player_head":{"texturewidth":64,"textureheight":64,"bones":[{"name":"head","pivot":[0,24,0],"cubes":[{"origin":[-4,0,-4],"size":[8,8,8],"uv":[0,0]}]}]}}';

    /** @var int $gravity */
    protected $gravity = 0;
    public $width = 0.5, $height = 0.6;

    /**
     * @param int $currentTick
     * @return bool
     */
    public function onUpdate(int $currentTick): bool
    {

        $this->yaw+=5.5;
        //TODO: Add bouncing
        $this->move($this->motion->x, $this->motion->y, $this->motion->z);
        $this->updateMovement();

        parent::onUpdate($currentTick);
        return true;
    }

    /**
     * @param Skin $skin
     */
    public function setSkin(Skin $skin) : void{
        parent::setSkin(new Skin($skin->getSkinId(), $skin->getSkinData(), '', 'geometry.player_head', self::GEOMETRY));
    }

    /**
     * @param EntityDamageEvent $source
     */
    public function attack(EntityDamageEvent $source): void
    {
        $source->setCancelled();
    }

}<?php


namespace BedWars\game\player;

use pocketmine\Player;
use pocketmine\level\Position;
use pocketmine\entity\EffectInstance;


class PlayerCache
{
    /** @var Player $player */
    private $player;
    /** @var string $nametag */
    private $nametag;
    /** @var array $inventoryContents */
    private $inventoryContents = array();
    /** @var int $health */
    private $health;
    /** @var int $maxHealth */
    private $maxHealth;
    /** @var int $food */
    private $food;
    /** @var Position $position */
    private $position;
    /** @var EffectInstance[] $effects */
    private $effects;

    public function __construct(Player $player)
    {
        $this->nametag = $player->getNameTag();
        $this->inventoryContents = $player->getInventory()->getContents();
        $this->health = $player->getHealth();
        $this->maxHealth = $player->getMaxHealth();
        $this->food = $player->getMaxFood();
        $this->position = $player->asPosition();
        $this->effects = $player->getEffects();
        $this->player = $player;
    }

    public function load(){
        $this->player->setNameTag($this->nametag);
        $this->player->getInventory()->setContents($this->inventoryContents);
        $this->player->setHealth($this->health);
        $this->player->setMaxHealth($this->maxHealth);
        $this->player->setFood($this->food);
        $this->player->teleport($this->position);
        foreach($this->effects as $effect){
            $this->player->addEffect($effect);
        }
    }

}<?php


namespace BedWars\game\shop;


use BedWars\BedWars;
use BedWars\game\Game;
use BedWars\utils\Utils;
use pocketmine\item\Armor;
use pocketmine\item\enchantment\Enchantment;
use pocketmine\item\enchantment\EnchantmentInstance;
use pocketmine\item\Item;
use pocketmine\network\mcpe\protocol\ModalFormRequestPacket;
use pocketmine\Player;

class ItemShop
{

    const PURCHASE_TYPE_IRON = 0;
    const PURCHASE_TYPE_GOLD = 1;
    const PURCHASE_TYPE_EMERALD = 2;

    /**
     * @var array $shopWindows
     */
    public static $shopWindows = [
        1 => ["name" =>"§l§aArmor", "image" => "https://www.spigotmc.org/attachments/ftiroac-png.241966/"],
        2 => ["name" =>"§l§aWeapons", "image" => "http://icons.iconarchive.com/icons/chrisl21/minecraft/512/Stone-Sword-icon.png"],
        3 => ["name" =>"§l§aBlocks", "image" => "https://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/0/07/White_Wool.png"],
        4 => ["name" => "§l§aBows", "image" => "https://lh3.googleusercontent.com/MS2w4Tlmw4azfmxVcT9o29cq74YgMau26xni5DiqbzpxHFMIEpHtPxdGWWZlV-WD0oXNLUXsiKs2W2yAzMT0=s400"],
        5 => ["name" => "§l§aPotions" ,"image" => "http://www.blocksandgold.com//media/catalog/product/cache/3/image/200x/6cffa5908a86143a54dc6ad9b8a7c38e/s/p/splash_red.png"],
        6 => ["name" => "§l§aSpecials", "image" => "https://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/1/1e/TNT.png"]
    ];

    /**
     * @var array $shopPages
     */
    public static $shopPages = [
        0 => ["§6Chainmal Armor\n§l§e40 IRON" => ["image" => "https://www.spigotmc.org/attachments/ftiroac-png.241966/"],
            "§6Iron Armor §c[PERMANENT]\n§l§e12 GOLD" => ["image" => "http://www.minecraftopia.com/images/blocks/iron_boots.png"],
            "§6Diamond Armor §c[PERMANENT]\n§l§e6 EMERALD" => ["http://static.wixstatic.com/media/34c645_d8e567b9ae8645fa98e0775d45493df3.png"]],
        1 => ["§6Stone Sword\n§l§e10 IRON" => ["image" => "http://iconbug.com/data/0c/256/b86a957742c00c3804bd0fa293c98cde.png"],
            "§6Iron Sword\n§l§e7 GOLD" => ["image" => "https://vignette.wikia.nocookie.net/animaljam/images/2/27/Iron-Sword-icon.png/revision/latest/scale-to-width-down/480?cb=20141108192633"],
            "§6Diamond Sword\n§l§e7 EMERALD" => ["image" => "http://www.freepngimg.com/download/minecraft/16-2-diamond-sword-minecraft-png.png"],
            "§6Knockback Stick\n§l§e2 EMERALD" => ["image" => "https://vignette.wikia.nocookie.net/thetekkit/images/c/c4/Obsidian_Stick.png/revision/latest?cb=20121011074642"]],
        2 => ["§6Wool 16x\n§l§e4 IRON" => ["image" => "http://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/0/07/White_Wool.png"],
            "§6Sandstone 16x\n§l§e12 IRON" => ["image" => "http://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/d/d6/Sandstone.png"],
            "§6Endstone 12x\n§l§e24 IRON" => ["image" => "http://www.minecraftguides.org/blocks/endstone.png"],
            "§6Ladder 16x\n§l§e4 IRON" => ["image" => "https://hydra-media.cursecdn.com/minecraft.gamepedia.com/archive/6/63/20101021024334!Ladder.png"],
            "§6Oak Wood 16x\n§l§e4 GOLD" => ["image" => "https://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/0/0f/Oak_Wood_Planks.png"],
            "§6Obsidian 4x\n§l§e4 EMERALD" => ["image" => "https://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/2/23/Obsidian.png"]],
        3 => ["§6Normal Bow\n§l§e12 GOLD" => ["image" => "https://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/6/65/Bow.png"],
            "§6Bow §b(Power 1)\n§l§e24 GOLD" => ["image" => "https://i.imgur.com/MWw3yIJ.png"],
            "§6Bow §b(Power 1, Punch 1)\n§l§e6 EMERALD" => ["image" => "https://i.imgur.com/MWw3yIJ.png"]],
        4 => ["§6Speed II Potion (45 sec.)\n§l§e1 EMERALD" => ["image" => "http://www.blocksandgold.com//media/catalog/product/cache/3/image/200x/6cffa5908a86143a54dc6ad9b8a7c38e/p/o/potion_light_blue.png"],
            "§6Jump V Potion (45 sec.)\n§l§e1 EMERALD" => ["http://www.minecraftopia.com/images/blocks/potion_of_leaping.png"],
            "§6Invisibility Potion (30 sec.)\n§l§e1 EMERALD" => ["https://vignette.wikia.nocookie.net/minecraft-computer/images/7/78/Potion_blue.png/revision/latest?cb=20130701150754"]],
        5 => ["§6Golden Apple\n§l§e3 GOLD" => ["image" => "https://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/0/0e/Golden_Apple.png"],
            "§6Bedbug\n§l§e50 IRON" => ["image" => "https://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/0/04/Snowball.png"],
            "§6Fireball\n§l§e50 IRON" => ["image" => "https://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/9/98/Fire_Charge.png"],
            "§6TNT\n§l§e8 GOLD" => ["image" => "https://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/1/1e/TNT.png"],
            "§6Enderpearl\n§l§e4 EMERALD" => ["image" => "https://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/5/5a/Ender_Pearl.png"],
            "§6Water Bucker\n§l§e1 EMERALD" => ["image" => "https://vignette.wikia.nocookie.net/minecraftpocketedition/images/d/d3/Water_Bucket.png/revision/latest/fixed-aspect-ratio-down/width/320/height/320?cb=20141004050736&fill=transparent"],
            "§6Egg\n§l§e4 EMERALD" => ["image" => "https://d1u5p3l4wpay3k.cloudfront.net/minecraft_gamepedia/2/26/Egg.png"]
        ],
    ];

    /**
     * @var array $itemData
     */
    public static $itemData = [
        0 => [0 => ["name" => "Chainmal Armor", "type" => self::PURCHASE_TYPE_IRON, "amount" => 0, "price" => 40, "item" => ["id" => Item::CHAIN_LEGGINGS, "damage" => 0]],
            1 => ["name" => "Iron Armor", "type" => self::PURCHASE_TYPE_GOLD, "amount" => 0, "price" => 12, "item" => ["id" => Item::IRON_LEGGINGS, "damage" => 0]],
            2 => ["name" => "Diamond Armor ", "type" => self::PURCHASE_TYPE_EMERALD, "amount" => 0, "price" => 6, "item" => ["id" => ITEM::DIAMOND_LEGGINGS, "damage" => 0]]
        ],
        1 => [0 => ["name" => "Stone Sword", "type" => self::PURCHASE_TYPE_IRON, "amount" => 1, "price" => 10, "item" => ["id" => Item::STONE_SWORD, "damage" => 0]],
            1 => ["name" => "Iron Sword", "type" => self::PURCHASE_TYPE_GOLD, "amount" => 1, "price" => 7, "item" => ["id" => Item::IRON_SWORD, "damage" => 0]],
            2 => ["name" => "Diamond Sword", "type" => self::PURCHASE_TYPE_EMERALD, "amount" => 1, "price" => 7, "item" => ["id" => Item::DIAMOND_SWORD, "damage" => 0]],
            3 => ["name" => "Knockback Stick", "type" => self::PURCHASE_TYPE_EMERALD, "amount" => 1, "price" => 2, "item" => ["id" => Item::STICK, "damage" => 0]]
        ],
        2 => [0 => ["name" => "Wool 16x", "type" => self::PURCHASE_TYPE_IRON, "amount" => 16, "price" => 4, "item" => ["id" => Item::WOOL, "damage" => "depend"]],
            1 => ["name" => "Sandstone 16x", "type" => self::PURCHASE_TYPE_IRON, "amount" => 16, "price" => 12, "item" => ["id" => Item::SANDSTONE, "damage" => 0]],
            2 => ["name" => "Endstone 12x", "type" => self::PURCHASE_TYPE_IRON, "amount" => 12, "price" => 24,"item" => ["id" => Item::END_STONE, "damage" => 0]],
            3 => ["name" => "Ladder 16x", "type" => self::PURCHASE_TYPE_IRON, "amount" => 16, "price" => 4,"item" => ["id" => Item::LADDER, "damage" => 0]],
            4 => ["name" => "Oak Wood 16x", "type" => self::PURCHASE_TYPE_GOLD, "amount" => 16, "price" => 4, "item" => ["id" => 5, "damage" => 0]],
            5 => ["name" => "Obsidian 4x", "type" => self::PURCHASE_TYPE_EMERALD, "amount" => 4, "price" => 4, "item" => ["id" => Item::OBSIDIAN, "damage" =>0]]
        ],
        3 => [0 => ["name" => "Bow 1", "type" => self::PURCHASE_TYPE_GOLD, "amount" => 1, "price" => 12, "item" => ["id" => Item::BOW, "damage" => 0]],
            1 => ["name" => "Bow 2", "type" => self::PURCHASE_TYPE_GOLD, "amount" => 1, "price" => 24, "item" => ["id" => Item::BOW, "damage" => 0]],
            2 => ["name" => "Bow 3", "type" => self::PURCHASE_TYPE_EMERALD, "amount" => 1, "price" => 6, "item" => ["id" => Item::BOW, "damage" => 0]]
        ],
        4 => [0 => ["name" => "Potion of Speed", "type" => self::PURCHASE_TYPE_EMERALD, "amount" => 1, "price" => 1, "item" => ["id" => Item::POTION, "damage" => 8194]],
            1 => ["name" => "Jump Potion", "type" => self::PURCHASE_TYPE_EMERALD, "amount" => 1, "price" => 1, "item" => ["id" => Item::POTION, "damage" => 8203]],
            2 => ["name" => "Invisibility Potion", "type" => self::PURCHASE_TYPE_EMERALD, "amount" => 1, "price" => 1, "item" => ["id" => Item::POTION, "damage" => 8206]]
        ],
        5 => [0 => ["name" => "Golden Apple", "type" => self::PURCHASE_TYPE_GOLD, "amount" => 1, "price" => 3, "item" => ["id" => Item::GOLDEN_APPLE, "damage" => 0]],
            1 => ["name" => "Bedbug", "type" => self::PURCHASE_TYPE_IRON, "amount" => 1, "price" => 50, "item" => ["id" => Item::SNOWBALL, "damage" => 0]],
            2 => ["name" => "Fireball", "type" => self::PURCHASE_TYPE_IRON, "amount" => 1, "price" => 50, "item" => ["id" => Item::FIRE_CHARGE, "damage" => 0]],
            3 => ["name" => "TNT", "type" => self::PURCHASE_TYPE_GOLD, "amount" => 1, "price" => 8, "item" => ["id" => Item::TNT, "damage" => 0]],
            4 => ["name" => "Enderpearl", "type" => self::PURCHASE_TYPE_EMERALD, "amount" => 1, "price" => 4, "item" => ["id" => Item::ENDER_PEARL, "damage" => 0]],
            5 => ["name" => "Water Bucket", "type" => self::PURCHASE_TYPE_EMERALD, "amount" => 1, "price" => 1, "item" => ["id" => 326, "damage" => 0]],
            6 => ["name" => "Egg", "type" => self::PURCHASE_TYPE_EMERALD, "amount" => 1, "price" => 4, "item" => ["id" => Item::EGG, "damage" => 0]]
        ]
    ];

    /**
     * @param int $category
     * @return mixed
     */
    public static function getCategory(int $category){
        return self::$shopWindows[$category];
    }

    /**
     * @param int $id
     * @param $data
     * @param Player $p
     * @param BedWars $plugin
     */
    public static function handleTransaction(int $id, $data, Player $p, BedWars $plugin){
        if(is_null($data)){
            return;
        }
        $itemData = self::$itemData[$id][$data];
        $amount = $itemData['amount'];
        $price = $itemData['price'];
        $id = $itemData['item']['id'];
        $damage = (int)$itemData['item']['damage'];
        $p->sendMessage($itemData["amount"] . " & " . $itemData["price"]);
        $check = "";
        $type = $itemData['type'];
        $typeString = "";
        $removeItem = null;
        switch($type){
            case self::PURCHASE_TYPE_IRON;
                $typeString = "iron";
                $removeItem = Item::get(Item::IRON_INGOT, 0, $price);
                $check = $p->getInventory()->contains(Item::get(Item::IRON_INGOT, $damage, $price));
                break;
            case self::PURCHASE_TYPE_GOLD;
                $typeString = "gold";
                $removeItem = Item::get(Item::GOLD_INGOT, 0 , $price);
                $check = $p->getInventory()->contains(Item::get(Item::GOLD_INGOT, $damage, $price));
                break;
            case self::PURCHASE_TYPE_EMERALD;
                $typeString = "emerald";
                $removeItem = Item::get(Item::EMERALD, 0, $price);
                $check = $p->getInventory()->contains(Item::get(Item::EMERALD, $damage, $price));
                break;
        }

        if(!$check){
            $p->sendMessage("§cYou don't have enough " . strtolower(ucfirst($typeString)) . " to purchase this item!");
            return;
        }

        $playerTeam = $plugin->getPlayerTeam($p);
        if($playerTeam == null)return;


        if($id == Item::WOOL){
            $damage = Utils::colorIntoWool($playerTeam->getColor());
        }elseif(Item::get($id) instanceof Armor){
            self::handleArmorTransaction($data, $p);
            return;
        }
        $item = Item::get($id, $damage, $amount);
        $wasPurchased = false;

        //handle custom sword transactions
        foreach($p->getInventory()->getContents() as $index => $content){
            if(self::isSword($content->getId()) && self::isSword($id)) {
                $wasPurchased = true;
                if ($id !== $content->getId()) {
                    $p->getInventory()->removeItem($content);
                    $p->getInventory()->setItem($index, $item);
                }else{
                    $p->sendMessage("§cYou already have this sword!");
                    return;
                }
            }
        }
        $p->sendMessage("§aYou have sucesfully purchased §e" . $itemData['name'] . " §afor §e" . $price . " " .  ucfirst($typeString));
        if($wasPurchased){
            return;
        }

        if($id == Item::BOW){
            self::handleBowTransaction($data, $item);
        }

        $p->getInventory()->removeItem($removeItem);
        $p->getInventory()->addItem($item);
    }

    /**
     * @param int $data
     * @param Player $p
     */
    public static function handleArmorTransaction(int $data, Player $p){
        $data = intval($data);
        $boots = "";
        $leggings = "";
        switch ($data){
            case 0;
                $boots = Item::get(Item::CHAIN_BOOTS, 0, 1);
                $leggings = Item::get(Item::CHAIN_LEGGINGS, 0, 1);
                break;
            case 1;
                $boots = Item::get(Item::IRON_BOOTS);
                $leggings = Item::get(Item::IRON_LEGGINGS);
                break;
            case 2;
                $boots = Item::get(Item::DIAMOND_BOOTS);
                $leggings = Item::get(Item::DIAMOND_LEGGINGS);
        }
        $p->getArmorInventory()->setBoots($boots);
        $p->getArmorInventory()->setLeggings($leggings);
    }

    /**
     * @param int $data
     * @param Item $item
     */
    public static function handleBowTransaction(int $data, Item $item){
        switch ($data){
            case 1;
                $enchantment = new EnchantmentInstance(Enchantment::getEnchantment(Enchantment::POWER), 1);
                $item->addEnchantment($enchantment);
                break;
            case 2;
                $enchantment = new EnchantmentInstance(Enchantment::getEnchantment(Enchantment::POWER), 1);
                $enchantment1 = new EnchantmentInstance(Enchantment::getEnchantment(Enchantment::PUNCH), 1);
                foreach([$enchantment, $enchantment1] as $eIns){
                     $item->addEnchantment($eIns);
                }
        }
    }

    /**
     * @param int $itemId
     * @return bool
     */
    public static function isSword(int $itemId){
        $swords = [Item::IRON_SWORD, Item::STONE_SWORD, Item::WOODEN_SWORD, Item::DIAMOND_SWORD];
        if(in_array($itemId, $swords)){
            return true;
        }
        return false;
    }

    /**
     * @param int $itemId
     * @return bool
     */
    public static function isArmor(int $itemId){
        $armors = [Item::CHAIN_BOOTS, Item::CHAIN_BOOTS, Item::IRON_BOOTS, Item::IRON_LEGGINGS, Item::DIAMOND_BOOTS, Item::DIAMOND_LEGGINGS];
        if(in_array($itemId, $armors)){
            return true;
        }
        return false;
    }

    /**
     * @param Player $p
     */
    public static function sendDefaultShop(Player $p){
        $data['title'] = "Item Shop";
        $data['type'] = "form";
        $data['content'] = "";
        foreach(self::$shopWindows as $windows){
            $button =  ['text' => $windows['name']];
            $button['image']['type'] = "url";
            $button['image']['data'] = $windows['image'];
            $data['buttons'][] = $button;
        }

        $packet = new ModalFormRequestPacket();
        $packet->formId = 50;
        $packet->formData = json_encode($data);
        $p->dataPacket($packet);

    }


    /**
     * @param Player $p
     * @param int $page
     */
    public static function sendPage(Player $p, int $page){
        $formId = $page;
        $data['title'] = 'Page ' . $page;
        $data['type'] = 'form';
        $page = self::$shopPages[$page];
        $data['content'] = "";
        foreach($page as $itemsToBuy => $key){
            $string = strval($itemsToBuy);
            $button = ['text' => $string];
            if(!empty($key['image'])){
                $button['image']['type'] = 'url';
                $button['image']['data'] = $key['image'];
            }
            $data['buttons'][] = $button;
        }

        $packet = new ModalFormRequestPacket();
        $packet->formId = $formId;
        $packet->formData = json_encode($data);
        $p->dataPacket($packet);

    }



}<?php


namespace BedWars\game\shop;


use BedWars\BedWars;
use pocketmine\item\Armor;
use pocketmine\item\enchantment\Enchantment;
use pocketmine\item\enchantment\EnchantmentInstance;
use pocketmine\item\Item;
use pocketmine\item\Sword;
use pocketmine\network\mcpe\protocol\ModalFormRequestPacket;
use pocketmine\Player;
use pocketmine\utils\TextFormat;

class UpgradeShop
{

    /**
     * @var array $shopWindows
     */
    public static $shopWindows = [
        1 => ["name" => "§bSharpened Swords", "image" => "https://www.spigotmc.org/attachments/ftiroac-png.241966/"],
        2 => ["name" => "§bArmor Protection", "image" => "http://icons.iconarchive.com/icons/chrisl21/minecraft/512/Stone-Sword-icon.png"]
    ];

    public static $page_ids = [
        0 => 101,
        1 => 102
    ];

    public static $upgrades = [
        0 => ['name' => "§bSharpened Swords", "cost" => 2, "costMultiply" => false, 'identifier' => 'sharpenedSwords'],
        1 => ['name' => "§bArmor Protection", "cost" => 2, "costMultiply" => true, 'identifier' => 'armorProtection']
    ];

    const UPGRADE_DESCRIPTION = [
        1 => TextFormat::YELLOW . "Your team gets Protection on all armor pieces\n\n" . TextFormat::AQUA . "Protection I " . TextFormat::BOLD . TextFormat::YELLOW . "2 Diamonds\n" . TextFormat::RESET . TextFormat::AQUA . "Protection II " . TextFormat::BOLD . TextFormat::YELLOW . "4 Diamonds\n" . TextFormat::RESET . TextFormat::AQUA . "Protection III " . TextFormat::BOLD . TextFormat::YELLOW . "6 diamonds",
        0 => TextFormat::YELLOW . "Your team gets Sharpness I on all swords!\n\n" . TextFormat::BOLD . TextFormat::YELLOW . "2 Diamonds"
    ];

    const MAX_LEVELS = [
        'sharpenedSwords' => 1,
        'armorProtection' => 3
    ];


    /**
     * @param Player $p
     */
    public static function sendDefaultShop(Player $p)
    {
        $data['title'] = "Upgrade Shop";
        $data['type'] = "form";
        $data['content'] = "";
        foreach (self::$shopWindows as $windows) {
            $button = ['text' => $windows['name']];
            $button['image']['type'] = "url";
            $button['image']['data'] = $windows['image'];
            $data['buttons'][] = $button;
        }

        $packet = new ModalFormRequestPacket();
        $packet->formId = 100;
        $packet->formData = json_encode($data);
        $p->dataPacket($packet);

    }

    /**
     * @param $formId
     * @param Player $player
     * @param BedWars $plugin
     */
    public static function handleTransaction($formId, Player $player, BedWars $plugin): void
    {
        $playerTeam = $plugin->getPlayerTeam($player);
        $upgradeData = self::$upgrades[array_search($formId, self::$page_ids)];
        $cost = $upgradeData['cost'];
        if ($upgradeData['costMultiply']) {
            $upgradeValue = $playerTeam->getUpgrade($upgradeData['identifier']);
            $upgradeValue = $upgradeValue + 1;
            $cost = $cost * $upgradeValue;
        }

        if (!$player->getInventory()->contains(Item::get(Item::DIAMOND, 0, $cost))) {
            return;
        }


        $playerTeam->upgrade($upgradeData['identifier']);

        $player->getInventory()->removeItem(Item::get(Item::DIAMOND, 0, $cost));

        $player->sendMessage(TextFormat::GREEN . "Upgraded!");

        switch ($upgradeData['identifier']) {
            case 'sharpenedSwords';
            foreach ($playerTeam->getPlayers() as $player) {
                    foreach ($player->getInventory()->getContents() as $index => $item) {
                        if ($item instanceof Sword){
                            $item->addEnchantment(new EnchantmentInstance(Enchantment::getEnchantment(Enchantment::SHARPNESS)), $playerTeam->getUpgrade('sharpenedSwords'));
                            $player->getInventory()->setItem($index, $item);
                        }
                    }
                }
        break;
        case 'armorProtection';
        $player->sendMessage("Upgradearmor");
        foreach ($playerTeam->getPlayers() as $player) {
            $helmet = $player->getArmorInventory()->getHelmet();
            $chestplate = $player->getArmorInventory()->getChestplate();
            $leggings = $player->getArmorInventory()->getLeggings();
            $boots = $player->getArmorInventory()->getBoots();

            foreach([$helmet, $chestplate, $leggings, $boots] as $armor){
                $armor->addEnchantment(new EnchantmentInstance(Enchantment::getEnchantment(Enchantment::PROTECTION)), $playerTeam->getUpgrade('armorProtection'));
            }

            $player->getArmorInventory()->setHelmet($helmet);
            $player->getArmorInventory()->setChestplate($chestplate);
            $player->getArmorInventory()->setLeggings($leggings);
            $player->getArmorInventory()->setBoots($boots);
        }
        break;
    }
}

    /**
     * @param $selectedUpgrade
     * @param Player $player
     * @param BedWars $plugin
     */
    public static function sendBuyPage($selectedUpgrade, Player $player, BedWars $plugin) : void{
        $playerTeam = $plugin->getPlayerTeam($player);
        $formId = self::$page_ids[intval($selectedUpgrade)];

        $upgradeData = self::$upgrades[intval($selectedUpgrade)];

        $cost = $upgradeData['cost'];

        if($upgradeData['costMultiply']){
            $upgradeValue = $playerTeam->getUpgrade($upgradeData['identifier']);
            $upgradeValue = $upgradeValue + 1;
            $cost = $cost * $upgradeValue;
        }


        $formData = array();
        $formData['type'] = 'form';
        $formData['title'] = 'Upgrade Info';
        $formData['content'] = self::UPGRADE_DESCRIPTION[intval($selectedUpgrade)] . "\n";

        if($playerTeam->getUpgrade($upgradeData['identifier']) == self::MAX_LEVELS[$upgradeData['identifier']]){
            $formData['content'].="\n" . TextFormat::WHITE . "Level: " . TextFormat::YELLOW . "MAX";
        }elseif($playerTeam->getUpgrade($upgradeData['identifier']) < self::MAX_LEVELS[$upgradeData['identifier']] && $player->getInventory()->contains(Item::get(Item::DIAMOND, 0, $cost))){
            $formData['content'].="\n" . TextFormat::RESET . TextFormat::GREEN . "Tap to buy\n" . TextFormat::WHITE . "Level: " . TextFormat::YELLOW . $playerTeam->getUpgrade($upgradeData['identifier']);
        }elseif($playerTeam->getUpgrade($upgradeData['identifier']) < self::MAX_LEVELS[$upgradeData['identifier']]){
            $formData['content'].="\n" . TextFormat::RESET . TextFormat::RED . "You need $cost diamonds\n" . TextFormat::WHITE . "Level: " . TextFormat::YELLOW . $playerTeam->getUpgrade($upgradeData['identifier']);
        }

        $formData['buttons'][] = ['text' => "Confirm"];

        $packet = new ModalFormRequestPacket();
        $packet->formId = $formId;
        $packet->formData = json_encode($formData);

        $player->dataPacket($packet);
    }
}<?php


namespace BedWars\utils;
use pocketmine\network\mcpe\protocol\RemoveObjectivePacket;
use pocketmine\network\mcpe\protocol\SetDisplayObjectivePacket;
use pocketmine\network\mcpe\protocol\SetScorePacket;
use pocketmine\network\mcpe\protocol\types\ScorePacketEntry;
use pocketmine\Player;

class Scoreboard
{

    /** @var array $scoreboards */
    private static $scoreboards = array();

    /**
     * @param Player $player
     * @param string $objectiveName
     * @param string $displayName
     */
    public static function new(Player $player, string $objectiveName, string $displayName): void{
        if(isset(self::$scoreboards[$player->getName()])){
            self::remove($player);
        }
        $pk = new SetDisplayObjectivePacket();
        $pk->displaySlot = "sidebar";
        $pk->objectiveName = $player->getName();
        $pk->displayName = $displayName;
        $pk->criteriaName = "dummy";
        $pk->sortOrder = 0;
        $player->sendDataPacket($pk);
        self::$scoreboards[$player->getName()] = $objectiveName;
    }

    /**
     * @param Player $player
     */
    public static function remove(Player $player): void{
        $objectiveName = self::getObjectiveName($player);
        $pk = new RemoveObjectivePacket();
        $pk->objectiveName = $player->getName();
        $player->sendDataPacket($pk);
        unset(self::$scoreboards[$player->getName()]);
    }

    /**
     * @param Player $player
     * @param int $score
     * @param string $message
     */
    public static function setLine(Player $player, int $score, string $message): void{
        if(!isset(self::$scoreboards[$player->getName()])){
            return;
        }
        if($score > 15 || $score < 1){
            error_log("Score must be between the value of 1-15. $score out of range");
            return;
        }
        $objectiveName = self::getObjectiveName($player);
        $entry = new ScorePacketEntry();
        $entry->objectiveName = $player->getName();
        $entry->type = $entry::TYPE_FAKE_PLAYER;
        $entry->customName = $message;
        $entry->score = $score;
        $entry->scoreboardId = $score;
        $pk = new SetScorePacket();
        $pk->type = $pk::TYPE_CHANGE;
        $pk->entries[] = $entry;
        $player->sendDataPacket($pk);
    }

    /**
     * @param Player $player
     * @return string|null
     */
    public static function getObjectiveName(Player $player): ?string{
        return isset(self::$scoreboards[$player->getName()]) ? self::$scoreboards[$player->getName()] : null;
    }


}<?php


namespace BedWars\utils;

use pocketmine\entity\Skin;
use pocketmine\math\Vector3;
use pocketmine\utils\Color;
use pocketmine\utils\TextFormat;


class Utils
{

    const WOOL_COLOR = [
        '§a' => 5,
        '§c' => 14,
        '§e' => 4,
        '§6' => 1,
        '§f' => 0,
        '§b' => 3,
        '§1' => 11
    ];

    /**
     * @param string $color
     * @return string
     */
    public static function colorIntoWool(string $color) : int{
        return self::WOOL_COLOR[$color];
    }

    /**
     * @param int $woolDamage
     * @return string
     */
    public static function woolIntoColor(int $woolDamage) : string{
        $replace = [
            '§a' => 5,
            '§c' => 14,
            '§e' => 4,
            '§6' => 1,
            '§f' => 0,
            '§b' => 3,
            '§1' => 11
        ];

        return array_search($woolDamage, self::WOOL_COLOR);
    }

    /**
     * @param string $color
     * @return Color
     */
    public static function colorIntoObject(string $color) : Color{
        $replace = [
            '§a' => [0, 225, 0],
            '§c' => [225, 0, 0],
            '§e' => [225, 225, 0],
            '§6' => [255, 153, 51],
            '§f' => [225, 225, 225],
            '§b' => [51, 255, 255],
            '§1' => [0, 0, 225]
        ];

        $a = $replace[$color];
        return new Color($a[0], $a[1], $a[2]);
    }

    /**
     * @param string $delimeter
     * @param string $string
     * @param float $yaw
     * @param float $pitch
     * @return Vector3
     */
    public static function stringToVector(string $delimeter, string $string, &$yaw = 0.0, &$pitch = 0.0) : Vector3{
        $split = explode($delimeter, $string);
        if(isset($split[3]) && isset($split[4])){
            $yaw = floatval($split[3]);
            $pitch = floatval($split[4]);
        }
        return new Vector3(intval($split[0]), intval($split[1]), intval($split[2]));
    }

    /**
     * @param string $delimeter
     * @param Vector3 $vector
     * @return string
     */
    public static function vectorToString(string $delimeter, Vector3 $vector, $yaw = 0.0, $pitch = 0.0) : string{
        $array = [$vector->getX(), $vector->getY(), $vector->getZ()];
        if($yaw > 0 && $pitch > 0){
            $array[] = $yaw;
            $array[] = $pitch;
        }
        $string = "";
        foreach($array as $splitValue){
            $string.=$splitValue . ":";
        }
        return $string;
    }

    /**
     * @param $N
     * @return string
     */
    public static function rome($N){
        $c='IVXLCDM';
        for($a=5,$b=$s='';$N;$b++,$a^=7)//todo add 2 sector
            for($o=$N%$a,$N=$N/$a^0;$o--;$s=@$c[$o>2?$b+$N-($N&=-2)+$o=1:$b].$s);
        return $s;
    }

    /**
     * @param string $path
     * @return Skin|null
     */
    public static function getSkinFromFile(string $path) : ?Skin{

        $img = @imagecreatefrompng($path);
        $bytes = '';
        $l = (int) @getimagesize($path)[1];
        for ($y = 0; $y < $l; $y++) {
            for ($x = 0; $x < 64; $x++) {
                $rgba = @imagecolorat($img, $x, $y);
                $a = ((~((int)($rgba >> 24))) << 1) & 0xff;
                $r = ($rgba >> 16) & 0xff;
                $g = ($rgba >> 8) & 0xff;
                $b = $rgba & 0xff;
                $bytes .= chr($r) . chr($g) . chr($b) . chr($a);
            }
        }
        @imagedestroy($img);
        return new Skin("Standard_CustomSlim", $bytes);
    }


}6���%��V�!�c�n�4   GBMB
