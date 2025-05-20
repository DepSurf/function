# Function: <code>do_readahead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8119c44e)
Location: mm/readahead.c:543
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In fs/jbd2/recovery.c (ffffffff812eb5ea)
Location: fs/jbd2/recovery.c:70
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811b166b)
Location: mm/readahead.c:542
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In fs/jbd2/recovery.c (ffffffff8131904c)
Location: fs/jbd2/recovery.c:70
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811c1cab)
Location: mm/readahead.c:559
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In fs/jbd2/recovery.c (ffffffff8132f03c)
Location: fs/jbd2/recovery.c:70
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811c9f54)
Location: mm/readahead.c:559
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In fs/jbd2/recovery.c (ffffffff813440c5)
Location: fs/jbd2/recovery.c:70
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811dee24)
Location: mm/readahead.c:559
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In fs/jbd2/recovery.c (ffffffff81368765)
Location: fs/jbd2/recovery.c:70
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81200577)
Location: mm/readahead.c:572
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In fs/jbd2/recovery.c (ffffffff81396ffe)
Location: fs/jbd2/recovery.c:67
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/jbd2/recovery.c (ffffffff813afd6e)
Location: fs/jbd2/recovery.c:67
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/jbd2/recovery.c (ffffffff813da2ca)
Location: fs/jbd2/recovery.c:67
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/jbd2/recovery.c (ffffffff813f431a)
Location: fs/jbd2/recovery.c:67
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:67
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff814415a0-ffffffff81441732: do_readahead.isra.0 (STB_LOCAL)
ffffffff814425a6-ffffffff814425b9: do_readahead.isra.0.cold (STB_LOCAL)
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
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:66
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff8145d790-ffffffff8145d922: do_readahead.isra.0 (STB_LOCAL)
ffffffff81becd31-ffffffff81becd44: do_readahead.isra.0.cold (STB_LOCAL)
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
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:66
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff814630b0-ffffffff81463240: do_readahead.isra.0 (STB_LOCAL)
ffffffff81bdedf1-ffffffff81bdee04: do_readahead.isra.0.cold (STB_LOCAL)
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
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:66
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff814b85b0-ffffffff814b8779: do_readahead.isra.0 (STB_LOCAL)
ffffffff81cce635-ffffffff81cce648: do_readahead.isra.0.cold (STB_LOCAL)
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
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:66
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff815420b0-ffffffff815422b4: do_readahead.isra.0 (STB_LOCAL)
ffffffff81e816e8-ffffffff81e816fb: do_readahead.isra.0.cold (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffffffff815e0d10)
Location: fs/jbd2/recovery.c:66
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff815e0d10-ffffffff815e0f0e: do_readahead.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81618600)
Location: fs/jbd2/recovery.c:67
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff81618600-ffffffff816187fe: do_readahead.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff81651550)
Location: fs/jbd2/recovery.c:67
Inline: True
Direct callers:
  - fs/jbd2/recovery.c:jread
```
**Symbols:**

```
ffffffff81651550-ffffffff81651765: do_readahead.isra.0 (STB_LOCAL)
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
In fs/jbd2/recovery.c (ffff8000104cfc1c)
Location: fs/jbd2/recovery.c:67
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (c06926c8)
Location: fs/jbd2/recovery.c:67
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (c000000000608afc)
Location: fs/jbd2/recovery.c:67
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/jbd2/recovery.c (ffffffe0003472ac)
Location: fs/jbd2/recovery.c:67
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
</details>
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
In fs/jbd2/recovery.c (ffffffff813ec8fa)
Location: fs/jbd2/recovery.c:67
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff813dd37a)
Location: fs/jbd2/recovery.c:67
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/jbd2/recovery.c (ffffffff813e9c7a)
Location: fs/jbd2/recovery.c:67
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/jbd2/recovery.c (ffffffff813ff5c5)
Location: fs/jbd2/recovery.c:67
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
</details>
</li>
</ul>

## Differences
