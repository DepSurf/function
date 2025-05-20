# Function: <code>downgrade_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810c9fd0)
Location: kernel/locking/rwsem.c:102
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff810c9fd0-ffffffff810c9ffb: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810ce910)
Location: kernel/locking/rwsem.c:124
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff810ce910-ffffffff810ce942: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810d5550)
Location: kernel/locking/rwsem.c:124
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/ext4/file.c:ext4_file_write_iter
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff810d5550-ffffffff810d5582: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810d4520)
Location: kernel/locking/rwsem.c:125
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff810d4520-ffffffff810d4552: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810dc480)
Location: kernel/locking/rwsem.c:142
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff810dc480-ffffffff810dc4b2: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810e4ac0)
Location: kernel/locking/rwsem.c:144
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff810e4ac0-ffffffff810e4af5: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f00f0)
Location: kernel/locking/rwsem.c:145
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff810f00f0-ffffffff810f0124: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f7d70)
Location: kernel/locking/rwsem.c:1560
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff810f7d70-ffffffff810f7e36: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81103ba0)
Location: kernel/locking/rwsem.c:1594
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff81103ba0-ffffffff81103c66: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110e730)
Location: kernel/locking/rwsem.c:1591
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff8110e730-ffffffff8110e7f6: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110b9b0)
Location: kernel/locking/rwsem.c:1466
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff8110b9b0-ffffffff8110ba76: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8110d7d0)
Location: kernel/locking/rwsem.c:1466
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff8110d7d0-ffffffff8110d896: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8112d030)
Location: kernel/locking/rwsem.c:1583
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/sparse-vmemmap.c:vmemmap_remap_free
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff8112d030-ffffffff8112d0f6: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8114e340)
Location: kernel/locking/rwsem.c:1612
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff8114e340-ffffffff8114e410: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8117d2d0)
Location: kernel/locking/rwsem.c:1633
Inline: False
Direct callers:
  - mm/mmap.c:do_mas_align_munmap
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff8117d2d0-ffffffff8117d3a0: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8118df80)
Location: kernel/locking/rwsem.c:1633
Inline: False
Direct callers:
  - mm/memory.c:lock_mm_and_find_vma
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_stack
  - fs/exec.c:get_arg_page
  - fs/readdir.c:wrap_directory_iterator
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff8118df80-ffffffff8118e071: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8119c930)
Location: kernel/locking/rwsem.c:1639
Inline: False
Direct callers:
  - mm/memory.c:lock_mm_and_find_vma
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_stack
  - fs/exec.c:get_arg_page
  - fs/readdir.c:wrap_directory_iterator
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff8119c930-ffffffff8119ca21: downgrade_write (STB_GLOBAL)
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
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffff800010169678)
Location: kernel/locking/rwsem.c:1594
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffff800010169678-ffff8000101697d8: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c03b55d0)
Location: kernel/locking/rwsem.c:1594
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
c03b55d0-c03b56c4: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c0000000001c0e80)
Location: kernel/locking/rwsem.c:1594
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
c0000000001c0e80-c0000000001c0fb8: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffe00010aa4e)
Location: kernel/locking/rwsem.c:1594
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffe00010aa4e-ffffffe00010aaf4: downgrade_write (STB_GLOBAL)
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
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fceb0)
Location: kernel/locking/rwsem.c:1594
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff810fceb0-ffffffff810fcf76: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810ed0c0)
Location: kernel/locking/rwsem.c:1594
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff810ed0c0-ffffffff810ed186: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fa070)
Location: kernel/locking/rwsem.c:1594
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff810fa070-ffffffff810fa136: downgrade_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void downgrade_write(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff811051e0)
Location: kernel/locking/rwsem.c:1594
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - fs/proc/task_mmu.c:clear_refs_write
  - security/keys/key.c:unregister_key_type
```
**Symbols:**

```
ffffffff811051e0-ffffffff811052a6: downgrade_write (STB_GLOBAL)
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
