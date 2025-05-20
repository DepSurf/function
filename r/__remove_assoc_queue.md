# Function: <code>__remove_assoc_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __remove_assoc_queue(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81242770)
Location: fs/buffer.c:483
Inline: False
Direct callers:
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff81242770-ffffffff812427ce: __remove_assoc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __remove_assoc_queue(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126aaa0)
Location: fs/buffer.c:479
Inline: False
Direct callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff8126aaa0-ffffffff8126aafe: __remove_assoc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __remove_assoc_queue(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127dbb0)
Location: fs/buffer.c:480
Inline: False
Direct callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff8127dbb0-ffffffff8127dc0e: __remove_assoc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128d0ad)
Location: fs/buffer.c:479
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __remove_assoc_queue(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ae2c0)
Location: fs/buffer.c:458
Inline: False
Direct callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff812ae2c0-ffffffff812ae300: __remove_assoc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __remove_assoc_queue(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d5f70)
Location: fs/buffer.c:450
Inline: False
Direct callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff812d5f70-ffffffff812d5fb0: __remove_assoc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __remove_assoc_queue(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812eb340)
Location: fs/buffer.c:451
Inline: False
Direct callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff812eb340-ffffffff812eb380: __remove_assoc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __remove_assoc_queue(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:452
Inline: False
Direct callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffff8130cb70-ffffffff8130cbae: __remove_assoc_queue (STB_LOCAL)
ffffffff81311bcd-ffffffff81311be0: __remove_assoc_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132135b)
Location: fs/buffer.c:452
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135ba86)
Location: fs/buffer.c:478
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136a036)
Location: fs/buffer.c:477
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81371f3f)
Location: fs/buffer.c:477
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c0f62)
Location: fs/buffer.c:477
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81447c24)
Location: fs/buffer.c:477
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d67a4)
Location: fs/buffer.c:477
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150cd94)
Location: fs/buffer.c:518
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81541994)
Location: fs/buffer.c:512
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
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
void __remove_assoc_queue(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d7610)
Location: fs/buffer.c:452
Inline: False
Direct callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffff8000103d7610-ffff8000103d766c: __remove_assoc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __remove_assoc_queue(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b10a8)
Location: fs/buffer.c:452
Inline: False
Direct callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
**Symbols:**

```
c05b10a8-c05b110c: __remove_assoc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __remove_assoc_queue(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dbdb0)
Location: fs/buffer.c:452
Inline: False
Direct callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
c0000000004dbdb0-c0000000004dbdf0: __remove_assoc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __remove_assoc_queue(struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000290ef4)
Location: fs/buffer.c:452
Inline: False
Direct callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
**Symbols:**

```
ffffffe000290ef4-ffffffe000290f3c: __remove_assoc_queue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131993b)
Location: fs/buffer.c:452
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130a4fb)
Location: fs/buffer.c:452
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131740b)
Location: fs/buffer.c:452
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81328ffb)
Location: fs/buffer.c:452
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
