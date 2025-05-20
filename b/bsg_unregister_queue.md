# Function: <code>bsg_unregister_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff813d5eb0)
Location: block/bsg.c:956
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff813d5eb0-ffffffff813d5f41: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8141bba0)
Location: block/bsg.c:956
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff8141bba0-ffffffff8141bc3f: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814373d0)
Location: block/bsg.c:959
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff814373d0-ffffffff8143746f: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814443f0)
Location: block/bsg.c:958
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff814443f0-ffffffff81444491: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81471940)
Location: block/bsg.c:949
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81471940-ffffffff814719dc: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814a4f70)
Location: block/bsg.c:883
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff814a4f70-ffffffff814a4fea: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814bfdd0)
Location: block/bsg.c:450
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff814bfdd0-ffffffff814bfe4a: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814ee520)
Location: block/bsg.c:389
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff814ee520-ffffffff814ee59a: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81507980)
Location: block/bsg.c:389
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81507980-ffffffff815079fa: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81568a60)
Location: block/bsg.c:390
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81568a60-ffffffff81568ada: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81583390)
Location: block/bsg.c:392
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81583390-ffffffff8158340d: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8158a1c0)
Location: block/bsg.c:392
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff8158a1c0-ffffffff8158a23d: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bsg_unregister_queue(struct bsg_device *bd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff815ef200)
Location: block/bsg.c:176
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff815ef200-ffffffff815ef24c: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bsg_unregister_queue(struct bsg_device *bd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff816a0180)
Location: block/bsg.c:176
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff816a0180-ffffffff816a01d7: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bsg_unregister_queue(struct bsg_device *bd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8175ebf0)
Location: block/bsg.c:176
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff8175ebf0-ffffffff8175ec55: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bsg_unregister_queue(struct bsg_device *bd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8179daf0)
Location: block/bsg.c:178
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff8179daf0-ffffffff8179db55: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bsg_unregister_queue(struct bsg_device *bd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff817e1540)
Location: block/bsg.c:178
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff817e1540-ffffffff817e15a2: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffff8000106098a0)
Location: block/bsg.c:389
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffff8000106098a0-ffff80001060991c: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (c07b5218)
Location: block/bsg.c:389
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
c07b5218-c07b5294: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (c0000000007a63b0)
Location: block/bsg.c:389
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
c0000000007a63b0-c0000000007a6460: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffe00044360c)
Location: block/bsg.c:389
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffe00044360c-ffffffe00044368e: bsg_unregister_queue (STB_GLOBAL)
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
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814fff60)
Location: block/bsg.c:389
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff814fff60-ffffffff814fffda: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814f0470)
Location: block/bsg.c:389
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff814f0470-ffffffff814f04ea: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814fbff0)
Location: block/bsg.c:389
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff814fbff0-ffffffff814fc06a: bsg_unregister_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bsg_unregister_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff815150a0)
Location: block/bsg.c:389
Inline: True
Direct callers:
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff815150a0-ffffffff8151511a: bsg_unregister_queue (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bsg_device *bd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
</ul>
</details>
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
