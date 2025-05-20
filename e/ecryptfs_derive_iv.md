# Function: <code>ecryptfs_derive_iv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81305570)
Location: fs/ecryptfs/crypto.c:171
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff81305570-ffffffff813056f2: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81339810)
Location: fs/ecryptfs/crypto.c:153
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff81339810-ffffffff81339994: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8134f5b0)
Location: fs/ecryptfs/crypto.c:153
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff8134f5b0-ffffffff8134f734: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81364050)
Location: fs/ecryptfs/crypto.c:153
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff81364050-ffffffff813641f0: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81388d70)
Location: fs/ecryptfs/crypto.c:139
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff81388d70-ffffffff81388f10: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:139
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff813b9a84-ffffffff813b9a90: ecryptfs_derive_iv.cold.28 (STB_LOCAL)
ffffffff813b7be0-ffffffff813b7d74: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:139
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff813d2fd9-ffffffff813d3012: ecryptfs_derive_iv.cold.26 (STB_LOCAL)
ffffffff813d1170-ffffffff813d12f4: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:125
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff813fda97-ffffffff813fdad0: ecryptfs_derive_iv.cold (STB_LOCAL)
ffffffff813fbcb0-ffffffff813fbe2c: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:125
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff81417983-ffffffff814179bc: ecryptfs_derive_iv.cold (STB_LOCAL)
ffffffff81415b90-ffffffff81415d0c: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:110
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff81465f63-ffffffff81465f9c: ecryptfs_derive_iv.cold (STB_LOCAL)
ffffffff81464120-ffffffff814642a1: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:110
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff81bee6d2-ffffffff81bee70b: ecryptfs_derive_iv.cold (STB_LOCAL)
ffffffff8147f8e0-ffffffff8147fa61: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:110
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff81be070b-ffffffff81be0744: ecryptfs_derive_iv.cold (STB_LOCAL)
ffffffff81485140-ffffffff814852bc: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:110
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff81cd0ea8-ffffffff81cd0ee1: ecryptfs_derive_iv.cold (STB_LOCAL)
ffffffff814dc860-ffffffff814dc9dc: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:110
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff81e840e3-ffffffff81e8411c: ecryptfs_derive_iv.cold (STB_LOCAL)
ffffffff8156a770-ffffffff8156a922: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8160e550)
Location: fs/ecryptfs/crypto.c:110
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff8160e550-ffffffff8160e738: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff816463c0)
Location: fs/ecryptfs/crypto.c:110
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff816463c0-ffffffff816465cf: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8167f880)
Location: fs/ecryptfs/crypto.c:110
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff8167f880-ffffffff8167fa8f: ecryptfs_derive_iv (STB_GLOBAL)
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
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f7108)
Location: fs/ecryptfs/crypto.c:125
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffff8000104f7108-ffff8000104f72d4: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b48ac)
Location: fs/ecryptfs/crypto.c:125
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
c06b48ac-c06b4a74: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c0000000006385c0)
Location: fs/ecryptfs/crypto.c:125
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
c0000000006385c0-c000000000638810: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe000365c56)
Location: fs/ecryptfs/crypto.c:125
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffe000365c56-ffffffe000365dc6: ecryptfs_derive_iv (STB_GLOBAL)
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
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:125
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff8140ff63-ffffffff8140ff9c: ecryptfs_derive_iv.cold (STB_LOCAL)
ffffffff8140e170-ffffffff8140e2ec: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:125
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff814009e3-ffffffff81400a1c: ecryptfs_derive_iv.cold (STB_LOCAL)
ffffffff813febf0-ffffffff813fed6c: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:125
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff8140d2e3-ffffffff8140d31c: ecryptfs_derive_iv.cold (STB_LOCAL)
ffffffff8140b4f0-ffffffff8140b66c: ecryptfs_derive_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_derive_iv(char *iv, struct ecryptfs_crypt_stat *crypt_stat, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:125
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
**Symbols:**

```
ffffffff81422f63-ffffffff81422f9c: ecryptfs_derive_iv.cold (STB_LOCAL)
ffffffff81421190-ffffffff8142130c: ecryptfs_derive_iv (STB_GLOBAL)
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
