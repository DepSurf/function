# Function: <code>__inc_zone_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811ad9e0)
Location: mm/vmstat.c:264
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_zone_page_state
  - mm/vmstat.c:zone_statistics
  - mm/vmstat.c:zone_statistics
  - mm/vmstat.c:zone_statistics
  - mm/vmstat.c:zone_statistics
  - mm/vmstat.c:zone_statistics
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811ad9e0-ffffffff811ada31: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6c10)
Location: mm/vmstat.c:303
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811c6c10-ffffffff811c6c6b: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6d30)
Location: mm/vmstat.c:303
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811d6d30-ffffffff811d6d8b: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811dfb90)
Location: mm/vmstat.c:303
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811dfb90-ffffffff811dfbeb: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f59a0)
Location: mm/vmstat.c:378
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811f59a0-ffffffff811f59fb: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216c20)
Location: mm/vmstat.c:378
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81216c20-ffffffff81216c7b: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229b30)
Location: mm/vmstat.c:378
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81229b30-ffffffff81229b8b: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812397c0)
Location: mm/vmstat.c:379
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812397c0-ffffffff8123981b: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81247ac0)
Location: mm/vmstat.c:379
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81247ac0-ffffffff81247b1b: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81275434)
Location: mm/vmstat.c:379
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_zone_page_state
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81275cb0-ffffffff81275d0b: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127fce4)
Location: mm/vmstat.c:384
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_zone_page_state
```
**Symbols:**

```
ffffffff81280590-ffffffff812805eb: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284e24)
Location: mm/vmstat.c:390
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_zone_page_state
```
**Symbols:**

```
ffffffff81285690-ffffffff812856f2: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c2d2c)
Location: mm/vmstat.c:408
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_zone_page_state
```
**Symbols:**

```
ffffffff812c40c0-ffffffff812c4181: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8131ff4c)
Location: mm/vmstat.c:437
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_zone_page_state
```
**Symbols:**

```
ffffffff81321910-ffffffff813219ed: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81393abc)
Location: mm/vmstat.c:432
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_zone_page_state
```
**Symbols:**

```
ffffffff81395940-ffffffff81395a1d: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c753c)
Location: mm/vmstat.c:433
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_zone_page_state
```
**Symbols:**

```
ffffffff813c8570-ffffffff813c864d: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f11cc)
Location: mm/vmstat.c:432
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_zone_page_state
```
**Symbols:**

```
ffffffff813f2f60-ffffffff813f303d: __inc_zone_state (STB_GLOBAL)
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
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dc018)
Location: mm/vmstat.c:379
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffff8000102dc018-ffff8000102dc0ec: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c0501fd8)
Location: mm/vmstat.c:379
Inline: False
Direct callers:
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
c0501fd8-c0502084: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039bc40)
Location: mm/vmstat.c:379
Inline: False
Direct callers:
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
c00000000039bc40-c00000000039bce0: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f50c4)
Location: mm/vmstat.c:379
Inline: False
Direct callers:
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffe0001f50c4-ffffffe0001f5176: __inc_zone_state (STB_GLOBAL)
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
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81240110)
Location: mm/vmstat.c:379
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81240110-ffffffff8124016b: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81233110)
Location: mm/vmstat.c:379
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81233110-ffffffff8123316b: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123deb0)
Location: mm/vmstat.c:379
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff8123deb0-ffffffff8123df0b: __inc_zone_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __inc_zone_state(struct zone *zone, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124d5e0)
Location: mm/vmstat.c:379
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_zone_page_state
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff8124d5e0-ffffffff8124d63b: __inc_zone_state (STB_GLOBAL)
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
