# Function: <code>shmem_file_setup_with_mnt</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811eda20)
Location: mm/shmem.c:4303
Inline: True
```
**Symbols:**

```
ffffffff811eda20-ffffffff811eda4e: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812106f0)
Location: mm/shmem.c:4019
Inline: True
```
**Symbols:**

```
ffffffff812106f0-ffffffff8121071c: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812259f0)
Location: mm/shmem.c:3978
Inline: True
```
**Symbols:**

```
ffffffff812259f0-ffffffff81225a1c: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81232bb0)
Location: mm/shmem.c:4059
Inline: True
```
**Symbols:**

```
ffffffff81232bb0-ffffffff81232bdd: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81240dd0)
Location: mm/shmem.c:4181
Inline: True
```
**Symbols:**

```
ffffffff81240dd0-ffffffff81240dfd: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81271df0)
Location: mm/shmem.c:4144
Inline: False
```
**Symbols:**

```
ffffffff81271df0-ffffffff81271e03: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81278d30)
Location: mm/shmem.c:4251
Inline: False
```
**Symbols:**

```
ffffffff81278d30-ffffffff81278d43: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127dce0)
Location: mm/shmem.c:4195
Inline: False
```
**Symbols:**

```
ffffffff8127dce0-ffffffff8127dcf3: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bbbf0)
Location: mm/shmem.c:4131
Inline: False
```
**Symbols:**

```
ffffffff812bbbf0-ffffffff812bbc03: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81316920)
Location: mm/shmem.c:4143
Inline: False
```
**Symbols:**

```
ffffffff81316920-ffffffff81316942: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138b2d0)
Location: mm/shmem.c:4272
Inline: False
```
**Symbols:**

```
ffffffff8138b2d0-ffffffff8138b2f2: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bc9e0)
Location: mm/shmem.c:4481
Inline: False
```
**Symbols:**

```
ffffffff813bc9e0-ffffffff813bca02: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e8cd0)
Location: mm/shmem.c:4856
Inline: False
```
**Symbols:**

```
ffffffff813e8cd0-ffffffff813e8cf2: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d2928)
Location: mm/shmem.c:4181
Inline: True
```
**Symbols:**

```
ffff8000102d2928-ffff8000102d299c: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fa408)
Location: mm/shmem.c:4181
Inline: False
```
**Symbols:**

```
c04fa408-c04fa438: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000390350)
Location: mm/shmem.c:4181
Inline: True
```
**Symbols:**

```
c000000000390350-c000000000390388: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ef5ca)
Location: mm/shmem.c:4181
Inline: True
```
**Symbols:**

```
ffffffe0001ef5ca-ffffffe0001ef62c: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81239420)
Location: mm/shmem.c:4181
Inline: True
```
**Symbols:**

```
ffffffff81239420-ffffffff8123944d: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122c460)
Location: mm/shmem.c:4181
Inline: True
```
**Symbols:**

```
ffffffff8122c460-ffffffff8122c48d: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812371c0)
Location: mm/shmem.c:4181
Inline: True
```
**Symbols:**

```
ffffffff812371c0-ffffffff812371ed: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct file *shmem_file_setup_with_mnt(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81244f70)
Location: mm/shmem.c:4181
Inline: True
```
**Symbols:**

```
ffffffff81244f70-ffffffff81244f9d: shmem_file_setup_with_mnt (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
