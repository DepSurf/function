# Function: <code>write_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int write_pool(struct entropy_store *r, const char *buffer, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81512930)
Location: drivers/char/random.c:1491
Inline: False
Direct callers:
  - drivers/char/random.c:random_ioctl
```
**Symbols:**

```
ffffffff81512930-ffffffff815129d5: write_pool (STB_LOCAL)
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
In drivers/char/random.c (ffffffff815657e0)
Location: drivers/char/random.c:1776
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff815657e0-ffffffff8156588e: write_pool.constprop.38 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff81591f40)
Location: drivers/char/random.c:1776
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff81591f40-ffffffff81591fee: write_pool.constprop.40 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff815a5da0)
Location: drivers/char/random.c:1804
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff815a5da0-ffffffff815a5e4f: write_pool.constprop.37 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff8160c6a0)
Location: drivers/char/random.c:1803
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff8160c6a0-ffffffff8160c74f: write_pool.constprop.37 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff81646310)
Location: drivers/char/random.c:1895
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff81646310-ffffffff816463f9: write_pool.constprop.29 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff816643f0)
Location: drivers/char/random.c:1920
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff816643f0-ffffffff816644da: write_pool.constprop.30 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff81699ce0)
Location: drivers/char/random.c:2001
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff81699ce0-ffffffff81699dcc: write_pool.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff816bca10)
Location: drivers/char/random.c:2062
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff816bca10-ffffffff816bcafc: write_pool.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff81771030)
Location: drivers/char/random.c:1887
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff81771030-ffffffff81771115: write_pool.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff8178c060)
Location: drivers/char/random.c:1886
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff8178c060-ffffffff8178c145: write_pool.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff8176eed0)
Location: drivers/char/random.c:1862
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff8176eed0-ffffffff8176efb4: write_pool.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff817f4690)
Location: drivers/char/random.c:1884
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff817f4690-ffffffff817f47fa: write_pool.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/char/random.c (ffff8000108ae180)
Location: drivers/char/random.c:2062
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffff8000108ae180-ffff8000108ae370: write_pool.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (c09a9a7c)
Location: drivers/char/random.c:2062
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
c09a9a7c-c09a9b88: write_pool.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (c000000000946350)
Location: drivers/char/random.c:2062
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
c000000000946350-c000000000946484: write_pool.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffe0005619d8)
Location: drivers/char/random.c:2062
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffe0005619d8-ffffffe000561a74: write_pool.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff81682470)
Location: drivers/char/random.c:2062
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff81682470-ffffffff8168255c: write_pool.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff816602f0)
Location: drivers/char/random.c:2062
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff816602f0-ffffffff816603dc: write_pool.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff816b0850)
Location: drivers/char/random.c:2062
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff816b0850-ffffffff816b093c: write_pool.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff816cafb0)
Location: drivers/char/random.c:2062
Inline: True
Direct callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_write
```
**Symbols:**

```
ffffffff816cafb0-ffffffff816cb097: write_pool.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
