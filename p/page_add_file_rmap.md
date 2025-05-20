# Function: <code>page_add_file_rmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811cafc0)
Location: mm/rmap.c:1208
Inline: False
Direct callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff811cafc0-ffffffff811cb016: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e7e20)
Location: mm/rmap.c:1271
Inline: False
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff811e7e20-ffffffff811e7f3e: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f91a0)
Location: mm/rmap.c:1270
Inline: False
Direct callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff811f91a0-ffffffff811f92be: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81203d50)
Location: mm/rmap.c:1173
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff81203d50-ffffffff81203ec1: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121cac0)
Location: mm/rmap.c:1177
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff8121cac0-ffffffff8121cc31: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123e840)
Location: mm/rmap.c:1179
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff8123e840-ffffffff8123ea52: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81252dd0)
Location: mm/rmap.c:1181
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff81252dd0-ffffffff81252fe6: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81265180)
Location: mm/rmap.c:1182
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff81265180-ffffffff812652ed: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81273a10)
Location: mm/rmap.c:1180
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff81273a10-ffffffff81273bab: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a4e10)
Location: mm/rmap.c:1201
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_set_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff812a4e10-ffffffff812a4fc6: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b03d0)
Location: mm/rmap.c:1207
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_set_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff812b03d0-ffffffff812b050a: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b59d0)
Location: mm/rmap.c:1210
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff812b59d0-ffffffff812b5b1e: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f7660)
Location: mm/rmap.c:1211
Inline: False
Direct callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
**Symbols:**

```
ffffffff812f7660-ffffffff812f779e: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, struct vm_area_struct *vma, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135d110)
Location: mm/rmap.c:1293
Inline: False
Direct callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
**Symbols:**

```
ffffffff8135d110-ffffffff8135d3fa: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, struct vm_area_struct *vma, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d7c90)
Location: mm/rmap.c:1324
Inline: False
Direct callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
**Symbols:**

```
ffffffff813d7c90-ffffffff813d7f47: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, struct vm_area_struct *vma, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140c750)
Location: mm/rmap.c:1316
Inline: False
Direct callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
**Symbols:**

```
ffffffff8140c750-ffffffff8140c91d: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff8000103095d8)
Location: mm/rmap.c:1180
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffff8000103095d8-ffff800010309810: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c05261bc)
Location: mm/rmap.c:1180
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:insert_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
c05261bc-c0526284: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003d8c00)
Location: mm/rmap.c:1180
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
c0000000003d8c00-c0000000003d8ef8: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe000213994)
Location: mm/rmap.c:1180
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffe000213994-ffffffe000213a4e: page_add_file_rmap (STB_GLOBAL)
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
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126c060)
Location: mm/rmap.c:1180
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff8126c060-ffffffff8126c1fb: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125e0d0)
Location: mm/rmap.c:1180
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff8125e0d0-ffffffff8125e26b: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81269e00)
Location: mm/rmap.c:1180
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff81269e00-ffffffff81269f9b: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void page_add_file_rmap(struct page *page, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81279770)
Location: mm/rmap.c:1180
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:vm_insert_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff81279770-ffffffff8127990b: page_add_file_rmap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool compound</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, compound</code> ➡️ <code>page, vma, compound</code>
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
