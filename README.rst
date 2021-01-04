.. # ------------------( SYNOPSIS                           )------------------

.. image:: https://user-images.githubusercontent.com/217028/103398869-63d2ab00-4b36-11eb-948a-e32a947952c6.png
   :align: center

========================================
The Legend of Heroes: Trails… for Linux!
========================================

.. parsed-literal::

   There's no such thing as a dumb question, Regnitz…
            but that one came awfully close.
                          — Instructor Neithardt

This repository unofficially hosts `Lutris-based Linux installers <lutris_>`__
for numerous entries in Falcom_'s legendary `Kiseki (i.e., "The Legend of
Heroes: Trails…",『英雄伝説 …の軌跡』) universe <Kiseki_>`__: the
longest-running continuously interconnected Japanese role-playing (JRPG)
franchise, now spanning three decades of profitable development.

All installers hosted at this repository ship with out-of-the-box support for
input controllers, in-game videos, and full Japanese voice acting with fully
localized English subtitles – including:

* High-quality Japanese voice acting converted by `Zhenjian Yang`_'s
  `third-party SoraVoice library <SoraVoice_>`__ from the Japan-only
  *Evolution* Vita ports of the original *Sora no Kiseki* trilogy (i.e., *Sora
  no Kiseki FC*, *Sora no Kiseki SC*, *Sora no Kiseki the 3rd*).
* High-quality unofficial translations by the `third-party localization group
  Geofront <Geofront_>`__ for those entries still lacking official translations
  (i.e., *Zero no Kiseki*, *Ao no Kiseki*).

This repository also serves as a `central hub for detailing and resolving
issues in Linux emulation of supported Kiseki entries <local issues_>`__. Help
us get a better idea of the state of these installers by `submitting a new
issue documenting your installation and playthrough experience <local issue
new_>`__.

    ⚠️
    These installers are **not officially endorsed** by Falcom_, `Nippon Ichi
    Software (NIS)`_, or XSEED_. We still love you, `Toshihiro Kondo`_.

.. # ------------------( TABLE OF CONTENTS                  )------------------
.. # Blank line. By default, Docutils appears to only separate the subsequent
.. # table of contents heading from the prior paragraph by less than a single
.. # blank line, hampering this table's readability and aesthetic comeliness.

|

.. # Table of contents, excluding the above document heading. While the
.. # official reStructuredText documentation suggests that a language-specific
.. # heading will automatically prepend this table, this does *NOT* appear to
.. # be the case. Instead, this heading must be explicitly declared.

.. contents:: **Contents**
   :local:

.. # ------------------( DESCRIPTION                        )------------------

Installation
============

This repository currently hosts installers for only some of the available
*Kiseki* titles. As we continue playing through the series ourselves,
additional installers for later *Kiseki* titles will be added.

We apologize for the inconvenience and hope you enjoy your stay in Liberl.

The Legend of Heroes: Trails in the Sky (Sora no Kiseki FC)
-----------------------------------------------------------

`The Legend of Heroes: Trails in the Sky <Kiseki sora fc_>`__ (Japan: *Eiyuu
Densetsu: Sora no Kiseki First Chapter (FC)*,『英雄伝説 空の軌跡』) is the
first title in the *Kiseki* arc, originally released in 2004 for the
PlayStation Portable (PSP) and subsequently ported first to the PlayStation
Vita in 2015 as *Eiyuu Densetsu: Sora no Kiseki FC Evolution* and then to PC in
2016 via both GOG_ and Steam_.

These instructions assume you've purchased and downloaded the `Good Old Games
(GOG) version of this game <sora fc GOG_>`__. We hope to add an equivalent
Steam installer at a later date.

#. Download **Japanese dialogue voices** converted from the *Evolution* Vita
   port: [#sora-fc-dialogue]_

   #. Browse to this `MEGA-hosted filelocker folder <MEGA sora fc dialogue
      voices folder_>`__.
   #. Download *only* the **1.92GB** file named
      ``The Legend of Heroes - Trails in the Sky FC - Evolution Voices Files 20180518 Update.zip``.

#. Download **Japanese battle voices** converted from the original PSP release:
   [#sora-fc-battle]_

   #. Browse to this `MEGA-hosted filelocker folder <MEGA sora fc battle voices
      folder_>`__.
   #. Download the **66.4MB** file named ``ED6_DT1A.dat``.
   #. Download the **17KB** file named ``ED6_DT1A.dir``.

#. Download our `well-tested Lutris GOG installer <local sora fc GOG_>`__.
#. Open a terminal to the directory containing that file.
#. Copy-and-paste this command into that terminal:

            lutris -i sora-no-kiseki-voices-gog.yml

#. After installation, enable Japanese battle voices:

   #. Run the game.
   #. Open the *Options* menu.
   #. Switch the *Voices* setting to Japanese.

Brace for awesomeness. Your trail begins today.

.. [#sora-fc-dialogue]
   Japanese dialogue voice files are also available from other sites (e.g.,
   nyaa), typically under a directory named ``The Legend of Heroes - Trails in
   the Sky FC - Evolution Voices Mod/`` whose parent directory also contains a
   copy of the GOG version of this game. Please download from these sites
   *only* if you have already purchased this game. Falcom deserves all of your
   wallet for their service to humanity.

.. [#sora-fc-battle]
   Japanese battle voice files are also available from other sites (e.g.,
   nyaa), typically under a directory named ``The Legend of Heroes - Trails in
   the Sky FC - Japanese Battle Voices/`` whose parent directory also contains
   a copy of the GOG version of this game. Please download from these sites
   *only* if you have already purchased this game. Falcom deserves all of your
   wallet for their service to humanity.

The Legend of Heroes: Trails in the Sky SC (Sora no Kiseki SC)
--------------------------------------------------------------

*To be announced...*

See Also
========

If you enjoy this, you might also enjoy:

* `Ao no Kanata no Four Rhythm (Aokana)… for Linux! <leycec Aokana_>`__,
  `Lutris installers <Lutris_>`__ automating patching and execution for the
  fan-produced native Linux port of the `shounen sports chuunibyou <chuuni_>`__
  visual novel Aokana_.
* `Fate/stay night [Réalta Nua] Ultimate Edition… for Linux! <leycec Fate/stay
  night_>`__, a `Lutris installers <Lutris_>`__ automating patching and
  execution of the *[Réalta Nua]* variant of the seminal `shounen chuunibyou
  <chuuni_>`__ visual novel `Fate/stay night`_.

.. # ------------------( LINKS ~ falcom                     )------------------
.. _Falcom:
   https://en.wikipedia.org/wiki/Nihon_Falcom
.. _Toshihiro Kondo:
   https://www.gamasutra.com/view/feature/6585/a_30_year_fantasy_the_story_of_.php

.. # ------------------( LINKS ~ falcom : kiseki            )------------------
.. _Kiseki:
   https://en.wikipedia.org/wiki/Trails_(series)
.. _Kiseki sora fc:
   https://en.wikipedia.org/wiki/The_Legend_of_Heroes:_Trails_in_the_Sky

.. # ------------------( LINKS ~ falcom : kiseki : soft     )------------------
.. _Geofront:
   https://geofront.esterior.net
.. _SoraVoice:
   https://github.com/ZhenjianYang/SoraVoice
.. _Zhenjian Yang:
   https://github.com/ZhenjianYang

.. # ------------------( LINKS ~ falcom : publisher         )------------------
.. _Nippon Ichi Software (NIS):
   https://nisamerica.com
.. _XSEED:
   https://www.xseedgames.com

.. # ------------------( LINKS ~ filelocker : sora fc       )------------------
.. _MEGA sora fc dialogue voices folder:
   https://mega.nz/folder/QkFDgLBC#UiLo3rUekisptpzONidpmw/folder/U1933IaT
.. _MEGA sora fc battle voices folder:
   https://mega.nz/folder/QkFDgLBC#UiLo3rUekisptpzONidpmw/folder/U1933IaT

.. # ------------------( LINKS ~ lutris                     )------------------
.. _Lutris:
   https://lutris.net

.. # ------------------( LINKS ~ leycec                     )------------------
.. _leycec:
   https://github/leycec

.. # ------------------( LINKS ~ leycec : other             )------------------
.. _chuuni:
   https://forums.fuwanovel.net/topic/1820-chuuni-what-is-this-genre
.. _leycec Aokana:
   https://github.com/leycec/aokana-linux
.. _leycec Fate/stay jight:
   https://github.com/leycec/fsnrnue
.. _Aokana:
   https://nekonyansoft.com/shop/product/22
.. _Fate/stay night:
   https://typemoon.fandom.com/wiki/Fate/stay_night

.. # ------------------( LINKS ~ linux                      )------------------
.. _WINE:
   https://www.winehq.org
.. _Proton:
   https://github.com/ValveSoftware/Proton

.. # ------------------( LINKS ~ local                      )------------------
.. _local issues:
   https://github.com/leycec/kiseki-linux/issues
.. _local issue new:
   https://github.com/leycec/kiseki-linux/issues/new/choose
.. _local pull requests:
   https://github.com/leycec/kiseki-linux/pulls

.. # ------------------( LINKS ~ local : script             )------------------
.. _local sora fc GOG:
   https://github.com/leycec/kiseki-linux/raw/main/lutris/2004-sora_no_kiseki_fc/sora-no-kiseki-fc-gog-voiced.yml

.. # ------------------( LINKS ~ store : gog                )------------------
.. _GOG:
   https://www.gog.com
.. _sora fc GOG:
   https://www.gog.com/game/the_legend_of_heroes_trails_in_the_sky

.. # ------------------( LINKS ~ store : steam              )------------------
.. _Steam:
   https://store.steampowered.com
