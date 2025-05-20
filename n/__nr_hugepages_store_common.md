# Function: <code>__nr_hugepages_store_common</code>

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
In mm/hugetlb.c (ffffffff811dc08e)
Location: mm/hugetlb.c:2261
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
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
In mm/hugetlb.c (ffffffff811fa4ab)
Location: mm/hugetlb.c:2312
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120a7a0)
Location: mm/hugetlb.c:2418
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff8120a7a0-ffffffff8120ad7b: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81215b20)
Location: mm/hugetlb.c:2396
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81215b20-ffffffff812160fa: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81230750)
Location: mm/hugetlb.c:2404
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81230750-ffffffff81230daa: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81252f30)
Location: mm/hugetlb.c:2406
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81252f30-ffffffff81253221: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812679a0)
Location: mm/hugetlb.c:2400
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff812679a0-ffffffff81267c82: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81282110)
Location: mm/hugetlb.c:2477
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81282110-ffffffff812823f0: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81291b90)
Location: mm/hugetlb.c:2594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81291b90-ffffffff81291f0f: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c5300)
Location: mm/hugetlb.c:2877
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff812c5300-ffffffff812c53c4: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d0f10)
Location: mm/hugetlb.c:2830
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff812d0f10-ffffffff812d0fd4: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d7cf0)
Location: mm/hugetlb.c:2995
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff812d7cf0-ffffffff812d7db4: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8131e700)
Location: mm/hugetlb.c:3280
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff8131e700-ffffffff8131e7c4: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138a850)
Location: mm/hugetlb.c:3552
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff8138a850-ffffffff8138a932: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140a2b0)
Location: mm/hugetlb.c:3720
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff8140a2b0-ffffffff8140a392: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143d910)
Location: mm/hugetlb.c:3750
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff8143d910-ffffffff8143d9f2: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff814758d0)
Location: mm/hugetlb.c:4008
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_mempolicy_store
  - mm/hugetlb.c:nr_hugepages_store
```
**Symbols:**

```
ffffffff814758d0-ffffffff814759b2: __nr_hugepages_store_common (STB_LOCAL)
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
In mm/hugetlb.c (ffff80001032ff5c)
Location: mm/hugetlb.c:2594
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000408210)
Location: mm/hugetlb.c:2594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
c000000000408210-c00000000040875c: __nr_hugepages_store_common (STB_LOCAL)
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
In mm/hugetlb.c (ffffffe00022eea4)
Location: mm/hugetlb.c:2594
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler
  - mm/hugetlb.c:nr_hugepages_store
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
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128a170)
Location: mm/hugetlb.c:2594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff8128a170-ffffffff8128a4ef: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127bfa0)
Location: mm/hugetlb.c:2594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff8127bfa0-ffffffff8127c31f: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81287f80)
Location: mm/hugetlb.c:2594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81287f80-ffffffff812882ff: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t __nr_hugepages_store_common(bool obey_mempolicy, struct hstate *h, int nid, long unsigned int count, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812983c0)
Location: mm/hugetlb.c:2594
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff812983c0-ffffffff8129871e: __nr_hugepages_store_common (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
