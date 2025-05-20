# Function: <code>register_cdrom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff815ff8d0)
Location: drivers/cdrom/cdrom.c:586
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff815ff8d0-ffffffff815ffb8c: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8165f730)
Location: drivers/cdrom/cdrom.c:586
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8165f730-ffffffff8165f9dd: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8168d520)
Location: drivers/cdrom/cdrom.c:586
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8168d520-ffffffff8168d7cd: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff816a2950)
Location: drivers/cdrom/cdrom.c:587
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff816a2950-ffffffff816a2bbe: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8170dc40)
Location: drivers/cdrom/cdrom.c:587
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8170dc40-ffffffff8170deae: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:587
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8174fc00-ffffffff8174fc2a: register_cdrom.cold.27 (STB_LOCAL)
ffffffff8174ce90-ffffffff8174d0ce: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:588
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81774024-ffffffff8177404e: register_cdrom.cold.26 (STB_LOCAL)
ffffffff81771080-ffffffff817712fa: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff817b1f1e-ffffffff817b1f4e: register_cdrom.cold (STB_LOCAL)
ffffffff817aef30-ffffffff817af1a3: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff817e226e-ffffffff817e228b: register_cdrom.cold (STB_LOCAL)
ffffffff817df230-ffffffff817df4aa: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct gendisk *disk, struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff818b0df4-ffffffff818b0e11: register_cdrom.cold (STB_LOCAL)
ffffffff818ad8b0-ffffffff818adb46: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct gendisk *disk, struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81c1a5ea-ffffffff81c1a607: register_cdrom.cold (STB_LOCAL)
ffffffff818bc4f0-ffffffff818bc77a: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct gendisk *disk, struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81c0c4d6-ffffffff81c0c4f3: register_cdrom.cold (STB_LOCAL)
ffffffff8189f150-ffffffff8189f3da: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct gendisk *disk, struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81d12fb4-ffffffff81d1304f: register_cdrom.cold (STB_LOCAL)
ffffffff819338c0-ffffffff81933bbb: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct gendisk *disk, struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:585
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81edddfe-ffffffff81edde99: register_cdrom.cold (STB_LOCAL)
ffffffff81a8b2c0-ffffffff81a8b5ef: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct gendisk *disk, struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:585
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8209e2ad-ffffffff8209e32b: register_cdrom.cold (STB_LOCAL)
ffffffff81c0c430-ffffffff81c0c77b: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct gendisk *disk, struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:586
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8211f8e7-ffffffff8211f965: register_cdrom.cold (STB_LOCAL)
ffffffff81c73cf0-ffffffff81c7403b: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct gendisk *disk, struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:586
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff822010bd-ffffffff8220113b: register_cdrom.cold (STB_LOCAL)
ffffffff81d286c0-ffffffff81d28a0b: register_cdrom (STB_GLOBAL)
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
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffff800010a0d0a0)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffff800010a0d0a0-ffff800010a0d348: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c0ae4dd4)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
c0ae4dd4-c0ae5284: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c000000000ac2e30)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
c000000000ac2e30-c000000000ac31ec: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffe0006330ac)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffe0006330ac-ffffffe000633322: register_cdrom (STB_GLOBAL)
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
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8179a64e-ffffffff8179a66b: register_cdrom.cold (STB_LOCAL)
ffffffff81797610-ffffffff8179788a: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8178c31e-ffffffff8178c33b: register_cdrom.cold (STB_LOCAL)
ffffffff817892e0-ffffffff8178955a: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff817d70ee-ffffffff817d710b: register_cdrom.cold (STB_LOCAL)
ffffffff817d40b0-ffffffff817d432a: register_cdrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int register_cdrom(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:589
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff817f138e-ffffffff817f13ab: register_cdrom.cold (STB_LOCAL)
ffffffff817ee350-ffffffff817ee5ca: register_cdrom (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param reordered. </b>
<code>cdi</code> ➡️ <code>disk, cdi</code>
</li>
</ul>
</details>
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
