# Function: <code>mapping_set_exiting</code>

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
In mm/truncate.c (ffffffff8119f505)
Location: include/linux/pagemap.h:57
Inline: True
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
In mm/truncate.c (ffffffff811b5235)
Location: include/linux/pagemap.h:57
Inline: True
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
In mm/truncate.c (ffffffff811c5845)
Location: include/linux/pagemap.h:58
Inline: True
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
In mm/truncate.c (ffffffff811cdb55)
Location: include/linux/pagemap.h:77
Inline: True
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
In mm/truncate.c (ffffffff811e2f0c)
Location: include/linux/pagemap.h:80
Inline: True
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
In mm/truncate.c (ffffffff81204565)
Location: include/linux/pagemap.h:80
Inline: True
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
In mm/truncate.c (ffffffff81216f25)
Location: include/linux/pagemap.h:80
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
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
In mm/truncate.c (ffffffff81226885)
Location: include/linux/pagemap.h:80
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
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
In mm/truncate.c (ffffffff812346f5)
Location: include/linux/pagemap.h:80
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
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
In mm/truncate.c (ffffffff81261cb5)
Location: include/linux/pagemap.h:81
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126bfb5)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81270eb5)
Location: include/linux/pagemap.h:88
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812ade75)
Location: include/linux/pagemap.h:88
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
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
In mm/truncate.c (ffffffff81308a65)
Location: include/linux/pagemap.h:252
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
```
```
In mm/shmem.c (ffffffff8131a42e)
Location: include/linux/pagemap.h:252
Inline: True
Inline callers:
  - mm/shmem.c:shmem_evict_inode
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
In mm/truncate.c (ffffffff81372865)
Location: include/linux/pagemap.h:252
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
```
```
In mm/shmem.c (ffffffff8138e6d8)
Location: include/linux/pagemap.h:252
Inline: True
Inline callers:
  - mm/shmem.c:shmem_evict_inode
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
In mm/truncate.c (ffffffff813a49d5)
Location: include/linux/pagemap.h:256
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
```
```
In mm/shmem.c (ffffffff813c15c5)
Location: include/linux/pagemap.h:256
Inline: True
Inline callers:
  - mm/shmem.c:shmem_evict_inode
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
In mm/truncate.c (ffffffff813ce535)
Location: include/linux/pagemap.h:260
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
```
```
In mm/shmem.c (ffffffff813ec292)
Location: include/linux/pagemap.h:260
Inline: True
Inline callers:
  - mm/shmem.c:shmem_evict_inode
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
In mm/truncate.c (ffff8000102c4c88)
Location: include/linux/pagemap.h:80
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
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
In mm/truncate.c (c04ef54c)
Location: include/linux/pagemap.h:80
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
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
In mm/truncate.c (c00000000037f3f8)
Location: include/linux/pagemap.h:80
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
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
In mm/truncate.c (ffffffe0001e53f6)
Location: include/linux/pagemap.h:80
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
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
In mm/truncate.c (ffffffff8122cd45)
Location: include/linux/pagemap.h:80
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
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
In mm/truncate.c (ffffffff8121fe25)
Location: include/linux/pagemap.h:80
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
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
In mm/truncate.c (ffffffff8122aae5)
Location: include/linux/pagemap.h:80
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
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
In mm/truncate.c (ffffffff81239ef5)
Location: include/linux/pagemap.h:80
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_final
```
</details>
</li>
</ul>

## Differences
