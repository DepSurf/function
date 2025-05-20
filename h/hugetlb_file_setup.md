# Function: <code>hugetlb_file_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff812f4fb0)
Location: fs/hugetlbfs/inode.c:1235
Inline: False
Direct callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff812f4fb0-ffffffff812f5307: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813289b0)
Location: fs/hugetlbfs/inode.c:1241
Inline: False
Direct callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff813289b0-ffffffff81328d19: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8133e6f0)
Location: fs/hugetlbfs/inode.c:1239
Inline: False
Direct callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff8133e6f0-ffffffff8133ea59: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813532d0)
Location: fs/hugetlbfs/inode.c:1300
Inline: False
Direct callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff813532d0-ffffffff8135361b: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81377ef0)
Location: fs/hugetlbfs/inode.c:1300
Inline: False
Direct callers:
  - mm/shmem.c:SyS_memfd_create
  - mm/mmap.c:SyS_mmap_pgoff
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81377ef0-ffffffff8137823b: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1321
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff813a6cb4-ffffffff813a6cd9: hugetlb_file_setup.cold.26 (STB_LOCAL)
ffffffff813a6930-ffffffff813a6c2b: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1327
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff813bfaa4-ffffffff813bfaca: hugetlb_file_setup.cold.26 (STB_LOCAL)
ffffffff813bf7c0-ffffffff813bfa34: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1367
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff813ea29d-ffffffff813ea2c3: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff813ea000-ffffffff813ea26a: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1367
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff8140433d-ffffffff81404363: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff814040a0-ffffffff8140430a: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1453
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__do_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff8145217d-ffffffff814521a3: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff81451ee0-ffffffff8145214a: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1454
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__do_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81bed739-ffffffff81bed75f: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff8146e420-ffffffff8146e68a: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1448
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__do_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81bdf83c-ffffffff81bdf862: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff81473a60-ffffffff81473cca: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct ucounts **ucounts, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1449
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__do_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81ccf778-ffffffff81ccf7f8: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff814ca680-ffffffff814ca95c: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1500
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__do_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81e8294e-ffffffff81e829ce: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff81556640-ffffffff815568d7: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1576
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__do_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff82071c62-ffffffff82071cb4: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff815f8140-ffffffff815f8448: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1571
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__do_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff820f18f7-ffffffff820f1949: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff816300c0-ffffffff816303c8: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1593
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__do_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff821cebd9-ffffffff821cec2b: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff81669570-ffffffff81669878: hugetlb_file_setup (STB_GLOBAL)
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
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffff8000104e28f8)
Location: fs/hugetlbfs/inode.c:1367
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__arm64_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffff8000104e28f8-ffff8000104e2bd4: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (0)
Location: include/linux/hugetlb.h:306
Inline: True
```
```
In mm/memfd.c (0)
Location: include/linux/hugetlb.h:306
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/hugetlb.h:306
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (c00000000061fa40)
Location: fs/hugetlbfs/inode.c:1367
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__se_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
c00000000061fa40-c00000000061fdfc: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffe00035643a)
Location: fs/hugetlbfs/inode.c:1367
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__se_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffe00035643a-ffffffe00035667e: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1367
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff813fc91d-ffffffff813fc943: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff813fc680-ffffffff813fc8ea: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1367
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff813ed39d-ffffffff813ed3c3: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff813ed100-ffffffff813ed36a: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1367
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff813f9c9d-ffffffff813f9cc3: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff813f9a00-ffffffff813f9c6a: hugetlb_file_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct file *hugetlb_file_setup(const char *name, size_t size, vm_flags_t acctflag, struct user_struct **user, int creat_flags, int page_size_log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:1367
Inline: False
Direct callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/memfd.c:__ia32_sys_memfd_create
  - mm/memfd.c:__x64_sys_memfd_create
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff8140f8eb-ffffffff8140f911: hugetlb_file_setup.cold (STB_LOCAL)
ffffffff8140f650-ffffffff8140f8b8: hugetlb_file_setup (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ucounts **ucounts</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_struct **user</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct ucounts **ucounts</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, size, acctflag, ucounts, creat_flags, page_size_log</code> ➡️ <code>name, size, acctflag, creat_flags, page_size_log</code>
</li>
</ul>
</details>
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
