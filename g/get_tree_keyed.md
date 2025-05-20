# Function: <code>get_tree_keyed</code>

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
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e1980)
Location: fs/super.c:1241
Inline: False
Direct callers:
  - fs/proc/root.c:proc_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff812e1980-ffffffff812e199c: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81318520)
Location: fs/super.c:1241
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff81318520-ffffffff813185e2: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813238f0)
Location: fs/super.c:1188
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff813238f0-ffffffff813239b2: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813299b0)
Location: fs/super.c:1190
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff813299b0-ffffffff81329a72: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81376fe0)
Location: fs/super.c:1190
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff81376fe0-ffffffff813770a2: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f6260)
Location: fs/super.c:1189
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff813f6260-ffffffff813f6317: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147fd70)
Location: fs/super.c:1190
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff8147fd70-ffffffff8147fd9f: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b4a60)
Location: fs/super.c:1201
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff814b4a60-ffffffff814b4a8f: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e5db0)
Location: fs/super.c:1299
Inline: False
Direct callers:
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff814e5db0-ffffffff814e5e52: get_tree_keyed (STB_GLOBAL)
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
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010388d90)
Location: fs/super.c:1241
Inline: False
Direct callers:
  - fs/proc/root.c:proc_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffff800010388d90-ffff800010388dd8: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c0571380)
Location: fs/super.c:1241
Inline: False
Direct callers:
  - fs/proc/root.c:proc_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
c0571380-c05713b0: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047fcd0)
Location: fs/super.c:1241
Inline: False
Direct callers:
  - fs/proc/root.c:proc_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
c00000000047fcd0-c00000000047fcf8: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025b2ba)
Location: fs/super.c:1241
Inline: False
Direct callers:
  - fs/proc/root.c:proc_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffe00025b2ba-ffffffe00025b2f8: get_tree_keyed (STB_GLOBAL)
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
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d9f60)
Location: fs/super.c:1241
Inline: False
Direct callers:
  - fs/proc/root.c:proc_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff812d9f60-ffffffff812d9f7c: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cabe0)
Location: fs/super.c:1241
Inline: False
Direct callers:
  - fs/proc/root.c:proc_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff812cabe0-ffffffff812cabfc: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7d70)
Location: fs/super.c:1241
Inline: False
Direct callers:
  - fs/proc/root.c:proc_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff812d7d70-ffffffff812d7d8c: get_tree_keyed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_tree_keyed(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *), void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e8bb0)
Location: fs/super.c:1241
Inline: False
Direct callers:
  - fs/proc/root.c:proc_get_tree
  - ipc/mqueue.c:mqueue_get_tree
```
**Symbols:**

```
ffffffff812e8bb0-ffffffff812e8bcc: get_tree_keyed (STB_GLOBAL)
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
