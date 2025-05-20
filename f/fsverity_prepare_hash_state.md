# Function: <code>fsverity_prepare_hash_state</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(const struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813500d0)
Location: fs/verity/hash_algs.c:104
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff813500d0-ffffffff81350314: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81396a40)
Location: fs/verity/hash_algs.c:156
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81396a40-ffffffff81396cb9: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813a8670)
Location: fs/verity/hash_algs.c:156
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff813a8670-ffffffff813a88e9: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813af6e0)
Location: fs/verity/hash_algs.c:156
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff813af6e0-ffffffff813af955: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813ff2d0)
Location: fs/verity/hash_algs.c:156
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff813ff2d0-ffffffff813ff545: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81472e70)
Location: fs/verity/hash_algs.c:156
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81472e70-ffffffff8147312a: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81504cb0)
Location: fs/verity/hash_algs.c:158
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81504cb0-ffffffff81504f6a: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(const struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff8153c280)
Location: fs/verity/hash_algs.c:111
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff8153c280-ffffffff8153c416: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(const struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81571560)
Location: fs/verity/hash_algs.c:111
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81571560-ffffffff815716e4: fsverity_prepare_hash_state (STB_GLOBAL)
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
const u8 *fsverity_prepare_hash_state(const struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffff800010411d38)
Location: fs/verity/hash_algs.c:104
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffff800010411d38-ffff800010411f88: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(const struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (c05de390)
Location: fs/verity/hash_algs.c:104
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
c05de390-c05de5e0: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(const struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (c00000000051f920)
Location: fs/verity/hash_algs.c:104
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
c00000000051f920-c00000000051fc30: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(const struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffe0002b9e76)
Location: fs/verity/hash_algs.c:104
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffe0002b9e76-ffffffe0002ba05e: fsverity_prepare_hash_state (STB_GLOBAL)
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
const u8 *fsverity_prepare_hash_state(const struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813486b0)
Location: fs/verity/hash_algs.c:104
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff813486b0-ffffffff813488f4: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(const struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81339390)
Location: fs/verity/hash_algs.c:104
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81339390-ffffffff813395d4: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(const struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81346180)
Location: fs/verity/hash_algs.c:104
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81346180-ffffffff813463c4: fsverity_prepare_hash_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const u8 *fsverity_prepare_hash_state(const struct fsverity_hash_alg *alg, const u8 *salt, size_t salt_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81359460)
Location: fs/verity/hash_algs.c:104
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
**Symbols:**

```
ffffffff81359460-ffffffff813596a4: fsverity_prepare_hash_state (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>const struct fsverity_hash_alg *alg</code> ➡️ <code>struct fsverity_hash_alg *alg</code>
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
<b>Param type changed. </b>
<code>struct fsverity_hash_alg *alg</code> ➡️ <code>const struct fsverity_hash_alg *alg</code>
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
