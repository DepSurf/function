# Function: <code>hugetlb_vmdelete_list</code>

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
In fs/hugetlbfs/inode.c (ffffffff812f4b0c)
Location: fs/hugetlbfs/inode.c:456
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81326f20)
Location: fs/hugetlbfs/inode.c:328
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81326f20-ffffffff81326fca: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8133cc90)
Location: fs/hugetlbfs/inode.c:328
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8133cc90-ffffffff8133cd3a: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813517f0)
Location: fs/hugetlbfs/inode.c:337
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813517f0-ffffffff81351892: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81376300)
Location: fs/hugetlbfs/inode.c:348
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81376300-ffffffff813763a2: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813a4c10)
Location: fs/hugetlbfs/inode.c:342
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813a4c10-ffffffff813a4cb2: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813bda10)
Location: fs/hugetlbfs/inode.c:342
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813bda10-ffffffff813bdab2: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813e82f0)
Location: fs/hugetlbfs/inode.c:356
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813e82f0-ffffffff813e8395: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81402390)
Location: fs/hugetlbfs/inode.c:356
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81402390-ffffffff81402435: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8144ff90)
Location: fs/hugetlbfs/inode.c:402
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8144ff90-ffffffff81450032: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8146c4a0)
Location: fs/hugetlbfs/inode.c:402
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8146c4a0-ffffffff8146c542: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81471b50)
Location: fs/hugetlbfs/inode.c:407
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81471b50-ffffffff81471bf2: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff814c8660)
Location: fs/hugetlbfs/inode.c:407
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff814c8660-ffffffff814c86f8: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end, zap_flags_t zap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81553c80)
Location: fs/hugetlbfs/inode.c:417
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff81553c80-ffffffff81553d36: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end, zap_flags_t zap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff815f61c0)
Location: fs/hugetlbfs/inode.c:523
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff815f61c0-ffffffff815f6286: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end, zap_flags_t zap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8162e150)
Location: fs/hugetlbfs/inode.c:522
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8162e150-ffffffff8162e219: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end, zap_flags_t zap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff81667610)
Location: fs/hugetlbfs/inode.c:555
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81667610-ffffffff816676d9: hugetlb_vmdelete_list (STB_LOCAL)
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
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffff8000104e07f8)
Location: fs/hugetlbfs/inode.c:356
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffff8000104e07f8-ffff8000104e08a8: hugetlb_vmdelete_list (STB_LOCAL)
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
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (c00000000061d0e0)
Location: fs/hugetlbfs/inode.c:356
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
c00000000061d0e0-c00000000061d1e4: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffe0003549d8)
Location: fs/hugetlbfs/inode.c:356
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffe0003549d8-ffffffe000354a68: hugetlb_vmdelete_list (STB_LOCAL)
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
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813fa970)
Location: fs/hugetlbfs/inode.c:356
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813fa970-ffffffff813faa15: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813eb3f0)
Location: fs/hugetlbfs/inode.c:356
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813eb3f0-ffffffff813eb495: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff813f7cf0)
Location: fs/hugetlbfs/inode.c:356
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813f7cf0-ffffffff813f7d95: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hugetlb_vmdelete_list(struct rb_root_cached *root, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff8140da40)
Location: fs/hugetlbfs/inode.c:356
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff8140da40-ffffffff8140dae5: hugetlb_vmdelete_list (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rb_root *root</code> ➡️ <code>struct rb_root_cached *root</code>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>zap_flags_t zap_flags</code>
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
