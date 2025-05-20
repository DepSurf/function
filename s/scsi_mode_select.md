# Function: <code>scsi_mode_select</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815af320)
Location: drivers/scsi/scsi_lib.c:2343
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff815af320-ffffffff815af56d: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81607580)
Location: drivers/scsi/scsi_lib.c:2216
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81607580-ffffffff816077d4: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81636c50)
Location: drivers/scsi/scsi_lib.c:2257
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81636c50-ffffffff81636eac: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164a290)
Location: drivers/scsi/scsi_lib.c:2339
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8164a290-ffffffff8164a4d9: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b3510)
Location: drivers/scsi/scsi_lib.c:2417
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff816b3510-ffffffff816b3759: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ef600)
Location: drivers/scsi/scsi_lib.c:2433
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff816ef600-ffffffff816ef834: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81712d70)
Location: drivers/scsi/scsi_lib.c:2024
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81712d70-ffffffff81712fa4: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174f800)
Location: drivers/scsi/scsi_lib.c:1977
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8174f800-ffffffff8174fa42: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817739f0)
Location: drivers/scsi/scsi_lib.c:2024
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff817739f0-ffffffff81773c32: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81834d30)
Location: drivers/scsi/scsi_lib.c:2003
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81834d30-ffffffff81834f72: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81845670)
Location: drivers/scsi/scsi_lib.c:2012
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81845670-ffffffff818458b2: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81828910)
Location: drivers/scsi/scsi_lib.c:2027
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81828910-ffffffff81828b60: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b4210)
Location: drivers/scsi/scsi_lib.c:2017
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff818b4210-ffffffff818b4460: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a00a80)
Location: drivers/scsi/scsi_lib.c:2078
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81a00a80-ffffffff81a00cc9: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7f440)
Location: drivers/scsi/scsi_lib.c:2083
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81b7f440-ffffffff81b7f689: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd3420)
Location: drivers/scsi/scsi_lib.c:2089
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_cdl_enable
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81bd3420-ffffffff81bd365d: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c280a0)
Location: drivers/scsi/scsi_lib.c:2086
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_cdl_enable
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81c280a0-ffffffff81c282dd: scsi_mode_select (STB_GLOBAL)
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
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010976b50)
Location: drivers/scsi/scsi_lib.c:2024
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffff800010976b50-ffff800010976d30: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4b898)
Location: drivers/scsi/scsi_lib.c:2024
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
c0a4b898-c0a4ba80: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a31bc0)
Location: drivers/scsi/scsi_lib.c:2024
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
c000000000a31bc0-c000000000a31e3c: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005df2b8)
Location: drivers/scsi/scsi_lib.c:2024
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffe0005df2b8-ffffffe0005df442: scsi_mode_select (STB_GLOBAL)
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
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817280e0)
Location: drivers/scsi/scsi_lib.c:2024
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff817280e0-ffffffff81728322: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81701510)
Location: drivers/scsi/scsi_lib.c:2024
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81701510-ffffffff81701752: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81766eb0)
Location: drivers/scsi/scsi_lib.c:2024
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81766eb0-ffffffff817670f2: scsi_mode_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_mode_select(struct scsi_device *sdev, int pf, int sp, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817825d0)
Location: drivers/scsi/scsi_lib.c:2024
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff817825d0-ffffffff81782812: scsi_mode_select (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int modepage</code>
</li>
<li>
<b>Param reordered. </b>
<code>sdev, pf, sp, modepage, buffer, len, timeout, retries, data, sshdr</code> ➡️ <code>sdev, pf, sp, buffer, len, timeout, retries, data, sshdr</code>
</li>
</ul>
</details>
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
