# Function: <code>bsg_scsi_register_queue</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814a5360)
Location: block/bsg.c:957
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff814a5360-ffffffff814a53d9: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814c02c0)
Location: block/bsg.c:524
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff814c02c0-ffffffff814c031e: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814eea20)
Location: block/bsg.c:463
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff814eea20-ffffffff814eea7d: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81507e80)
Location: block/bsg.c:463
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff81507e80-ffffffff81507edd: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff815690c0)
Location: block/bsg.c:464
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff815690c0-ffffffff8156911d: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff815839f0)
Location: block/bsg.c:466
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff815839f0-ffffffff81583a4d: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8158a800)
Location: block/bsg.c:466
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff8158a800-ffffffff8158a85d: bsg_scsi_register_queue (STB_GLOBAL)
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
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffff80001060aa28)
Location: block/bsg.c:463
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffff80001060aa28-ffff80001060aab8: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (c07b58d0)
Location: block/bsg.c:463
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
c07b58d0-c07b5954: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (c0000000007a6de0)
Location: block/bsg.c:463
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
c0000000007a6de0-c0000000007a6e78: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffe00044399e)
Location: block/bsg.c:463
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffe00044399e-ffffffe000443a24: bsg_scsi_register_queue (STB_GLOBAL)
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
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81500460)
Location: block/bsg.c:463
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff81500460-ffffffff815004bd: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814f0970)
Location: block/bsg.c:463
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff814f0970-ffffffff814f09cd: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814fc4f0)
Location: block/bsg.c:463
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff814fc4f0-ffffffff814fc54d: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bsg_scsi_register_queue(struct request_queue *q, struct device *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff815155a0)
Location: block/bsg.c:463
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff815155a0-ffffffff815155fd: bsg_scsi_register_queue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
