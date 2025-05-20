# Function: <code>__inode_add_bytes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81211333)
Location: fs/stat.c:447
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:inode_claim_rsv_space
```
**Symbols:**

```
ffffffff81211f40-ffffffff81211f92: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81237de3)
Location: fs/stat.c:447
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:inode_claim_rsv_space
```
**Symbols:**

```
ffffffff81238a10-ffffffff81238a62: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8124aaa3)
Location: fs/stat.c:449
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:inode_claim_rsv_space
```
**Symbols:**

```
ffffffff8124b6c0-ffffffff8124b712: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812564e3)
Location: fs/stat.c:665
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:inode_claim_rsv_space
```
**Symbols:**

```
ffffffff81256460-ffffffff812564b2: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81278723)
Location: fs/stat.c:666
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff812786a0-ffffffff812786f2: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812a05f3)
Location: fs/stat.c:672
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff8129f0c0-ffffffff8129f112: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b55d3)
Location: fs/stat.c:675
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff812b40a0-ffffffff812b40f2: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d2383)
Location: fs/stat.c:677
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff812d0de0-ffffffff812d0e32: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e3f13)
Location: fs/stat.c:677
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff812e2970-ffffffff812e29c2: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131b1d3)
Location: fs/stat.c:704
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81319cf0-ffffffff81319d42: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813265a3)
Location: fs/stat.c:692
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81325380-ffffffff813253d2: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c6b3)
Location: fs/stat.c:710
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff8132b3e0-ffffffff8132b432: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379e23)
Location: fs/stat.c:728
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81378b50-ffffffff81378ba2: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f8bc3)
Location: fs/stat.c:750
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff813f7eb0-ffffffff813f7f0c: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81482193)
Location: fs/stat.c:767
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff814812f0-ffffffff8148134c: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b6da3)
Location: fs/stat.c:780
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff814b5f20-ffffffff814b5f7c: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e90d3)
Location: fs/stat.c:802
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff814e8230-ffffffff814e828c: __inode_add_bytes (STB_GLOBAL)
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
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038aa94)
Location: fs/stat.c:677
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffff80001038a310-ffff80001038a374: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (c057235c)
Location: fs/stat.c:677
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
c05722c4-c0572334: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000482e38)
Location: fs/stat.c:677
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
c000000000481590-c0000000004815dc: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025cc3c)
Location: fs/stat.c:677
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffe00025c304-ffffffe00025c368: __inode_add_bytes (STB_GLOBAL)
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
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812dc4f3)
Location: fs/stat.c:677
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff812daf50-ffffffff812dafa2: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cd173)
Location: fs/stat.c:677
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff812cbbd0-ffffffff812cbc22: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812da303)
Location: fs/stat.c:677
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff812d8d60-ffffffff812d8db2: __inode_add_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __inode_add_bytes(struct inode *inode, loff_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e9c13)
Location: fs/stat.c:677
Inline: True
Inline callers:
  - fs/stat.c:inode_add_bytes
Direct callers:
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff812e9b90-ffffffff812e9be2: __inode_add_bytes (STB_GLOBAL)
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
