# Function: <code>dvd_read_disckey</code>

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
In drivers/cdrom/cdrom.c (ffffffff815febfe)
Location: drivers/cdrom/cdrom.c:1864
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
In drivers/cdrom/cdrom.c (ffffffff8165eb3c)
Location: drivers/cdrom/cdrom.c:1864
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
In drivers/cdrom/cdrom.c (ffffffff8168c92c)
Location: drivers/cdrom/cdrom.c:1864
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
In drivers/cdrom/cdrom.c (ffffffff816a206f)
Location: drivers/cdrom/cdrom.c:1862
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
In drivers/cdrom/cdrom.c (ffffffff8170d346)
Location: drivers/cdrom/cdrom.c:1862
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
In drivers/cdrom/cdrom.c (ffffffff8174c6b0)
Location: drivers/cdrom/cdrom.c:1859
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
In drivers/cdrom/cdrom.c (ffffffff81770818)
Location: drivers/cdrom/cdrom.c:1859
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
In drivers/cdrom/cdrom.c (ffffffff817ae6f8)
Location: drivers/cdrom/cdrom.c:1860
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
In drivers/cdrom/cdrom.c (ffffffff817de9d8)
Location: drivers/cdrom/cdrom.c:1867
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
int dvd_read_disckey(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818ac1c0)
Location: drivers/cdrom/cdrom.c:1870
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff818ac1c0-ffffffff818ac2a5: dvd_read_disckey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dvd_read_disckey(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818bae00)
Location: drivers/cdrom/cdrom.c:1853
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff818bae00-ffffffff818baee5: dvd_read_disckey (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffffffff8189ee85)
Location: drivers/cdrom/cdrom.c:1853
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff81933571)
Location: drivers/cdrom/cdrom.c:1853
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
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
In drivers/cdrom/cdrom.c (ffffffff81a8b0df)
Location: drivers/cdrom/cdrom.c:1855
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dvd_read_disckey(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c0ae10)
Location: drivers/cdrom/cdrom.c:1855
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff81c0ae10-ffffffff81c0af01: dvd_read_disckey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dvd_read_disckey(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c726f0)
Location: drivers/cdrom/cdrom.c:1838
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff81c726f0-ffffffff81c727e1: dvd_read_disckey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dvd_read_disckey(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81d27040)
Location: drivers/cdrom/cdrom.c:1838
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff81d27040-ffffffff81d2715f: dvd_read_disckey (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffff800010a0e5d0)
Location: drivers/cdrom/cdrom.c:1867
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
In drivers/cdrom/cdrom.c (c0ae58ac)
Location: drivers/cdrom/cdrom.c:1867
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
In drivers/cdrom/cdrom.c (c000000000ac21f0)
Location: drivers/cdrom/cdrom.c:1867
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
In drivers/cdrom/cdrom.c (ffffffe000632bac)
Location: drivers/cdrom/cdrom.c:1867
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
In drivers/cdrom/cdrom.c (ffffffff81796db8)
Location: drivers/cdrom/cdrom.c:1867
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
In drivers/cdrom/cdrom.c (ffffffff81788a88)
Location: drivers/cdrom/cdrom.c:1867
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
In drivers/cdrom/cdrom.c (ffffffff817d3858)
Location: drivers/cdrom/cdrom.c:1867
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
In drivers/cdrom/cdrom.c (ffffffff817edaf8)
Location: drivers/cdrom/cdrom.c:1867
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
