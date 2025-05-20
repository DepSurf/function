# Function: <code>sd_setup_write_same16_cmnd</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816579e0)
Location: drivers/scsi/sd.c:771
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff816579e0-ffffffff81657b23: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816c0ea0)
Location: drivers/scsi/sd.c:787
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff816c0ea0-ffffffff816c0fe3: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816fd510)
Location: drivers/scsi/sd.c:787
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff816fd510-ffffffff816fd64a: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81722b80)
Location: drivers/scsi/sd.c:795
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81722b80-ffffffff81722cea: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175e020)
Location: drivers/scsi/sd.c:858
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff8175e020-ffffffff8175e177: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81781ed0)
Location: drivers/scsi/sd.c:858
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81781ed0-ffffffff81782027: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81844470)
Location: drivers/scsi/sd.c:872
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
```
**Symbols:**

```
ffffffff81844470-ffffffff818445cd: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81854790)
Location: drivers/scsi/sd.c:906
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
```
**Symbols:**

```
ffffffff81854790-ffffffff81854900: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81838040)
Location: drivers/scsi/sd.c:906
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81838040-ffffffff818381a4: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:906
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff818c3f00-ffffffff818c409c: sd_setup_write_same16_cmnd (STB_LOCAL)
ffffffff81d0ccdd-ffffffff81d0cd35: sd_setup_write_same16_cmnd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:869
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81a0fc60-ffffffff81a0fdcd: sd_setup_write_same16_cmnd (STB_LOCAL)
ffffffff81ed5af6-ffffffff81ed5b4e: sd_setup_write_same16_cmnd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:869
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81b8fe70-ffffffff81b8ffdd: sd_setup_write_same16_cmnd (STB_LOCAL)
ffffffff8209bca0-ffffffff8209bcf8: sd_setup_write_same16_cmnd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:879
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81be6340-ffffffff81be6496: sd_setup_write_same16_cmnd (STB_LOCAL)
ffffffff8211cbf0-ffffffff8211cc58: sd_setup_write_same16_cmnd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:919
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81c3b9f0-ffffffff81c3bb43: sd_setup_write_same16_cmnd (STB_LOCAL)
ffffffff821fab5b-ffffffff821fabc3: sd_setup_write_same16_cmnd.cold (STB_LOCAL)
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
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff800010988d50)
Location: drivers/scsi/sd.c:858
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffff800010988d50-ffff800010988ea4: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a5ac28)
Location: drivers/scsi/sd.c:858
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
c0a5ac28-c0a5adc8: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a48a20)
Location: drivers/scsi/sd.c:858
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
c000000000a48a20-c000000000a48c30: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005eced4)
Location: drivers/scsi/sd.c:858
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffe0005eced4-ffffffe0005ed0be: sd_setup_write_same16_cmnd (STB_LOCAL)
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
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817365c0)
Location: drivers/scsi/sd.c:858
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff817365c0-ffffffff81736717: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81718260)
Location: drivers/scsi/sd.c:858
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81718260-ffffffff817183b7: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81776d50)
Location: drivers/scsi/sd.c:858
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81776d50-ffffffff81776ea7: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same16_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81790cb0)
Location: drivers/scsi/sd.c:858
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81790cb0-ffffffff81790e25: sd_setup_write_same16_cmnd (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
