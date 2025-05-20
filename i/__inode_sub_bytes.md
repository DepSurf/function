# Function: <code>__inode_sub_bytes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812113a0)
Location: fs/stat.c:467
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:inode_reclaim_rsv_space
```
**Symbols:**

```
ffffffff812113a0-ffffffff812113f0: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81237ec3)
Location: fs/stat.c:467
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:inode_reclaim_rsv_space
```
**Symbols:**

```
ffffffff81237e50-ffffffff81237ea0: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8124ab83)
Location: fs/stat.c:469
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:inode_reclaim_rsv_space
```
**Symbols:**

```
ffffffff8124ab10-ffffffff8124ab60: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812565c3)
Location: fs/stat.c:686
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:inode_reclaim_rsv_space
```
**Symbols:**

```
ffffffff81256550-ffffffff812565a0: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81278803)
Location: fs/stat.c:687
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff81278790-ffffffff812787e0: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129f193)
Location: fs/stat.c:693
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff8129f120-ffffffff8129f170: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b4173)
Location: fs/stat.c:696
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff812b4100-ffffffff812b4150: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d0eb3)
Location: fs/stat.c:698
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff812d0e40-ffffffff812d0e90: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e2a43)
Location: fs/stat.c:698
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff812e29d0-ffffffff812e2a20: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131ae43)
Location: fs/stat.c:725
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff81319d50-ffffffff81319da0: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813264d3)
Location: fs/stat.c:713
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff813253e0-ffffffff81325430: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c5e3)
Location: fs/stat.c:731
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff8132b440-ffffffff8132b490: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379d53)
Location: fs/stat.c:749
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff81378bb0-ffffffff81378c00: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f8c53)
Location: fs/stat.c:771
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff813f7f10-ffffffff813f7f6e: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81482233)
Location: fs/stat.c:788
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff81481360-ffffffff814813be: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b6e43)
Location: fs/stat.c:801
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff814b5f90-ffffffff814b5fee: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e9173)
Location: fs/stat.c:823
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff814e82a0-ffffffff814e82fe: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038a954)
Location: fs/stat.c:698
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffff80001038a378-ffff80001038a3d8: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (c057247c)
Location: fs/stat.c:698
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
c05723d4-c0572454: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000481aa8)
Location: fs/stat.c:698
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
c0000000004815e0-c000000000481628: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025c662)
Location: fs/stat.c:698
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffe00025c368-ffffffe00025c3ca: __inode_sub_bytes (STB_GLOBAL)
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
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812db023)
Location: fs/stat.c:698
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff812dafb0-ffffffff812db000: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cbca3)
Location: fs/stat.c:698
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff812cbc30-ffffffff812cbc80: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d8e33)
Location: fs/stat.c:698
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff812d8dc0-ffffffff812d8e10: __inode_sub_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __inode_sub_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e9cf3)
Location: fs/stat.c:698
Inline: True
Inline callers:
  - fs/stat.c:inode_sub_bytes
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
```
**Symbols:**

```
ffffffff812e9c80-ffffffff812e9cd0: __inode_sub_bytes (STB_GLOBAL)
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
