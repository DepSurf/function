# Function: <code>fsverity_get_hash_alg</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
const struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:39
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff8135059b-ffffffff81350670: fsverity_get_hash_alg.cold (STB_LOCAL)
ffffffff81350010-ffffffff813500ce: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:41
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81396fd3-ffffffff8139707b: fsverity_get_hash_alg.cold (STB_LOCAL)
ffffffff813968d0-ffffffff813969e6: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:41
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81beb3fc-ffffffff81beb4a4: fsverity_get_hash_alg.cold (STB_LOCAL)
ffffffff813a8500-ffffffff813a8616: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:41
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81bdd450-ffffffff81bdd4f8: fsverity_get_hash_alg.cold (STB_LOCAL)
ffffffff813af550-ffffffff813af666: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:41
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81cc6d57-ffffffff81cc6dfe: fsverity_get_hash_alg.cold (STB_LOCAL)
ffffffff813ff100-ffffffff813ff259: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:41
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81e79293-ffffffff81e7933a: fsverity_get_hash_alg.cold (STB_LOCAL)
ffffffff81472c50-ffffffff81472dc7: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff815049c0)
Location: fs/verity/hash_algs.c:43
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff815049c0-ffffffff81504bd7: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff8153c0c0)
Location: fs/verity/hash_algs.c:42
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff8153c0c0-ffffffff8153c26d: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff815713a0)
Location: fs/verity/hash_algs.c:42
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff815713a0-ffffffff8157154d: fsverity_get_hash_alg (STB_GLOBAL)
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
const struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffff800010411b78)
Location: fs/verity/hash_algs.c:39
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffff800010411b78-ffff800010411d34: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (c05de1e8)
Location: fs/verity/hash_algs.c:39
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
c05de1e8-c05de390: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (c00000000051f6f0)
Location: fs/verity/hash_algs.c:39
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
c00000000051f6f0-c00000000051f91c: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffe0002b9d20)
Location: fs/verity/hash_algs.c:39
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffe0002b9d20-ffffffe0002b9e76: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
const struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:39
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81348b7b-ffffffff81348c50: fsverity_get_hash_alg.cold (STB_LOCAL)
ffffffff813485f0-ffffffff813486ae: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
const struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:39
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff8133985b-ffffffff81339930: fsverity_get_hash_alg.cold (STB_LOCAL)
ffffffff813392d0-ffffffff8133938e: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
const struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:39
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff8134664b-ffffffff81346720: fsverity_get_hash_alg.cold (STB_LOCAL)
ffffffff813460c0-ffffffff8134617e: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
const struct fsverity_hash_alg *fsverity_get_hash_alg(const struct inode *inode, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/hash_algs.c (0)
Location: fs/verity/hash_algs.c:39
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff8135992b-ffffffff81359a00: fsverity_get_hash_alg.cold (STB_LOCAL)
ffffffff813593a0-ffffffff8135945e: fsverity_get_hash_alg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>const struct fsverity_hash_alg *</code> ➡️ <code>struct fsverity_hash_alg *</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct fsverity_hash_alg *</code> ➡️ <code>const struct fsverity_hash_alg *</code>
</li>
</ul>
</details>
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
