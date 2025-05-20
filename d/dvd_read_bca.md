# Function: <code>dvd_read_bca</code>

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
In drivers/cdrom/cdrom.c (ffffffff815fea8b)
Location: drivers/cdrom/cdrom.c:1892
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
In drivers/cdrom/cdrom.c (ffffffff8165e9e2)
Location: drivers/cdrom/cdrom.c:1892
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
In drivers/cdrom/cdrom.c (ffffffff8168c7d2)
Location: drivers/cdrom/cdrom.c:1892
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
In drivers/cdrom/cdrom.c (ffffffff816a1e5f)
Location: drivers/cdrom/cdrom.c:1890
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
In drivers/cdrom/cdrom.c (ffffffff8170d125)
Location: drivers/cdrom/cdrom.c:1890
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
In drivers/cdrom/cdrom.c (ffffffff8174c772)
Location: drivers/cdrom/cdrom.c:1887
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
In drivers/cdrom/cdrom.c (ffffffff81770902)
Location: drivers/cdrom/cdrom.c:1887
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
In drivers/cdrom/cdrom.c (ffffffff817ae900)
Location: drivers/cdrom/cdrom.c:1888
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
In drivers/cdrom/cdrom.c (ffffffff817debe0)
Location: drivers/cdrom/cdrom.c:1895
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
int dvd_read_bca(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818ac2b0)
Location: drivers/cdrom/cdrom.c:1898
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff818ac2b0-ffffffff818ac3c6: dvd_read_bca (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dvd_read_bca(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818baef0)
Location: drivers/cdrom/cdrom.c:1881
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff818baef0-ffffffff818bb006: dvd_read_bca (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffffffff8189ef74)
Location: drivers/cdrom/cdrom.c:1881
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
In drivers/cdrom/cdrom.c (ffffffff81933660)
Location: drivers/cdrom/cdrom.c:1881
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dvd_read_bca(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81a88590)
Location: drivers/cdrom/cdrom.c:1883
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff81a88590-ffffffff81a886a9: dvd_read_bca (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dvd_read_bca(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c0af20)
Location: drivers/cdrom/cdrom.c:1883
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff81c0af20-ffffffff81c0b03f: dvd_read_bca (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dvd_read_bca(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c72800)
Location: drivers/cdrom/cdrom.c:1866
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff81c72800-ffffffff81c7291f: dvd_read_bca (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dvd_read_bca(struct cdrom_device_info *cdi, dvd_struct *s, struct packet_command *cgc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81d27170)
Location: drivers/cdrom/cdrom.c:1866
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
```
**Symbols:**

```
ffffffff81d27170-ffffffff81d272b9: dvd_read_bca (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffff800010a0e680)
Location: drivers/cdrom/cdrom.c:1895
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
In drivers/cdrom/cdrom.c (c0ae593c)
Location: drivers/cdrom/cdrom.c:1895
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
In drivers/cdrom/cdrom.c (c000000000ac20d0)
Location: drivers/cdrom/cdrom.c:1895
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
In drivers/cdrom/cdrom.c (ffffffe0006328a6)
Location: drivers/cdrom/cdrom.c:1895
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
In drivers/cdrom/cdrom.c (ffffffff81796fc0)
Location: drivers/cdrom/cdrom.c:1895
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
In drivers/cdrom/cdrom.c (ffffffff81788c90)
Location: drivers/cdrom/cdrom.c:1895
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
In drivers/cdrom/cdrom.c (ffffffff817d3a60)
Location: drivers/cdrom/cdrom.c:1895
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
In drivers/cdrom/cdrom.c (ffffffff817edd00)
Location: drivers/cdrom/cdrom.c:1895
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
