# Function: <code>alloc_file_clone</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812b0ef0)
Location: fs/file_table.c:241
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812b0ef0-ffffffff812b0f3f: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812cd7e0)
Location: fs/file_table.c:242
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812cd7e0-ffffffff812cd823: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812df200)
Location: fs/file_table.c:242
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812df200-ffffffff812df243: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81316060)
Location: fs/file_table.c:243
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81316060-ffffffff813160a3: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81321640)
Location: fs/file_table.c:242
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81321640-ffffffff81321683: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81327660)
Location: fs/file_table.c:241
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81327660-ffffffff813276a3: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81374c60)
Location: fs/file_table.c:242
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81374c60-ffffffff81374ca3: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff813f3d70)
Location: fs/file_table.c:278
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff813f3d70-ffffffff813f3dbd: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff8147cc40)
Location: fs/file_table.c:281
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8147cc40-ffffffff8147cc8d: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff814b1a00)
Location: fs/file_table.c:345
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff814b1a00-ffffffff814b1a53: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff814e31e0)
Location: fs/file_table.c:337
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff814e31e0-ffffffff814e3233: alloc_file_clone (STB_GLOBAL)
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
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffff800010385a68)
Location: fs/file_table.c:242
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffff800010385a68-ffff800010385acc: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c056e914)
Location: fs/file_table.c:242
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
c056e914-c056e958: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c00000000047bc30)
Location: fs/file_table.c:242
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
c00000000047bc30-c00000000047bca0: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffe0002586fe)
Location: fs/file_table.c:242
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffe0002586fe-ffffffe000258754: alloc_file_clone (STB_GLOBAL)
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
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d77e0)
Location: fs/file_table.c:242
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812d77e0-ffffffff812d7823: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812c8460)
Location: fs/file_table.c:242
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812c8460-ffffffff812c84a3: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d55f0)
Location: fs/file_table.c:242
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812d55f0-ffffffff812d5633: alloc_file_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *alloc_file_clone(struct file *base, int flags, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812e6440)
Location: fs/file_table.c:242
Inline: False
Direct callers:
  - fs/pipe.c:create_pipe_files
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812e6440-ffffffff812e6483: alloc_file_clone (STB_GLOBAL)
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
