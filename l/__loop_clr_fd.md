# Function: <code>__loop_clr_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816cb890)
Location: drivers/block/loop.c:1086
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816cb890-ffffffff816cbc84: __loop_clr_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1123
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81706e90-ffffffff81707285: __loop_clr_fd (STB_LOCAL)
ffffffff81709d6d-ffffffff81709d8a: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1143
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8172b0e0-ffffffff8172b4d5: __loop_clr_fd (STB_LOCAL)
ffffffff8172e06a-ffffffff8172e087: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1251
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff817e7030-ffffffff817e748f: __loop_clr_fd (STB_LOCAL)
ffffffff817eac39-ffffffff817eac57: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1243
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff817fbc80-ffffffff817fc0d0: __loop_clr_fd (STB_LOCAL)
ffffffff81c0f9fa-ffffffff81c0fa18: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1250
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff817e0d30-ffffffff817e1177: __loop_clr_fd (STB_LOCAL)
ffffffff81c01b8e-ffffffff81c01bac: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1373
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81870260-ffffffff818707ca: __loop_clr_fd (STB_LOCAL)
ffffffff81d05a38-ffffffff81d05a6b: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1136
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff819b5890-ffffffff819b5ae3: __loop_clr_fd (STB_LOCAL)
ffffffff81ece14f-ffffffff81ece181: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1136
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81b2a960-ffffffff81b2abde: __loop_clr_fd (STB_LOCAL)
ffffffff820999d2-ffffffff820999e7: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1136
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81b7ac40-ffffffff81b7aec7: __loop_clr_fd (STB_LOCAL)
ffffffff8211aa72-ffffffff8211aa87: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1132
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81bcea10-ffffffff81bcec8a: __loop_clr_fd (STB_LOCAL)
ffffffff821f88e3-ffffffff821f88f8: __loop_clr_fd.cold (STB_LOCAL)
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
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff8000109235c8)
Location: drivers/block/loop.c:1143
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffff8000109235c8-ffff800010923934: __loop_clr_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a0650c)
Location: drivers/block/loop.c:1143
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
c0a0650c-c0a0689c: __loop_clr_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c6060)
Location: drivers/block/loop.c:1143
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
c0000000009c6060-c0000000009c6510: __loop_clr_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe00059fb68)
Location: drivers/block/loop.c:1143
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffe00059fb68-ffffffe00059ff36: __loop_clr_fd (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1143
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816f0ec0-ffffffff816f12b5: __loop_clr_fd (STB_LOCAL)
ffffffff816f3e4a-ffffffff816f3e67: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1143
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816cafd0-ffffffff816cb3bf: __loop_clr_fd (STB_LOCAL)
ffffffff816cdf4a-ffffffff816cdf67: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1143
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8171e5a0-ffffffff8171e995: __loop_clr_fd (STB_LOCAL)
ffffffff8172152a-ffffffff81721547: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __loop_clr_fd(struct loop_device *lo, bool release);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1143
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff817399e0-ffffffff81739dcc: __loop_clr_fd (STB_LOCAL)
ffffffff8173c8f7-ffffffff8173c914: __loop_clr_fd.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
