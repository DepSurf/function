# Function: <code>blk_set_queue_dying</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5d00)
Location: block/blk-core.c:516
Inline: True
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff813b5d00-ffffffff813b5d7d: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fc640)
Location: block/blk-core.c:516
Inline: True
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff813fc640-ffffffff813fc6e5: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81416050)
Location: block/blk-core.c:517
Inline: True
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81416050-ffffffff814160f5: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81423970)
Location: block/blk-core.c:586
Inline: True
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81423970-ffffffff81423a3d: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144f100)
Location: block/blk-core.c:626
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff8144f100-ffffffff8144f1dc: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81481cc0)
Location: block/blk-core.c:687
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81481cc0-ffffffff81481d81: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149cc60)
Location: block/blk-core.c:274
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff8149cc60-ffffffff8149cc9e: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb520)
Location: block/blk-core.c:308
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff814cb520-ffffffff814cb55e: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e4710)
Location: block/blk-core.c:311
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff814e4710-ffffffff814e474e: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81543080)
Location: block/blk-core.c:330
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81543080-ffffffff815430c1: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f8d0)
Location: block/blk-core.c:343
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff8155f8d0-ffffffff8155f911: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81568010)
Location: block/blk-core.c:344
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81568010-ffffffff81568051: blk_set_queue_dying (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0ce8)
Location: block/blk-core.c:311
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffff8000105e0ce8-ffff8000105e0d58: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e344)
Location: block/blk-core.c:311
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
c078e344-c078e3a0: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007741a0)
Location: block/blk-core.c:311
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
c0000000007741a0-c000000000774228: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe0004235f8)
Location: block/blk-core.c:311
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffe0004235f8-ffffffe00042364c: blk_set_queue_dying (STB_GLOBAL)
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
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dccf0)
Location: block/blk-core.c:311
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/nvme/host/multipath.c:nvme_mpath_remove_disk
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff814dccf0-ffffffff814dcd2e: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd6a0)
Location: block/blk-core.c:311
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/nvme/host/multipath.c:nvme_mpath_remove_disk
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff814cd6a0-ffffffff814cd6de: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8d80)
Location: block/blk-core.c:311
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff814d8d80-ffffffff814d8dbe: blk_set_queue_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_set_queue_dying(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f1990)
Location: block/blk-core.c:311
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff814f1990-ffffffff814f19ce: blk_set_queue_dying (STB_GLOBAL)
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
