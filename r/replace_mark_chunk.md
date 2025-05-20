# Function: <code>replace_mark_chunk</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void replace_mark_chunk(struct fsnotify_mark *mark, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (ffffffff81167091)
Location: kernel/audit_tree.c:281
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:replace_chunk
```
**Symbols:**

```
ffffffff81166a20-ffffffff81166a2b: replace_mark_chunk.part.9 (STB_LOCAL)
ffffffff81166a30-ffffffff81166a67: replace_mark_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void replace_mark_chunk(struct fsnotify_mark *mark, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (ffffffff81173c9a)
Location: kernel/audit_tree.c:281
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:replace_chunk
```
**Symbols:**

```
ffffffff81173610-ffffffff8117361b: replace_mark_chunk.part.0 (STB_LOCAL)
ffffffff81173620-ffffffff81173657: replace_mark_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void replace_mark_chunk(struct fsnotify_mark *mark, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (ffffffff8117fb0a)
Location: kernel/audit_tree.c:281
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:replace_chunk
```
**Symbols:**

```
ffffffff8117f480-ffffffff8117f48b: replace_mark_chunk.part.0 (STB_LOCAL)
ffffffff8117f490-ffffffff8117f4c7: replace_mark_chunk (STB_LOCAL)
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
In kernel/audit_tree.c (ffffffff81192ed2)
Location: kernel/audit_tree.c:281
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:replace_chunk
  - kernel/audit_tree.c:replace_chunk
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
In kernel/audit_tree.c (ffffffff81190042)
Location: kernel/audit_tree.c:279
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:replace_chunk
  - kernel/audit_tree.c:replace_chunk
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
In kernel/audit_tree.c (ffffffff81190f72)
Location: kernel/audit_tree.c:279
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
  - kernel/audit_tree.c:replace_chunk
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
In kernel/audit_tree.c (ffffffff811b9e52)
Location: kernel/audit_tree.c:279
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
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
In kernel/audit_tree.c (ffffffff811ece0e)
Location: kernel/audit_tree.c:279
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
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
In kernel/audit_tree.c (ffffffff8123339e)
Location: kernel/audit_tree.c:279
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
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
In kernel/audit_tree.c (ffffffff8124a04d)
Location: kernel/audit_tree.c:279
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
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
In kernel/audit_tree.c (ffffffff81263f5d)
Location: kernel/audit_tree.c:279
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void replace_mark_chunk(struct fsnotify_mark *mark, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (ffff8000101f499c)
Location: kernel/audit_tree.c:281
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:replace_chunk
```
**Symbols:**

```
ffff8000101f4428-ffff8000101f443c: replace_mark_chunk.part.0 (STB_LOCAL)
ffff8000101f4440-ffff8000101f4490: replace_mark_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void replace_mark_chunk(struct fsnotify_mark *mark, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (c04349d8)
Location: kernel/audit_tree.c:281
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
Direct callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:replace_chunk
```
**Symbols:**

```
c04347e8-c0434800: replace_mark_chunk.part.0 (STB_LOCAL)
c0434800-c0434850: replace_mark_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void replace_mark_chunk(struct fsnotify_mark *mark, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (c00000000026981c)
Location: kernel/audit_tree.c:281
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:replace_chunk
```
**Symbols:**

```
c000000000269350-c0000000002693a0: replace_mark_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void replace_mark_chunk(struct fsnotify_mark *mark, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (ffffffe000167c14)
Location: kernel/audit_tree.c:281
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:replace_chunk
```
**Symbols:**

```
ffffffe0001676ee-ffffffe000167702: replace_mark_chunk.part.0 (STB_LOCAL)
ffffffe000167702-ffffffe00016774e: replace_mark_chunk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void replace_mark_chunk(struct fsnotify_mark *mark, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (ffffffff8117812a)
Location: kernel/audit_tree.c:281
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:replace_chunk
```
**Symbols:**

```
ffffffff81177aa0-ffffffff81177aab: replace_mark_chunk.part.0 (STB_LOCAL)
ffffffff81177ab0-ffffffff81177ae7: replace_mark_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void replace_mark_chunk(struct fsnotify_mark *mark, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (ffffffff8116b2ca)
Location: kernel/audit_tree.c:281
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:replace_chunk
```
**Symbols:**

```
ffffffff8116ac40-ffffffff8116ac4b: replace_mark_chunk.part.0 (STB_LOCAL)
ffffffff8116ac50-ffffffff8116ac87: replace_mark_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void replace_mark_chunk(struct fsnotify_mark *mark, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (ffffffff81175efa)
Location: kernel/audit_tree.c:281
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:replace_chunk
```
**Symbols:**

```
ffffffff81175870-ffffffff8117587b: replace_mark_chunk.part.0 (STB_LOCAL)
ffffffff81175880-ffffffff811758b7: replace_mark_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void replace_mark_chunk(struct fsnotify_mark *mark, struct audit_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit_tree.c (ffffffff811837e2)
Location: kernel/audit_tree.c:281
Inline: True
Inline callers:
  - kernel/audit_tree.c:prune_tree_chunks
Direct callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:replace_chunk
```
**Symbols:**

```
ffffffff81183150-ffffffff8118315b: replace_mark_chunk.part.0 (STB_LOCAL)
ffffffff81183160-ffffffff81183197: replace_mark_chunk (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
