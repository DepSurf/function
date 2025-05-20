# Function: <code>d_ancestor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812247af)
Location: fs/dcache.c:2697
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:is_subdir
```
**Symbols:**

```
ffffffff81226110-ffffffff81226135: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124ec22)
Location: fs/dcache.c:2868
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff8124e7b0-ffffffff8124e7d5: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81261c32)
Location: fs/dcache.c:2878
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812617c0-ffffffff812617e5: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126f4f2)
Location: fs/dcache.c:2908
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff8126f030-ffffffff8126f055: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81291e12)
Location: fs/dcache.c:2920
Inline: True
Inline callers:
  - fs/dcache.c:is_subdir
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff81291950-ffffffff81291975: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b563e)
Location: fs/dcache.c:2905
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812b7f80-ffffffff812b7fa5: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ca95e)
Location: fs/dcache.c:2859
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812cd0e0-ffffffff812cd105: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e7388)
Location: fs/dcache.c:2928
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812e9cd0-ffffffff812e9cf0: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8ef7)
Location: fs/dcache.c:2928
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812fb870-ffffffff812fb890: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81331eb7)
Location: fs/dcache.c:2949
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
Direct callers:
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
```
**Symbols:**

```
ffffffff81334550-ffffffff81334570: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133d8d7)
Location: fs/dcache.c:2956
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
Direct callers:
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
```
**Symbols:**

```
ffffffff8133ff10-ffffffff8133ff30: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81343bd7)
Location: fs/dcache.c:2982
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
Direct callers:
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
```
**Symbols:**

```
ffffffff81346420-ffffffff81346440: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81391507)
Location: fs/dcache.c:2984
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
Direct callers:
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
```
**Symbols:**

```
ffffffff81393f90-ffffffff81393fb0: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814134a7)
Location: fs/dcache.c:3008
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
Direct callers:
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
```
**Symbols:**

```
ffffffff814159c0-ffffffff814159e8: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149e8d7)
Location: fs/dcache.c:3064
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
Direct callers:
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
```
**Symbols:**

```
ffffffff814a0d70-ffffffff814a0d98: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d49b9)
Location: fs/dcache.c:3064
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff814d6080-ffffffff814d60a8: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81506cf9)
Location: fs/dcache.c:2892
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff81508410-ffffffff81508438: d_ancestor (STB_GLOBAL)
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
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a81c8)
Location: fs/dcache.c:2928
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffff8000103aad50-ffff8000103aad98: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0588ff4)
Location: fs/dcache.c:2928
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
c058bcfc-c058bd38: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a1a90)
Location: fs/dcache.c:2928
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
c0000000004a5f90-c0000000004a5fc0: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026efee)
Location: fs/dcache.c:2928
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffe0002708a4-ffffffe0002708da: d_ancestor (STB_GLOBAL)
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
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f14d7)
Location: fs/dcache.c:2928
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812f3e50-ffffffff812f3e70: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e2107)
Location: fs/dcache.c:2928
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812e4a80-ffffffff812e4aa0: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ef2e7)
Location: fs/dcache.c:2928
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff812f1c60-ffffffff812f1c80: d_ancestor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_ancestor(struct dentry *p1, struct dentry *p2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813005f7)
Location: fs/dcache.c:2928
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff81302e80-ffffffff81302ea0: d_ancestor (STB_GLOBAL)
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
