# Function: <code>lsm_inode_alloc</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139e77e)
Location: security/security.c:519
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
  - security/security.c:lsm_early_inode
```
**Symbols:**

```
ffffffff8139db90-ffffffff8139dbcc: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4203)
Location: security/security.c:481
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
  - security/security.c:lsm_early_inode
```
**Symbols:**

```
ffffffff813c34a0-ffffffff813c34df: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140fa85)
Location: security/security.c:548
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffff8140f340-ffffffff8140f380: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143d0a5)
Location: security/security.c:547
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffff8143c790-ffffffff8143c7d0: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456b85)
Location: security/security.c:581
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffff81456300-ffffffff81456340: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a9995)
Location: security/security.c:634
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffff814a90b0-ffffffff814a90f6: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6f9e)
Location: security/security.c:636
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffff814c66b0-ffffffff814c66f6: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cd15e)
Location: security/security.c:639
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffff814cc7b0-ffffffff814cc7eb: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815262de)
Location: security/security.c:639
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffff81525930-ffffffff8152596b: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815ba74e)
Location: security/security.c:667
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffff815b9b20-ffffffff815b9b63: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8166611e)
Location: security/security.c:716
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
```
**Symbols:**

```
ffffffff81665310-ffffffff81665353: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169e70e)
Location: security/security.c:724
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
```
**Symbols:**

```
ffffffff8169d890-ffffffff8169d8d3: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816db05e)
Location: security/security.c:729
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
```
**Symbols:**

```
ffffffff816da020-ffffffff816da063: lsm_inode_alloc (STB_GLOBAL)
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
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffff80001054258c)
Location: security/security.c:581
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffff800010541af0-ffff800010541b48: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (c06f8534)
Location: security/security.c:581
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
c06f7ad8-c06f7b34: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000695964)
Location: security/security.c:581
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
c0000000006944b0-c000000000694534: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039eea0)
Location: security/security.c:581
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffe00039e6d2-ffffffe00039e724: lsm_inode_alloc (STB_GLOBAL)
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
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144f165)
Location: security/security.c:581
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffff8144e8e0-ffffffff8144e920: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143fbb5)
Location: security/security.c:581
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffff8143f330-ffffffff8143f370: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144b205)
Location: security/security.c:581
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffff8144a980-ffffffff8144a9c0: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int lsm_inode_alloc(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814625d5)
Location: security/security.c:581
Inline: True
Inline callers:
  - security/security.c:security_inode_alloc
Direct callers:
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
**Symbols:**

```
ffffffff81461d50-ffffffff81461d90: lsm_inode_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
