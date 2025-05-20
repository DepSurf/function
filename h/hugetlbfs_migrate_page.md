# Function: <code>hugetlbfs_migrate_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff812f3e70)
Location: fs/hugetlbfs/inode.c:839
Inline: False
```
**Symbols:**

```
ffffffff812f3e70-ffffffff812f3ea9: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813270e0)
Location: fs/hugetlbfs/inode.c:846
Inline: False
```
**Symbols:**

```
ffffffff813270e0-ffffffff81327119: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8133ce50)
Location: fs/hugetlbfs/inode.c:844
Inline: False
```
**Symbols:**

```
ffffffff8133ce50-ffffffff8133ce89: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81351d00)
Location: fs/hugetlbfs/inode.c:840
Inline: False
```
**Symbols:**

```
ffffffff81351d00-ffffffff81351d39: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813768a0)
Location: fs/hugetlbfs/inode.c:834
Inline: True
```
**Symbols:**

```
ffffffff813768a0-ffffffff813768f9: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813a5090)
Location: fs/hugetlbfs/inode.c:855
Inline: True
```
**Symbols:**

```
ffffffff813a5090-ffffffff813a50e0: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813bde90)
Location: fs/hugetlbfs/inode.c:853
Inline: True
```
**Symbols:**

```
ffffffff813bde90-ffffffff813bdef8: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813e8be0)
Location: fs/hugetlbfs/inode.c:879
Inline: True
```
**Symbols:**

```
ffffffff813e8be0-ffffffff813e8c48: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81402c80)
Location: fs/hugetlbfs/inode.c:879
Inline: True
```
**Symbols:**

```
ffffffff81402c80-ffffffff81402ce8: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81450750)
Location: fs/hugetlbfs/inode.c:958
Inline: True
```
**Symbols:**

```
ffffffff81450750-ffffffff814507b8: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8146cc60)
Location: fs/hugetlbfs/inode.c:959
Inline: True
```
**Symbols:**

```
ffffffff8146cc60-ffffffff8146ccc8: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81472030)
Location: fs/hugetlbfs/inode.c:959
Inline: True
```
**Symbols:**

```
ffffffff81472030-ffffffff81472098: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff814c89c0)
Location: fs/hugetlbfs/inode.c:960
Inline: True
```
**Symbols:**

```
ffffffff814c89c0-ffffffff814c8a28: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81554110)
Location: fs/hugetlbfs/inode.c:1011
Inline: True
```
**Symbols:**

```
ffffffff81554110-ffffffff81554190: hugetlbfs_migrate_page (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffff8000104e1498)
Location: fs/hugetlbfs/inode.c:879
Inline: True
```
**Symbols:**

```
ffff8000104e1498-ffff8000104e1528: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (c00000000061e220)
Location: fs/hugetlbfs/inode.c:879
Inline: True
```
**Symbols:**

```
c00000000061e220-c00000000061e2ec: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffe000355578)
Location: fs/hugetlbfs/inode.c:879
Inline: True
```
**Symbols:**

```
ffffffe000355578-ffffffe0003555e6: hugetlbfs_migrate_page (STB_LOCAL)
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
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813fb260)
Location: fs/hugetlbfs/inode.c:879
Inline: True
```
**Symbols:**

```
ffffffff813fb260-ffffffff813fb2c8: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813ebce0)
Location: fs/hugetlbfs/inode.c:879
Inline: True
```
**Symbols:**

```
ffffffff813ebce0-ffffffff813ebd48: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813f85e0)
Location: fs/hugetlbfs/inode.c:879
Inline: True
```
**Symbols:**

```
ffffffff813f85e0-ffffffff813f8648: hugetlbfs_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int hugetlbfs_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8140e3e0)
Location: fs/hugetlbfs/inode.c:879
Inline: True
```
**Symbols:**

```
ffffffff8140e3e0-ffffffff8140e448: hugetlbfs_migrate_page (STB_LOCAL)
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
