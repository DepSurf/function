# Function: <code>d_revalidate</code>

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
In fs/namei.c (ffffffff81217894)
Location: fs/namei.c:765
Inline: True
Inline callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
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
In fs/namei.c (ffffffff81242170)
Location: fs/namei.c:770
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
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
In fs/namei.c (ffffffff81255042)
Location: fs/namei.c:770
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
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
In fs/namei.c (ffffffff81261000)
Location: fs/namei.c:779
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff8125caa0-ffffffff8125caac: d_revalidate.part.14 (STB_LOCAL)
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
In fs/namei.c (ffffffff812836e4)
Location: fs/namei.c:780
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff8127ee00-ffffffff8127ee12: d_revalidate.part.18 (STB_LOCAL)
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
In fs/namei.c (ffffffff812a9eab)
Location: fs/namei.c:764
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812a5790-ffffffff812a57a2: d_revalidate.part.26 (STB_LOCAL)
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
In fs/namei.c (ffffffff812bfbe0)
Location: fs/namei.c:764
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812ba8f0-ffffffff812ba902: d_revalidate.part.25 (STB_LOCAL)
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
In fs/namei.c (ffffffff812dc37b)
Location: fs/namei.c:762
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812d74f0-ffffffff812d7502: d_revalidate.part.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812ede8b)
Location: fs/namei.c:755
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812e9050-ffffffff812e9062: d_revalidate.part.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff81322938)
Location: fs/namei.c:765
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
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
In fs/namei.c (ffffffff8132ded8)
Location: fs/namei.c:765
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
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
In fs/namei.c (ffffffff81333fe8)
Location: fs/namei.c:824
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
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
In fs/namei.c (ffffffff81381938)
Location: fs/namei.c:851
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
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
In fs/namei.c (ffffffff81400985)
Location: fs/namei.c:845
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
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
In fs/namei.c (ffffffff8148a7e9)
Location: fs/namei.c:853
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
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
In fs/namei.c (ffffffff814c0699)
Location: fs/namei.c:856
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
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
In fs/namei.c (ffffffff814f2b79)
Location: fs/namei.c:859
Inline: True
Inline callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
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
In fs/namei.c (ffff80001039767c)
Location: fs/namei.c:755
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffff8000103923d0-ffff8000103923ec: d_revalidate.part.0 (STB_LOCAL)
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
In fs/namei.c (c057dc28)
Location: fs/namei.c:755
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
c05799bc-c05799d8: d_revalidate.part.0 (STB_LOCAL)
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
In fs/namei.c (c000000000491560)
Location: fs/namei.c:755
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
c00000000048add0-c00000000048ae0c: d_revalidate.part.0 (STB_LOCAL)
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
In fs/namei.c (ffffffe0002656f8)
Location: fs/namei.c:755
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffe000261614-ffffffe00026162a: d_revalidate.part.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812e646b)
Location: fs/namei.c:755
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812e1630-ffffffff812e1642: d_revalidate.part.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812d70ab)
Location: fs/namei.c:755
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812d2270-ffffffff812d2282: d_revalidate.part.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812e427b)
Location: fs/namei.c:755
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812df440-ffffffff812df452: d_revalidate.part.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812f51fb)
Location: fs/namei.c:755
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/namei.c:lookup_dcache
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812f0830-ffffffff812f0842: d_revalidate.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
