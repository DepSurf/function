# Function: <code>ext4_xattr_delete_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_xattr_delete_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812df270)
Location: fs/ext4/xattr.c:1486
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff812df270-ffffffff812df32f: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_xattr_delete_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130efd0)
Location: fs/ext4/xattr.c:1588
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8130efd0-ffffffff8130f09b: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_xattr_delete_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81324df0)
Location: fs/ext4/xattr.c:1602
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81324df0-ffffffff81324ebb: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133ea80)
Location: fs/ext4/xattr.c:2795
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff8133ea80-ffffffff8133ee05: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81363060)
Location: fs/ext4/xattr.c:2831
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81363060-ffffffff81363411: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81391800)
Location: fs/ext4/xattr.c:2848
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81391800-ffffffff81391bab: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813aa440)
Location: fs/ext4/xattr.c:2853
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813aa440-ffffffff813aa7ed: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d4620)
Location: fs/ext4/xattr.c:2854
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813d4620-ffffffff813d49dc: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813edd00)
Location: fs/ext4/xattr.c:2854
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813edd00-ffffffff813ee0bc: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8143ac10)
Location: fs/ext4/xattr.c:2841
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff8143ac10-ffffffff8143b02f: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81453780)
Location: fs/ext4/xattr.c:2848
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81453780-ffffffff81453bab: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814590a0)
Location: fs/ext4/xattr.c:2848
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff814590a0-ffffffff814594d2: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814ad1b0)
Location: fs/ext4/xattr.c:2831
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff814ad1b0-ffffffff814ad5ef: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81535240)
Location: fs/ext4/xattr.c:2846
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81535240-ffffffff8153565f: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815d3680)
Location: fs/ext4/xattr.c:2872
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff815d3680-ffffffff815d3a09: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8160b230)
Location: fs/ext4/xattr.c:2919
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff8160b230-ffffffff8160b5f8: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81643ff0)
Location: fs/ext4/xattr.c:2919
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81643ff0-ffffffff816443b8: ext4_xattr_delete_inode (STB_GLOBAL)
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
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c6ce8)
Location: fs/ext4/xattr.c:2854
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffff8000104c6ce8-ffff8000104c70d8: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c068aca8)
Location: fs/ext4/xattr.c:2854
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
c068aca8-c068b0b8: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005ff190)
Location: fs/ext4/xattr.c:2854
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
c0000000005ff190-c0000000005ff64c: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe000341008)
Location: fs/ext4/xattr.c:2854
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffe000341008-ffffffe000341332: ext4_xattr_delete_inode (STB_GLOBAL)
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
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e62e0)
Location: fs/ext4/xattr.c:2854
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813e62e0-ffffffff813e669c: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d6d60)
Location: fs/ext4/xattr.c:2854
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813d6d60-ffffffff813d711c: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e3660)
Location: fs/ext4/xattr.c:2854
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813e3660-ffffffff813e3a1c: ext4_xattr_delete_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_xattr_delete_inode(handle_t *handle, struct inode *inode, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f8a70)
Location: fs/ext4/xattr.c:2854
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813f8a70-ffffffff813f8e2c: ext4_xattr_delete_inode (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ext4_xattr_inode_array **ea_inode_array</code>
</li>
<li>
<b>Param added. </b>
<code>int extra_credits</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
