# Function: <code>sync_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8123c2d0)
Location: fs/fs-writeback.c:2370
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff8123c2d0-ffffffff8123c32e: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812641cf)
Location: fs/fs-writeback.c:2448
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff81264190-ffffffff812641a0: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8127760f)
Location: fs/fs-writeback.c:2446
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff812775d0-ffffffff812775e0: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812849af)
Location: fs/fs-writeback.c:2455
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff81284970-ffffffff81284980: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a74ef)
Location: fs/fs-writeback.c:2470
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff812a74b0-ffffffff812a74c0: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812ce0bc)
Location: fs/fs-writeback.c:2468
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff812ce070-ffffffff812ce080: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812e33bc)
Location: fs/fs-writeback.c:2497
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff812e3370-ffffffff812e3380: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130119c)
Location: fs/fs-writeback.c:2512
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff81301150-ffffffff81301160: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131387c)
Location: fs/fs-writeback.c:2600
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff81313830-ffffffff81313840: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134d13c)
Location: fs/fs-writeback.c:2609
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff8134d0f0-ffffffff8134d100: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135a03c)
Location: fs/fs-writeback.c:2602
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff81359ff0-ffffffff8135a000: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81360cac)
Location: fs/fs-writeback.c:2603
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff81360c60-ffffffff81360c70: sync_inode (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c9390)
Location: fs/fs-writeback.c:2600
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffff8000103c9308-ffff8000103c933c: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a6588)
Location: fs/fs-writeback.c:2600
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
c05a6514-c05a6530: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004cb7c4)
Location: fs/fs-writeback.c:2600
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
c0000000004cb740-c0000000004cb754: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000287888)
Location: fs/fs-writeback.c:2600
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffe00028783c-ffffffe00028786e: sync_inode (STB_GLOBAL)
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
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130be5c)
Location: fs/fs-writeback.c:2600
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff8130be10-ffffffff8130be20: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fca7c)
Location: fs/fs-writeback.c:2600
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff812fca30-ffffffff812fca40: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81309c4c)
Location: fs/fs-writeback.c:2600
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff81309c00-ffffffff81309c10: sync_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sync_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131bc6c)
Location: fs/fs-writeback.c:2600
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inode_metadata
```
**Symbols:**

```
ffffffff8131bc20-ffffffff8131bc30: sync_inode (STB_GLOBAL)
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
