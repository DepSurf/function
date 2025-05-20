# Function: <code>__inc_node_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6cb0)
Location: mm/vmstat.c:319
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811c6cb0-ffffffff811c6d0d: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6dd0)
Location: mm/vmstat.c:319
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811d6dd0-ffffffff811d6e2d: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811dfc30)
Location: mm/vmstat.c:319
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811dfc30-ffffffff811dfc8d: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f5a40)
Location: mm/vmstat.c:394
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811f5a40-ffffffff811f5a9d: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216cc0)
Location: mm/vmstat.c:394
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81216cc0-ffffffff81216d1d: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229bd0)
Location: mm/vmstat.c:394
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81229bd0-ffffffff81229c2d: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81239860)
Location: mm/vmstat.c:395
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81239860-ffffffff812398bd: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81247b60)
Location: mm/vmstat.c:395
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81247b60-ffffffff81247bbd: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81274db7)
Location: mm/vmstat.c:395
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_node_page_state
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81275d10-ffffffff81275d6d: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127fc67)
Location: mm/vmstat.c:400
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_node_page_state
```
**Symbols:**

```
ffffffff812805f0-ffffffff8128064d: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284da7)
Location: mm/vmstat.c:406
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_node_page_state
```
**Symbols:**

```
ffffffff81285700-ffffffff81285764: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c2c61)
Location: mm/vmstat.c:431
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_node_page_state
```
**Symbols:**

```
ffffffff812c4190-ffffffff812c4227: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8131fe71)
Location: mm/vmstat.c:460
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_node_page_state
```
**Symbols:**

```
ffffffff813219f0-ffffffff81321aa3: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813939a5)
Location: mm/vmstat.c:453
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_node_page_state
```
**Symbols:**

```
ffffffff81395a30-ffffffff81395b10: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c66a5)
Location: mm/vmstat.c:454
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_node_page_state
```
**Symbols:**

```
ffffffff813c8660-ffffffff813c8740: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f1a65)
Location: mm/vmstat.c:453
Inline: True
Inline callers:
  - mm/vmstat.c:__inc_node_page_state
```
**Symbols:**

```
ffffffff813f3050-ffffffff813f3130: __inc_node_state (STB_GLOBAL)
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
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dc148)
Location: mm/vmstat.c:395
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffff8000102dc148-ffff8000102dc21c: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c05020f0)
Location: mm/vmstat.c:395
Inline: False
Direct callers:
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
c05020f0-c050219c: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039bda0)
Location: mm/vmstat.c:395
Inline: False
Direct callers:
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
c00000000039bda0-c00000000039be3c: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f520e)
Location: mm/vmstat.c:395
Inline: False
Direct callers:
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffe0001f520e-ffffffe0001f52c8: __inc_node_state (STB_GLOBAL)
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
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812401b0)
Location: mm/vmstat.c:395
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812401b0-ffffffff8124020d: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812331b0)
Location: mm/vmstat.c:395
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812331b0-ffffffff8123320d: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123df50)
Location: mm/vmstat.c:395
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff8123df50-ffffffff8123dfad: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __inc_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124d680)
Location: mm/vmstat.c:395
Inline: False
Direct callers:
  - mm/vmstat.c:__inc_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff8124d680-ffffffff8124d6dd: __inc_node_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
