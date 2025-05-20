# Function: <code>sd_zbc_print_zones</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81648fe0)
Location: drivers/scsi/sd_zbc.c:633
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81648fe0-ffffffff816490c4: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8165d930)
Location: drivers/scsi/sd_zbc.c:619
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff8165d930-ffffffff8165d9f2: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff816c6f10)
Location: drivers/scsi/sd_zbc.c:669
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff816c6f10-ffffffff816c6fd2: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff817037a0)
Location: drivers/scsi/sd_zbc.c:738
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff817037a0-ffffffff81703861: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81725d10)
Location: drivers/scsi/sd_zbc.c:495
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81725d10-ffffffff81725dd1: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81761450)
Location: drivers/scsi/sd_zbc.c:525
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81761450-ffffffff81761511: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81785440)
Location: drivers/scsi/sd_zbc.c:524
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81785440-ffffffff81785501: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81849590)
Location: drivers/scsi/sd_zbc.c:636
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_print_capacity
  - drivers/scsi/sd.c:sd_print_capacity
```
**Symbols:**

```
ffffffff81849590-ffffffff81849651: sd_zbc_print_zones (STB_GLOBAL)
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
In drivers/scsi/sd_zbc.c (ffffffff81859acb)
Location: drivers/scsi/sd_zbc.c:637
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
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
In drivers/scsi/sd_zbc.c (ffffffff8183c80b)
Location: drivers/scsi/sd_zbc.c:640
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
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
In drivers/scsi/sd_zbc.c (ffffffff818c91a1)
Location: drivers/scsi/sd_zbc.c:639
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
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
In drivers/scsi/sd_zbc.c (ffffffff81a16716)
Location: drivers/scsi/sd_zbc.c:758
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
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
In drivers/scsi/sd_zbc.c (ffffffff81b97526)
Location: drivers/scsi/sd_zbc.c:764
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
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
In drivers/scsi/sd_zbc.c (ffffffff81bedaee)
Location: drivers/scsi/sd_zbc.c:766
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
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
In drivers/scsi/sd_zbc.c (ffffffff81c4321c)
Location: drivers/scsi/sd_zbc.c:766
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
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
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffff80001098bcc0)
Location: drivers/scsi/sd_zbc.c:524
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffff80001098bcc0-ffff80001098bdb4: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (c0a5e060)
Location: drivers/scsi/sd_zbc.c:524
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
c0a5e060-c0a5e12c: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (c000000000a4ca90)
Location: drivers/scsi/sd_zbc.c:524
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
c000000000a4ca90-c000000000a4cbc0: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffe0005f03a2)
Location: drivers/scsi/sd_zbc.c:524
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffe0005f03a2-ffffffe0005f044c: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81739b30)
Location: drivers/scsi/sd_zbc.c:524
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81739b30-ffffffff81739bf1: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8171b7d0)
Location: drivers/scsi/sd_zbc.c:524
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff8171b7d0-ffffffff8171b891: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8177a2c0)
Location: drivers/scsi/sd_zbc.c:524
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff8177a2c0-ffffffff8177a381: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sd_zbc_print_zones(struct scsi_disk *sdkp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff817940f0)
Location: drivers/scsi/sd_zbc.c:524
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff817940f0-ffffffff817941b1: sd_zbc_print_zones (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
