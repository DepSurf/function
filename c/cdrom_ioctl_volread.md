# Function: <code>cdrom_ioctl_volread</code>

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
In drivers/cdrom/cdrom.c (ffffffff81602563)
Location: drivers/cdrom/cdrom.c:2716
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
In drivers/cdrom/cdrom.c (ffffffff81662272)
Location: drivers/cdrom/cdrom.c:2726
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
In drivers/cdrom/cdrom.c (ffffffff81690062)
Location: drivers/cdrom/cdrom.c:2726
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
In drivers/cdrom/cdrom.c (ffffffff816a520e)
Location: drivers/cdrom/cdrom.c:2732
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
In drivers/cdrom/cdrom.c (ffffffff81710592)
Location: drivers/cdrom/cdrom.c:2732
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
In drivers/cdrom/cdrom.c (ffffffff8174f22f)
Location: drivers/cdrom/cdrom.c:2729
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
In drivers/cdrom/cdrom.c (ffffffff817735ae)
Location: drivers/cdrom/cdrom.c:2732
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
In drivers/cdrom/cdrom.c (ffffffff817b140f)
Location: drivers/cdrom/cdrom.c:2733
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
In drivers/cdrom/cdrom.c (ffffffff817e175f)
Location: drivers/cdrom/cdrom.c:2740
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
int cdrom_ioctl_volread(struct cdrom_device_info *cdi, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818acf60)
Location: drivers/cdrom/cdrom.c:2757
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff818acf60-ffffffff818ad01e: cdrom_ioctl_volread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cdrom_ioctl_volread(struct cdrom_device_info *cdi, void *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818bbba0)
Location: drivers/cdrom/cdrom.c:2740
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff818bbba0-ffffffff818bbc5e: cdrom_ioctl_volread (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffffffff818a2312)
Location: drivers/cdrom/cdrom.c:2740
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
In drivers/cdrom/cdrom.c (ffffffff81936df0)
Location: drivers/cdrom/cdrom.c:2685
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
In drivers/cdrom/cdrom.c (ffffffff81a8dc4a)
Location: drivers/cdrom/cdrom.c:2724
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
In drivers/cdrom/cdrom.c (ffffffff81c0f3bb)
Location: drivers/cdrom/cdrom.c:2724
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
In drivers/cdrom/cdrom.c (ffffffff81c76dbf)
Location: drivers/cdrom/cdrom.c:2710
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
In drivers/cdrom/cdrom.c (ffffffff81d2b7bf)
Location: drivers/cdrom/cdrom.c:2710
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
In drivers/cdrom/cdrom.c (ffff800010a0f534)
Location: drivers/cdrom/cdrom.c:2740
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
In drivers/cdrom/cdrom.c (c0ae7e24)
Location: drivers/cdrom/cdrom.c:2740
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
In drivers/cdrom/cdrom.c (c000000000ac652c)
Location: drivers/cdrom/cdrom.c:2740
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
In drivers/cdrom/cdrom.c (ffffffe0006356d2)
Location: drivers/cdrom/cdrom.c:2740
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
In drivers/cdrom/cdrom.c (ffffffff81799b3f)
Location: drivers/cdrom/cdrom.c:2740
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
In drivers/cdrom/cdrom.c (ffffffff8178b80f)
Location: drivers/cdrom/cdrom.c:2740
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
In drivers/cdrom/cdrom.c (ffffffff817d65df)
Location: drivers/cdrom/cdrom.c:2740
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
In drivers/cdrom/cdrom.c (ffffffff817f087f)
Location: drivers/cdrom/cdrom.c:2740
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
