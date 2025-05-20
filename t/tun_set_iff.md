# Function: <code>tun_set_iff</code>

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
In drivers/net/tun.c (ffffffff815f0035)
Location: drivers/net/tun.c:1606
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff8164f45f)
Location: drivers/net/tun.c:1706
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff81681782)
Location: drivers/net/tun.c:1697
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff816965cf)
Location: drivers/net/tun.c:1738
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff817013d9)
Location: drivers/net/tun.c:2197
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
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
In drivers/net/tun.c (ffffffff8173dde0)
Location: drivers/net/tun.c:2538
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8173dde0-ffffffff8173e43f: tun_set_iff.constprop.71 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff81761d40)
Location: drivers/net/tun.c:2698
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81761d40-ffffffff817623b7: tun_set_iff.constprop.73 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff8179fa50)
Location: drivers/net/tun.c:2693
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8179fa50-ffffffff817a00f6: tun_set_iff.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff817c3ce0)
Location: drivers/net/tun.c:2697
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817c3ce0-ffffffff817c4386: tun_set_iff.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff8188f740)
Location: drivers/net/tun.c:2677
Inline: True
```
**Symbols:**

```
ffffffff8188f740-ffffffff8188fdd5: tun_set_iff.constprop.0.isra.0 (STB_LOCAL)
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
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2599
Inline: True
```
**Symbols:**

```
ffffffff8189dac0-ffffffff8189e1f5: tun_set_iff.constprop.0.isra.0 (STB_LOCAL)
ffffffff81c19676-ffffffff81c1968e: tun_set_iff.constprop.0.isra.0.cold (STB_LOCAL)
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
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2604
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81880220-ffffffff8188097d: tun_set_iff.constprop.0 (STB_LOCAL)
ffffffff81c0b4d1-ffffffff81c0b4e9: tun_set_iff.constprop.0.cold (STB_LOCAL)
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
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2655
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81911ac0-ffffffff81912048: tun_set_iff.constprop.0 (STB_LOCAL)
ffffffff81d10afc-ffffffff81d10b14: tun_set_iff.constprop.0.cold (STB_LOCAL)
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
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2705
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81a64a00-ffffffff81a64fcd: tun_set_iff.constprop.0 (STB_LOCAL)
ffffffff81edb8e4-ffffffff81edb8fc: tun_set_iff.constprop.0.cold (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff81befc80)
Location: drivers/net/tun.c:2709
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81befc80-ffffffff81bf029b: tun_set_iff.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff81c48200)
Location: drivers/net/tun.c:2730
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81c48200-ffffffff81c4881c: tun_set_iff.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff81cfdb80)
Location: drivers/net/tun.c:2742
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81cfdb80-ffffffff81cfe17b: tun_set_iff.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffff8000109de810)
Location: drivers/net/tun.c:2697
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffff8000109de810-ffff8000109dedf4: tun_set_iff.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (c0ac3a34)
Location: drivers/net/tun.c:2697
Inline: True
```
**Symbols:**

```
c0ac3a34-c0ac409c: tun_set_iff.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (c000000000a9ff90)
Location: drivers/net/tun.c:2697
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
c000000000a9ff90-c000000000aa06e8: tun_set_iff.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffe000629016)
Location: drivers/net/tun.c:2697
Inline: True
```
**Symbols:**

```
ffffffe000629016-ffffffe0006295ac: tun_set_iff.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff817887c0)
Location: drivers/net/tun.c:2697
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817887c0-ffffffff81788e66: tun_set_iff.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff81768110)
Location: drivers/net/tun.c:2697
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81768110-ffffffff817687b6: tun_set_iff.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff817b8b60)
Location: drivers/net/tun.c:2697
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817b8b60-ffffffff817b9206: tun_set_iff.constprop.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff817d3830)
Location: drivers/net/tun.c:2697
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817d3830-ffffffff817d3ed6: tun_set_iff.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
