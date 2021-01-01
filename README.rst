.. # ------------------( SYNOPSIS                           )------------------

.. image:: https://user-images.githubusercontent.com/217028/103398869-63d2ab00-4b36-11eb-948a-e32a947952c6.png
   :align: center

=======================================================
( Kiseki | Trails | Legend of Heroes | 軌跡 ) for Linux
=======================================================

.. parsed-literal::

   There's no such thing as a dumb question, Regnitz,
       but that one came awfully close.

                           — Instructor Neithardt

This repository unofficially hosts `Lutris-based Linux installers <lutris_>`__
for *all* entries in Falcom_'s acclaimed `"Kiseki" (i.e., "Trails", "Legend of
Heroes", 『英雄伝説 …の軌跡』) universe <Kiseki_>`__: the longest-running
continuously interconnected Japanese role-playing (JRPG) franchise now spanning
three decades of active development.

All installers hosted at this repository ship with out-of-the-box support for
popular controllers, in-game cutscenes and videos, and full Japanese voice
acting with fully localized English subtitles – including:

* High-quality Japanese voice acting converted by `Zhenjian Yang`_'s
  `third-party SoraVoice library <SoraVoice_>`__ from the Japan-only
  *Evolution* Vita ports of the original *Sora no Kiseki* trilogy (i.e., *Sora
  no Kiseki FC*, *Sora no Kiseki SC*, *Sora no Kiseki the 3rd*).
* High-quality unofficial translations by the `third-party localization group
  Geofront <Geofront_>`__ for those entries still lacking official translations
  (i.e., *Zero no Kiseki*, *Ao no Kiseki*).

This repository also serves as a `central hub for debating, detailing, and
resolving issues in Linux emulation of all Kiseki entries <local issues_>`__.
Help us get a better idea of the state of these installers by `submitting a new
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

This repository currently hosts installers for only a subset of the available
*Kiseki* titles. As we continue playing through the series ourselves,
additional installers for later *Kiseki* titles will be added.

The Legend of Heroes: Trails in the Sky (Sora no Kiseki FC)
-----------------------------------------------------------

*The Legend of Heroes: Trails in the Sky* (Japan: *Eiyuu Densetsu: Sora no
Kiseki First Chapter (FC)*) is the first entry in the *Kiseki* series,
originally released in 2004 for the PlayStation Portable (PSP) and subsequently
ported first to the PlayStation Vita in 2015 as *Eiyuu Densetsu: Sora no Kiseki
FC Evolution* and then to Steam in 2016.

The following instructions assume you have purchased and downloaded the `Good
Old Games (GOG) version of this entry <sora fc GOG_>`__. We hope to add an
equivalent Steam installer at a later date.

#. Download **Japanese voices** ripped from the Japan-only *Evolution* Vita
   port:

   #. Browse to this `MEGA-hosted filelocker folder <sora fc voices
      folder_>`__.
   #. Right-click the folder named ``The Legend of Heroes - Trails in the Sky
      FC - Evolution Voices Mod``.
   #. Expand the **Download...** item.
   #. Click the **Download as ZIP** sub-item.
   #. Right-click the folder named ``The Legend of Heroes - Trails in the Sky
      FC - Japanese Battle Voices``.
   #. Expand the **Download...** item.
   #. Click the **Download as ZIP** sub-item.

#. Download our `well-tested Lutris installer <local sora fc GOG_>`__.
#. Open a terminal to the directory containing that file.
#. Copy-and-paste this command into that terminal:

            lutris -i sora-no-kiseki-voices-gog.yml

#. After installation, enable Japanese battle voices by:

   #. Running *The Legend of Heroes: Trails in the Sky.*
   #. Open the *Options* menu.
   #. Switch the *Voices* setting to Japanese.

Brace for awesomeness. Your trail begins today.

See Also
========

If you enjoy this, you might also enjoy:

* `Ao no Kanata no Four Rhythm (Aokana)… for Linux! <leycec Aokana_>`__, a suite
  of `Lutris installers <Lutris_>`__ automating patching, installation, and
  execution for the fan-produced native Linux port of the `shounen sports
  chuunibyou <chuuni_>`__ visual novel Aokana_.
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
.. _sora fc dialog voices folder:
   https://mega.nz/folder/QkFDgLBC#UiLo3rUekisptpzONidpmw/folder/U1933IaT
.. _sora fc battle voices folder:
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
   https://github.com/leycec/kiseki-linux/raw/main/lutris/sora-no-kiseki-voices-gog.yml

.. # ------------------( LINKS ~ store : gog                )------------------
.. _GOG:
   https://www.gog.com
.. _sora fc GOG:
   https://www.gog.com/game/the_legend_of_heroes_trails_in_the_sky
