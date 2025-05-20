# Function: <code>security_d_instantiate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c510)
Location: security/security.c:1125
Inline: False
Direct callers:
  - fs/dcache.c:d_instantiate_no_diralias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_instantiate_unique
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_obtain_alias
```
**Symbols:**

```
ffffffff8133c510-ffffffff8133c55d: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81371ae0)
Location: security/security.c:1149
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_no_diralias
```
**Symbols:**

```
ffffffff81371ae0-ffffffff81371b2d: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388410)
Location: security/security.c:1170
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_instantiate_no_diralias
```
**Symbols:**

```
ffffffff81388410-ffffffff8138845d: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139d410)
Location: security/security.c:1918
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_instantiate_no_diralias
```
**Symbols:**

```
ffffffff8139d410-ffffffff8139d45d: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2cc0)
Location: security/security.c:1892
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_instantiate_no_diralias
```
**Symbols:**

```
ffffffff813c2cc0-ffffffff813c2d13: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2e10)
Location: security/security.c:1274
Inline: False
Direct callers:
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff813f2e10-ffffffff813f2e5a: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140e2b0)
Location: security/security.c:1918
Inline: False
Direct callers:
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff8140e2b0-ffffffff8140e2fa: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c070)
Location: security/security.c:1937
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff8143c070-ffffffff8143c0bd: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455d20)
Location: security/security.c:1976
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff81455d20-ffffffff81455d6b: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8630)
Location: security/security.c:2178
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff814a8630-ffffffff814a867b: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5bc0)
Location: security/security.c:2195
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff814c5bc0-ffffffff814c5c0b: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cbea0)
Location: security/security.c:2258
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff814cbea0-ffffffff814cbeeb: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524e20)
Location: security/security.c:2266
Inline: False
Direct callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff81524e20-ffffffff81524e6b: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b8dd0)
Location: security/security.c:2277
Inline: False
Direct callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff815b8dd0-ffffffff815b8e25: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816644b0)
Location: security/security.c:2353
Inline: False
Direct callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff816644b0-ffffffff81664505: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169c980)
Location: security/security.c:3987
Inline: False
Direct callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff8169c980-ffffffff8169c9d5: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d93f0)
Location: security/security.c:4016
Inline: False
Direct callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff816d93f0-ffffffff816d9445: security_d_instantiate (STB_GLOBAL)
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
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541380)
Location: security/security.c:1976
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffff800010541380-ffff8000105413e4: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f73c4)
Location: security/security.c:1976
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
c06f73c4-c06f7428: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006939e0)
Location: security/security.c:1976
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
c0000000006939e0-c000000000693aa0: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e0de)
Location: security/security.c:1976
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffe00039e0de-ffffffe00039e12e: security_d_instantiate (STB_GLOBAL)
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
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e300)
Location: security/security.c:1976
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff8144e300-ffffffff8144e34b: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ed50)
Location: security/security.c:1976
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff8143ed50-ffffffff8143ed9b: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a3a0)
Location: security/security.c:1976
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff8144a3a0-ffffffff8144a3eb: security_d_instantiate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_d_instantiate(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461770)
Location: security/security.c:1976
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:d_instantiate_new
```
**Symbols:**

```
ffffffff81461770-ffffffff814617bb: security_d_instantiate (STB_GLOBAL)
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
