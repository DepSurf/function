# Function: <code>sd_spinup_disk</code>

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
In drivers/scsi/sd.c (ffffffff815bdb0c)
Location: drivers/scsi/sd.c:1854
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
In drivers/scsi/sd.c (ffffffff81616915)
Location: drivers/scsi/sd.c:1865
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
In drivers/scsi/sd.c (ffffffff816463b3)
Location: drivers/scsi/sd.c:1919
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
In drivers/scsi/sd.c (ffffffff8165af29)
Location: drivers/scsi/sd.c:2053
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
In drivers/scsi/sd.c (ffffffff816c4579)
Location: drivers/scsi/sd.c:2091
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
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2060
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
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2047
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2066
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff8175cd00-ffffffff8175d0a8: sd_spinup_disk (STB_LOCAL)
ffffffff817606c1-ffffffff81760700: sd_spinup_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2074
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81780bd0-ffffffff81780f78: sd_spinup_disk (STB_LOCAL)
ffffffff81784652-ffffffff81784691: sd_spinup_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2094
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81846bd0-ffffffff81846f8e: sd_spinup_disk (STB_LOCAL)
ffffffff81848173-ffffffff818481a1: sd_spinup_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2138
Inline: False
```
**Symbols:**

```
ffffffff818565c0-ffffffff8185698c: sd_spinup_disk (STB_LOCAL)
ffffffff81c16cfd-ffffffff81c16d2b: sd_spinup_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2153
Inline: False
```
**Symbols:**

```
ffffffff81839350-ffffffff8183971b: sd_spinup_disk (STB_LOCAL)
ffffffff81c08b43-ffffffff81c08b71: sd_spinup_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2111
Inline: False
```
**Symbols:**

```
ffffffff818c5950-ffffffff818c5da0: sd_spinup_disk (STB_LOCAL)
ffffffff81d0cf1b-ffffffff81d0cf49: sd_spinup_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2043
Inline: False
```
**Symbols:**

```
ffffffff81a123a0-ffffffff81a12808: sd_spinup_disk (STB_LOCAL)
ffffffff81ed5d41-ffffffff81ed5d6e: sd_spinup_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81b926b0)
Location: drivers/scsi/sd.c:2084
Inline: False
```
**Symbols:**

```
ffffffff81b926b0-ffffffff81b92b77: sd_spinup_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81be8bc0)
Location: drivers/scsi/sd.c:2191
Inline: False
```
**Symbols:**

```
ffffffff81be8bc0-ffffffff81be9061: sd_spinup_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81c3e120)
Location: drivers/scsi/sd.c:2236
Inline: False
```
**Symbols:**

```
ffffffff81c3e120-ffffffff81c3e5c3: sd_spinup_disk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff800010987328)
Location: drivers/scsi/sd.c:2074
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffff800010987328-ffff8000109876f0: sd_spinup_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a59c84)
Location: drivers/scsi/sd.c:2074
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
c0a59c84-c0a5a080: sd_spinup_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a47530)
Location: drivers/scsi/sd.c:2074
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
c000000000a47530-c000000000a47a78: sd_spinup_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005ebdaa)
Location: drivers/scsi/sd.c:2074
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffe0005ebdaa-ffffffe0005ec15c: sd_spinup_disk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2074
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff817352c0-ffffffff81735668: sd_spinup_disk (STB_LOCAL)
ffffffff81738d42-ffffffff81738d81: sd_spinup_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2074
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81716f60-ffffffff81717308: sd_spinup_disk (STB_LOCAL)
ffffffff8171a9e2-ffffffff8171aa21: sd_spinup_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2074
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81775a50-ffffffff81775df8: sd_spinup_disk (STB_LOCAL)
ffffffff817794d2-ffffffff81779511: sd_spinup_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void sd_spinup_disk(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:2074
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff8178f830-ffffffff8178fbd8: sd_spinup_disk (STB_LOCAL)
ffffffff81793310-ffffffff8179334f: sd_spinup_disk.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
