# Function: <code>alloc_fs_context</code>

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
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8130aac0)
Location: fs/fs_context.c:251
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff8130aac0-ffffffff8130ac48: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8131da80)
Location: fs/fs_context.c:251
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff8131da80-ffffffff8131dc2e: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81357810)
Location: fs/fs_context.c:224
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff81357810-ffffffff813579e4: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81364230)
Location: fs/fs_context.c:224
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff81364230-ffffffff813644df: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8136aca0)
Location: fs/fs_context.c:224
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff8136aca0-ffffffff8136af40: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813b9960)
Location: fs/fs_context.c:247
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff813b9960-ffffffff813b9c00: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8143f3f0)
Location: fs/fs_context.c:247
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff8143f3f0-ffffffff8143f6a7: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814ce090)
Location: fs/fs_context.c:247
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff814ce090-ffffffff814ce347: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81504290)
Location: fs/fs_context.c:247
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff81504290-ffffffff81504547: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81538f50)
Location: fs/fs_context.c:275
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff81538f50-ffffffff81539209: alloc_fs_context (STB_LOCAL)
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
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffff8000103d5b50)
Location: fs/fs_context.c:251
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffff8000103d5b50-ffff8000103d5d44: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c05af108)
Location: fs/fs_context.c:251
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
c05af108-c05af2f8: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c0000000004d9190)
Location: fs/fs_context.c:251
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
c0000000004d9190-c0000000004d9468: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffe00028f48e)
Location: fs/fs_context.c:251
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffe00028f48e-ffffffe00028f5ea: alloc_fs_context (STB_LOCAL)
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
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81316060)
Location: fs/fs_context.c:251
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff81316060-ffffffff8131620e: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81306c50)
Location: fs/fs_context.c:251
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff81306c50-ffffffff81306dfe: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81313e50)
Location: fs/fs_context.c:251
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff81313e50-ffffffff81313ffe: alloc_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fs_context *alloc_fs_context(struct file_system_type *fs_type, struct dentry *reference, unsigned int sb_flags, unsigned int sb_flags_mask, enum fs_context_purpose purpose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813256a0)
Location: fs/fs_context.c:251
Inline: False
Direct callers:
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:fs_context_for_reconfigure
  - fs/fs_context.c:fs_context_for_mount
```
**Symbols:**

```
ffffffff813256a0-ffffffff8132584e: alloc_fs_context (STB_LOCAL)
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
