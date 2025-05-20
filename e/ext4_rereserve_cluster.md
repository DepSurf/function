# Function: <code>ext4_rereserve_cluster</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81350510)
Location: fs/ext4/extents.c:2508
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
**Symbols:**

```
ffffffff81350510-ffffffff813505bd: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813791d0)
Location: fs/ext4/extents.c:2525
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff813791d0-ffffffff8137927f: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81391580)
Location: fs/ext4/extents.c:2571
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff81391580-ffffffff8139162f: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dd060)
Location: fs/ext4/extents.c:2392
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff813dd060-ffffffff813dd10f: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813ee980)
Location: fs/ext4/extents.c:2391
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff813ee980-ffffffff813eea2f: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f4f50)
Location: fs/ext4/extents.c:2394
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff813f4f50-ffffffff813f4fff: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2432
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff814471a0-ffffffff8144726e: ext4_rereserve_cluster (STB_LOCAL)
ffffffff81cc8e91-ffffffff81cc8ed2: ext4_rereserve_cluster.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2431
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff814c3690-ffffffff814c3769: ext4_rereserve_cluster (STB_LOCAL)
ffffffff81e7bbb4-ffffffff81e7bbf5: ext4_rereserve_cluster.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2438
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff8155b9a0-ffffffff8155ba79: ext4_rereserve_cluster (STB_LOCAL)
ffffffff8206c239-ffffffff8206c27a: ext4_rereserve_cluster.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2438
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff815937c0-ffffffff81593899: ext4_rereserve_cluster (STB_LOCAL)
ffffffff820ec0cb-ffffffff820ec10c: ext4_rereserve_cluster.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2414
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff815cc4b0-ffffffff815cc589: ext4_rereserve_cluster (STB_LOCAL)
ffffffff821c9303-ffffffff821c9344: ext4_rereserve_cluster.cold (STB_LOCAL)
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
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff8000104649c8)
Location: fs/ext4/extents.c:2571
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffff8000104649c8-ffff800010464ac0: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c06251a8)
Location: fs/ext4/extents.c:2571
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
c06251a8-c0625288: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000582280)
Location: fs/ext4/extents.c:2571
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
c000000000582280-c0000000005823a0: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f304e)
Location: fs/ext4/extents.c:2571
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffe0002f304e-ffffffe0002f3138: ext4_rereserve_cluster (STB_LOCAL)
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
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81389b60)
Location: fs/ext4/extents.c:2571
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff81389b60-ffffffff81389c0f: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137a5f0)
Location: fs/ext4/extents.c:2571
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff8137a5f0-ffffffff8137a69f: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813874c0)
Location: fs/ext4/extents.c:2571
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff813874c0-ffffffff8138756f: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode *inode, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139b1a0)
Location: fs/ext4/extents.c:2571
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
```
**Symbols:**

```
ffffffff8139b1a0-ffffffff8139b24d: ext4_rereserve_cluster (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
