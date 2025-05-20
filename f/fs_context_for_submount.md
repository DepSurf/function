# Function: <code>fs_context_for_submount</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8130aca0)
Location: fs/fs_context.c:323
Inline: False
```
**Symbols:**

```
ffffffff8130aca0-ffffffff8130acba: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8131dc80)
Location: fs/fs_context.c:321
Inline: False
```
**Symbols:**

```
ffffffff8131dc80-ffffffff8131dc9a: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81357a40)
Location: fs/fs_context.c:295
Inline: False
```
**Symbols:**

```
ffffffff81357a40-ffffffff81357a5a: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81364530)
Location: fs/fs_context.c:295
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff81364530-ffffffff8136454a: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8136af90)
Location: fs/fs_context.c:295
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff8136af90-ffffffff8136afaa: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813b9c50)
Location: fs/fs_context.c:318
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff813b9c50-ffffffff813b9c6a: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8143f720)
Location: fs/fs_context.c:318
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff8143f720-ffffffff8143f749: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814ce3f0)
Location: fs/fs_context.c:318
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff814ce3f0-ffffffff814ce419: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff815045f0)
Location: fs/fs_context.c:326
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff815045f0-ffffffff81504666: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff815392b0)
Location: fs/fs_context.c:354
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff815392b0-ffffffff81539326: fs_context_for_submount (STB_GLOBAL)
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
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffff8000103d5dd8)
Location: fs/fs_context.c:321
Inline: False
```
**Symbols:**

```
ffff8000103d5dd8-ffff8000103d5e18: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c05af36c)
Location: fs/fs_context.c:321
Inline: False
```
**Symbols:**

```
c05af36c-c05af3a0: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c0000000004d94d0)
Location: fs/fs_context.c:321
Inline: False
```
**Symbols:**

```
c0000000004d94d0-c0000000004d94f0: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffe00028f662)
Location: fs/fs_context.c:321
Inline: False
```
**Symbols:**

```
ffffffe00028f662-ffffffe00028f69a: fs_context_for_submount (STB_GLOBAL)
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
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81316260)
Location: fs/fs_context.c:321
Inline: False
```
**Symbols:**

```
ffffffff81316260-ffffffff8131627a: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81306e50)
Location: fs/fs_context.c:321
Inline: False
```
**Symbols:**

```
ffffffff81306e50-ffffffff81306e6a: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81314050)
Location: fs/fs_context.c:321
Inline: False
```
**Symbols:**

```
ffffffff81314050-ffffffff8131406a: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fs_context *fs_context_for_submount(struct file_system_type *type, struct dentry *reference);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813258a0)
Location: fs/fs_context.c:321
Inline: False
```
**Symbols:**

```
ffffffff813258a0-ffffffff813258ba: fs_context_for_submount (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
