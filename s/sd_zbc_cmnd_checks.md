# Function: <code>sd_zbc_cmnd_checks</code>

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
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81848d10)
Location: drivers/scsi/sd_zbc.c:244
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81848d10-ffffffff81848d9a: sd_zbc_cmnd_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81859200)
Location: drivers/scsi/sd_zbc.c:245
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81859200-ffffffff81859273: sd_zbc_cmnd_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8183bee0)
Location: drivers/scsi/sd_zbc.c:245
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff8183bee0-ffffffff8183bf53: sd_zbc_cmnd_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:244
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff818c82e0-ffffffff818c836b: sd_zbc_cmnd_checks (STB_LOCAL)
ffffffff81d0cfda-ffffffff81d0cffe: sd_zbc_cmnd_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:325
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81a15130-ffffffff81a151d8: sd_zbc_cmnd_checks (STB_LOCAL)
ffffffff81ed5e26-ffffffff81ed5e4a: sd_zbc_cmnd_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:328
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81b95da0-ffffffff81b95e48: sd_zbc_cmnd_checks (STB_LOCAL)
ffffffff8209bf9b-ffffffff8209bfbf: sd_zbc_cmnd_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:330
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81bec360-ffffffff81bec408: sd_zbc_cmnd_checks (STB_LOCAL)
ffffffff8211cefc-ffffffff8211cf20: sd_zbc_cmnd_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:330
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81c41a20-ffffffff81c41ac5: sd_zbc_cmnd_checks (STB_LOCAL)
ffffffff821fae14-ffffffff821fae38: sd_zbc_cmnd_checks.cold (STB_LOCAL)
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
