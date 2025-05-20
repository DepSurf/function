# Function: <code>vfs_parse_fs_string</code>

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
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8130a940)
Location: fs/fs_context.c:171
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff8130a940-ffffffff8130a9e2: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8131d900)
Location: fs/fs_context.c:171
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff8131d900-ffffffff8131d9a2: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81357320)
Location: fs/fs_context.c:143
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff81357320-ffffffff813573c4: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81363cd0)
Location: fs/fs_context.c:143
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff81363cd0-ffffffff81363d74: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8136a750)
Location: fs/fs_context.c:143
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff8136a750-ffffffff8136a7f4: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813b9410)
Location: fs/fs_context.c:166
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff813b9410-ffffffff813b94b4: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8143ec20)
Location: fs/fs_context.c:166
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff8143ec20-ffffffff8143eccc: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814cd860)
Location: fs/fs_context.c:166
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff814cd860-ffffffff814cd90c: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81503a30)
Location: fs/fs_context.c:166
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff81503a30-ffffffff81503adc: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81538680)
Location: fs/fs_context.c:170
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/fs_context.c:vfs_parse_monolithic_sep
```
**Symbols:**

```
ffffffff81538680-ffffffff8153872c: vfs_parse_fs_string (STB_GLOBAL)
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
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffff8000103d56a0)
Location: fs/fs_context.c:171
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffff8000103d56a0-ffff8000103d5760: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c05af8e8)
Location: fs/fs_context.c:171
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
c05af8e8-c05af9a4: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c0000000004d8ec0)
Location: fs/fs_context.c:171
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
c0000000004d8ec0-c0000000004d8f90: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffe00028fa50)
Location: fs/fs_context.c:171
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffe00028fa50-ffffffe00028fad8: vfs_parse_fs_string (STB_GLOBAL)
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
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81315ee0)
Location: fs/fs_context.c:171
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff81315ee0-ffffffff81315f82: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81306ad0)
Location: fs/fs_context.c:171
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff81306ad0-ffffffff81306b72: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81313cd0)
Location: fs/fs_context.c:171
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff81313cd0-ffffffff81313d72: vfs_parse_fs_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_parse_fs_string(struct fs_context *fc, const char *key, const char *value, size_t v_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81325520)
Location: fs/fs_context.c:171
Inline: False
Direct callers:
  - mm/shmem.c:shmem_parse_options
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/fs_context.c:generic_parse_monolithic
```
**Symbols:**

```
ffffffff81325520-ffffffff813255c2: vfs_parse_fs_string (STB_GLOBAL)
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
