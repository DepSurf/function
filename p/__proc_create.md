# Function: <code>__proc_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127ee60)
Location: fs/proc/generic.c:358
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_symlink
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_create_data
  - fs/proc/generic.c:proc_create_mount_point
```
**Symbols:**

```
ffffffff8127ee60-ffffffff8127f0e0: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812abeb0)
Location: fs/proc/generic.c:362
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_data
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff812abeb0-ffffffff812ac11f: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c1780)
Location: fs/proc/generic.c:362
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_data
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff812c1780-ffffffff812c1a05: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812cec50)
Location: fs/proc/generic.c:345
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_data
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff812cec50-ffffffff812ceea3: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3450)
Location: fs/proc/generic.c:347
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_data
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff812f3450-ffffffff812f35fb: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813202b0)
Location: fs/proc/generic.c:374
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff813202b0-ffffffff813204e0: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337390)
Location: fs/proc/generic.c:374
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff81337390-ffffffff813375cf: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135f4b0)
Location: fs/proc/generic.c:375
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff8135f4b0-ffffffff8135f708: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377710)
Location: fs/proc/generic.c:375
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff81377710-ffffffff81377968: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0580)
Location: fs/proc/generic.c:387
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff813c0580-ffffffff813c07df: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d23d0)
Location: fs/proc/generic.c:397
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff813d23d0-ffffffff813d262e: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d91d0)
Location: fs/proc/generic.c:392
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff813d91d0-ffffffff813d942e: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142a900)
Location: fs/proc/generic.c:392
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff8142a900-ffffffff8142ab5e: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a3ed0)
Location: fs/proc/generic.c:392
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff814a3ed0-ffffffff814a4151: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815392e0)
Location: fs/proc/generic.c:392
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff815392e0-ffffffff81539561: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81571520)
Location: fs/proc/generic.c:391
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff81571520-ffffffff815717a1: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815a9ed0)
Location: fs/proc/generic.c:391
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir
  - fs/proc/generic.c:proc_mkdir_mode
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff815a9ed0-ffffffff815aa151: __proc_create (STB_LOCAL)
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
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff800010443390)
Location: fs/proc/generic.c:375
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffff800010443390-ffff800010443650: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0608698)
Location: fs/proc/generic.c:375
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
c0608698-c0608964: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c000000000558a00)
Location: fs/proc/generic.c:375
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
c000000000558a00-c000000000558cf4: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002d9ac0)
Location: fs/proc/generic.c:375
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffe0002d9ac0-ffffffe0002d9cd6: __proc_create (STB_LOCAL)
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
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136fcf0)
Location: fs/proc/generic.c:375
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff8136fcf0-ffffffff8136ff48: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360780)
Location: fs/proc/generic.c:375
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff81360780-ffffffff813609d8: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136d7c0)
Location: fs/proc/generic.c:375
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff8136d7c0-ffffffff8136da18: __proc_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct proc_dir_entry *__proc_create(struct proc_dir_entry **parent, const char *name, umode_t mode, nlink_t nlink);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813810f0)
Location: fs/proc/generic.c:375
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_create_reg
  - fs/proc/generic.c:proc_create_mount_point
  - fs/proc/generic.c:proc_mkdir_data
  - fs/proc/generic.c:proc_symlink
```
**Symbols:**

```
ffffffff813810f0-ffffffff8138134b: __proc_create (STB_LOCAL)
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
