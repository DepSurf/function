# Function: <code>sd_zbc_parse_report</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81648286)
Location: drivers/scsi/sd_zbc.c:61
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
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
In drivers/scsi/sd_zbc.c (ffffffff8165cce8)
Location: drivers/scsi/sd_zbc.c:61
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
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
In drivers/scsi/sd_zbc.c (ffffffff816c6348)
Location: drivers/scsi/sd_zbc.c:42
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
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
In drivers/scsi/sd_zbc.c (ffffffff81702a80)
Location: drivers/scsi/sd_zbc.c:42
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
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
In drivers/scsi/sd_zbc.c (ffffffff8172556d)
Location: drivers/scsi/sd_zbc.c:42
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd_zbc.c (ffffffff81760bd2)
Location: drivers/scsi/sd_zbc.c:30
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd_zbc.c (ffffffff81784b72)
Location: drivers/scsi/sd_zbc.c:30
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sd_zbc_parse_report(struct scsi_disk *sdkp, u8 *buf, unsigned int idx, report_zones_cb cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81848420)
Location: drivers/scsi/sd_zbc.c:47
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81848420-ffffffff8184857a: sd_zbc_parse_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sd_zbc_parse_report(struct scsi_disk *sdkp, u8 *buf, unsigned int idx, report_zones_cb cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81858930)
Location: drivers/scsi/sd_zbc.c:47
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81858930-ffffffff81858a68: sd_zbc_parse_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sd_zbc_parse_report(struct scsi_disk *sdkp, u8 *buf, unsigned int idx, report_zones_cb cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8183b8b0)
Location: drivers/scsi/sd_zbc.c:47
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff8183b8b0-ffffffff8183b9ed: sd_zbc_parse_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sd_zbc_parse_report(struct scsi_disk *sdkp, u8 *buf, unsigned int idx, report_zones_cb cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:47
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff818c8370-ffffffff818c84e2: sd_zbc_parse_report (STB_LOCAL)
ffffffff81d0cffe-ffffffff81d0d0ad: sd_zbc_parse_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sd_zbc_parse_report(struct scsi_disk *sdkp, const u8 *buf, unsigned int idx, report_zones_cb cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:73
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81a15860-ffffffff81a15b35: sd_zbc_parse_report (STB_LOCAL)
ffffffff81ed5f07-ffffffff81ed60b3: sd_zbc_parse_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sd_zbc_parse_report(struct scsi_disk *sdkp, const u8 *buf, unsigned int idx, report_zones_cb cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:76
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81b96580-ffffffff81b96855: sd_zbc_parse_report (STB_LOCAL)
ffffffff8209c07c-ffffffff8209c228: sd_zbc_parse_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sd_zbc_parse_report(struct scsi_disk *sdkp, const u8 *buf, unsigned int idx, report_zones_cb cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:76
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81becb10-ffffffff81becdf2: sd_zbc_parse_report (STB_LOCAL)
ffffffff8211cfc8-ffffffff8211d174: sd_zbc_parse_report.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sd_zbc_parse_report(struct scsi_disk *sdkp, const u8 *buf, unsigned int idx, report_zones_cb cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:76
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81c421e0-ffffffff81c424c2: sd_zbc_parse_report (STB_LOCAL)
ffffffff821faf0d-ffffffff821fb0b9: sd_zbc_parse_report.cold (STB_LOCAL)
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
In drivers/scsi/sd_zbc.c (ffff80001098b74c)
Location: drivers/scsi/sd_zbc.c:30
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd_zbc.c (c0a5da50)
Location: drivers/scsi/sd_zbc.c:30
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd_zbc.c (c000000000a4c3b0)
Location: drivers/scsi/sd_zbc.c:30
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd_zbc.c (ffffffe0005efb7a)
Location: drivers/scsi/sd_zbc.c:30
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd_zbc.c (ffffffff81739262)
Location: drivers/scsi/sd_zbc.c:30
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd_zbc.c (ffffffff8171af02)
Location: drivers/scsi/sd_zbc.c:30
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd_zbc.c (ffffffff817799f2)
Location: drivers/scsi/sd_zbc.c:30
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
In drivers/scsi/sd_zbc.c (ffffffff81793822)
Location: drivers/scsi/sd_zbc.c:30
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 *buf</code> ➡️ <code>const u8 *buf</code>
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
