---
title: Ротация Шамана Совершенствования
layout: page
last_update: 2021-10-05
wow: 9.1
toc: true
author: Amani
description: Описание ротации Шамана Совершенствования. Приоритет способностей на этой странице динамически меняется в зависимости от того, какие выбраны таланты, легендарный предмет и ковенант.
image: /assets/img/logos/rotation.png
custom-javascript-list:
    - "/assets/js/rotation_switches.js"
---

<details markdown=1><summary><i>Журнал изменений</i></summary>
<br>

* **05.10.2021**: Приоритет при активном баффе от легендарки Ветра рока теперь показан сразу в соответствующих разделах. Добавлен динамический список приоритетов на АоЕ. Изменен приоритет Удара бури, Сокрушающей молнии и Цепной молнии на АоЕ.
* **17.09.2021**: Обновлен опенер, теперь динамически меняется для любого билда.
* **20.08.2021**: Добавлен выбор билда для Мифик+ и рейда.

</details>
<p></p>

# Выбор билда

Приоритет способностей на этой странице динамически меняется в зависимости от того, какие выбраны таланты, легендарка и ковенант:

<div class="container">
  <div class="row">
    <div class="col text-center">
      <a href="/enh/rotation.html" id="raid_build_enh" button="button" class="btn btn-outline-primary guide-btn">Выбрать билд для Рейда</a>
      <a href="/enh/rotation.html" id="mplus_build_enh" button="button" class="btn btn-outline-primary guide-btn">Выбрать билд для Мифик+</a>
    </div>
  </div>
</div>

<p></p>

{% include talents.html data=site.data.talents.enh active="3201031" switch=true %}

# Открывающая ротация, «Opener»

**Опенер** – это фиксированный порядок кастов в самом начале боя против одной цели.

1. {:.witch-apl}{{ site.data.spells.wt }} до пула, максимально близко к боссу.
1. {:.actuators-apl}{{ site.data.spells.wt }} до пула, максимально близко к боссу.
1. {:.wolf-apl}{{ site.data.spells.wt }} до пула, максимально близко к боссу.
1. {:.leg_kyrian-apl}{{ site.data.spells.wt }} до пула, максимально близко к боссу.
1. {:.leg_venthyr-apl}{{ site.data.spells.wt }} до пула, максимально близко к боссу.
1. {:.leg_fae-apl}{{ site.data.spells.wt }} до пула, максимально близко к боссу.
1. {:.leg_necrolords-apl}{{ site.data.spells.wt }} до пула, максимально близко к боссу.
2. {:.sk_enh-apl}[Хранитель бурь](https://ru.wowhead.com/spell=320137) прекастом до пула.
3. {:.vt-apl}{{ site.data.spells.fs }} в момент пула, по дороге к боссу.
3. {:.ch-apl}{{ site.data.spells.fs }} в момент пула, по дороге к боссу.
3. {:.ft-apl}{{ site.data.spells.fs }} в момент пула, по дороге к боссу.
3. {:.pw-apl}{{ site.data.covenants.pw }} в момент пула, по дороге к боссу.
3. {:.vt-apl}{{ site.data.covenants.vt }} сразу после пула, под босса.
4. {:.spike-apl}{{ site.data.spells.spike }}.
5. {:.wolf-apl}{{ site.data.spells.feral }}.
6. {{ site.data.spells.ss }}.
5. {:.leg_fae-apl}{{ site.data.spells.feral }}.
7. {:.ft-apl}{{ site.data.covenants.ft }}.
5. {:.witch-apl}{{ site.data.spells.feral }}.
5. {:.actuators-apl}{{ site.data.spells.feral }}.
5. {:.doom-apl}{{ site.data.spells.feral }}.
5. {:.leg_kyrian-apl}{{ site.data.spells.feral }}.
5. {:.leg_venthyr-apl}{{ site.data.spells.feral }}.
5. {:.leg_necrolords-apl}{{ site.data.spells.feral }}.
6. {:.asc_enh-apl}{{ site.data.spells.asc_enh }}.
6. {:.asc_enh-apl}{{ site.data.spells.windstrike }}.
1. {:.doom-apl}{{ site.data.spells.wt }} для активации эффекта легендарки {{ site.data.legend.doom }}.
7. Продолжайте обычную ротацию.

# Бой против одной цели

Ниже представлен список приоритетов способностей, который динамически меняется в зависимости от выбранных выше талантов, легендарки и ковенанта.

* {:.doom-apl}Список приоритетов **БЕЗ** активного баффа от легендарки {{ site.data.legend.doom }}:

1. {:.witch-apl}{{ site.data.spells.wt }}, если тотем не активен.
1. {:.actuators-apl}{{ site.data.spells.wt }}, если тотем не активен.
1. {:.wolf-apl}{{ site.data.spells.wt }}, если тотем не активен.
2. {:.pw-apl}{{ site.data.covenants.pw }}, если нет активного баффа от этого заклинания.
3. {{ site.data.spells.fs }}, если отсутствует на цели.
4. {{ site.data.spells.feral }}.
6. {:.hh-apl}{{ site.data.spells.ll }} с баффом от таланта {{ site.data.spells.hh }}.
6. {:.lf-apl}{{ site.data.spells.ll }} при отсутствии дебаффа {{ site.data.spells.lf }}.
7. {:.doom-apl}{{ site.data.spells.wt }}, если возможно получить бафф от легендарки {{ site.data.legend.doom }}.
8. {:.asc_enh-apl}{{ site.data.spells.asc_enh }}.
9. {:.asc_enh-apl}{{ site.data.spells.windstrike }}.
11. {:.vt-apl}{{ site.data.covenants.vt }}. 
10. {:.hailstorm-apl}{{ site.data.spells.frs }} с баффом от таланта {{ site.data.spells.hailstorm }}.
12. {:.spike-apl}{{ site.data.spells.spike }}.
13. {:.ft-apl}{{ site.data.covenants.ft }}. 
17. {:.witch-apl}{{ site.data.spells.ss }}.
13. {:.sk_enh-apl}{{ site.data.spells.cl }} под баффом от [Хранителя бурь](https://ru.wowhead.com/spell=320137).
14. {:.eb-apl}{{ site.data.spells.eb }} при **5+** стаках [Оружия Водоворота](https://ru.wowhead.com/spell=187880).
15. {:.ch-apl}{{ site.data.covenants.ch }} при **5+** стаках [Оружия Водоворота](https://ru.wowhead.com/spell=187880).
13. {:.sk_enh-apl}[Хранитель бурь](https://ru.wowhead.com/spell=320137) при **5+** стаках [Оружия Водоворота](https://ru.wowhead.com/spell=187880).
16. {{ site.data.spells.lb }} при **8+** стаках [Оружия Водоворота](https://ru.wowhead.com/spell=187880).
17. {:.actuators-apl}{{ site.data.spells.ss }}.
17. {:.wolf-apl}{{ site.data.spells.ss }}.
17. {:.doom-apl}{{ site.data.spells.ss }}.
17. {:.leg_fae-apl}{{ site.data.spells.ss }}.
18. {{ site.data.spells.ll }}.
19. {{ site.data.spells.crush }}.
20. {{ site.data.spells.fs }}, если до спадения осталось менее **5.4** секунд.
21. {{ site.data.spells.frs }}. 
22. {:.is-apl}{{ site.data.spells.is }}.
23. {:.sunder-apl}{{ site.data.spells.sunder }}.
24. {:.fn-apl}{{ site.data.spells.fn }} при активном {{ site.data.spells.fs }}.
25. {{ site.data.spells.lb }} при **5+** стаках [Оружия Водоворота](https://ru.wowhead.com/spell=187880).
26. {{ site.data.spells.wt }}, если все другие способности недоступны.

<hr style="height:1px;background-color:#bbb">
<p></p>

* {:.doom-apl}Список приоритетов **при активном** баффе от легендарки {{ site.data.legend.doom }}:

1. {:.doom-apl .asc_enh-apl}{{ site.data.spells.ss }} / {{ site.data.spells.windstrike }}.
1. {:.doom-apl .spirits-apl}{{ site.data.spells.ss }}.
1. {:.doom-apl .spike-apl}{{ site.data.spells.ss }}.
3. {:.doom-apl}{{ site.data.spells.crush }}.
4. {:.doom-apl .sunder-apl}{{ site.data.spells.sunder }}.
5. {:.doom-apl .is-apl}{{ site.data.spells.is }}.
6. {:.doom-apl}Все остальные способности, согласно обычной ротации.

# Бой на АоЕ

Ниже представлен список приоритетов в бою против **2** и более целей.

* {:.doom-apl}Список приоритетов **БЕЗ** активного баффа от легендарки {{ site.data.legend.doom }}:

1. {{ site.data.spells.feral }}.
1. {:.asc_enh-apl}{{ site.data.spells.asc_enh }}, стараясь задеть максимальное количество целей при активации.
1. {:.doom-apl}{{ site.data.spells.wt }}, если возможно получить бафф от легендарки {{ site.data.legend.doom }}.
2. {:.hailstorm-apl}{{ site.data.spells.frs }} с баффом от таланта {{ site.data.spells.hailstorm }}.
3. {:.sunder-apl}{{ site.data.spells.sunder }} на максимальное количество целей.
4. {:.pw-apl .actuators-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .actuators-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .actuators-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .actuators-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .actuators-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .actuators-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .actuators-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .actuators-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .actuators-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .witch-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .witch-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .witch-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .witch-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .witch-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .witch-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .witch-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .witch-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .witch-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .wolf-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .wolf-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .wolf-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .wolf-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .wolf-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .wolf-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .wolf-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .wolf-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .wolf-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .doom-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .doom-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .doom-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .doom-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .doom-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .doom-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .doom-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .doom-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .doom-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .leg_fae-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .leg_fae-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .leg_fae-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .leg_fae-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .leg_fae-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .leg_fae-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .leg_fae-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .leg_fae-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.pw-apl .leg_fae-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .actuators-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .actuators-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .actuators-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .actuators-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .actuators-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .actuators-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .actuators-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .actuators-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .actuators-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .witch-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .witch-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .witch-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .witch-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .witch-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .witch-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .witch-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .witch-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .witch-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .wolf-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .wolf-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .wolf-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .wolf-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .wolf-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .wolf-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .wolf-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .wolf-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .wolf-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .doom-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .doom-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .doom-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .doom-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .doom-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .doom-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .doom-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .doom-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .doom-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .leg_fae-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .leg_fae-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .leg_fae-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .leg_fae-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .leg_fae-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .leg_fae-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .leg_fae-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .leg_fae-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.vt-apl .leg_fae-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .actuators-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .actuators-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .actuators-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .actuators-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .actuators-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .actuators-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .actuators-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .actuators-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .actuators-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .witch-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .witch-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .witch-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .witch-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .witch-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .witch-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .witch-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .witch-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .witch-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .wolf-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .wolf-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .wolf-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .wolf-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .wolf-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .wolf-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .wolf-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .wolf-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .wolf-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .doom-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .doom-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .doom-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .doom-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .doom-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .doom-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .doom-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .doom-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .doom-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .leg_fae-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .leg_fae-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .leg_fae-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .leg_fae-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .leg_fae-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .leg_fae-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .leg_fae-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .leg_fae-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ch-apl .leg_fae-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .actuators-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .actuators-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .actuators-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .actuators-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .actuators-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .actuators-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .actuators-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .actuators-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .actuators-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .witch-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .witch-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .witch-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .witch-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .witch-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .witch-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .witch-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .witch-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .witch-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .wolf-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .wolf-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .wolf-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .wolf-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .wolf-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .wolf-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .wolf-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .wolf-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .wolf-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .doom-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .doom-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .doom-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .doom-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .doom-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .doom-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .doom-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .doom-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .doom-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .leg_fae-apl .lf-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .leg_fae-apl .lf-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .leg_fae-apl .lf-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .leg_fae-apl .fw-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .leg_fae-apl .fw-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .leg_fae-apl .fw-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .leg_fae-apl .eb-apl .ea-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .leg_fae-apl .eb-apl .hailstorm-apl}{{ site.data.spells.fs }} на максимальное количество целей.
4. {:.ft-apl .leg_fae-apl .eb-apl .fn-apl}{{ site.data.spells.fs }} на максимальное количество целей.
5. {:.pw-apl}{{ site.data.covenants.pw }}, если нет активного баффа от этого заклинания.
6. {:.fn-apl}{{ site.data.spells.fn }}, если под [Огненным шоком](https://ru.wowhead.com/spell=188389) **3+** цели.
7. {:.vt-apl}{{ site.data.covenants.vt }}.
8. {:.pw-apl}{{ site.data.spells.lb }}, если есть бафф от [Первозданной волны](https://ru.wowhead.com/spell=326059) и **5+** стаков [Оружия Водоворота](https://ru.wowhead.com/spell=187880).
9. {:.sk_enh-apl}{{ site.data.spells.cl }}, если есть бафф от [Хранителя бурь](https://ru.wowhead.com/spell=320137).
10. {{ site.data.spells.crush }}, если бафф не активен.
11. {:.lf-apl}{{ site.data.spells.ll }} по цели без активного дебаффа от таланта }{{ site.data.spells.lf }}.
12. {:.actuators-apl}{{ site.data.spells.ll }} при наличии **6+** стаков от легендарки [Преобразователи изначальной лавы](https://ru.wowhead.com/spell=335895).
13. {:.hh-apl}{{ site.data.spells.ll }} с баффом от таланта {{ site.data.spells.hh }}.
14. {{ site.data.spells.ss }}.
14. {:.asc_enh-apl}{{ site.data.spells.ss }} / {{ site.data.spells.windstrike }}.
15. {{ site.data.spells.crush }}.
16. {:.ch-apl}{{ site.data.covenants.ch }} при **5+** стаках [Оружия Водоворота](https://ru.wowhead.com/spell=187880).
17. {:.eb-apl}{{ site.data.spells.eb }} при **5+** стаках [Оружия Водоворота](https://ru.wowhead.com/spell=187880).
18. {:.sk_enh-apl}[Хранитель бурь](https://ru.wowhead.com/spell=320137) при **5+** стаках [Оружия Водоворота](https://ru.wowhead.com/spell=187880).
19. {{ site.data.spells.cl }} при **5+** стаках [Оружия Водоворота](https://ru.wowhead.com/spell=187880).
20. {{ site.data.spells.ll }}.
21. {{ site.data.spells.fs }}.
22. {:.is-apl}{{ site.data.spells.is }}.
23. {:.fn-apl}{{ site.data.spells.fn }}, если под [Огненным шоком](https://ru.wowhead.com/spell=188389) **2** цели.
24. {:.spike-apl}{{ site.data.spells.spike }}.
25. {:.witch-apl}{{ site.data.spells.wt }}.
25. {:.actuators-apl}{{ site.data.spells.wt }}.
25. {:.wolf-apl}{{ site.data.spells.wt }}.
25. {:.leg_fae-apl}{{ site.data.spells.wt }}.

<hr style="height:1px;background-color:#bbb">
<p></p>

* {:.doom-apl}Список приоритетов **при активном** баффе от легендарки {{ site.data.legend.doom }}:

1. {:.doom-apl}{{ site.data.spells.crush }}.
4. {:.doom-apl .sunder-apl}{{ site.data.spells.sunder }}.
1. {:.doom-apl .asc_enh-apl}{{ site.data.spells.ss }} / {{ site.data.spells.windstrike }}.
1. {:.doom-apl .spirits-apl}{{ site.data.spells.ss }}.
1. {:.doom-apl .spike-apl}{{ site.data.spells.ss }}.
4. {:.doom-apl}{{ site.data.spells.cl }} при **5+** стаках [Оружия Водоворота](https://ru.wowhead.com/spell=187880).
5. {:.doom-apl}Все остальные способности, согласно обычной ротации.

# Важные моменты 

* **Не стоит сразу тратить стаки [Оружия Водоворота](https://ru.wowhead.com/spell=187880), и не стоит уходить в оверкап.** Лучше всего сливать их на **7-8** стаках, в удобное время между кулдаунами других способностей.
* **Держите шоки на кулдауне.** Это относится как к бою против одной цели, где необходимо поддерживать {{ site.data.spells.fs }}, так и к АОЕ со взятым талантом {{ site.data.spells.hailstorm }}. Шоки позволяют снижать простои в ротации, так что используйте их по первой возможности.
* **Используйте прок [Вестника шторма](https://ru.wowhead.com/spell=201845/) так быстро, насколько это возможно.** Наша задача не дать прокам и кулдауну [Удара бури](https://ru.wowhead.com/spell=17364/) пропасть зря, поэтому реагировать на {{ site.data.spells.sb }} крайне важно.
* Аналогичная ситуация с талантом {{ site.data.spells.hh }} – {{ site.data.spells.ll }} с этим баффом имеет гораздо больший приоритет, чем без него.
* Перед применением [Перерождения](https://ru.wowhead.com/spell=114051) всегда используйте {{ site.data.spells.ss }}, так как его кулдаун сбросится после после активации этого таланта.
* Обновляйте {{ site.data.spells.fs }}, когда до конца его спадения осталось менее **5.4** секунд, чтобы это время добавилось к новому [Огненному шоку](https://ru.wowhead.com/spell=188389).
* Для уменьшения количества простоев следует сначала использовать способности с коротким кулдауном, а уже затем с долгим. Это отражено в списке приоритетов.
* Во время активного баффа от легендарки {{ site.data.legend.doom }} главная задача – нанести как можно больше ударов с **правой руки**, вызывая прок [Неистовства ветра](https://ru.wowhead.com/spell=33757). К таким способностям относятся {{ site.data.spells.windstrike }}, {{ site.data.spells.ss }}, {{ site.data.spells.crush }}, {{ site.data.spells.sunder }} и автоатаки.
* За счет того, что {{ site.data.spells.crush }} считается атакой с правой руки, шанс на прок [Оружия неистовства ветра](https://ru.wowhead.com/spell=33757) рассчитывается на каждую пораженную цель.
