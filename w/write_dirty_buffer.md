# Function: <code>write_dirty_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int rw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81246480)
Location: fs/buffer.c:3115
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff81246480-ffffffff812464fb: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126f3c0)
Location: fs/buffer.c:3174
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff8126f3c0-ffffffff8126f43f: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812825c0)
Location: fs/buffer.c:3215
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff812825c0-ffffffff8128263f: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128fc70)
Location: fs/buffer.c:3202
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff8128fc70-ffffffff8128fcef: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b29a0)
Location: fs/buffer.c:3170
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff812b29a0-ffffffff812b2a1f: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812da8b0)
Location: fs/buffer.c:3141
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff812da8b0-ffffffff812da932: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812efd90)
Location: fs/buffer.c:3153
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff812efd90-ffffffff812efe12: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81311620)
Location: fs/buffer.c:3160
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff81311620-ffffffff813116ab: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81324600)
Location: fs/buffer.c:3137
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff81324600-ffffffff8132468b: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135b060)
Location: fs/buffer.c:3138
Inline: True
Direct callers:
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff8135b060-ffffffff8135b0f6: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81369180)
Location: fs/buffer.c:3119
Inline: True
Direct callers:
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff81369180-ffffffff81369216: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136f910)
Location: fs/buffer.c:3140
Inline: True
Direct callers:
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff8136f910-ffffffff8136f9a6: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813be510)
Location: fs/buffer.c:3119
Inline: True
Direct callers:
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff813be510-ffffffff813be5a6: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81444830)
Location: fs/buffer.c:3104
Inline: True
Direct callers:
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff81444830-ffffffff814448d7: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, blk_opf_t op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d3650)
Location: fs/buffer.c:2711
Inline: True
Direct callers:
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff814d3650-ffffffff814d36f5: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, blk_opf_t op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150b990)
Location: fs/buffer.c:2849
Inline: True
Direct callers:
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff8150b990-ffffffff8150ba35: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, blk_opf_t op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81540590)
Location: fs/buffer.c:2809
Inline: True
Direct callers:
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff81540590-ffffffff81540635: write_dirty_buffer (STB_GLOBAL)
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
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103dd970)
Location: fs/buffer.c:3137
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffff8000103dd970-ffff8000103ddab4: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b6e74)
Location: fs/buffer.c:3137
Inline: True
Direct callers:
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
c05b6e74-c05b6f94: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e34a0)
Location: fs/buffer.c:3137
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
c0000000004e34a0-c0000000004e35d8: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe00029592c)
Location: fs/buffer.c:3137
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffe00029592c-ffffffe0002959e8: write_dirty_buffer (STB_GLOBAL)
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
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131cbe0)
Location: fs/buffer.c:3137
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff8131cbe0-ffffffff8131cc6b: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130d780)
Location: fs/buffer.c:3137
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff8130d780-ffffffff8130d80b: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131a6b0)
Location: fs/buffer.c:3137
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff8131a6b0-ffffffff8131a73b: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void write_dirty_buffer(struct buffer_head *bh, int op_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132c3c0)
Location: fs/buffer.c:3137
Inline: True
Direct callers:
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/checkpoint.c:__flush_batch
  - fs/fat/misc.c:fat_sync_bhs
```
**Symbols:**

```
ffffffff8132c3c0-ffffffff8132c440: write_dirty_buffer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int op_flags</code> ➡️ <code>blk_opf_t op_flags</code>
</li>
</ul>
</details>
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
