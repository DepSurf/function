# Function: <code>free_pool_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811db220)
Location: mm/hugetlb.c:1379
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
```
**Symbols:**

```
ffffffff811db220-ffffffff811db30e: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f9470)
Location: mm/hugetlb.c:1406
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
```
**Symbols:**

```
ffffffff811f9470-ffffffff811f9560: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812096b0)
Location: mm/hugetlb.c:1406
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff812096b0-ffffffff812097a5: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81214f40)
Location: mm/hugetlb.c:1424
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff81214f40-ffffffff81215032: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8122fc30)
Location: mm/hugetlb.c:1430
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff8122fc30-ffffffff8122fd22: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81252090)
Location: mm/hugetlb.c:1447
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff81252090-ffffffff81252182: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81267190)
Location: mm/hugetlb.c:1448
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff81267190-ffffffff81267282: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81281610)
Location: mm/hugetlb.c:1479
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff81281610-ffffffff81281706: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81291110)
Location: mm/hugetlb.c:1559
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff81291110-ffffffff81291206: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c4c20)
Location: mm/hugetlb.c:1804
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff812c4c20-ffffffff812c4d2f: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d0990)
Location: mm/hugetlb.c:1752
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff812d0990-ffffffff812d0a9f: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032f760)
Location: mm/hugetlb.c:1559
Inline: False
Direct callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffff80001032f760-ffff80001032f8a8: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000407180)
Location: mm/hugetlb.c:1559
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
c000000000407180-c00000000040733c: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022d4fc)
Location: mm/hugetlb.c:1559
Inline: False
Direct callers:
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffe00022d4fc-ffffffe00022d5d0: free_pool_huge_page (STB_LOCAL)
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
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812896f0)
Location: mm/hugetlb.c:1559
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff812896f0-ffffffff812897e6: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127b590)
Location: mm/hugetlb.c:1559
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff8127b590-ffffffff8127b686: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81287500)
Location: mm/hugetlb.c:1559
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff81287500-ffffffff812875f6: free_pool_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int free_pool_huge_page(struct hstate *h, nodemask_t *nodes_allowed, bool acct_surplus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81297c40)
Location: mm/hugetlb.c:1559
Inline: False
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:return_unused_surplus_pages
```
**Symbols:**

```
ffffffff81297c40-ffffffff81297d36: free_pool_huge_page (STB_LOCAL)
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
