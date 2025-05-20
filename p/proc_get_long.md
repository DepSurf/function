# Function: <code>proc_get_long</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (ffffffff81088010)
Location: kernel/sysctl.c:1950
Inline: True
Direct callers:
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
```
**Symbols:**

```
ffffffff81088010-ffffffff810881ba: proc_get_long.constprop.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (ffffffff8108aea0)
Location: kernel/sysctl.c:2070
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff8108aea0-ffffffff8108b04a: proc_get_long.constprop.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (ffffffff8108fdf0)
Location: kernel/sysctl.c:2055
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff8108fdf0-ffffffff8108ffa0: proc_get_long.constprop.14 (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff8108cec0)
Location: kernel/sysctl.c:2079
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff8108cec0-ffffffff8108d0bd: proc_get_long.constprop.14 (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff81093b90)
Location: kernel/sysctl.c:2071
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff81093b90-ffffffff81093d8d: proc_get_long.constprop.15 (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2076
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810975f0-ffffffff810977d4: proc_get_long.constprop.15 (STB_LOCAL)
ffffffff81098d16-ffffffff81098d22: proc_get_long.constprop.15.cold.18 (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2124
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff8109f910-ffffffff8109faf4: proc_get_long.constprop.16 (STB_LOCAL)
ffffffff810a1098-ffffffff810a10a4: proc_get_long.constprop.16.cold.19 (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2209
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810a4000-ffffffff810a41ef: proc_get_long.constprop.0 (STB_LOCAL)
ffffffff810a5aee-ffffffff810a5afa: proc_get_long.constprop.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2211
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810aa5e0-ffffffff810aa7cf: proc_get_long.constprop.0 (STB_LOCAL)
ffffffff810ac0ce-ffffffff810ac0da: proc_get_long.constprop.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:440
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:do_proc_douintvec_w
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810b1f60-ffffffff810b2159: proc_get_long.constprop.0 (STB_LOCAL)
ffffffff810b3c9d-ffffffff810b3ca9: proc_get_long.constprop.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:439
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:do_proc_douintvec_w
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810ad790-ffffffff810ad989: proc_get_long.constprop.0 (STB_LOCAL)
ffffffff81bdb8d9-ffffffff81bdb8e5: proc_get_long.constprop.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:451
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810ae9a0-ffffffff810aeb96: proc_get_long.constprop.0 (STB_LOCAL)
ffffffff81bcd9cb-ffffffff81bcd9d7: proc_get_long.constprop.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:460
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810c07c0-ffffffff810c09e3: proc_get_long.constprop.0 (STB_LOCAL)
ffffffff81ca4447-ffffffff81ca4453: proc_get_long.constprop.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:340
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810d7d70-ffffffff810d7fc3: proc_get_long.constprop.0 (STB_LOCAL)
ffffffff81e53c9b-ffffffff81e53ca7: proc_get_long.constprop.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff810f78a0)
Location: kernel/sysctl.c:343
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810f78a0-ffffffff810f7ae2: proc_get_long.constprop.0 (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff81103ca0)
Location: kernel/sysctl.c:342
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff81103ca0-ffffffff81103ee2: proc_get_long.constprop.0 (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff8110d5f0)
Location: kernel/sysctl.c:342
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff8110d5f0-ffffffff8110d832: proc_get_long.constprop.0 (STB_LOCAL)
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
In kernel/sysctl.c (ffff800010102898)
Location: kernel/sysctl.c:2211
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffff800010102898-ffff800010102a24: proc_get_long.constprop.0 (STB_LOCAL)
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
In kernel/sysctl.c (c035eb14)
Location: kernel/sysctl.c:2211
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
c035eb14-c035ecbc: proc_get_long.constprop.0 (STB_LOCAL)
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
In kernel/sysctl.c (c00000000014a0e0)
Location: kernel/sysctl.c:2211
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
c00000000014a0e0-c00000000014a34c: proc_get_long.constprop.0 (STB_LOCAL)
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
In kernel/sysctl.c (ffffffe0000c9674)
Location: kernel/sysctl.c:2211
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffe0000c9674-ffffffe0000c97ac: proc_get_long.constprop.0 (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2211
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810a3f00-ffffffff810a40ef: proc_get_long.constprop.0 (STB_LOCAL)
ffffffff810a59ee-ffffffff810a59fa: proc_get_long.constprop.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2211
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810928e0-ffffffff81092acf: proc_get_long.constprop.0 (STB_LOCAL)
ffffffff810943ce-ffffffff810943da: proc_get_long.constprop.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2211
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810a3eb0-ffffffff810a409f: proc_get_long.constprop.0 (STB_LOCAL)
ffffffff810a599e-ffffffff810a59aa: proc_get_long.constprop.0.cold (STB_LOCAL)
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
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2211
Inline: True
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810abf70-ffffffff810ac15f: proc_get_long.constprop.0 (STB_LOCAL)
ffffffff810ada5e-ffffffff810ada6a: proc_get_long.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
