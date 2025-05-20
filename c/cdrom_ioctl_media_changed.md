# Function: <code>cdrom_ioctl_media_changed</code>

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
In drivers/cdrom/cdrom.c (ffffffff81602178)
Location: drivers/cdrom/cdrom.c:2346
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
In drivers/cdrom/cdrom.c (ffffffff81662001)
Location: drivers/cdrom/cdrom.c:2356
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
In drivers/cdrom/cdrom.c (ffffffff8168fdf1)
Location: drivers/cdrom/cdrom.c:2356
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
In drivers/cdrom/cdrom.c (ffffffff816a5000)
Location: drivers/cdrom/cdrom.c:2362
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
In drivers/cdrom/cdrom.c (ffffffff81710380)
Location: drivers/cdrom/cdrom.c:2362
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
In drivers/cdrom/cdrom.c (ffffffff8174efa1)
Location: drivers/cdrom/cdrom.c:2359
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
In drivers/cdrom/cdrom.c (ffffffff817732ed)
Location: drivers/cdrom/cdrom.c:2362
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
In drivers/cdrom/cdrom.c (ffffffff817b0e67)
Location: drivers/cdrom/cdrom.c:2363
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
In drivers/cdrom/cdrom.c (ffffffff817e11b7)
Location: drivers/cdrom/cdrom.c:2370
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff818b0527)
Location: drivers/cdrom/cdrom.c:2382
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cdrom_ioctl_media_changed(struct cdrom_device_info *cdi, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818bcde0)
Location: drivers/cdrom/cdrom.c:2365
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff818bcde0-ffffffff818bcf41: cdrom_ioctl_media_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cdrom_ioctl_media_changed(struct cdrom_device_info *cdi, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8189fa60)
Location: drivers/cdrom/cdrom.c:2365
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff8189fa60-ffffffff8189fbbf: cdrom_ioctl_media_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cdrom_ioctl_media_changed(struct cdrom_device_info *cdi, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:2310
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff819341c0-ffffffff8193432e: cdrom_ioctl_media_changed (STB_LOCAL)
ffffffff81d13060-ffffffff81d13075: cdrom_ioctl_media_changed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cdrom_ioctl_media_changed(struct cdrom_device_info *cdi, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:2314
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81a8be70-ffffffff81a8bffc: cdrom_ioctl_media_changed (STB_LOCAL)
ffffffff81eddeaa-ffffffff81eddebf: cdrom_ioctl_media_changed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cdrom_ioctl_media_changed(struct cdrom_device_info *cdi, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:2314
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81c0cdf0-ffffffff81c0cf7c: cdrom_ioctl_media_changed (STB_LOCAL)
ffffffff8209e32b-ffffffff8209e340: cdrom_ioctl_media_changed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cdrom_ioctl_media_changed(struct cdrom_device_info *cdi, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:2297
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81c74910-ffffffff81c74abe: cdrom_ioctl_media_changed (STB_LOCAL)
ffffffff8211f965-ffffffff8211f97a: cdrom_ioctl_media_changed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cdrom_ioctl_media_changed(struct cdrom_device_info *cdi, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:2297
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81d292e0-ffffffff81d294bd: cdrom_ioctl_media_changed (STB_LOCAL)
ffffffff8220113b-ffffffff82201150: cdrom_ioctl_media_changed.cold (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffff800010a0ef64)
Location: drivers/cdrom/cdrom.c:2370
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
In drivers/cdrom/cdrom.c (c0ae70fc)
Location: drivers/cdrom/cdrom.c:2370
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
In drivers/cdrom/cdrom.c (c000000000ac58f0)
Location: drivers/cdrom/cdrom.c:2370
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
In drivers/cdrom/cdrom.c (ffffffe000635276)
Location: drivers/cdrom/cdrom.c:2370
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
In drivers/cdrom/cdrom.c (ffffffff81799597)
Location: drivers/cdrom/cdrom.c:2370
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
In drivers/cdrom/cdrom.c (ffffffff8178b267)
Location: drivers/cdrom/cdrom.c:2370
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
In drivers/cdrom/cdrom.c (ffffffff817d6037)
Location: drivers/cdrom/cdrom.c:2370
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
In drivers/cdrom/cdrom.c (ffffffff817f02d7)
Location: drivers/cdrom/cdrom.c:2370
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
