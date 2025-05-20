# Function: <code>shmem_undo_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a9860)
Location: mm/shmem.c:400
Inline: False
Direct callers:
  - mm/shmem.c:shmem_truncate_range
  - mm/shmem.c:shmem_fallocate
```
**Symbols:**

```
ffffffff811a9860-ffffffff811a9ff0: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c1d50)
Location: mm/shmem.c:743
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffff811c1d50-ffffffff811c27c3: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d1e20)
Location: mm/shmem.c:749
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffff811d1e20-ffffffff811d286c: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811da8e0)
Location: mm/shmem.c:765
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffff811da8e0-ffffffff811db1c5: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f06b0)
Location: mm/shmem.c:788
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffff811f06b0-ffffffff811f0fc5: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81212200)
Location: mm/shmem.c:797
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffff81212200-ffffffff81212b03: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81223cc0)
Location: mm/shmem.c:776
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffff81223cc0-ffffffff812245bd: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812342e0)
Location: mm/shmem.c:783
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffff812342e0-ffffffff81234c00: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81242510)
Location: mm/shmem.c:798
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffff81242510-ffffffff81242e39: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126fcd0)
Location: mm/shmem.c:840
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
**Symbols:**

```
ffffffff8126fcd0-ffffffff8127053d: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127aeb0)
Location: mm/shmem.c:899
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
**Symbols:**

```
ffffffff8127aeb0-ffffffff8127b624: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81280040)
Location: mm/shmem.c:890
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
**Symbols:**

```
ffffffff81280040-ffffffff8128078c: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812be340)
Location: mm/shmem.c:920
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
**Symbols:**

```
ffffffff812be340-ffffffff812beba3: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:912
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
**Symbols:**

```
ffffffff81319a90-ffffffff8131a2dd: shmem_undo_range (STB_LOCAL)
ffffffff81e6c364-ffffffff81e6c398: shmem_undo_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:906
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
**Symbols:**

```
ffffffff8138dd20-ffffffff8138e588: shmem_undo_range (STB_LOCAL)
ffffffff82062e1b-ffffffff82062e4f: shmem_undo_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:915
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
**Symbols:**

```
ffffffff813c0ca0-ffffffff813c1477: shmem_undo_range (STB_LOCAL)
ffffffff820e26e7-ffffffff820e271b: shmem_undo_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:964
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
**Symbols:**

```
ffffffff813eb8f0-ffffffff813ec103: shmem_undo_range (STB_LOCAL)
ffffffff821bf0da-ffffffff821bf10c: shmem_undo_range.cold (STB_LOCAL)
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
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d4850)
Location: mm/shmem.c:798
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffff8000102d4850-ffff8000102d5050: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fcb70)
Location: mm/shmem.c:798
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
c04fcb70-c04fd1b0: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000394110)
Location: mm/shmem.c:798
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
c000000000394110-c000000000394cb0: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001f0732)
Location: mm/shmem.c:798
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffe0001f0732-ffffffe0001f0cfc: shmem_undo_range (STB_LOCAL)
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
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123ab60)
Location: mm/shmem.c:798
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffff8123ab60-ffffffff8123b489: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122db60)
Location: mm/shmem.c:798
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffff8122db60-ffffffff8122e483: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81238900)
Location: mm/shmem.c:798
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffff81238900-ffffffff81239229: shmem_undo_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void shmem_undo_range(struct inode *inode, loff_t lstart, loff_t lend, bool unfalloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81247f80)
Location: mm/shmem.c:798
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_truncate_range
```
**Symbols:**

```
ffffffff81247f80-ffffffff81248914: shmem_undo_range (STB_LOCAL)
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
