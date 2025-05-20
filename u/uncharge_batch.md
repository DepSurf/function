# Function: <code>uncharge_batch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uncharge_batch(struct mem_cgroup *memcg, long unsigned int pgpgout, long unsigned int nr_anon, long unsigned int nr_file, long unsigned int nr_huge, struct page *dummy_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fd790)
Location: mm/memcontrol.c:5422
Inline: False
Direct callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:uncharge_list
```
**Symbols:**

```
ffffffff811fd790-ffffffff811fd8f5: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uncharge_batch(struct mem_cgroup *memcg, long unsigned int pgpgout, long unsigned int nr_anon, long unsigned int nr_file, long unsigned int nr_huge, long unsigned int nr_kmem, struct page *dummy_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81221390)
Location: mm/memcontrol.c:5489
Inline: False
Direct callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:uncharge_list
```
**Symbols:**

```
ffffffff81221390-ffffffff81221537: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uncharge_batch(struct mem_cgroup *memcg, long unsigned int pgpgout, long unsigned int nr_anon, long unsigned int nr_file, long unsigned int nr_huge, long unsigned int nr_kmem, struct page *dummy_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81233b00)
Location: mm/memcontrol.c:5474
Inline: False
Direct callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:uncharge_list
```
**Symbols:**

```
ffffffff81233b00-ffffffff81233ca7: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uncharge_batch(struct mem_cgroup *memcg, long unsigned int pgpgout, long unsigned int nr_anon, long unsigned int nr_file, long unsigned int nr_kmem, long unsigned int nr_huge, long unsigned int nr_shmem, struct page *dummy_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123f370)
Location: mm/memcontrol.c:5531
Inline: False
Direct callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:uncharge_list
```
**Symbols:**

```
ffffffff8123f370-ffffffff8123f548: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125f110)
Location: mm/memcontrol.c:5630
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffff8125f110-ffffffff8125f2b7: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812834c0)
Location: mm/memcontrol.c:5698
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffff812834c0-ffffffff8128377d: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81297030)
Location: mm/memcontrol.c:6029
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffff81297030-ffffffff812972ed: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b2c70)
Location: mm/memcontrol.c:6321
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffff812b2c70-ffffffff812b2df6: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c4740)
Location: mm/memcontrol.c:6661
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffff812c4740-ffffffff812c48c6: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f97e0)
Location: mm/memcontrol.c:6537
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffff812f97e0-ffffffff812f9924: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81305570)
Location: mm/memcontrol.c:6795
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff81305570-ffffffff813056af: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130cba0)
Location: mm/memcontrol.c:6655
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffff8130cba0-ffffffff8130ccd3: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81357520)
Location: mm/memcontrol.c:6839
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_list
  - mm/memcontrol.c:__mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffff81357520-ffffffff81357646: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d0aa0)
Location: mm/memcontrol.c:6829
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_list
  - mm/memcontrol.c:__mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_folio
```
**Symbols:**

```
ffffffff813d0aa0-ffffffff813d0be2: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81455990)
Location: mm/memcontrol.c:7018
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_list
  - mm/memcontrol.c:__mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_folio
```
**Symbols:**

```
ffffffff81455990-ffffffff81455ad2: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148b7b0)
Location: mm/memcontrol.c:7086
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_list
  - mm/memcontrol.c:__mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_folio
```
**Symbols:**

```
ffffffff8148b7b0-ffffffff8148b8f2: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bb040)
Location: mm/memcontrol.c:7413
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_list
  - mm/memcontrol.c:__mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_folio
```
**Symbols:**

```
ffffffff814bb040-ffffffff814bb182: uncharge_batch (STB_LOCAL)
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
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010367368)
Location: mm/memcontrol.c:6661
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffff800010367368-ffff8000103674f8: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0558a8c)
Location: mm/memcontrol.c:6661
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
c0558a8c-c0558c6c: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000454860)
Location: mm/memcontrol.c:6661
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
c000000000454860-c000000000454acc: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000245512)
Location: mm/memcontrol.c:6661
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffe000245512-ffffffe0002456c6: uncharge_batch (STB_LOCAL)
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
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bcd20)
Location: mm/memcontrol.c:6661
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffff812bcd20-ffffffff812bcea6: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ade70)
Location: mm/memcontrol.c:6661
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffff812ade70-ffffffff812adfe2: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bab30)
Location: mm/memcontrol.c:6661
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffff812bab30-ffffffff812bacb6: uncharge_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uncharge_batch(const struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cb270)
Location: mm/memcontrol.c:6661
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:uncharge_page
```
**Symbols:**

```
ffffffff812cb270-ffffffff812cb406: uncharge_batch (STB_LOCAL)
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
<code>long unsigned int nr_kmem</code>
</li>
<li>
<b>Param reordered. </b>
<code>memcg, pgpgout, nr_anon, nr_file, nr_huge, dummy_page</code> ➡️ <code>memcg, pgpgout, nr_anon, nr_file, nr_huge, nr_kmem, dummy_page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int nr_shmem</code>
</li>
<li>
<b>Param reordered. </b>
<code>memcg, pgpgout, nr_anon, nr_file, nr_huge, nr_kmem, dummy_page</code> ➡️ <code>memcg, pgpgout, nr_anon, nr_file, nr_kmem, nr_huge, nr_shmem, dummy_page</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct uncharge_gather *ug</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup *memcg</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int pgpgout</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_anon</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_file</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_kmem</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_huge</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_shmem</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *dummy_page</code>
</li>
</ul>
</details>
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
