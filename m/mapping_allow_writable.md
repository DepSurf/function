# Function: <code>mapping_allow_writable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a8ad4)
Location: include/linux/fs.h:556
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bf8bb)
Location: include/linux/fs.h:559
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d000f)
Location: include/linux/fs.h:510
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d9762)
Location: include/linux/fs.h:521
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811eea1f)
Location: include/linux/fs.h:525
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff8129453f)
Location: include/linux/fs.h:527
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812a9271)
Location: include/linux/fs.h:564
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812c5995)
Location: include/linux/fs.h:576
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812d73a5)
Location: include/linux/fs.h:583
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff8130c315)
Location: include/linux/fs.h:601
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0cff)
Location: include/linux/fs.h:565
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff812a38a9)
Location: include/linux/fs.h:565
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_file
```
```
In mm/memfd.c (ffffffff81318258)
Location: include/linux/fs.h:565
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1a76)
Location: include/linux/fs.h:566
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff812a90d9)
Location: include/linux/fs.h:566
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_file
```
```
In mm/memfd.c (ffffffff8131e445)
Location: include/linux/fs.h:566
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b3636)
Location: include/linux/fs.h:573
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff812ea732)
Location: include/linux/fs.h:573
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_file
```
```
In mm/memfd.c (ffffffff8136b81b)
Location: include/linux/fs.h:573
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9876)
Location: include/linux/fs.h:528
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff8134d392)
Location: include/linux/fs.h:528
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_file
```
```
In mm/memfd.c (ffffffff813e9996)
Location: include/linux/fs.h:528
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e6e79)
Location: include/linux/fs.h:543
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff813cbc88)
Location: include/linux/fs.h:543
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
```
```
In mm/memfd.c (ffffffff814719b6)
Location: include/linux/fs.h:543
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f28bf)
Location: include/linux/fs.h:558
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff81400504)
Location: include/linux/fs.h:558
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_link
```
```
In mm/memfd.c (ffffffff814a6312)
Location: include/linux/fs.h:558
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fb673)
Location: include/linux/fs.h:591
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff8142c72a)
Location: include/linux/fs.h:591
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_link
```
```
In mm/memfd.c (ffffffff814d7262)
Location: include/linux/fs.h:591
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffff80001037c5d4)
Location: include/linux/fs.h:583
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (c0566f2c)
Location: include/linux/fs.h:583
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (c000000000471820)
Location: include/linux/fs.h:583
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffe00025296a)
Location: include/linux/fs.h:583
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812cf985)
Location: include/linux/fs.h:583
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812c0605)
Location: include/linux/fs.h:583
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812cd795)
Location: include/linux/fs.h:583
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812de5a5)
Location: include/linux/fs.h:583
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
</ul>

## Differences
