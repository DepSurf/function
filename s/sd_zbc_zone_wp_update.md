# Function: <code>sd_zbc_zone_wp_update</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd *cmd, unsigned int good_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81848af0)
Location: drivers/scsi/sd_zbc.c:439
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
**Symbols:**

```
ffffffff81848af0-ffffffff81848cbb: sd_zbc_zone_wp_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd *cmd, unsigned int good_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81858fc0)
Location: drivers/scsi/sd_zbc.c:440
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
**Symbols:**

```
ffffffff81858fc0-ffffffff818591a1: sd_zbc_zone_wp_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd *cmd, unsigned int good_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8183bca0)
Location: drivers/scsi/sd_zbc.c:442
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
**Symbols:**

```
ffffffff8183bca0-ffffffff8183be8e: sd_zbc_zone_wp_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd *cmd, unsigned int good_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:441
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
**Symbols:**

```
ffffffff818c85e0-ffffffff818c87fe: sd_zbc_zone_wp_update (STB_LOCAL)
ffffffff81d0d0ad-ffffffff81d0d12c: sd_zbc_zone_wp_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd *cmd, unsigned int good_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:525
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
**Symbols:**

```
ffffffff81a15640-ffffffff81a15855: sd_zbc_zone_wp_update (STB_LOCAL)
ffffffff81ed5ea0-ffffffff81ed5f07: sd_zbc_zone_wp_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd *cmd, unsigned int good_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:529
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
**Symbols:**

```
ffffffff81b96070-ffffffff81b962f8: sd_zbc_zone_wp_update (STB_LOCAL)
ffffffff8209bfea-ffffffff8209c051: sd_zbc_zone_wp_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd *cmd, unsigned int good_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:531
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
**Symbols:**

```
ffffffff81bec870-ffffffff81becaf2: sd_zbc_zone_wp_update (STB_LOCAL)
ffffffff8211cf6a-ffffffff8211cfc8: sd_zbc_zone_wp_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd *cmd, unsigned int good_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:531
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
```
**Symbols:**

```
ffffffff81c41f30-ffffffff81c421ca: sd_zbc_zone_wp_update (STB_LOCAL)
ffffffff821fae82-ffffffff821faf0d: sd_zbc_zone_wp_update.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
