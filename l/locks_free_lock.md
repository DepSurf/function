# Function: <code>locks_free_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8125f820)
Location: fs/locks.c:286
Inline: False
Direct callers:
  - fs/locks.c:locks_dispose_list
  - fs/locks.c:lease_alloc
  - fs/locks.c:__posix_lock_file
  - fs/locks.c:__posix_lock_file
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:__break_lease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:SyS_flock
  - fs/locks.c:fcntl_setlk
```
**Symbols:**

```
ffffffff8125f820-ffffffff8125f871: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128b8a0)
Location: fs/locks.c:313
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:SyS_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffff8128b8a0-ffffffff8128b8fa: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a06a0)
Location: fs/locks.c:323
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:SyS_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffff812a06a0-ffffffff812a06fa: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812af4e0)
Location: fs/locks.c:323
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:SyS_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffff812af4e0-ffffffff812af53a: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d2f60)
Location: fs/locks.c:340
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:SyS_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffff812d2f60-ffffffff812d2fba: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fd850)
Location: fs/locks.c:340
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffff812fd850-ffffffff812fd8aa: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813130e0)
Location: fs/locks.c:372
Inline: False
Direct callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffff813130e0-ffffffff81313149: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133e5f8)
Location: fs/locks.c:379
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffff8133a990-ffffffff8133a9b6: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81356be8)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffff81352ec0-ffffffff81352ee6: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139e0dc)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff81399680-ffffffff813996a8: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813afa6c)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:generic_delete_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff813ab160-ffffffff813ab188: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b6cfc)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff813b2630-ffffffff813b2658: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814069fc)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
```
**Symbols:**

```
ffffffff814024f0-ffffffff81402518: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8147b545)
Location: fs/locks.c:332
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__do_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81476e90-ffffffff81476ebf: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150e0d5)
Location: fs/locks.c:332
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff815096e0-ffffffff8150970f: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815458a8)
Location: fs/locks.c:333
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81540ca0-ffffffff81540ccf: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157ae08)
Location: fs/locks.c:332
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81576180-ffffffff815761af: locks_free_lock (STB_GLOBAL)
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
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff8000104196fc)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__arm64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffff800010414938-ffff800010414974: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e5abc)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_getlk64
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__se_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
c05e1434-c05e1468: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000529224)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__se_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
c0000000005236d0-c000000000523718: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bfeb6)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__se_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffe0002bc634-ffffffe0002bc670: locks_free_lock (STB_GLOBAL)
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
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134f1c8)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffff8134b4a0-ffffffff8134b4c6: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133fea8)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffff8133c180-ffffffff8133c1a6: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134cc98)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffff81348f70-ffffffff81348f96: locks_free_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void locks_free_lock(struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813601d6)
Location: fs/locks.c:380
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__ia32_sys_flock
  - fs/locks.c:__x64_sys_flock
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:fcntl_setlease
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:lease_alloc
  - fs/locks.c:locks_dispose_list
```
**Symbols:**

```
ffffffff8135c3a0-ffffffff8135c3c6: locks_free_lock (STB_GLOBAL)
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
