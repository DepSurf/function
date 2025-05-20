# Function: <code>sd_validate_opt_xfer_size</code>

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
In drivers/scsi/sd.c (ffffffff81723a59)
Location: drivers/scsi/sd.c:3050
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffff8175eeb1)
Location: drivers/scsi/sd.c:3036
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffff81782e11)
Location: drivers/scsi/sd.c:3046
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool sd_validate_opt_xfer_size(struct scsi_disk *sdkp, unsigned int dev_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81842590)
Location: drivers/scsi/sd.c:3076
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81842590-ffffffff818427a9: sd_validate_opt_xfer_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool sd_validate_opt_xfer_size(struct scsi_disk *sdkp, unsigned int dev_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81851ff0)
Location: drivers/scsi/sd.c:3118
Inline: False
```
**Symbols:**

```
ffffffff81851ff0-ffffffff81852209: sd_validate_opt_xfer_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool sd_validate_opt_xfer_size(struct scsi_disk *sdkp, unsigned int dev_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81835080)
Location: drivers/scsi/sd.c:3133
Inline: False
```
**Symbols:**

```
ffffffff81835080-ffffffff818352a0: sd_validate_opt_xfer_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool sd_validate_opt_xfer_size(struct scsi_disk *sdkp, unsigned int dev_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c13d0)
Location: drivers/scsi/sd.c:3103
Inline: False
```
**Symbols:**

```
ffffffff818c13d0-ffffffff818c15f0: sd_validate_opt_xfer_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool sd_validate_opt_xfer_size(struct scsi_disk *sdkp, unsigned int dev_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81a0db50)
Location: drivers/scsi/sd.c:3146
Inline: False
```
**Symbols:**

```
ffffffff81a0db50-ffffffff81a0de3a: sd_validate_opt_xfer_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool sd_validate_opt_xfer_size(struct scsi_disk *sdkp, unsigned int dev_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81b8dab0)
Location: drivers/scsi/sd.c:3187
Inline: False
```
**Symbols:**

```
ffffffff81b8dab0-ffffffff81b8dd9a: sd_validate_opt_xfer_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool sd_validate_opt_xfer_size(struct scsi_disk *sdkp, unsigned int dev_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81be3b40)
Location: drivers/scsi/sd.c:3305
Inline: False
```
**Symbols:**

```
ffffffff81be3b40-ffffffff81be3e2a: sd_validate_opt_xfer_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool sd_validate_opt_xfer_size(struct scsi_disk *sdkp, unsigned int dev_max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81c38df0)
Location: drivers/scsi/sd.c:3352
Inline: False
```
**Symbols:**

```
ffffffff81c38df0-ffffffff81c390da: sd_validate_opt_xfer_size (STB_LOCAL)
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
In drivers/scsi/sd.c (ffff800010989a0c)
Location: drivers/scsi/sd.c:3046
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (c0a5bb74)
Location: drivers/scsi/sd.c:3046
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (c000000000a49d0c)
Location: drivers/scsi/sd.c:3046
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffe0005edc64)
Location: drivers/scsi/sd.c:3046
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffff81737501)
Location: drivers/scsi/sd.c:3046
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffff817191a1)
Location: drivers/scsi/sd.c:3046
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffff81777c91)
Location: drivers/scsi/sd.c:3046
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffff81791ab1)
Location: drivers/scsi/sd.c:3046
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
