# Function: <code>inode_has_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812427dd)
Location: fs/buffer.c:492
Inline: True
Inline callers:
  - fs/buffer.c:invalidate_inode_buffers
  - fs/buffer.c:remove_inode_buffers
Direct callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:inode_lru_isolate
```
**Symbols:**

```
ffffffff812447e0-ffffffff812447ff: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126cdb3)
Location: fs/buffer.c:488
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8126cd10-ffffffff8126cd32: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81280043)
Location: fs/buffer.c:489
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8127ffa0-ffffffff8127ffc2: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128d923)
Location: fs/buffer.c:486
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8128d880-ffffffff8128d8a2: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b04d3)
Location: fs/buffer.c:465
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff812b0430-ffffffff812b0452: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d82a5)
Location: fs/buffer.c:457
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff812d8230-ffffffff812d8252: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ed4e5)
Location: fs/buffer.c:458
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff812ed470-ffffffff812ed492: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130ef05)
Location: fs/buffer.c:459
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8130eea0-ffffffff8130eec2: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81321f25)
Location: fs/buffer.c:459
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81321ec0-ffffffff81321ee2: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135da45)
Location: fs/buffer.c:485
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8135d970-ffffffff8135d992: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136b635)
Location: fs/buffer.c:484
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8136b560-ffffffff8136b582: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81371ed5)
Location: fs/buffer.c:484
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81371e00-ffffffff81371e22: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c0ef5)
Location: fs/buffer.c:484
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff813c0e20-ffffffff813c0e42: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81447bb5)
Location: fs/buffer.c:484
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81447ac0-ffffffff81447ae8: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d6735)
Location: fs/buffer.c:484
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff814d6620-ffffffff814d6648: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150cd25)
Location: fs/buffer.c:525
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8150cc10-ffffffff8150cc38: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81541925)
Location: fs/buffer.c:519
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81541880-ffffffff815418a8: inode_has_buffers (STB_GLOBAL)
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
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103dac38)
Location: fs/buffer.c:459
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffff8000103dab90-ffff8000103dabc4: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b3fd8)
Location: fs/buffer.c:459
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
c05b3f48-c05b3f6c: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dfe18)
Location: fs/buffer.c:459
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
c0000000004dfd50-c0000000004dfd70: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe0002936b8)
Location: fs/buffer.c:459
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffe000293622-ffffffe000293650: inode_has_buffers (STB_GLOBAL)
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
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131a505)
Location: fs/buffer.c:459
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8131a4a0-ffffffff8131a4c2: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130b0a5)
Location: fs/buffer.c:459
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff8130b040-ffffffff8130b062: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81317fd5)
Location: fs/buffer.c:459
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81317f70-ffffffff81317f92: inode_has_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int inode_has_buffers(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81329be5)
Location: fs/buffer.c:459
Inline: True
Inline callers:
  - fs/buffer.c:remove_inode_buffers
  - fs/buffer.c:invalidate_inode_buffers
Direct callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:__destroy_inode
```
**Symbols:**

```
ffffffff81329b80-ffffffff81329ba2: inode_has_buffers (STB_GLOBAL)
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
