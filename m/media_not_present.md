# Function: <code>media_not_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff815bc310)
Location: drivers/scsi/sd.c:1370
Inline: True
Direct callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff815bc310-ffffffff815bc381: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81614b80)
Location: drivers/scsi/sd.c:1377
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffff81614b80-ffffffff81614bf1: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81644510)
Location: drivers/scsi/sd.c:1396
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffff81644510-ffffffff81644581: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81658270)
Location: drivers/scsi/sd.c:1503
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffff81658270-ffffffff816582d8: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816c1730)
Location: drivers/scsi/sd.c:1541
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffff816c1730-ffffffff816c1798: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816fdd80)
Location: drivers/scsi/sd.c:1510
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffff816fdd80-ffffffff816fdde8: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81720950)
Location: drivers/scsi/sd.c:1505
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffff81720950-ffffffff817209b8: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175c000)
Location: drivers/scsi/sd.c:1524
Inline: True
Direct callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffff8175c000-ffffffff8175c074: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8177fea0)
Location: drivers/scsi/sd.c:1524
Inline: True
Direct callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffff8177fea0-ffffffff8177ff14: media_not_present (STB_LOCAL)
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
In drivers/scsi/sd.c (ffffffff81847041)
Location: drivers/scsi/sd.c:1549
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81856a4f)
Location: drivers/scsi/sd.c:1593
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
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
In drivers/scsi/sd.c (ffffffff818397df)
Location: drivers/scsi/sd.c:1607
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
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
In drivers/scsi/sd.c (ffffffff818c5e5f)
Location: drivers/scsi/sd.c:1591
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
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
In drivers/scsi/sd.c (ffffffff81a128ec)
Location: drivers/scsi/sd.c:1478
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
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
In drivers/scsi/sd.c (ffffffff81b92c6c)
Location: drivers/scsi/sd.c:1483
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
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
In drivers/scsi/sd.c (ffffffff81be9168)
Location: drivers/scsi/sd.c:1510
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
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
In drivers/scsi/sd.c (ffffffff81c3e6c8)
Location: drivers/scsi/sd.c:1550
Inline: True
Inline callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff8000109864c8)
Location: drivers/scsi/sd.c:1524
Inline: True
Direct callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffff8000109864c8-ffff80001098655c: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a59868)
Location: drivers/scsi/sd.c:1524
Inline: True
Direct callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
c0a59868-c0a59900: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a47080)
Location: drivers/scsi/sd.c:1524
Inline: True
Direct callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
c000000000a47080-c000000000a47118: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005eba2c)
Location: drivers/scsi/sd.c:1524
Inline: True
Direct callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffe0005eba2c-ffffffe0005ebaae: media_not_present (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81734590)
Location: drivers/scsi/sd.c:1524
Inline: True
Direct callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffff81734590-ffffffff81734604: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81716230)
Location: drivers/scsi/sd.c:1524
Inline: True
Direct callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffff81716230-ffffffff817162a4: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81774d20)
Location: drivers/scsi/sd.c:1524
Inline: True
Direct callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffff81774d20-ffffffff81774d94: media_not_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int media_not_present(struct scsi_disk *sdkp, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8178eb00)
Location: drivers/scsi/sd.c:1524
Inline: True
Direct callers:
  - drivers/scsi/sd.c:read_capacity_10
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_check_events
```
**Symbols:**

```
ffffffff8178eb00-ffffffff8178eb74: media_not_present (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
