# Function: <code>tk_xtime_add</code>

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
In kernel/time/timekeeping.c (ffffffff810f4db3)
Location: kernel/time/timekeeping.c:90
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
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
In kernel/time/timekeeping.c (ffffffff810fc22c)
Location: kernel/time/timekeeping.c:90
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
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
In kernel/time/timekeeping.c (ffffffff810ff12c)
Location: kernel/time/timekeeping.c:90
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
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
In kernel/time/timekeeping.c (ffffffff81101540)
Location: kernel/time/timekeeping.c:96
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81101540-ffffffff811015e5: tk_xtime_add.constprop.15 (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff8110c380)
Location: kernel/time/timekeeping.c:115
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8110c380-ffffffff8110c425: tk_xtime_add.constprop.14 (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff81117bf0)
Location: kernel/time/timekeeping.c:115
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81117bf0-ffffffff81117c8e: tk_xtime_add.isra.7.constprop.19 (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff81123210)
Location: kernel/time/timekeeping.c:121
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81123210-ffffffff811232ae: tk_xtime_add.isra.8.constprop.20 (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff8112d9e0)
Location: kernel/time/timekeeping.c:122
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8112d9e0-ffffffff8112da86: tk_xtime_add.isra.0.constprop.0 (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff81139990)
Location: kernel/time/timekeeping.c:122
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81139990-ffffffff81139a36: tk_xtime_add.isra.0.constprop.0 (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff81148e1a)
Location: kernel/time/timekeeping.c:122
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8114528a)
Location: kernel/time/timekeeping.c:142
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8114634a)
Location: kernel/time/timekeeping.c:142
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8116a5d8)
Location: kernel/time/timekeeping.c:142
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8119e1d1)
Location: kernel/time/timekeeping.c:144
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811dcda1)
Location: kernel/time/timekeeping.c:144
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811f126e)
Location: kernel/time/timekeeping.c:144
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff812073ae)
Location: kernel/time/timekeeping.c:144
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
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
In kernel/time/timekeeping.c (ffff8000101a3a88)
Location: kernel/time/timekeeping.c:122
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffff8000101a3a88-ffff8000101a3b50: tk_xtime_add.isra.0.constprop.0 (STB_LOCAL)
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
In kernel/time/timekeeping.c (c03ee378)
Location: kernel/time/timekeeping.c:122
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
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
In kernel/time/timekeeping.c (c0000000002054b0)
Location: kernel/time/timekeeping.c:122
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
c0000000002054b0-c000000000205598: tk_xtime_add.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe000130600)
Location: kernel/time/timekeeping.c:122
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffe000130600-ffffffe00013068a: tk_xtime_add.isra.0.constprop.0 (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff81132140)
Location: kernel/time/timekeeping.c:122
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81132140-ffffffff811321e6: tk_xtime_add.isra.0.constprop.0 (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff81124ba0)
Location: kernel/time/timekeeping.c:122
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81124ba0-ffffffff81124c46: tk_xtime_add.isra.0.constprop.0 (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff8112fe60)
Location: kernel/time/timekeeping.c:122
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8112fe60-ffffffff8112ff06: tk_xtime_add.isra.0.constprop.0 (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff8113c880)
Location: kernel/time/timekeeping.c:122
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8113c880-ffffffff8113c926: tk_xtime_add.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
