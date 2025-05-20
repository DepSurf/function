# Function: <code>sd_setup_write_same10_cmnd</code>

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
int sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81657b30)
Location: drivers/scsi/sd.c:801
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81657b30-ffffffff81657c77: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816c0ff0)
Location: drivers/scsi/sd.c:817
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff816c0ff0-ffffffff816c1137: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816fd650)
Location: drivers/scsi/sd.c:817
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff816fd650-ffffffff816fd78e: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81722cf0)
Location: drivers/scsi/sd.c:827
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81722cf0-ffffffff81722e5e: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175dec0)
Location: drivers/scsi/sd.c:889
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff8175dec0-ffffffff8175e01b: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81782030)
Location: drivers/scsi/sd.c:889
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81782030-ffffffff8178218b: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81844300)
Location: drivers/scsi/sd.c:903
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
```
**Symbols:**

```
ffffffff81844300-ffffffff81844461: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81854610)
Location: drivers/scsi/sd.c:938
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
  - drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd
```
**Symbols:**

```
ffffffff81854610-ffffffff81854784: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818381b0)
Location: drivers/scsi/sd.c:938
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff818381b0-ffffffff81838318: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:938
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff818c40a0-ffffffff818c4240: sd_setup_write_same10_cmnd (STB_LOCAL)
ffffffff81d0cd35-ffffffff81d0cd8d: sd_setup_write_same10_cmnd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:901
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81a0fdd0-ffffffff81a0ff41: sd_setup_write_same10_cmnd (STB_LOCAL)
ffffffff81ed5b4e-ffffffff81ed5ba6: sd_setup_write_same10_cmnd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:901
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81b8fff0-ffffffff81b90161: sd_setup_write_same10_cmnd (STB_LOCAL)
ffffffff8209bcf8-ffffffff8209bd50: sd_setup_write_same10_cmnd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
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
ffffffff81be64b0-ffffffff81be660a: sd_setup_write_same10_cmnd (STB_LOCAL)
ffffffff8211cc58-ffffffff8211ccc0: sd_setup_write_same10_cmnd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: drivers/scsi/sd.c:946
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81c3b880-ffffffff81c3b9d7: sd_setup_write_same10_cmnd (STB_LOCAL)
ffffffff821faaf3-ffffffff821fab5b: sd_setup_write_same10_cmnd.cold (STB_LOCAL)
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff800010988bf8)
Location: drivers/scsi/sd.c:889
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffff800010988bf8-ffff800010988d50: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a5aac8)
Location: drivers/scsi/sd.c:889
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
c0a5aac8-c0a5ac28: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a48c30)
Location: drivers/scsi/sd.c:889
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
c000000000a48c30-c000000000a48e20: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005ecd2a)
Location: drivers/scsi/sd.c:889
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffe0005ecd2a-ffffffe0005eced4: sd_setup_write_same10_cmnd (STB_LOCAL)
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
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81736720)
Location: drivers/scsi/sd.c:889
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81736720-ffffffff8173687b: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817183c0)
Location: drivers/scsi/sd.c:889
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff817183c0-ffffffff8171851b: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81776eb0)
Location: drivers/scsi/sd.c:889
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81776eb0-ffffffff8177700b: sd_setup_write_same10_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_status_t sd_setup_write_same10_cmnd(struct scsi_cmnd *cmd, bool unmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81790b30)
Location: drivers/scsi/sd.c:889
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_init_command
```
**Symbols:**

```
ffffffff81790b30-ffffffff81790ca9: sd_setup_write_same10_cmnd (STB_LOCAL)
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
