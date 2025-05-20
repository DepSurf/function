# Function: <code>cdrom_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff815fddc0)
Location: drivers/cdrom/cdrom.c:1255
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff815fddc0-ffffffff815fe078: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8165dd50)
Location: drivers/cdrom/cdrom.c:1255
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff8165dd50-ffffffff8165dfde: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8168bb40)
Location: drivers/cdrom/cdrom.c:1255
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff8168bb40-ffffffff8168bdce: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff816a0b00)
Location: drivers/cdrom/cdrom.c:1253
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff816a0b00-ffffffff816a0d7e: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8170bcf0)
Location: drivers/cdrom/cdrom.c:1253
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff8170bcf0-ffffffff8170bf90: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1250
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff8174fada-ffffffff8174fb97: cdrom_release.cold.26 (STB_LOCAL)
ffffffff8174b120-ffffffff8174b30e: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1250
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff81773efe-ffffffff81773fbb: cdrom_release.cold.25 (STB_LOCAL)
ffffffff8176f340-ffffffff8176f52e: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1251
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff817b1de2-ffffffff817b1ea6: cdrom_release.cold (STB_LOCAL)
ffffffff817ad1b0-ffffffff817ad3b9: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1258
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff817e2132-ffffffff817e21f6: cdrom_release.cold (STB_LOCAL)
ffffffff817dd490-ffffffff817dd699: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818abfc0)
Location: drivers/cdrom/cdrom.c:1261
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff818abfc0-ffffffff818ac0fe: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818bac00)
Location: drivers/cdrom/cdrom.c:1261
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff818bac00-ffffffff818bad3e: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8189dfd0)
Location: drivers/cdrom/cdrom.c:1261
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff8189dfd0-ffffffff8189e10e: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1261
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff81d12cef-ffffffff81d12d2e: cdrom_release.cold (STB_LOCAL)
ffffffff81932750-ffffffff819328be: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1262
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff81eddb65-ffffffff81eddba4: cdrom_release.cold (STB_LOCAL)
ffffffff81a89db0-ffffffff81a89f1f: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1262
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff8209e613-ffffffff8209e652: cdrom_release.cold (STB_LOCAL)
ffffffff81c10330-ffffffff81c1049f: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1254
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff8211f6b6-ffffffff8211f70a: cdrom_release.cold (STB_LOCAL)
ffffffff81c71fc0-ffffffff81c7211f: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1254
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff82200e8c-ffffffff82200ee0: cdrom_release.cold (STB_LOCAL)
ffffffff81d26870-ffffffff81d269cf: cdrom_release (STB_GLOBAL)
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
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffff800010a0a890)
Location: drivers/cdrom/cdrom.c:1258
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffff800010a0a890-ffff800010a0ab98: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c0ae249c)
Location: drivers/cdrom/cdrom.c:1258
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
c0ae249c-c0ae27f4: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c000000000ac0350)
Location: drivers/cdrom/cdrom.c:1258
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
c000000000ac0350-c000000000ac0760: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffe000631636)
Location: drivers/cdrom/cdrom.c:1258
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffe000631636-ffffffe0006318dc: cdrom_release (STB_GLOBAL)
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
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1258
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff8179a512-ffffffff8179a5d6: cdrom_release.cold (STB_LOCAL)
ffffffff81795870-ffffffff81795a79: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1258
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff8178c1e2-ffffffff8178c2a6: cdrom_release.cold (STB_LOCAL)
ffffffff81787540-ffffffff81787749: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1258
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff817d6fb2-ffffffff817d7076: cdrom_release.cold (STB_LOCAL)
ffffffff817d2310-ffffffff817d2519: cdrom_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void cdrom_release(struct cdrom_device_info *cdi, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1258
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_release
```
**Symbols:**

```
ffffffff817f1252-ffffffff817f1316: cdrom_release.cold (STB_LOCAL)
ffffffff817ec5b0-ffffffff817ec7b9: cdrom_release (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
</ul>
</details>
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
