# Function: <code>sd_zbc_setup_reset_cmnd</code>

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
int sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81648730)
Location: drivers/scsi/sd_zbc.c:234
Inline: False
```
**Symbols:**

```
ffffffff81648730-ffffffff8164884a: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8165d070)
Location: drivers/scsi/sd_zbc.c:234
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff8165d070-ffffffff8165d168: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff816c66d0)
Location: drivers/scsi/sd_zbc.c:249
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff816c66d0-ffffffff816c67c8: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81702c90)
Location: drivers/scsi/sd_zbc.c:238
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81702c90-ffffffff81702d88: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_status_t sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81725660)
Location: drivers/scsi/sd_zbc.c:190
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81725660-ffffffff8172575f: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_status_t sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81760cc0)
Location: drivers/scsi/sd_zbc.c:215
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81760cc0-ffffffff81760dbf: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_status_t sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81784c60)
Location: drivers/scsi/sd_zbc.c:216
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81784c60-ffffffff81784d73: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
blk_status_t sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffff80001098b870)
Location: drivers/scsi/sd_zbc.c:216
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffff80001098b870-ffff80001098b988: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_status_t sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (c0a5dbc4)
Location: drivers/scsi/sd_zbc.c:216
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
c0a5dbc4-c0a5dd44: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_status_t sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (c000000000a4c580)
Location: drivers/scsi/sd_zbc.c:216
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
c000000000a4c580-c000000000a4c6b8: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_status_t sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffe0005efe56)
Location: drivers/scsi/sd_zbc.c:216
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffe0005efe56-ffffffe0005f001e: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
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
blk_status_t sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81739350)
Location: drivers/scsi/sd_zbc.c:216
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81739350-ffffffff81739463: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_status_t sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8171aff0)
Location: drivers/scsi/sd_zbc.c:216
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff8171aff0-ffffffff8171b103: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_status_t sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81779ae0)
Location: drivers/scsi/sd_zbc.c:216
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81779ae0-ffffffff81779bf3: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_status_t sd_zbc_setup_reset_cmnd(struct scsi_cmnd *cmd, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81793910)
Location: drivers/scsi/sd_zbc.c:216
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81793910-ffffffff81793a23: sd_zbc_setup_reset_cmnd (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool all</code>
</li>
</ul>
</details>
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
