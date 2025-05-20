# Function: <code>blk_verify_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t has_write_perm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff813cbc30)
Location: block/scsi_ioctl.c:210
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff813cbc30-ffffffff813cbc90: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t has_write_perm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff8140fee0)
Location: block/scsi_ioctl.c:210
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8140fee0-ffffffff8140ff31: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t has_write_perm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff8142b270)
Location: block/scsi_ioctl.c:213
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8142b270-ffffffff8142b2c1: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t has_write_perm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814430f0)
Location: block/scsi_ioctl.c:213
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff814430f0-ffffffff81443141: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff8146fb80)
Location: block/scsi_ioctl.c:213
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8146fb80-ffffffff8146fbd6: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814a3ef0)
Location: block/scsi_ioctl.c:210
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff814a3ef0-ffffffff814a3f46: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814be960)
Location: block/scsi_ioctl.c:210
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
ffffffff814be960-ffffffff814be9b6: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814ed210)
Location: block/scsi_ioctl.c:196
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
ffffffff814ed210-ffffffff814ed26c: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81506650)
Location: block/scsi_ioctl.c:196
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
ffffffff81506650-ffffffff815066ac: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81567060)
Location: block/scsi_ioctl.c:202
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:blk_fill_sghdr_rq
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
ffffffff81567060-ffffffff815670bc: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81581ef0)
Location: block/scsi_ioctl.c:200
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:blk_fill_sghdr_rq
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
ffffffff81581ef0-ffffffff81581f4c: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81588ce0)
Location: block/scsi_ioctl.c:200
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
ffffffff81588ce0-ffffffff81588d3c: blk_verify_command (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffff800010607990)
Location: block/scsi_ioctl.c:196
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
ffff800010607990-ffff800010607a1c: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c07b3b04)
Location: block/scsi_ioctl.c:196
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
  - drivers/scsi/sg.c:sg_new_write
```
**Symbols:**

```
c07b3b04-c07b3b84: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c0000000007a46d0)
Location: block/scsi_ioctl.c:196
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
c0000000007a46d0-c0000000007a4794: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffe00044249a)
Location: block/scsi_ioctl.c:196
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
ffffffe00044249a-ffffffe000442520: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814fec30)
Location: block/scsi_ioctl.c:196
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
ffffffff814fec30-ffffffff814fec8c: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814ef140)
Location: block/scsi_ioctl.c:196
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
ffffffff814ef140-ffffffff814ef19c: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814facc0)
Location: block/scsi_ioctl.c:196
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
ffffffff814facc0-ffffffff814fad1c: blk_verify_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int blk_verify_command(unsigned char *cmd, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81513d70)
Location: block/scsi_ioctl.c:196
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
```
**Symbols:**

```
ffffffff81513d70-ffffffff81513dcc: blk_verify_command (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>fmode_t mode</code>
</li>
<li>
<b>Param removed. </b>
<code>fmode_t has_write_perm</code>
</li>
</ul>
</details>
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
