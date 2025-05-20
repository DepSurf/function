# Function: <code>restore_bytes</code>

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
In mm/slub.c (ffffffff811e82d6)
Location: mm/slub.c:689
Inline: True
Inline callers:
  - mm/slub.c:check_bytes_and_report
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
In mm/slub.c (ffffffff812078a1)
Location: mm/slub.c:707
Inline: True
Inline callers:
  - mm/slub.c:check_bytes_and_report
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
In mm/slub.c (ffffffff812198d1)
Location: mm/slub.c:706
Inline: True
Inline callers:
  - mm/slub.c:check_bytes_and_report
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812252c0)
Location: mm/slub.c:708
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff812252c0-ffffffff81225302: restore_bytes.constprop.81 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81240940)
Location: mm/slub.c:743
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff81240940-ffffffff81240982: restore_bytes.constprop.81 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8126ab6d)
Location: mm/slub.c:729
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff8126ab6d-ffffffff8126abad: restore_bytes.constprop.83 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8127f3fd)
Location: mm/slub.c:734
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff8127f3fd-ffffffff8127f43d: restore_bytes.constprop.85 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8129b28b)
Location: mm/slub.c:726
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff8129b28b-ffffffff8129b2cb: restore_bytes.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812ab14b)
Location: mm/slub.c:726
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff812ab14b-ffffffff812ab18b: restore_bytes.constprop.0 (STB_LOCAL)
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
In mm/slub.c (ffffffff812dfbd5)
Location: mm/slub.c:772
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff812dfbd5-ffffffff812dfc15: restore_bytes.constprop.0 (STB_LOCAL)
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
In mm/slub.c (ffffffff81be919d)
Location: mm/slub.c:767
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff81be919d-ffffffff81be91dd: restore_bytes.constprop.0 (STB_LOCAL)
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
In mm/slub.c (ffffffff81bdb328)
Location: mm/slub.c:779
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff81bdb328-ffffffff81bdb368: restore_bytes.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void restore_bytes(struct kmem_cache *s, char *message, u8 data, void *from, void *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81cc0cb5)
Location: mm/slub.c:900
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff81cc0cb5-ffffffff81cc0cf8: restore_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void restore_bytes(struct kmem_cache *s, char *message, u8 data, void *from, void *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81e73203)
Location: mm/slub.c:947
Inline: False
Direct callers:
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff81e73203-ffffffff81e7325a: restore_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void restore_bytes(struct kmem_cache *s, char *message, u8 data, void *from, void *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81423d10)
Location: mm/slub.c:1025
Inline: False
Direct callers:
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff81423d10-ffffffff81423d6a: restore_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void restore_bytes(struct kmem_cache *s, char *message, u8 data, void *from, void *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81458fb0)
Location: mm/slub.c:1046
Inline: False
Direct callers:
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff81458fb0-ffffffff8145900a: restore_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void restore_bytes(struct kmem_cache *s, char *message, u8 data, void *from, void *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81453f70)
Location: mm/slub.c:1159
Inline: False
Direct callers:
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff81453f70-ffffffff81453fca: restore_bytes (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffff80001034d680)
Location: mm/slub.c:726
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffff80001034d680-ffff80001034d6e4: restore_bytes.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (c05508dc)
Location: mm/slub.c:726
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
c05508dc-c055092c: restore_bytes.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (c00000000042cf50)
Location: mm/slub.c:726
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
c00000000042cf50-c00000000042cfc8: restore_bytes.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe000237ac4)
Location: mm/slub.c:726
Inline: True
Inline callers:
  - mm/slub.c:check_bytes_and_report
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812a372b)
Location: mm/slub.c:726
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff812a372b-ffffffff812a376b: restore_bytes.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812951fb)
Location: mm/slub.c:726
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff812951fb-ffffffff8129523b: restore_bytes.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812a153b)
Location: mm/slub.c:726
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff812a153b-ffffffff812a157b: restore_bytes.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812b16eb)
Location: mm/slub.c:726
Inline: True
Direct callers:
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff812b16eb-ffffffff812b172b: restore_bytes.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
