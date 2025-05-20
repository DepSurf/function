# Function: <code>scsi_verify_blk_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff813cc0a0)
Location: block/scsi_ioctl.c:692
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff813cc0a0-ffffffff813cc1a5: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff8140ff40)
Location: block/scsi_ioctl.c:692
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff8140ff40-ffffffff8141004a: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff8142b2d0)
Location: block/scsi_ioctl.c:695
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/md/dm.c:dm_blk_ioctl
```
**Symbols:**

```
ffffffff8142b2d0-ffffffff8142b3da: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81443150)
Location: block/scsi_ioctl.c:693
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff81443150-ffffffff81443259: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff8146fbe0)
Location: block/scsi_ioctl.c:693
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff8146fbe0-ffffffff8146fce9: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814a4b35)
Location: block/scsi_ioctl.c:689
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff814a3e70-ffffffff814a3ea0: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814bf5f5)
Location: block/scsi_ioctl.c:689
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff814be8e0-ffffffff814be910: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814ede45)
Location: block/scsi_ioctl.c:675
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff814ed170-ffffffff814ed1a0: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff815072b5)
Location: block/scsi_ioctl.c:675
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff815065b0-ffffffff815065e0: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81566f20)
Location: block/scsi_ioctl.c:855
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl_common
```
**Symbols:**

```
ffffffff81566f20-ffffffff81566f50: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81581cc0)
Location: block/scsi_ioctl.c:846
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl_common
```
**Symbols:**

```
ffffffff81581cc0-ffffffff81581cf3: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81588bb0)
Location: block/scsi_ioctl.c:842
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl_common
```
**Symbols:**

```
ffffffff81588bb0-ffffffff81588be3: scsi_verify_blk_ioctl (STB_GLOBAL)
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
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffff800010609698)
Location: block/scsi_ioctl.c:675
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffff8000106078d8-ffff800010607928: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c07b4b98)
Location: block/scsi_ioctl.c:675
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
c07b3a7c-c07b3ac8: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c0000000007a5b94)
Location: block/scsi_ioctl.c:675
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
c0000000007a4590-c0000000007a4608: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffe000443004)
Location: block/scsi_ioctl.c:675
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
Direct callers:
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffe0004423f0-ffffffe00044242c: scsi_verify_blk_ioctl (STB_GLOBAL)
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
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814ff895)
Location: block/scsi_ioctl.c:675
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff814feb90-ffffffff814febc0: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814efda5)
Location: block/scsi_ioctl.c:675
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff814ef0a0-ffffffff814ef0d0: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814fb925)
Location: block/scsi_ioctl.c:675
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff814fac20-ffffffff814fac50: scsi_verify_blk_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int scsi_verify_blk_ioctl(struct block_device *bd, unsigned int cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff815149d5)
Location: block/scsi_ioctl.c:675
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff81513cd0-ffffffff81513d00: scsi_verify_blk_ioctl (STB_GLOBAL)
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
