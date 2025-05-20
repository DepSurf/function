# Function: <code>blk_mq_tagset_busy_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8140b030)
Location: block/blk-mq-tag.c:476
Inline: False
```
**Symbols:**

```
ffffffff8140b030-ffffffff8140b0b9: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81425bf0)
Location: block/blk-mq-tag.c:292
Inline: False
```
**Symbols:**

```
ffffffff81425bf0-ffffffff81425dcb: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814337a0)
Location: block/blk-mq-tag.c:279
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_busy_show
```
**Symbols:**

```
ffffffff814337a0-ffffffff8143397a: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8145f3c0)
Location: block/blk-mq-tag.c:289
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_busy_show
```
**Symbols:**

```
ffffffff8145f3c0-ffffffff8145f622: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81492c90)
Location: block/blk-mq-tag.c:305
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_busy_show
```
**Symbols:**

```
ffffffff81492c90-ffffffff81492ef6: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814acbb0)
Location: block/blk-mq-tag.c:352
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_busy_show
```
**Symbols:**

```
ffffffff814acbb0-ffffffff814ace17: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814daec0)
Location: block/blk-mq-tag.c:345
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_busy_show
```
**Symbols:**

```
ffffffff814daec0-ffffffff814db135: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814f4280)
Location: block/blk-mq-tag.c:346
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
```
**Symbols:**

```
ffffffff814f4280-ffffffff814f44f5: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81554b8e)
Location: block/blk-mq-tag.c:392
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
Direct callers:
  - block/blk-mq-debugfs.c:hctx_busy_show
  - drivers/scsi/hosts.c:scsi_host_busy_iter
  - drivers/scsi/hosts.c:scsi_host_complete_all_commands
  - drivers/scsi/hosts.c:scsi_host_busy
```
**Symbols:**

```
ffffffff81554b00-ffffffff81554b5c: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815712de)
Location: block/blk-mq-tag.c:352
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
Direct callers:
  - block/blk-mq-debugfs.c:hctx_busy_show
  - drivers/scsi/hosts.c:scsi_host_busy_iter
  - drivers/scsi/hosts.c:scsi_host_complete_all_commands
  - drivers/scsi/hosts.c:scsi_host_busy
```
**Symbols:**

```
ffffffff81571250-ffffffff815712af: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8157930e)
Location: block/blk-mq-tag.c:378
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
Direct callers:
  - block/blk-mq-debugfs.c:hctx_busy_show
  - drivers/scsi/hosts.c:scsi_host_busy_iter
  - drivers/scsi/hosts.c:scsi_host_complete_all_commands
  - drivers/scsi/hosts.c:scsi_host_busy
```
**Symbols:**

```
ffffffff81579280-ffffffff815792df: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:379
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
  - drivers/scsi/hosts.c:scsi_host_busy_iter
  - drivers/scsi/hosts.c:scsi_host_complete_all_commands
  - drivers/scsi/hosts.c:scsi_host_busy
```
**Symbols:**

```
ffffffff81cd8600-ffffffff81cd86b2: blk_mq_tagset_busy_iter.cold (STB_LOCAL)
ffffffff815de2a0-ffffffff815de559: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:435
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
  - drivers/scsi/hosts.c:scsi_host_busy_iter
  - drivers/scsi/hosts.c:scsi_host_complete_all_commands
  - drivers/scsi/hosts.c:scsi_host_busy
```
**Symbols:**

```
ffffffff81e8bd76-ffffffff81e8bece: blk_mq_tagset_busy_iter.cold (STB_LOCAL)
ffffffff8168c2e0-ffffffff8168c6ac: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:429
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
  - drivers/scsi/hosts.c:scsi_host_busy_iter
  - drivers/scsi/hosts.c:scsi_host_complete_all_commands
  - drivers/scsi/hosts.c:scsi_host_busy
```
**Symbols:**

```
ffffffff82076348-ffffffff820764a0: blk_mq_tagset_busy_iter.cold (STB_LOCAL)
ffffffff8174aa80-ffffffff8174ae3a: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:436
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
  - drivers/scsi/hosts.c:scsi_host_busy_iter
  - drivers/scsi/hosts.c:scsi_host_complete_all_commands
  - drivers/scsi/hosts.c:scsi_host_busy
```
**Symbols:**

```
ffffffff820f61d6-ffffffff820f6322: blk_mq_tagset_busy_iter.cold (STB_LOCAL)
ffffffff81787160-ffffffff8178752c: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:436
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
  - drivers/scsi/hosts.c:scsi_host_busy_iter
  - drivers/scsi/hosts.c:scsi_host_complete_all_commands
  - drivers/scsi/hosts.c:scsi_host_busy
```
**Symbols:**

```
ffffffff821d36fb-ffffffff821d3847: blk_mq_tagset_busy_iter.cold (STB_LOCAL)
ffffffff817c9840-ffffffff817c9c0c: blk_mq_tagset_busy_iter (STB_GLOBAL)
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
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffff8000105f3ee8)
Location: block/blk-mq-tag.c:346
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
```
**Symbols:**

```
ffff8000105f3ee8-ffff8000105f413c: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c079fbdc)
Location: block/blk-mq-tag.c:346
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
```
**Symbols:**

```
c079fbdc-c079fe58: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c00000000078b5c0)
Location: block/blk-mq-tag.c:346
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
```
**Symbols:**

```
c00000000078b5c0-c00000000078b924: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffe0004320a8)
Location: block/blk-mq-tag.c:346
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
```
**Symbols:**

```
ffffffe0004320a8-ffffffe0004322b0: blk_mq_tagset_busy_iter (STB_GLOBAL)
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
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814ec860)
Location: block/blk-mq-tag.c:346
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_dev_disable
```
**Symbols:**

```
ffffffff814ec860-ffffffff814ecad5: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814dcdb0)
Location: block/blk-mq-tag.c:346
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_dev_disable
```
**Symbols:**

```
ffffffff814dcdb0-ffffffff814dd025: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814e88f0)
Location: block/blk-mq-tag.c:346
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
```
**Symbols:**

```
ffffffff814e88f0-ffffffff814e8b65: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_tagset_busy_iter(struct blk_mq_tag_set *tagset, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81501890)
Location: block/blk-mq-tag.c:346
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-mq-debugfs.c:hctx_busy_show
```
**Symbols:**

```
ffffffff81501890-ffffffff81501b05: blk_mq_tagset_busy_iter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
