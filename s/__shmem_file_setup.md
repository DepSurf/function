# Function: <code>__shmem_file_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *__shmem_file_setup(const char *name, loff_t size, long unsigned int flags, unsigned int i_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a7dd0)
Location: mm/shmem.c:3347
Inline: False
Direct callers:
  - mm/shmem.c:SyS_memfd_create
  - mm/shmem.c:shmem_kernel_file_setup
  - mm/shmem.c:shmem_zero_setup
```
**Symbols:**

```
ffffffff811a7dd0-ffffffff811a800e: __shmem_file_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *__shmem_file_setup(const char *name, loff_t size, long unsigned int flags, unsigned int i_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bee20)
Location: mm/shmem.c:4108
Inline: False
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_kernel_file_setup
  - mm/shmem.c:SyS_memfd_create
```
**Symbols:**

```
ffffffff811bee20-ffffffff811bf062: __shmem_file_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *__shmem_file_setup(const char *name, loff_t size, long unsigned int flags, unsigned int i_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cea80)
Location: mm/shmem.c:4002
Inline: False
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_kernel_file_setup
  - mm/shmem.c:SyS_memfd_create
```
**Symbols:**

```
ffffffff811cea80-ffffffff811cecc2: __shmem_file_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff811dd33b)
Location: mm/shmem.c:4167
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_kernel_file_setup
  - mm/shmem.c:SyS_memfd_create
  - mm/shmem.c:SyS_memfd_create
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_kernel_file_setup
  - mm/shmem.c:SyS_memfd_create
```
**Symbols:**

```
ffffffff811d8270-ffffffff811d8473: __shmem_file_setup.part.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff811f2dca)
Location: mm/shmem.c:4213
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:SyS_memfd_create
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:SyS_memfd_create
```
**Symbols:**

```
ffffffff811ed7d0-ffffffff811ed9d7: __shmem_file_setup.part.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff81213fd6)
Location: mm/shmem.c:3929
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff812104a0-ffffffff812106a4: __shmem_file_setup.part.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff812259bc)
Location: mm/shmem.c:3911
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_setup
Direct callers:
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff81225870-ffffffff812259a4: __shmem_file_setup.part.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff81232b7c)
Location: mm/shmem.c:3992
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_setup
Direct callers:
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff81232a30-ffffffff81232b62: __shmem_file_setup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff81240d9c)
Location: mm/shmem.c:4114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_setup
Direct callers:
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff81240c50-ffffffff81240d82: __shmem_file_setup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct file *__shmem_file_setup(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags, unsigned int i_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81271c50)
Location: mm/shmem.c:4077
Inline: True
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup_with_mnt
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff81271c50-ffffffff81271db7: __shmem_file_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct file *__shmem_file_setup(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags, unsigned int i_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81278b90)
Location: mm/shmem.c:4184
Inline: True
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup_with_mnt
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff81278b90-ffffffff81278cf7: __shmem_file_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct file *__shmem_file_setup(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags, unsigned int i_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127db40)
Location: mm/shmem.c:4128
Inline: True
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup_with_mnt
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff8127db40-ffffffff8127dca7: __shmem_file_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct file *__shmem_file_setup(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags, unsigned int i_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bba50)
Location: mm/shmem.c:4064
Inline: True
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup_with_mnt
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff812bba50-ffffffff812bbbb7: __shmem_file_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct file *__shmem_file_setup(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags, unsigned int i_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81316770)
Location: mm/shmem.c:4076
Inline: True
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup_with_mnt
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff81316770-ffffffff813168e0: __shmem_file_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct file *__shmem_file_setup(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags, unsigned int i_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138b100)
Location: mm/shmem.c:4205
Inline: True
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup_with_mnt
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff8138b100-ffffffff8138b270: __shmem_file_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct file *__shmem_file_setup(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags, unsigned int i_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bc7e0)
Location: mm/shmem.c:4411
Inline: True
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup_with_mnt
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff813bc7e0-ffffffff813bc971: __shmem_file_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct file *__shmem_file_setup(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags, unsigned int i_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e8ae0)
Location: mm/shmem.c:4786
Inline: True
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup_with_mnt
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff813e8ae0-ffffffff813e8c70: __shmem_file_setup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffff8000102d28e4)
Location: mm/shmem.c:4114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_setup
Direct callers:
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffff8000102d2770-ffff8000102d28b8: __shmem_file_setup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct file *__shmem_file_setup(struct vfsmount *mnt, const char *name, loff_t size, long unsigned int flags, unsigned int i_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fa254)
Location: mm/shmem.c:4114
Inline: True
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup_with_mnt
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
c04fa254-c04fa3c8: __shmem_file_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (c0000000003903c4)
Location: mm/shmem.c:4114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
c000000000390120-c0000000003902e8: __shmem_file_setup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffe0001ef652)
Location: mm/shmem.c:4114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffe0001ef466-ffffffe0001ef56c: __shmem_file_setup.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff812393ec)
Location: mm/shmem.c:4114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_setup
Direct callers:
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff812392a0-ffffffff812393d2: __shmem_file_setup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff8122c42c)
Location: mm/shmem.c:4114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_setup
Direct callers:
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff8122c2e0-ffffffff8122c412: __shmem_file_setup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff8123718c)
Location: mm/shmem.c:4114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_setup
Direct callers:
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff81237040-ffffffff81237172: __shmem_file_setup.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/shmem.c (ffffffff81244f3c)
Location: mm/shmem.c:4114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_setup
Direct callers:
  - mm/shmem.c:shmem_file_setup
```
**Symbols:**

```
ffffffff81244df0-ffffffff81244f22: __shmem_file_setup.part.0 (STB_LOCAL)
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
</ul>
