# Function: <code>xen_swiotlb_fixup</code>

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
In drivers/xen/swiotlb-xen.c (ffffffff8181b215)
Location: drivers/xen/swiotlb-xen.c:159
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
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
In drivers/xen/swiotlb-xen.c (ffffffff818953ae)
Location: drivers/xen/swiotlb-xen.c:159
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
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
In drivers/xen/swiotlb-xen.c (ffffffff818c9c13)
Location: drivers/xen/swiotlb-xen.c:159
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
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
In drivers/xen/swiotlb-xen.c (ffffffff819011a7)
Location: drivers/xen/swiotlb-xen.c:161
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
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
In drivers/xen/swiotlb-xen.c (ffffffff8198b1cb)
Location: drivers/xen/swiotlb-xen.c:161
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
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
In drivers/xen/swiotlb-xen.c (ffffffff819e7a96)
Location: drivers/xen/swiotlb-xen.c:147
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
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
In drivers/xen/swiotlb-xen.c (ffffffff81a22f70)
Location: drivers/xen/swiotlb-xen.c:145
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a93017)
Location: drivers/xen/swiotlb-xen.c:120
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81aca7f3)
Location: drivers/xen/swiotlb-xen.c:120
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81bc2cf8)
Location: drivers/xen/swiotlb-xen.c:120
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
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
In drivers/xen/swiotlb-xen.c (ffffffff81740260)
Location: drivers/xen/swiotlb-xen.c:122
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81740260-ffffffff81740354: xen_swiotlb_fixup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_swiotlb_fixup(void *buf, long unsigned int nslabs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81723d30)
Location: drivers/xen/swiotlb-xen.c:107
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
```
**Symbols:**

```
ffffffff81723d30-ffffffff81723e21: xen_swiotlb_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xen_swiotlb_fixup(void *buf, long unsigned int nslabs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff817a2b70)
Location: drivers/xen/swiotlb-xen.c:107
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
```
**Symbols:**

```
ffffffff817a2b70-ffffffff817a2c26: xen_swiotlb_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xen_swiotlb_fixup(void *buf, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff818de500)
Location: drivers/xen/swiotlb-xen.c:107
Inline: False
```
**Symbols:**

```
ffffffff818de500-ffffffff818de5d4: xen_swiotlb_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xen_swiotlb_fixup(void *buf, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a31a10)
Location: drivers/xen/swiotlb-xen.c:107
Inline: False
```
**Symbols:**

```
ffffffff81a31a10-ffffffff81a31ae4: xen_swiotlb_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xen_swiotlb_fixup(void *buf, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a7b220)
Location: drivers/xen/swiotlb-xen.c:107
Inline: False
```
**Symbols:**

```
ffffffff81a7b220-ffffffff81a7b2f4: xen_swiotlb_fixup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xen_swiotlb_fixup(void *buf, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81acd6d0)
Location: drivers/xen/swiotlb-xen.c:107
Inline: False
```
**Symbols:**

```
ffffffff81acd6d0-ffffffff81acd7a4: xen_swiotlb_fixup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffff800010d9ded0)
Location: drivers/xen/swiotlb-xen.c:120
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a69663)
Location: drivers/xen/swiotlb-xen.c:120
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81ad5a73)
Location: drivers/xen/swiotlb-xen.c:120
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81ae1f33)
Location: drivers/xen/swiotlb-xen.c:120
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
