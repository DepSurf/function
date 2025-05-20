# Function: <code>iterate_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff81220380)
Location: fs/readdir.c:24
Inline: False
Direct callers:
  - fs/readdir.c:SyS_old_readdir
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_getdents64
  - fs/compat.c:compat_SyS_old_readdir
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_getdents64
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff81220380-ffffffff8122049a: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff81247e40)
Location: fs/readdir.c:24
Inline: False
Direct callers:
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
  - fs/compat.c:compat_SyS_getdents64
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff81247e40-ffffffff81247fde: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff8125ae80)
Location: fs/readdir.c:24
Inline: False
Direct callers:
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
  - fs/compat.c:compat_SyS_getdents64
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff8125ae80-ffffffff8125b01e: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff81267880)
Location: fs/readdir.c:25
Inline: False
Direct callers:
  - fs/readdir.c:compat_SyS_getdents
  - fs/readdir.c:compat_SyS_old_readdir
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff81267880-ffffffff81267a1c: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff8128a130)
Location: fs/readdir.c:26
Inline: False
Direct callers:
  - fs/readdir.c:compat_SyS_getdents
  - fs/readdir.c:compat_SyS_old_readdir
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff8128a130-ffffffff8128a2c3: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812b04f0)
Location: fs/readdir.c:26
Inline: False
Direct callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812b04f0-ffffffff812b0685: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812c5650)
Location: fs/readdir.c:26
Inline: False
Direct callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812c5650-ffffffff812c57f2: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812e20d0)
Location: fs/readdir.c:26
Inline: False
Direct callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812e20d0-ffffffff812e2274: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812f3ba0)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812f3ba0-ffffffff812f3d44: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff8132c310)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff8132c310-ffffffff8132c4b3: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff81337910)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff81337910-ffffffff81337ac8: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff8133e070)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff8133e070-ffffffff8133e228: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff8138b9f0)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__x64_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x64_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff8138b9f0-ffffffff8138bbb8: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff8140cf50)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff8140cf50-ffffffff8140d129: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff814979f0)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff814979f0-ffffffff81497bc9: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff814cc9c0)
Location: fs/readdir.c:87
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff814cc9c0-ffffffff814ccb39: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff814ff560)
Location: fs/readdir.c:87
Inline: False
Direct callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_sys_getdents64
  - fs/readdir.c:__x64_sys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff814ff560-ffffffff814ff760: iterate_dir (STB_GLOBAL)
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
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffff80001039f1a0)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__arm64_compat_sys_getdents
  - fs/readdir.c:__arm64_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__arm64_sys_getdents
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffff80001039f1a0-ffff80001039f340: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (c0584014)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
c0584014-c0584190: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (c000000000499870)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__se_compat_sys_getdents
  - fs/readdir.c:__se_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
  - fs/readdir.c:__se_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
c000000000499870-c000000000499ae8: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffe00026a034)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__se_sys_getdents
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffe00026a034-ffffffe00026a180: iterate_dir (STB_GLOBAL)
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
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812ec180)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812ec180-ffffffff812ec324: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812dcdb0)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812dcdb0-ffffffff812dcf54: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812e9f90)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812e9f90-ffffffff812ea134: iterate_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iterate_dir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (ffffffff812faf80)
Location: fs/readdir.c:40
Inline: False
Direct callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_old_readdir
  - fs/readdir.c:__ia32_compat_sys_old_readdir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__ia32_sys_old_readdir
  - fs/readdir.c:__x64_sys_old_readdir
  - fs/ecryptfs/file.c:ecryptfs_readdir
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812faf80-ffffffff812fb124: iterate_dir (STB_GLOBAL)
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
