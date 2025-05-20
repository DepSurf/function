# Function: <code>__writeback_single_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8123b010)
Location: fs/fs-writeback.c:1257
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff8123b010-ffffffff8123b339: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81262ed0)
Location: fs/fs-writeback.c:1294
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81262ed0-ffffffff812631e1: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81276320)
Location: fs/fs-writeback.c:1294
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81276320-ffffffff81276631: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812837a0)
Location: fs/fs-writeback.c:1308
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff812837a0-ffffffff81283ab2: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a6330)
Location: fs/fs-writeback.c:1311
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff812a6330-ffffffff812a6666: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812ccee0)
Location: fs/fs-writeback.c:1312
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff812ccee0-ffffffff812cd23b: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812e2210)
Location: fs/fs-writeback.c:1338
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff812e2210-ffffffff812e255a: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs-writeback.c (0)
Location: fs/fs-writeback.c:1353
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81300c20-ffffffff81300f5f: __writeback_single_inode (STB_LOCAL)
ffffffff8130244b-ffffffff8130245e: __writeback_single_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813132f0)
Location: fs/fs-writeback.c:1441
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff813132f0-ffffffff81313636: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134cc60)
Location: fs/fs-writeback.c:1452
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff8134cc60-ffffffff8134ced4: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81359be0)
Location: fs/fs-writeback.c:1450
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81359be0-ffffffff81359ddb: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813607b0)
Location: fs/fs-writeback.c:1462
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff813607b0-ffffffff81360a46: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813aee30)
Location: fs/fs-writeback.c:1605
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff813aee30-ffffffff813af0ba: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814335f0)
Location: fs/fs-writeback.c:1576
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff814335f0-ffffffff8143387d: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c1850)
Location: fs/fs-writeback.c:1587
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff814c1850-ffffffff814c1add: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f6be0)
Location: fs/fs-writeback.c:1592
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff814f6be0-ffffffff814f6e6d: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152b320)
Location: fs/fs-writeback.c:1614
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff8152b320-ffffffff8152b5ad: __writeback_single_inode (STB_LOCAL)
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
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c8b68)
Location: fs/fs-writeback.c:1441
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffff8000103c8b68-ffff8000103c8fc4: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a54a8)
Location: fs/fs-writeback.c:1441
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
c05a54a8-c05a590c: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004ca0e0)
Location: fs/fs-writeback.c:1441
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
c0000000004ca0e0-c0000000004ca61c: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000287226)
Location: fs/fs-writeback.c:1441
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffe000287226-ffffffe0002875b8: __writeback_single_inode (STB_LOCAL)
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
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130b8d0)
Location: fs/fs-writeback.c:1441
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff8130b8d0-ffffffff8130bc16: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fc4f0)
Location: fs/fs-writeback.c:1441
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff812fc4f0-ffffffff812fc836: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813096c0)
Location: fs/fs-writeback.c:1441
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff813096c0-ffffffff81309a06: __writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131a070)
Location: fs/fs-writeback.c:1441
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff8131a070-ffffffff8131a453: __writeback_single_inode (STB_LOCAL)
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
