# Function: <code>__d_rehash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __d_rehash(struct dentry *entry, struct hlist_bl_head *b);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81223470)
Location: fs/dcache.c:2410
Inline: True
Direct callers:
  - fs/dcache.c:d_rehash
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff81223470-ffffffff812234c3: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124ba90)
Location: fs/dcache.c:2343
Inline: True
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff8124ba90-ffffffff8124baf9: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125ea70)
Location: fs/dcache.c:2352
Inline: True
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff8125ea70-ffffffff8125ead9: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126c2d0)
Location: fs/dcache.c:2382
Inline: True
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff8126c2d0-ffffffff8126c339: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128e5e0)
Location: fs/dcache.c:2394
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff8128e5e0-ffffffff8128e640: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b47f0)
Location: fs/dcache.c:2408
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff812b47f0-ffffffff812b484a: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c9a70)
Location: fs/dcache.c:2389
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff812c9a70-ffffffff812c9aca: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6480)
Location: fs/dcache.c:2459
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff812e6480-ffffffff812e64da: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f7fe0)
Location: fs/dcache.c:2459
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff812f7fe0-ffffffff812f803a: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81330d60)
Location: fs/dcache.c:2480
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff81330d60-ffffffff81330dba: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133c6f0)
Location: fs/dcache.c:2487
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff8133c6f0-ffffffff8133c74a: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81342b70)
Location: fs/dcache.c:2514
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff81342b70-ffffffff81342bca: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2515
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff81390570-ffffffff813905e6: __d_rehash (STB_LOCAL)
ffffffff81cc3b31-ffffffff81cc3b50: __d_rehash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2540
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff81412b30-ffffffff81412bf7: __d_rehash (STB_LOCAL)
ffffffff81e76365-ffffffff81e76384: __d_rehash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2574
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff8149de10-ffffffff8149ded7: __d_rehash (STB_LOCAL)
ffffffff82068937-ffffffff82068956: __d_rehash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2574
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff814d3130-ffffffff814d31f7: __d_rehash (STB_LOCAL)
ffffffff820e8275-ffffffff820e8294: __d_rehash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2398
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff815058c0-ffffffff81505987: __d_rehash (STB_LOCAL)
ffffffff821c4fb2-ffffffff821c4fd1: __d_rehash.cold (STB_LOCAL)
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
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a5438)
Location: fs/dcache.c:2459
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffff8000103a5438-ffff8000103a5504: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0588730)
Location: fs/dcache.c:2459
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
c0588730-c0588840: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a0540)
Location: fs/dcache.c:2459
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
c0000000004a0540-c0000000004a0608: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026bb88)
Location: fs/dcache.c:2459
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffe00026bb88-ffffffe00026bc06: __d_rehash (STB_LOCAL)
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
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f05c0)
Location: fs/dcache.c:2459
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff812f05c0-ffffffff812f061a: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e11f0)
Location: fs/dcache.c:2459
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff812e11f0-ffffffff812e124a: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ee3d0)
Location: fs/dcache.c:2459
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff812ee3d0-ffffffff812ee42a: __d_rehash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __d_rehash(struct dentry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fff60)
Location: fs/dcache.c:2459
Inline: False
Direct callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_add
  - fs/dcache.c:d_rehash
```
**Symbols:**

```
ffffffff812fff60-ffffffff812fffe1: __d_rehash (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct hlist_bl_head *b</code>
</li>
</ul>
</details>
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
