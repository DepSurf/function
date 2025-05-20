# Function: <code>__dec_node_state</code>

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
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c6de0)
Location: mm/vmstat.c:363
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811c6de0-ffffffff811c6e43: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6f00)
Location: mm/vmstat.c:363
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811d6f00-ffffffff811d6f63: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811dfd60)
Location: mm/vmstat.c:363
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811dfd60-ffffffff811dfdc3: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f5b70)
Location: mm/vmstat.c:438
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff811f5b70-ffffffff811f5bd3: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81216df0)
Location: mm/vmstat.c:438
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81216df0-ffffffff81216e53: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81229d00)
Location: mm/vmstat.c:438
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81229d00-ffffffff81229d63: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81239990)
Location: mm/vmstat.c:439
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81239990-ffffffff812399f3: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81247c90)
Location: mm/vmstat.c:439
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81247c90-ffffffff81247cf3: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812753a7)
Location: mm/vmstat.c:439
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_node_page_state
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81275de0-ffffffff81275e43: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127f607)
Location: mm/vmstat.c:446
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_node_page_state
```
**Symbols:**

```
ffffffff812806c0-ffffffff81280723: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81284777)
Location: mm/vmstat.c:452
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_node_page_state
```
**Symbols:**

```
ffffffff812857e0-ffffffff81285846: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c3421)
Location: mm/vmstat.c:491
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_node_page_state
```
**Symbols:**

```
ffffffff812c4300-ffffffff812c43a0: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81320751)
Location: mm/vmstat.c:520
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_node_page_state
```
**Symbols:**

```
ffffffff81321b90-ffffffff81321c4c: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81394575)
Location: mm/vmstat.c:509
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_node_page_state
```
**Symbols:**

```
ffffffff81395c10-ffffffff81395cf2: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c7085)
Location: mm/vmstat.c:510
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_node_page_state
```
**Symbols:**

```
ffffffff813c8840-ffffffff813c8922: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f10b5)
Location: mm/vmstat.c:509
Inline: True
Inline callers:
  - mm/vmstat.c:__dec_node_page_state
```
**Symbols:**

```
ffffffff813f3230-ffffffff813f3312: __dec_node_state (STB_GLOBAL)
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
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dc398)
Location: mm/vmstat.c:439
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffff8000102dc398-ffff8000102dc46c: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c0502330)
Location: mm/vmstat.c:439
Inline: False
Direct callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
c0502330-c05023dc: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039c0a0)
Location: mm/vmstat.c:439
Inline: False
Direct callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
c00000000039c0a0-c00000000039c140: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f54d0)
Location: mm/vmstat.c:439
Inline: False
Direct callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffe0001f54d0-ffffffe0001f5590: __dec_node_state (STB_GLOBAL)
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
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812402e0)
Location: mm/vmstat.c:439
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812402e0-ffffffff81240343: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812332e0)
Location: mm/vmstat.c:439
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812332e0-ffffffff81233343: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123e080)
Location: mm/vmstat.c:439
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff8123e080-ffffffff8123e0e3: __dec_node_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __dec_node_state(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124d7b0)
Location: mm/vmstat.c:439
Inline: False
Direct callers:
  - mm/vmstat.c:__dec_node_page_state
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff8124d7b0-ffffffff8124d813: __dec_node_state (STB_GLOBAL)
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
