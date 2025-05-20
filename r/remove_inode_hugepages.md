# Function: <code>remove_inode_hugepages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff812f3760)
Location: fs/hugetlbfs/inode.c:349
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812f3760-ffffffff812f3ab8: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81327be0)
Location: fs/hugetlbfs/inode.c:386
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff81327be0-ffffffff8132802d: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8133d920)
Location: fs/hugetlbfs/inode.c:386
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff8133d920-ffffffff8133dd80: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81352640)
Location: fs/hugetlbfs/inode.c:395
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff81352640-ffffffff81352a19: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813771a0)
Location: fs/hugetlbfs/inode.c:406
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff813771a0-ffffffff81377542: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813a5dc0)
Location: fs/hugetlbfs/inode.c:400
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff813a5dc0-ffffffff813a617e: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813be7e0)
Location: fs/hugetlbfs/inode.c:400
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff813be7e0-ffffffff813beba4: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813e9080)
Location: fs/hugetlbfs/inode.c:414
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff813e9080-ffffffff813e9432: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81403120)
Location: fs/hugetlbfs/inode.c:414
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff81403120-ffffffff814034d2: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81450d70)
Location: fs/hugetlbfs/inode.c:459
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff81450d70-ffffffff81451189: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8146d290)
Location: fs/hugetlbfs/inode.c:459
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff8146d290-ffffffff8146d6a6: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81472960)
Location: fs/hugetlbfs/inode.c:464
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff81472960-ffffffff81472d1a: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:465
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff814c9410-ffffffff814c9821: remove_inode_hugepages (STB_LOCAL)
ffffffff81ccf534-ffffffff81ccf609: remove_inode_hugepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:476
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff81555540-ffffffff815559ed: remove_inode_hugepages (STB_LOCAL)
ffffffff81e8271c-ffffffff81e82808: remove_inode_hugepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:616
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff815f6990-ffffffff815f6c5a: remove_inode_hugepages (STB_LOCAL)
ffffffff82071959-ffffffff820719bb: remove_inode_hugepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:614
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff8162ea50-ffffffff8162ed12: remove_inode_hugepages (STB_LOCAL)
ffffffff820f15c1-ffffffff820f1623: remove_inode_hugepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/hugetlbfs/inode.c (0)
Location: fs/hugetlbfs/inode.c:647
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff81667f20-ffffffff81668201: remove_inode_hugepages (STB_LOCAL)
ffffffff821ce85b-ffffffff821ce8a2: remove_inode_hugepages.cold (STB_LOCAL)
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
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffff8000104e1c10)
Location: fs/hugetlbfs/inode.c:414
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffff8000104e1c10-ffff8000104e1f7c: remove_inode_hugepages (STB_LOCAL)
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
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (c00000000061e560)
Location: fs/hugetlbfs/inode.c:414
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
c00000000061e560-c00000000061e9f4: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffe0003557e4)
Location: fs/hugetlbfs/inode.c:414
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffe0003557e4-ffffffe000355aac: remove_inode_hugepages (STB_LOCAL)
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
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813fb700)
Location: fs/hugetlbfs/inode.c:414
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff813fb700-ffffffff813fbab2: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813ec180)
Location: fs/hugetlbfs/inode.c:414
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff813ec180-ffffffff813ec532: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813f8a80)
Location: fs/hugetlbfs/inode.c:414
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff813f8a80-ffffffff813f8e32: remove_inode_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void remove_inode_hugepages(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8140e8d0)
Location: fs/hugetlbfs/inode.c:414
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_evict_inode
```
**Symbols:**

```
ffffffff8140e8d0-ffffffff8140ec76: remove_inode_hugepages (STB_LOCAL)
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
