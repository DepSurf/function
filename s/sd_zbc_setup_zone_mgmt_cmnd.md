# Function: <code>sd_zbc_setup_zone_mgmt_cmnd</code>

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
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd *cmd, unsigned char op, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff818493d0)
Location: drivers/scsi/sd_zbc.c:384
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff818493d0-ffffffff818494ab: sd_zbc_setup_zone_mgmt_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd *cmd, unsigned char op, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81859690)
Location: drivers/scsi/sd_zbc.c:385
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81859690-ffffffff8185976e: sd_zbc_setup_zone_mgmt_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd *cmd, unsigned char op, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8183c390)
Location: drivers/scsi/sd_zbc.c:387
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff8183c390-ffffffff8183c46e: sd_zbc_setup_zone_mgmt_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd *cmd, unsigned char op, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:386
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81d0d20a-ffffffff81d0d221: sd_zbc_setup_zone_mgmt_cmnd.cold (STB_LOCAL)
ffffffff818c8cb0-ffffffff818c8d8f: sd_zbc_setup_zone_mgmt_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd *cmd, unsigned char op, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:471
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81ed6144-ffffffff81ed615b: sd_zbc_setup_zone_mgmt_cmnd.cold (STB_LOCAL)
ffffffff81a16210-ffffffff81a162fc: sd_zbc_setup_zone_mgmt_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd *cmd, unsigned char op, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:475
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff8209c2b1-ffffffff8209c2c8: sd_zbc_setup_zone_mgmt_cmnd.cold (STB_LOCAL)
ffffffff81b96fe0-ffffffff81b970cc: sd_zbc_setup_zone_mgmt_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd *cmd, unsigned char op, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:477
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff8211d1f5-ffffffff8211d20c: sd_zbc_setup_zone_mgmt_cmnd.cold (STB_LOCAL)
ffffffff81bed580-ffffffff81bed66c: sd_zbc_setup_zone_mgmt_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd *cmd, unsigned char op, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:477
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff821fb1ab-ffffffff821fb1c2: sd_zbc_setup_zone_mgmt_cmnd.cold (STB_LOCAL)
ffffffff81c42c80-ffffffff81c42d69: sd_zbc_setup_zone_mgmt_cmnd (STB_GLOBAL)
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
