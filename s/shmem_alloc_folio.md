# Function: <code>shmem_alloc_folio</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct folio *shmem_alloc_folio(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81316500)
Location: mm/shmem.c:1541
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
**Symbols:**

```
ffffffff81316500-ffffffff813165a4: shmem_alloc_folio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct folio *shmem_alloc_folio(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138a9e0)
Location: mm/shmem.c:1562
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
**Symbols:**

```
ffffffff8138a9e0-ffffffff8138aaaf: shmem_alloc_folio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct folio *shmem_alloc_folio(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bcf40)
Location: mm/shmem.c:1574
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
**Symbols:**

```
ffffffff813bcf40-ffffffff813bcfeb: shmem_alloc_folio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct folio *shmem_alloc_folio(gfp_t gfp, struct shmem_inode_info *info, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e7d90)
Location: mm/shmem.c:1620
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
```
**Symbols:**

```
ffffffff813e7d90-ffffffff813e7e56: shmem_alloc_folio (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
