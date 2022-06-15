.. # ------------------( SYNOPSIS                           )------------------

.. image:: https://user-images.githubusercontent.com/217028/103398869-63d2ab00-4b36-11eb-948a-e32a947952c6.png
   :align: center

========================================
The Legend of Heroes: Trails… for Linux!
========================================

.. parsed-literal::

   There's no such thing as a dumb question, Regnitz.
            But that one came awfully close.
                         — Instructor Neithardt

This repository unofficially hosts `Lutris-based Linux installers <lutris_>`__
for numerous entries in `Falcom's <Falcom_>`__ legendary `Kiseki ("The Legend
of Heroes: Trails…",『英雄伝説 …の軌跡』) universe <Kiseki_>`__ – the
longest-running continuously interconnected Japanese role-playing (JRPG)
franchise now spanning three decades of profitable development.

All installers hosted at this repository ship with out-of-the-box support for
input controllers, in-game videos, and full Japanese voice acting with fully
localized English subtitles. This includes:

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

    These instructions assume you've purchased and downloaded the `Good Old
    Games (GOG) version <sora fc GOG_>`__. We hope to add an equivalent Steam
    installer at a later date. Until then, our apologies, fam.

#. `Download and install Lutris <Lutris_>`__.
#. Download **Japanese dialogue voices** converted from the *Evolution* Vita
   port: [#sora-fc-dialogue]_

   #. `Browse to this MEGA-hosted filelocker folder <MEGA sora fc dialogue
      voices folder_>`__.
   #. Download *only* the **1.92GB** file named
      ``The Legend of Heroes - Trails in the Sky FC - Evolution Voices Files 20180518 Update.zip``.

#. Download **Japanese battle voices** converted from the original PSP release:
   [#sora-fc-battle]_

   #. `Browse to this MEGA-hosted filelocker folder <MEGA sora fc battle voices
      folder_>`__.
   #. Download the **66.4MB** file named ``ED6_DT1A.dat``.
   #. Download the **17KB** file named ``ED6_DT1A.dir``.

#. Download our `well-tested Lutris GOG installer <local sora fc GOG_>`__.
#. Open a terminal to the directory containing that file.
#. **Close** Lutris (if Lutris is already open).
#. Copy-and-paste this command into that terminal:

            lutris -i sora-no-kiseki-fc-gog-voiced.yml

#. Click **Install** twice. Just do it.
#. **Scroll** the resulting installation window down until you see a list of
   requested game files.
#. **Browse** Lutris manually to where each of the requested game files lives.
   Yes, this takes literally forever. No, it's not our fault. We blame the
   Erebonian Empire. What *aren't* those bad dudes responsible for!?
#. Click **Continue.**
#. **Scroll** the same window back up to watch Lutris leisurely download all of
   the remaining dependencies.
#. **Drink** a concerning amount of liquids while waiting for Lutris to fully
   extract and install these files. Pour one out for your kidneys, bro.
#. Repeatedly click **Next**, **Install**, and **Finish** when asked to install
   *LAV Filters* (i.e., the Windows component responsible for rendering in-game
   videos).
#. **Configure** the game appropriately. Towards the end of the installation
   process, this game's configuration utility (i.e., ``Config.exe``) will be
   automagically run. If you accidentally closed it or would merely like to
   reassess your life choices, you may `manually rerun this utility at any time
   by obeying the FAQ entry below <How do you reconfigure the game after
   installation?_>`__. While you're here, please do:

   * Change the **resolution** to the native resolution of your monitor. For
     example, `@leycec <leycec_>`__ changes the resolution to 1920x1080 to
     match the native resolution of his antiquated Gateway monitor. Do not mock
     him.
   * Enable **(Borderless) Window Mode.** When disabled, the keyboard arrow keys
     (and thus joystick support mapping onto those keys) will be largely
     dysfunctional. Interestingly, Windows users suffer the same issue.
   * Enable **Hardware Vertex Shading.** When disabled, performance stutters to
     a halt within urban environments.
   * Click **OK** when done.

#. Click **Close.**
#. Right-click the **The Legend of Heroes: Trails in the Sky** entry.
#. Click the **Configure** item.
#. Click the **Runner options** tab.
#. **Scroll** down.
#. Click the **down arrow** directly to the right of **Virtual desktop
   resolution.**
#. Select the **same resolution** that you configured above (i.e., the native
   resolution of your monitor).
#. (\ *Recommended*\ ) Enable **joystick support.** Sadly, Japanese voice acting
   and native joystick support is mutually exclusive. You can either have one or
   you can have the other. You of course want Japanese voice acting, which means
   you can't have native joystick support. So what do you do? You complain
   bitterly to anyone that might listen! How'd that go? Not so well? Then read.
   Although the game no longer provides native joystick support (...because we
   broke it), that's no obstacle to in-game progress. Just manually install a
   **Linux joystick mapping utility.** Many exist, but the one most Linux gamers
   care about in 2022 is AntiMicroX_:

   #. `Install AntiMicroX <AntiMicroX installation_>`__.
   #. Run **AntiMicroX.**
   #. If you have a **PlayStation 4 DualShock 4 (DS4):**

      #. Connect your DS4 via a wired microUSB-to-USB cable to your PC.
      #. Download our `DS4 AntiMicroX profile <Kiseki sora fc DS4 AntiMicroX
         profile_>`__.
      #. Click **Load.**
      #. Browse to the downloaded ``sora-no-kiseki-fc-ps4.gamecontroller.amgp``
         file.
      #. Let the turn-based pownage begin.

   #. Else, create your own **joystick-specific AntiMicroX profile**:

      #. Map the appropriate buttons of your joystick to these keyboard keys:

         * Your **up** button to the ``<Up>`` arrow key on your keyboard.
         * Your **down** button to the ``<Down>`` arrow key on your keyboard.
         * Your **left** button to the ``<Left>`` arrow key on your keyboard.
         * Your **right** button to the ``<Right>`` arrow key on your keyboard.
         * Your **left shoulder** button to the ``<Z>`` key on your keyboard.
         * Your **right shoulder** button to the ``<X>`` key on your keyboard.
         * Your Xbox-style **A** button to the ``<Left Button>`` on your mouse.
         * Your Xbox-style **B** button to the ``<Right Button>`` on your mouse.
         * Your Xbox-style **X** button to the ``<A>`` key on your keyboard.
         * Your Xbox-style **Y** button to the ``<Left Alt>`` key on your
           keyboard.
         * Your Xbox-style **Back** button to the ``<V>`` key on your keyboard.
         * Your Xbox-style **Guide** button to the ``<B>`` key on your keyboard.
         * Your Xbox-style **Start** button to the ``<Esc>`` key on your
           keyboard.
         * Whatever button you have available left to the ``<C>`` key on your
           keyboard.

      #. Click **Save.**
      #. Consider uploading your profile to save other users precious lifeforce.
         Just submit an issue or pull request with your profile and the type of
         your joystick. We'll do the rest. (Thanks in advance! Go, you.)

   #. Keep **AntiMicroX** running in the background, where it will act as a
      daemon process that continually maps (i.e., rebinds) joystick to keyboard
      inputs as you play.

#. Enable Japanese battle voices:

   #. Run the game.
   #. Open the **Options** menu in-game.
   #. Switch the **Voices** setting to Japanese.

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

Frequently Asked Questions (FAQ)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Should I play with a guide?
+++++++++++++++++++++++++++

**You should play with a guide** *if* you hope to read all content, which you
should, because this franchise sports the best writing of any JRPG – and let's
not even debate that prior claim. Like the adjacent *Tales of...* franchise, the
*Trails of...* franchise "features" a wide array of permanently missable
content. This includes missable:

* **Bracer points (BPs).** If you manage to obtain *all* BPs, you receive a
  significant reward when importing your save into the next entry (i.e., *The
  Legend of Heroes: Trails in the Sky Second Chapter (SC)*).
* **Side quests,** most of which yield juicy dialog, lore, and world-building.
* **Rewards,** the most significant of which are unique Quartz for casting Arts.
* **Writing.** This includes a chronological series of:

  * **Newspapers,** building the world around you as you live it.
  * **Book excerpts,** which are surprisingly well-written and mildly foreshadow
    future events in subsequent entries.

* **Voice acting.** The Japanese voice acting throughout the *Trails in the Sky*
  arc is among the best Japanese voice acting of all time for any media. No.
  Seriously. It is that good. Which makes its exclusion from the PC release all
  the more inexplicable. :superscript:`Licensing. Money. You love to hate it.`
  Although *some* of this voice acting is presented naturally through the course
  of the main quest, a shocking amount of this voice acting can only be accessed
  by pursuing hidden missables nobody has ever found naturally.

Which brings us to the next bold question...

Which guide should I play with?
+++++++++++++++++++++++++++++++

**You should play with** `Kartarius' spoiler-free "Guide and Walkthrough" at
GameFAQs <Kiseki sora fc faq_>`__, because that's the best guide for any game
we've ever read. No. Seriously. It also is that good. Unlike most guides that
shall remain nameless, Kartarius' guide is formatted in *extremely* readable
HTML **+** CSS split across multiple pages for readability. It really is
spoiler-free and will save your undivided attention from shadow madness while
hunting down all meaningful missables – which, of course, is most of them.

Regardless of whether you hope to **100%** the game, obtain most of the
missables, or just read most of the content, we strongly advise that everyone at
least **speak to all of the NPCs in Kartarius' guide whose names are prefixed by
either a "+" or "++"** (e.g., "+Claire (outside Abend Bar)", "++Aina"). Speaking
with these NPCs yields a conversation between those NPCs and the party; in the
case of NPCs whose names are prefixed by a "++", those conversations are
additionally voiced.

No game has ever worked so hard to hide so much content.

Which difficulty should I play on?
++++++++++++++++++++++++++++++++++

**Hard.** For clarity, let's accurately retranslate this game's four difficulty
settings into modern parlance:

+-------------------+-------------------------------------------------------+
| Stated Difficulty | Actual Difficulty                                     |
+===================+=======================================================+
| Easy              | **Babby's First JRPG**                                |
| Normal            | **Babby's First JRPG** (\ *Part Deux*\ )              |
| Hard              | **Normal**                                            |
| Nightmare         | **I GUZZLE THE BITTER TEARS OF YOUR SWEET SUFFERING** |
+-------------------+-------------------------------------------------------+

We all see the problem there, I trust. Out of four available difficulty
settings, only one difficulty setting is worth sinking 80 or more hours into.

On the high end (i.e., on "Nightmare"), you *will* stumble headfirst into
difficulty spikes that can only be overcome via luck-based save scumming and
non-fun farming for Quartz, food, EXP, and rare gear drops. You will repeatedly
pray to RNJesus for succour from your poor life choices.

On the low end (i.e., on "Easy" and "Normal"), you *will* blindly trainwreck
through all available combat by repeatedly pressing **X** to win. Not even the
**Turbo** button – which you will, of course, keep held down for 80 continuous
hours until your fragile wrist snaps under its oppressive load – can save your
playthrough from the blue pill of monotony. Do you like boredom? You will learn
to do so.

On the middle end (i.e., on "Hard"), you *will* meaningfully engage with
(mostly) fun subsystems like Quartz slots, character gear, and cooking
ingredients. Trash mobs and bosses alike require a modest amount of preparation.
Difficulty spikes are extremely uncommon, (mostly) tied to optional super
bosses, and always surmountable *without* requiring luck-based save scumming or
non-fun farming for Quartz, food, EXP, or rare gear drops.

Play on **Hard.** Fun is its own reward. Have fun. Be rewarded. You deserve it.

How do you reconfigure the game after installation?
+++++++++++++++++++++++++++++++++++++++++++++++++++

**Great question!** We're so glad you asked. You may have seen that our
installer automagically ran this game's configuration utility (i.e.,
``Config.exe``) towards the end of its installation process, right? It did that
because if it *didn't* do that, the game would fail to run. :superscript:`yeah.`

But what if you want to reconfigure the game *after* installation? What then,
huh? Huh? Easy! Just:

#. Run **Lutris.**
#. Right-click the **The Legend of Heroes: Trails in the Sky** entry.
#. Click the **Configure** item.
#. Click the **Game options** tab.
#. Click the **Browse** button directly to the right of **Executable**.
#. Double-click the ``Config.exe`` executable.
#. Click **Save.**
#. Double-click the **The Legend of Heroes: Trails in the Sky** entry.
#. Reconfigure as desired.
#. Click **OK** when done.
#. Right-click the **The Legend of Heroes: Trails in the Sky** entry again.
#. Click the **Configure** item again.
#. Click the **Game options** tab again.
#. Click the **Browse** button directly to the right of **Executable** again.
#. **Scroll** down. Way down. Further. Okay. Almost there. Now scroll some more.
#. Double-click the ``ed6_win.exe`` executable.
#. Click **Save.**

You're welcome.

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

.. # ------------------( LINKS ~ falcom : kiseki : fc       )------------------
.. _Kiseki sora fc:
   https://en.wikipedia.org/wiki/The_Legend_of_Heroes:_Trails_in_the_Sky
.. _Kiseki sora fc faq:
   https://gamefaqs.gamespot.com/pc/979866-the-legend-of-heroes-trails-in-the-sky/faqs/79398
.. _Kiseki sora fc DS4 AntiMicroX profile:
   https://raw.githubusercontent.com/leycec/kiseki-linux/main/lutris/2004-sora_no_kiseki_fc/sora-no-kiseki-fc-ps4.gamecontroller.amgp

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
   https://mega.nz/folder/QkFDgLBC#UiLo3rUekisptpzONidpmw/folder/40FgxYaA

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
.. _leycec Fate/stay night:
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

.. # ------------------( LINKS ~ linux : antimicrox         )------------------
.. _AntiMicroX:
   https://github.com/AntiMicroX/antimicrox
.. _AntiMicroX installation:
   https://github.com/AntiMicroX/antimicrox#installation

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
