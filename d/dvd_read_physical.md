# Function: <code>dvd_read_physical</code>

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
In drivers/cdrom/cdrom.c (ffffffff815fec88)
Location: drivers/cdrom/cdrom.c:1789
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff8165ebc7)
Location: drivers/cdrom/cdrom.c:1789
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff8168c9b7)
Location: drivers/cdrom/cdrom.c:1789
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff816a212c)
Location: drivers/cdrom/cdrom.c:1787
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff8170d408)
Location: drivers/cdrom/cdrom.c:1787
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff8174c53e)
Location: drivers/cdrom/cdrom.c:1784
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff817709af)
Location: drivers/cdrom/cdrom.c:1784
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff817ae7cf)
Location: drivers/cdrom/cdrom.c:1785
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff817deaaf)
Location: drivers/cdrom/cdrom.c:1792
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dvd_read_physical(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818ac540)
Location: drivers/cdrom/cdrom.c:1795
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff818ac540-ffffffff818ac723: dvd_read_physical (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dvd_read_physical(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818bb180)
Location: drivers/cdrom/cdrom.c:1778
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff818bb180-ffffffff818bb363: dvd_read_physical (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dvd_read_physical(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8189e1f0)
Location: drivers/cdrom/cdrom.c:1778
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff8189e1f0-ffffffff8189e3d7: dvd_read_physical (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dvd_read_physical(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff819314e0)
Location: drivers/cdrom/cdrom.c:1778
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff819314e0-ffffffff819316c7: dvd_read_physical (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dvd_read_physical(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81a88a10)
Location: drivers/cdrom/cdrom.c:1780
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff81a88a10-ffffffff81a88c2b: dvd_read_physical (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dvd_read_physical(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c09860)
Location: drivers/cdrom/cdrom.c:1780
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff81c09860-ffffffff81c09a7b: dvd_read_physical (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dvd_read_physical(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c70780)
Location: drivers/cdrom/cdrom.c:1763
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff81c70780-ffffffff81c709b5: dvd_read_physical (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dvd_read_physical(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81d25030)
Location: drivers/cdrom/cdrom.c:1763
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff81d25030-ffffffff81d25265: dvd_read_physical (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffff800010a0e48c)
Location: drivers/cdrom/cdrom.c:1792
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (c0ae5628)
Location: drivers/cdrom/cdrom.c:1792
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (c000000000ac22a4)
Location: drivers/cdrom/cdrom.c:1792
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffe000632a06)
Location: drivers/cdrom/cdrom.c:1792
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff81796e8f)
Location: drivers/cdrom/cdrom.c:1792
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff81788b5f)
Location: drivers/cdrom/cdrom.c:1792
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff817d392f)
Location: drivers/cdrom/cdrom.c:1792
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff817edbcf)
Location: drivers/cdrom/cdrom.c:1792
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
