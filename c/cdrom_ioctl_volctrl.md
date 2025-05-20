# Function: <code>cdrom_ioctl_volctrl</code>

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
In drivers/cdrom/cdrom.c (ffffffff816025d3)
Location: drivers/cdrom/cdrom.c:2702
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff816622da)
Location: drivers/cdrom/cdrom.c:2712
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff816900ca)
Location: drivers/cdrom/cdrom.c:2712
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff816a5271)
Location: drivers/cdrom/cdrom.c:2718
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817105fb)
Location: drivers/cdrom/cdrom.c:2718
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff8174f299)
Location: drivers/cdrom/cdrom.c:2715
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81773cce)
Location: drivers/cdrom/cdrom.c:2718
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817b1491)
Location: drivers/cdrom/cdrom.c:2719
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817e17e1)
Location: drivers/cdrom/cdrom.c:2726
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cdrom_ioctl_volctrl(struct cdrom_device_info *cdi, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818acbf0)
Location: drivers/cdrom/cdrom.c:2743
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff818acbf0-ffffffff818acca7: cdrom_ioctl_volctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cdrom_ioctl_volctrl(struct cdrom_device_info *cdi, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818bb830)
Location: drivers/cdrom/cdrom.c:2726
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff818bb830-ffffffff818bb8e7: cdrom_ioctl_volctrl (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffffffff818a2391)
Location: drivers/cdrom/cdrom.c:2726
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81936e7d)
Location: drivers/cdrom/cdrom.c:2671
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81a8e043)
Location: drivers/cdrom/cdrom.c:2710
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81c0f607)
Location: drivers/cdrom/cdrom.c:2710
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81c76d0c)
Location: drivers/cdrom/cdrom.c:2696
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81d2b70c)
Location: drivers/cdrom/cdrom.c:2696
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffff800010a0f5e4)
Location: drivers/cdrom/cdrom.c:2726
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (c0ae7bd0)
Location: drivers/cdrom/cdrom.c:2726
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (c000000000ac65a0)
Location: drivers/cdrom/cdrom.c:2726
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffe000635818)
Location: drivers/cdrom/cdrom.c:2726
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81799bc1)
Location: drivers/cdrom/cdrom.c:2726
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff8178b891)
Location: drivers/cdrom/cdrom.c:2726
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817d6661)
Location: drivers/cdrom/cdrom.c:2726
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817f0901)
Location: drivers/cdrom/cdrom.c:2726
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
</ul>
