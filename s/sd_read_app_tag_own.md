# Function: <code>sd_read_app_tag_own</code>

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
In drivers/scsi/sd.c (ffffffff815be1e0)
Location: drivers/scsi/sd.c:2605
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
In drivers/scsi/sd.c (ffffffff81617136)
Location: drivers/scsi/sd.c:2608
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
In drivers/scsi/sd.c (ffffffff81646c2a)
Location: drivers/scsi/sd.c:2671
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
In drivers/scsi/sd.c (ffffffff8165b78a)
Location: drivers/scsi/sd.c:2821
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
In drivers/scsi/sd.c (ffffffff816c4e04)
Location: drivers/scsi/sd.c:2859
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
In drivers/scsi/sd.c (ffffffff81701296)
Location: drivers/scsi/sd.c:2833
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
In drivers/scsi/sd.c (ffffffff81724132)
Location: drivers/scsi/sd.c:2820
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
In drivers/scsi/sd.c (ffffffff8175f2e5)
Location: drivers/scsi/sd.c:2806
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
In drivers/scsi/sd.c (ffffffff81783222)
Location: drivers/scsi/sd.c:2816
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
void sd_read_app_tag_own(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81844fa0)
Location: drivers/scsi/sd.c:2836
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81844fa0-ffffffff81845163: sd_read_app_tag_own (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sd_read_app_tag_own(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81855290)
Location: drivers/scsi/sd.c:2878
Inline: False
```
**Symbols:**

```
ffffffff81855290-ffffffff81855458: sd_read_app_tag_own (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sd_read_app_tag_own(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81838940)
Location: drivers/scsi/sd.c:2893
Inline: False
```
**Symbols:**

```
ffffffff81838940-ffffffff81838af2: sd_read_app_tag_own (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sd_read_app_tag_own(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c4240)
Location: drivers/scsi/sd.c:2863
Inline: False
```
**Symbols:**

```
ffffffff818c4240-ffffffff818c43f2: sd_read_app_tag_own (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sd_read_app_tag_own(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81a10f80)
Location: drivers/scsi/sd.c:2804
Inline: False
```
**Symbols:**

```
ffffffff81a10f80-ffffffff81a11159: sd_read_app_tag_own (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sd_read_app_tag_own(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81b91200)
Location: drivers/scsi/sd.c:2845
Inline: False
```
**Symbols:**

```
ffffffff81b91200-ffffffff81b913d9: sd_read_app_tag_own (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sd_read_app_tag_own(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81be7730)
Location: drivers/scsi/sd.c:2958
Inline: False
```
**Symbols:**

```
ffffffff81be7730-ffffffff81be7909: sd_read_app_tag_own (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sd_read_app_tag_own(struct scsi_disk *sdkp, unsigned char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81c3d3e0)
Location: drivers/scsi/sd.c:3008
Inline: False
```
**Symbols:**

```
ffffffff81c3d3e0-ffffffff81c3d5dd: sd_read_app_tag_own (STB_LOCAL)
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
In drivers/scsi/sd.c (ffff800010989d54)
Location: drivers/scsi/sd.c:2816
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
In drivers/scsi/sd.c (c0a5bf6c)
Location: drivers/scsi/sd.c:2816
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
In drivers/scsi/sd.c (c000000000a4a1bc)
Location: drivers/scsi/sd.c:2816
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
In drivers/scsi/sd.c (ffffffe0005ee0a8)
Location: drivers/scsi/sd.c:2816
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
In drivers/scsi/sd.c (ffffffff81737912)
Location: drivers/scsi/sd.c:2816
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
In drivers/scsi/sd.c (ffffffff817195b2)
Location: drivers/scsi/sd.c:2816
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
In drivers/scsi/sd.c (ffffffff817780a2)
Location: drivers/scsi/sd.c:2816
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
In drivers/scsi/sd.c (ffffffff81791ec2)
Location: drivers/scsi/sd.c:2816
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
