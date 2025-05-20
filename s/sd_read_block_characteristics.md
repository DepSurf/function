# Function: <code>sd_read_block_characteristics</code>

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
In drivers/scsi/sd.c (ffffffff815be102)
Location: drivers/scsi/sd.c:2717
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffff81617058)
Location: drivers/scsi/sd.c:2720
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffff81646a39)
Location: drivers/scsi/sd.c:2783
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffff8165b590)
Location: drivers/scsi/sd.c:2933
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffff816c4c0a)
Location: drivers/scsi/sd.c:2969
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffff8170173b)
Location: drivers/scsi/sd.c:2943
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
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
In drivers/scsi/sd.c (ffffffff81724683)
Location: drivers/scsi/sd.c:2930
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
In drivers/scsi/sd.c (ffffffff8175f5a5)
Location: drivers/scsi/sd.c:2916
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
In drivers/scsi/sd.c (ffffffff817834e2)
Location: drivers/scsi/sd.c:2926
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
void sd_read_block_characteristics(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81843190)
Location: drivers/scsi/sd.c:2946
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81843190-ffffffff818433c4: sd_read_block_characteristics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sd_read_block_characteristics(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81852c40)
Location: drivers/scsi/sd.c:2988
Inline: False
```
**Symbols:**

```
ffffffff81852c40-ffffffff81852e71: sd_read_block_characteristics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sd_read_block_characteristics(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818365b0)
Location: drivers/scsi/sd.c:3003
Inline: False
```
**Symbols:**

```
ffffffff818365b0-ffffffff818367df: sd_read_block_characteristics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sd_read_block_characteristics(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c1f80)
Location: drivers/scsi/sd.c:2973
Inline: False
```
**Symbols:**

```
ffffffff818c1f80-ffffffff818c21af: sd_read_block_characteristics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sd_read_block_characteristics(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81a0ea00)
Location: drivers/scsi/sd.c:2911
Inline: False
```
**Symbols:**

```
ffffffff81a0ea00-ffffffff81a0ec2e: sd_read_block_characteristics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sd_read_block_characteristics(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81b8ea80)
Location: drivers/scsi/sd.c:2952
Inline: False
```
**Symbols:**

```
ffffffff81b8ea80-ffffffff81b8ecae: sd_read_block_characteristics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sd_read_block_characteristics(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81be4b20)
Location: drivers/scsi/sd.c:3065
Inline: False
```
**Symbols:**

```
ffffffff81be4b20-ffffffff81be4d5c: sd_read_block_characteristics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sd_read_block_characteristics(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:3115
Inline: False
```
**Symbols:**

```
ffffffff81c3a3b0-ffffffff81c3a5c3: sd_read_block_characteristics (STB_LOCAL)
ffffffff821faa56-ffffffff821faa80: sd_read_block_characteristics.cold (STB_LOCAL)
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
In drivers/scsi/sd.c (ffff800010989f20)
Location: drivers/scsi/sd.c:2926
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
In drivers/scsi/sd.c (c0a5c1d0)
Location: drivers/scsi/sd.c:2926
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
In drivers/scsi/sd.c (c000000000a4a3f4)
Location: drivers/scsi/sd.c:2926
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
In drivers/scsi/sd.c (ffffffe0005ee24c)
Location: drivers/scsi/sd.c:2926
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
In drivers/scsi/sd.c (ffffffff81737bd2)
Location: drivers/scsi/sd.c:2926
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
In drivers/scsi/sd.c (ffffffff81719872)
Location: drivers/scsi/sd.c:2926
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
In drivers/scsi/sd.c (ffffffff81778362)
Location: drivers/scsi/sd.c:2926
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
In drivers/scsi/sd.c (ffffffff81792182)
Location: drivers/scsi/sd.c:2926
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
