# Function: <code>lo_simple_ioctl</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816cdd2f)
Location: drivers/block/loop.c:1548
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff81708c0e)
Location: drivers/block/loop.c:1599
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff8172ceee)
Location: drivers/block/loop.c:1619
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int lo_simple_ioctl(struct loop_device *lo, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1697
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff817e9e30-ffffffff817ea094: lo_simple_ioctl (STB_LOCAL)
ffffffff817eacd0-ffffffff817eacf7: lo_simple_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int lo_simple_ioctl(struct loop_device *lo, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1688
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff817fe8a0-ffffffff817feafa: lo_simple_ioctl (STB_LOCAL)
ffffffff81c0fa99-ffffffff81c0fac0: lo_simple_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int lo_simple_ioctl(struct loop_device *lo, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1705
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff817e35c0-ffffffff817e381f: lo_simple_ioctl (STB_LOCAL)
ffffffff81c01c30-ffffffff81c01c57: lo_simple_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int lo_simple_ioctl(struct loop_device *lo, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1842
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff8186ee60-ffffffff8186f0e9: lo_simple_ioctl (STB_LOCAL)
ffffffff81d05921-ffffffff81d05972: lo_simple_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int lo_simple_ioctl(struct loop_device *lo, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1506
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff819b7ea0-ffffffff819b80c2: lo_simple_ioctl (STB_LOCAL)
ffffffff81ece31d-ffffffff81ece346: lo_simple_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int lo_simple_ioctl(struct loop_device *lo, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1506
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81b2d1f0-ffffffff81b2d412: lo_simple_ioctl (STB_LOCAL)
ffffffff82099b5a-ffffffff82099b83: lo_simple_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int lo_simple_ioctl(struct loop_device *lo, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1506
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81b7d500-ffffffff81b7d722: lo_simple_ioctl (STB_LOCAL)
ffffffff8211abf8-ffffffff8211ac21: lo_simple_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int lo_simple_ioctl(struct loop_device *lo, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:1500
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81bd1480-ffffffff81bd16a2: lo_simple_ioctl (STB_LOCAL)
ffffffff821f8a7e-ffffffff821f8aa7: lo_simple_ioctl.cold (STB_LOCAL)
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
In drivers/block/loop.c (ffff8000109247f8)
Location: drivers/block/loop.c:1619
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (c0a07f74)
Location: drivers/block/loop.c:1619
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (c0000000009c86e8)
Location: drivers/block/loop.c:1619
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffe0005a194c)
Location: drivers/block/loop.c:1619
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff816f2cce)
Location: drivers/block/loop.c:1619
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff816ccdce)
Location: drivers/block/loop.c:1619
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff817203ae)
Location: drivers/block/loop.c:1619
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
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
In drivers/block/loop.c (ffffffff8173b76e)
Location: drivers/block/loop.c:1619
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
