# Function: <code>__dec_zone_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811ada80)
Location: mm/vmstat.c:286
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811ada80-ffffffff811adad7: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6d30)
Location: mm/vmstat.c:347
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811c6d30-ffffffff811c6d91: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6e50)
Location: mm/vmstat.c:347
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811d6e50-ffffffff811d6eb1: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811dfcb0)
Location: mm/vmstat.c:347
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811dfcb0-ffffffff811dfd11: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f5ac0)
Location: mm/vmstat.c:422
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811f5ac0-ffffffff811f5b21: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216d40)
Location: mm/vmstat.c:422
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81216d40-ffffffff81216da1: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229c50)
Location: mm/vmstat.c:422
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81229c50-ffffffff81229cb1: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812398e0)
Location: mm/vmstat.c:423
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812398e0-ffffffff81239941: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81247be0)
Location: mm/vmstat.c:423
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81247be0-ffffffff81247c41: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81274e34)
Location: mm/vmstat.c:423
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_zone_page_state
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81275d70-ffffffff81275dd1: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127f694)
Location: mm/vmstat.c:430
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_zone_page_state
```
**Symbols:**

```
ffffffff81280650-ffffffff812806b1: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284804)
Location: mm/vmstat.c:436
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_zone_page_state
```
**Symbols:**

```
ffffffff81285770-ffffffff812857d4: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c378d)
Location: mm/vmstat.c:468
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_zone_page_state
```
**Symbols:**

```
ffffffff812c4230-ffffffff812c42f3: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81320b6d)
Location: mm/vmstat.c:497
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_zone_page_state
```
**Symbols:**

```
ffffffff81321ab0-ffffffff81321b8f: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81394a3d)
Location: mm/vmstat.c:488
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_zone_page_state
```
**Symbols:**

```
ffffffff81395b20-ffffffff81395bff: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c67bd)
Location: mm/vmstat.c:489
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_zone_page_state
```
**Symbols:**

```
ffffffff813c8750-ffffffff813c882f: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f1cfd)
Location: mm/vmstat.c:488
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_zone_page_state
```
**Symbols:**

```
ffffffff813f3140-ffffffff813f321f: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dc268)
Location: mm/vmstat.c:423
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffff8000102dc268-ffff8000102dc33c: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c0502218)
Location: mm/vmstat.c:423
Inline: False
Direct callers:
  - mm/vmstat.c:dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
c0502218-c05022c4: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039bf30)
Location: mm/vmstat.c:423
Inline: False
Direct callers:
  - mm/vmstat.c:dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
c00000000039bf30-c00000000039bfd4: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f537a)
Location: mm/vmstat.c:423
Inline: False
Direct callers:
  - mm/vmstat.c:dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffe0001f537a-ffffffe0001f5432: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81240230)
Location: mm/vmstat.c:423
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81240230-ffffffff81240291: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81233230)
Location: mm/vmstat.c:423
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81233230-ffffffff81233291: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123dfd0)
Location: mm/vmstat.c:423
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff8123dfd0-ffffffff8123e031: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __dec_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124d700)
Location: mm/vmstat.c:423
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff8124d700-ffffffff8124d761: __dec_zone_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
