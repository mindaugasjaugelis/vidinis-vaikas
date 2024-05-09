---
layout: page
title: Privatumo politika
subtitle: Privatumo politika
description :
---

<script>
    function removeConsent(e) {
        e.stopPropagation();
        clear();
        $('#successClearMessage').attr('style', 'display:block;');
        $('#successAcceptMessage').attr('style', 'display:none;');
    }

    function accept() {
        acceptPolicy();
        $('#successClearMessage').attr('style', 'display:none;');
        $('#successAcceptMessage').attr('style', 'display:block;');
    }
    
    $(document).ready(function() {
        $('#removeConsentLink').click(removeConsent);
        $('#acceptConsentLink').click(accept);
    });
</script>

Sveiki atvykę į mūsų internetinį puslapį. Mes, esame įsipareigoję gerbti ir saugoti jūsų privatumą. Ši privatumo politika nusako, kaip mes renkame, naudojame, perduodame ir saugome jūsų asmeninę informaciją, kai naudojate mūsų svetainę.

### Duomenų rinkimas ir naudojimas
Mes naudojame Google Analytics, kad galėtume suprasti, kaip lankytojai naudoja mūsų svetainę. Google Analytics naudoja slapukus, kad rinktų anoniminę informaciją, įskaitant jūsų IP adresą, kurį jūsų naršyklė nusiunčia serveriui, tam, kad jis galėtų sudaryti ataskaitas apie svetainės naudojimą.

### Slapukai
Mūsų svetainė naudoja tik nebūtinus slapukus. Tai yra maži failai, kurie įrašomi į jūsų įrenginį, kai lankotės mūsų svetainėje. Šie slapukai nėra naudojami jokioje kitokioje tikslinėje rinkodaros ar reklamos veikloje.

### Jūsų teisės
Jūs turite pasirinkimą sutikti arba nesutikti su slapukų naudojimu Jūsų įrenginyje. Šis pasirinkimas neįtakoja svetainės funkcionalumo, tačiau mes labai vertiname Jūsų sutikimą naudoti jūsų veiklos svetaineje duomenis.

### Atnaujinimai
Mes galime atnaujinti šią privatumo politiką periodiškai, tad rekomenduojame reguliariai tikrinti šią puslapio dalį, kad gautumėte naujausią informaciją apie mūsų privatumo praktiką.<br>
Paskutinį kartą atnaujinta: 2024 m. gegužės 9 d.

### Sutikimas
Norėdami sutikti su mūsų privatumo politika, <a id="acceptConsentLink" style="cursor: pointer;">spauskite čia</a>.<br>
Jei jau sutikote su mūsų svetainės privatumo politika, tačiau norite savo sutikimą panaikinti, <a id="removeConsentLink" style="color: red; cursor: pointer;">spauskite čia</a>.
<strong id="successClearMessage" style="display: none;">Svetainės naudojami slapukai sėkmingai ištrinti iš jūsų įrenginio.</strong>
<strong id="successAcceptMessage" style="display: none;">Svetainės naudojami slapukai sėkmingai išsaugoti, Ačiū!</strong>