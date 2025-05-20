# Function: <code>__cond_resched_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aaf30)
Location: kernel/sched/core.c:4633
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810aaf30-ffffffff810aaf67: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810adbf0)
Location: kernel/sched/core.c:4884
Inline: True
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810adbf0-ffffffff810adc27: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3cf0)
Location: kernel/sched/core.c:4923
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810b3cf0-ffffffff810b3d41: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afcc0)
Location: kernel/sched/core.c:4824
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810afcc0-ffffffff810afd11: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b70a0)
Location: kernel/sched/core.c:4869
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810b70a0-ffffffff810b70ee: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bec80)
Location: kernel/sched/core.c:5008
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810bec80-ffffffff810becb9: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7f20)
Location: kernel/sched/core.c:4991
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810c7f20-ffffffff810c7f59: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cef30)
Location: kernel/sched/core.c:5444
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810cef30-ffffffff810cef6b: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8cf0)
Location: kernel/sched/core.c:5635
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810d8cf0-ffffffff810d8d2b: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1b80)
Location: kernel/sched/core.c:5868
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810e1b80-ffffffff810e1bd0: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810def60)
Location: kernel/sched/core.c:6688
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810def60-ffffffff810defb0: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0ba0)
Location: kernel/sched/core.c:6999
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810e0ba0-ffffffff810e0bf0: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f6cc0)
Location: kernel/sched/core.c:8203
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810f6cc0-ffffffff810f6d24: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110b260)
Location: kernel/sched/core.c:8335
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8110b260-ffffffff8110b2c1: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81131640)
Location: kernel/sched/core.c:8519
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff81131640-ffffffff811316a1: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113f890)
Location: kernel/sched/core.c:8629
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8113f890-ffffffff8113f8f1: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114a7f0)
Location: kernel/sched/core.c:8633
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8114a7f0-ffffffff8114a851: __cond_resched_lock (STB_GLOBAL)
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
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010138f38)
Location: kernel/sched/core.c:5635
Inline: True
Direct callers:
  - virt/kvm/arm/mmu.c:stage2_wp_range
  - virt/kvm/arm/mmu.c:stage2_wp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffff800010138f38-ffff800010138f8c: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038828c)
Location: kernel/sched/core.c:5635
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
c038828c-c038830c: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000185550)
Location: kernel/sched/core.c:5635
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
c000000000185550-c000000000185604: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e8c98)
Location: kernel/sched/core.c:5635
Inline: True
Direct callers:
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffe0000e8c98-ffffffe0000e8d24: __cond_resched_lock (STB_GLOBAL)
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
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d31c0)
Location: kernel/sched/core.c:5635
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810d31c0-ffffffff810d31fb: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c17f0)
Location: kernel/sched/core.c:5635
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810c17f0-ffffffff810c182b: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d08a0)
Location: kernel/sched/core.c:5635
Inline: True
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810d08a0-ffffffff810d08db: __cond_resched_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cond_resched_lock(spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da920)
Location: kernel/sched/core.c:5635
Inline: False
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff810da920-ffffffff810da973: __cond_resched_lock (STB_GLOBAL)
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
