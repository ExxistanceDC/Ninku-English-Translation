<div align="center"><img width="500" alt="Ninku Splash"  src="https://github.com/user-attachments/assets/11cbccaf-8235-4f87-ac31-3a4233510b84" /></div>

# Ninku English Translation Patch
An English patch for the Sega Saturn Japanese exclusive, <a href=https://segaretro.org/Ninku:_Tsuyokina_Yatsura_no_Daigekitotsu!>Ninku: Tsuyokina Yatsura no Daigekitotsu!</a>

Ninku is a 1v1 fighting game based on the manga/anime of the <a href=https://en.wikipedia.org/wiki/Ninku>same name</a>. With 2D character sprites and 3D backgrounds, it has a nice presentation (especially the camera work in the stage introductions) that is evocotive of later fighters like Marvel vs Capcom 2. Otherwise, it's a rather barebones affair with only an arcade mode and a versus mode. Still, it's another Saturn Japanese exclusive that is now available for English audiences!

## Table of Contents
1. [Overview](#Overview)
1. [Screenshots](#Screenshots)
1. [About the Game](#About-the-Game)
1. [Patching Instructions](#Patching-Instructions)
1. [Helpful Game Tips](#Helpful-Game-Tips)
1. [Credits & Special Thanks](#Credits)




## **Overview**
I call this my "weekend patch," in that I somehow stubbled across this game on YouTube, decided to investigate the game files, and spent the weekend redrawing textures. (Though figuring out how to re-encode the videos with subtitles took a good deal longer!) 

The following updates have been made to make the game fully English playable:

- Translated title screen, localized title
- Translated main menu
- Translated character names on character select screen
- In-game UI elements translated
- English subtitles for opening movie, game over, and character win quote FMVs



## **Screenshots**

<!-- Row 1 -->
<p>
  <img width="500" alt="Ninku Title Screen" src="https://github.com/user-attachments/assets/0ee7f1e6-dea6-446f-95cd-6c04e20c6e51" />
  <img width="500" alt="Ninku Opening Movie" src="https://github.com/user-attachments/assets/a4faceb9-e800-4916-8d35-2a99fbc188ac" />
</p>

<!-- Row 2 -->
<p>
  <img width="500" alt="Ninku Character Select" src="https://github.com/user-attachments/assets/c5dbecbf-6447-47a5-b2c5-ce765699a2fa" />
  <img width="500" alt="Ninku Battle" src="https://github.com/user-attachments/assets/fe4020dd-314d-4daa-a638-2888c4fcad13" />  
</p>

<!-- Row 3 -->
<p>
  <img width="500" alt="Ninku Winner" src="https://github.com/user-attachments/assets/d69aa6df-763a-4424-9719-7b13108ac183" />
  <img width="500" alt="Ninku Time Over" src="https://github.com/user-attachments/assets/7b72326d-1b22-4b23-9b3e-897fd9784a09" />
</p>

<!-- Row 4 -->
<p>  
  <img width="500" alt="Ninku Win Quote" src="https://github.com/user-attachments/assets/7747bc3c-00d4-4b51-81a9-5a3a8197f6a1" />
  <img width="500" alt="Ninku Loading Screen" src="https://github.com/user-attachments/assets/6a5de392-29da-4233-88fd-65f37bc12e57" />
</p>

## **About the Game**

<div align="center">
<table>
  <tr>
    <td><strong>Original Title</strong></td>
    <td>NINKU -忍空- 〜強気な奴等の大激突!〜</td>
  </tr>
  <tr>
    <td><strong>Localized Title</strong></td>
    <td>NINKU: Clash of the Toughest!</td>
  </tr>
  <tr>
    <td><strong>Developer</strong></td>
    <td>SIMS Co., Ltd.</td>
  </tr>
  <tr>
    <td><strong>Publisher</strong></td>
    <td>SEGA</td>
  </tr>
    <tr>
    <td><strong>Original Release Date</strong></td>
    <td>1996-02-02</td>
  </tr>
 </table>
</div>


## **Patching Instructions**

The patch comes in two flavors: a Sega Saturn Patcher .ssp or an XDelta .xdelta file. 

### Sega Saturn Patcher Instruction ###

1. Unzip patch bundle
2. Open the included version of **'SegaSaturnPatcher.exe'** 
3. After it opens, click **'Select Saturn Game'**
4. Next click **'CD Image'**
5. Find your original disc image on your computer, then click **'Open'**
6. Click the **'+ Game Patch (SSP)'** button
7. Go to where you unzipped the patch bundle and locate <kbd>NINKU_English_Translation_v1.0.ssp</kbd> and click **'Open'**
8. Finally, select **'Build Image'** and choose a directory to save it to
9. Burn to disc and play in your Sega Saturn or play in your favorite Sega Saturn emulator

### XDelta Instructions ###

1. Grab an XDelta patching utility like <a href='https://www.romhacking.net/utilities/704/'>Delta Patcher</a>
2. Unzip patch bundle
3. Open **'DeltaPatcher.exe'**
4. For the Original File, locate Track 01 of the original Ninku disc (for example: <kbd>Ninkuu - Tsuyokina Yatsura no Daigekitotsu! (Japan) (Track 01).bin</kbd>)
5. Locate the <kbd>Ninku_English_Translation_v1.0.xdelta</kbd>
6. Click **'Apply Patch'**
7. If successful, Track 01 will be replaced with the patched track.

**--> Important! <--**
- Tested with <kbd>Ninkuu - Tsuyokina Yatsura no Daigekitotsu! (Japan).zip</kbd>
- Use the included version of SegaSaturnPatcher (1.95.8035.20705). Sound looping errors were discovered when using other versions.
- You may need .NET version 5.0 for the above version of SegaSaturnPatcher.

## Helpful Game Tips ##

1. Streak indicator: as you win matches, a meter in the bottom corner of the screen will fill in. Winning five matches in a row will complete the Roman numeral "V." Winning another five matches in a row will result in another complete "V" being added.
<div align="center"><img width="318" height="64" alt="image" src="https://github.com/user-attachments/assets/9ab26c5f-bf77-466c-ab7b-cd042ef00954" />
</div>



## **Credits**

**Translation**
- Exxistance

**Texture Art**
- Exxistance

**QA**
- Exxistance
- wonder-inc
- Patrick “TraynoCo” Traynor

**Special Thanks**
- Shadowmask (for writing the excellent tutorial, <a href=https://www.segasaturnshiro.com/2024/07/05/create-your-own-saturn-video-discs-tools-and-tutorial/>Create Your Own Saturn Video Discs</a>, as well as providing additional advice)
- Malenko (whose <a href=https://segaxtreme.net/threads/saturn-15bpp-tool-tutorial.25687/>Saturn 15bpp tool tutorial </a> was invaluable for some of this translation's graphics)
