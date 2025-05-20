# Function: <code>ext4_kvfree_array_rcu</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813ce790)
Location: fs/ext4/resize.c:34
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff813ce790-ffffffff813ce7df: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8141a5ce)
Location: fs/ext4/resize.c:34
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff8141c390-ffffffff8141c3e5: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8142e7b3)
Location: fs/ext4/resize.c:34
Inline: True
Inline callers:
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff81430140-ffffffff81430195: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81436360)
Location: fs/ext4/resize.c:34
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff81436360-ffffffff814363b5: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81489f40)
Location: fs/ext4/resize.c:34
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff81489f40-ffffffff81489f95: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8150cf20)
Location: fs/ext4/resize.c:35
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff8150cf20-ffffffff8150cf7c: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff815a7c30)
Location: fs/ext4/resize.c:35
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff815a7c30-ffffffff815a7c8c: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff815de4a0)
Location: fs/ext4/resize.c:35
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff815de4a0-ffffffff815de4fc: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81616f20)
Location: fs/ext4/resize.c:33
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff81616f20-ffffffff81616fab: ext4_kvfree_array_rcu (STB_GLOBAL)
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
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffff8000104a70e8)
Location: fs/ext4/resize.c:34
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffff8000104a70e8-ffff8000104a7144: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0669214)
Location: fs/ext4/resize.c:34
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
c0669214-c0669270: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0000000005d49d0)
Location: fs/ext4/resize.c:34
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
c0000000005d49d0-c0000000005d4a68: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffe000327b0e)
Location: fs/ext4/resize.c:34
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffe000327b0e-ffffffe000327b6e: ext4_kvfree_array_rcu (STB_GLOBAL)
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
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c6d70)
Location: fs/ext4/resize.c:34
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff813c6d70-ffffffff813c6dbf: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b77f0)
Location: fs/ext4/resize.c:34
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff813b77f0-ffffffff813b783f: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c4200)
Location: fs/ext4/resize.c:34
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff813c4200-ffffffff813c424f: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_kvfree_array_rcu(void *to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813d93d0)
Location: fs/ext4/resize.c:34
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
**Symbols:**

```
ffffffff813d93d0-ffffffff813d941f: ext4_kvfree_array_rcu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
