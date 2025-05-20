# Function: <code>do_migrate_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8181a4f8)
Location: mm/memory_hotplug.c:1435
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81893fad)
Location: mm/memory_hotplug.c:1588
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818c86ad)
Location: mm/memory_hotplug.c:1593
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818ffb1c)
Location: mm/memory_hotplug.c:1391
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81989dc7)
Location: mm/memory_hotplug.c:1379
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819e6534)
Location: mm/memory_hotplug.c:1388
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a21995)
Location: mm/memory_hotplug.c:1367
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1349
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff8129c310-ffffffff8129c63f: do_migrate_range (STB_LOCAL)
ffffffff8129d481-ffffffff8129d501: do_migrate_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1324
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812abd70-ffffffff812ac0ad: do_migrate_range (STB_LOCAL)
ffffffff812acc16-ffffffff812acc7b: do_migrate_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1294
Inline: True
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812e11b0-ffffffff812e1520: do_migrate_range.isra.0 (STB_LOCAL)
ffffffff812e1c26-ffffffff812e1c8b: do_migrate_range.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1288
Inline: True
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff812ebf70-ffffffff812ec46d: do_migrate_range.isra.0 (STB_LOCAL)
ffffffff81be9a08-ffffffff81be9a6d: do_migrate_range.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1531
Inline: True
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff812c68e0-ffffffff812c6d0f: do_migrate_range.isra.0 (STB_LOCAL)
ffffffff81bda4c5-ffffffff81bda52a: do_migrate_range.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1690
Inline: True
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff8130b360-ffffffff8130b7fe: do_migrate_range.isra.0 (STB_LOCAL)
ffffffff81cbe680-ffffffff81cbe6d4: do_migrate_range.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1626
Inline: True
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81373e10-ffffffff81374529: do_migrate_range.isra.0 (STB_LOCAL)
ffffffff81e70673-ffffffff81e706c7: do_migrate_range.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f18c0)
Location: mm/memory_hotplug.c:1624
Inline: True
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff813f18c0-ffffffff813f204e: do_migrate_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81425400)
Location: mm/memory_hotplug.c:1598
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81425400-ffffffff81425b0f: do_migrate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81452640)
Location: mm/memory_hotplug.c:1780
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81452640-ffffffff81452d50: do_migrate_range (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042e060)
Location: mm/memory_hotplug.c:1324
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
c00000000042e060-c00000000042e610: do_migrate_range (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1324
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812a4350-ffffffff812a468d: do_migrate_range (STB_LOCAL)
ffffffff812a51f6-ffffffff812a525b: do_migrate_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1324
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff81295e20-ffffffff8129615d: do_migrate_range (STB_LOCAL)
ffffffff81296cc6-ffffffff81296d2b: do_migrate_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1324
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812a2160-ffffffff812a249d: do_migrate_range (STB_LOCAL)
ffffffff812a3006-ffffffff812a306b: do_migrate_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1324
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812b24c0-ffffffff812b27fd: do_migrate_range (STB_LOCAL)
ffffffff812b3296-ffffffff812b32fb: do_migrate_range.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
