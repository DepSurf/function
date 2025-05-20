# Function: <code>remove_huge_page</code>

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
In fs/hugetlbfs/inode.c (ffffffff812f38c3)
Location: fs/hugetlbfs/inode.c:320
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In fs/hugetlbfs/inode.c (ffffffff81327d72)
Location: fs/hugetlbfs/inode.c:320
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In fs/hugetlbfs/inode.c (ffffffff8133dabd)
Location: fs/hugetlbfs/inode.c:320
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813518b0)
Location: fs/hugetlbfs/inode.c:329
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813518b0-ffffffff813518e6: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813763c0)
Location: fs/hugetlbfs/inode.c:340
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813763c0-ffffffff813763f6: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813a4cd0)
Location: fs/hugetlbfs/inode.c:334
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813a4cd0-ffffffff813a4d06: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813bdad0)
Location: fs/hugetlbfs/inode.c:334
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813bdad0-ffffffff813bdb06: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813e83b0)
Location: fs/hugetlbfs/inode.c:348
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813e83b0-ffffffff813e83e6: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81402450)
Location: fs/hugetlbfs/inode.c:348
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81402450-ffffffff81402486: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81450ba0)
Location: fs/hugetlbfs/inode.c:394
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81450ba0-ffffffff81450bd6: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8146d0b0)
Location: fs/hugetlbfs/inode.c:394
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8146d0b0-ffffffff8146d0e6: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff814727a0)
Location: fs/hugetlbfs/inode.c:399
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff814727a0-ffffffff814727d6: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff814c9020)
Location: fs/hugetlbfs/inode.c:399
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff814c9020-ffffffff814c9056: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81555430)
Location: fs/hugetlbfs/inode.c:409
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81555430-ffffffff815554c6: remove_huge_page (STB_LOCAL)
```
</details>
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
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffff8000104e1b08)
Location: fs/hugetlbfs/inode.c:348
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffff8000104e1b08-ffff8000104e1b9c: remove_huge_page (STB_LOCAL)
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
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (c00000000061d200)
Location: fs/hugetlbfs/inode.c:348
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
c00000000061d200-c00000000061d2b0: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffe000354a7c)
Location: fs/hugetlbfs/inode.c:348
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffe000354a7c-ffffffe000354ae0: remove_huge_page (STB_LOCAL)
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
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813faa30)
Location: fs/hugetlbfs/inode.c:348
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813faa30-ffffffff813faa66: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813eb4b0)
Location: fs/hugetlbfs/inode.c:348
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813eb4b0-ffffffff813eb4e6: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813f7db0)
Location: fs/hugetlbfs/inode.c:348
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813f7db0-ffffffff813f7de6: remove_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void remove_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8140db00)
Location: fs/hugetlbfs/inode.c:348
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_error_remove_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8140db00-ffffffff8140db36: remove_huge_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
