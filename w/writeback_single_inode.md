# Function: <code>writeback_single_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct bdi_writeback *wb, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8123c020)
Location: fs/fs-writeback.c:1343
Inline: False
Direct callers:
  - fs/fs-writeback.c:write_inode_now
  - fs/fs-writeback.c:sync_inode
```
**Symbols:**

```
ffffffff8123c020-ffffffff8123c1b5: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81263f40)
Location: fs/fs-writeback.c:1380
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff81263f40-ffffffff812640d0: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81277380)
Location: fs/fs-writeback.c:1380
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff81277380-ffffffff81277510: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81284760)
Location: fs/fs-writeback.c:1394
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff81284760-ffffffff812848a9: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a72c0)
Location: fs/fs-writeback.c:1397
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff812a72c0-ffffffff812a73ea: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812cde80)
Location: fs/fs-writeback.c:1398
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff812cde80-ffffffff812cdfaa: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812e3190)
Location: fs/fs-writeback.c:1424
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff812e3190-ffffffff812e32b0: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs-writeback.c (0)
Location: fs/fs-writeback.c:1439
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff81300f60-ffffffff81301082: writeback_single_inode (STB_LOCAL)
ffffffff8130245e-ffffffff813024af: writeback_single_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81313640)
Location: fs/fs-writeback.c:1527
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff81313640-ffffffff81313769: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134cee0)
Location: fs/fs-writeback.c:1538
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff8134cee0-ffffffff8134d022: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81359de0)
Location: fs/fs-writeback.c:1534
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff81359de0-ffffffff81359f22: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81360a50)
Location: fs/fs-writeback.c:1548
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff81360a50-ffffffff81360b92: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813af0c0)
Location: fs/fs-writeback.c:1691
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff813af0c0-ffffffff813af202: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81433b90)
Location: fs/fs-writeback.c:1670
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff81433b90-ffffffff81433cf1: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c1af0)
Location: fs/fs-writeback.c:1681
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff814c1af0-ffffffff814c1c77: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f6e80)
Location: fs/fs-writeback.c:1686
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff814f6e80-ffffffff814f7007: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152b5c0)
Location: fs/fs-writeback.c:1708
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff8152b5c0-ffffffff8152b747: writeback_single_inode (STB_LOCAL)
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
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c8fc8)
Location: fs/fs-writeback.c:1527
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffff8000103c8fc8-ffff8000103c9228: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a6264)
Location: fs/fs-writeback.c:1527
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
c05a6264-c05a6428: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004cb3e0)
Location: fs/fs-writeback.c:1527
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
c0000000004cb3e0-c0000000004cb620: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe0002875b8)
Location: fs/fs-writeback.c:1527
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffe0002875b8-ffffffe00028778c: writeback_single_inode (STB_LOCAL)
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
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130bc20)
Location: fs/fs-writeback.c:1527
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff8130bc20-ffffffff8130bd49: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fc840)
Location: fs/fs-writeback.c:1527
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff812fc840-ffffffff812fc969: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81309a10)
Location: fs/fs-writeback.c:1527
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff81309a10-ffffffff81309b39: writeback_single_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int writeback_single_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131ba30)
Location: fs/fs-writeback.c:1527
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
  - fs/fs-writeback.c:write_inode_now
```
**Symbols:**

```
ffffffff8131ba30-ffffffff8131bb55: writeback_single_inode (STB_LOCAL)
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
<b>Param removed. </b>
<code>struct bdi_writeback *wb</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, wb, wbc</code> ➡️ <code>inode, wbc</code>
</li>
</ul>
</details>
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
