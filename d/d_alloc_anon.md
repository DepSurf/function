# Function: <code>d_alloc_anon</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b7526)
Location: fs/dcache.c:1717
Inline: True
Inline callers:
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffff812b74f0-ffffffff812b7502: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cc686)
Location: fs/dcache.c:1720
Inline: True
Inline callers:
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffff812cc650-ffffffff812cc662: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e92f0)
Location: fs/dcache.c:1785
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffff812e9240-ffffffff812e9252: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fae90)
Location: fs/dcache.c:1785
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffff812fade0-ffffffff812fadf2: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81332fc2)
Location: fs/dcache.c:1806
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
Direct callers:
  - fs/nsfs.c:__ns_get_path
```
**Symbols:**

```
ffffffff81330ac0-ffffffff81330ad2: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133e4f2)
Location: fs/dcache.c:1813
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
Direct callers:
  - fs/nsfs.c:__ns_get_path
```
**Symbols:**

```
ffffffff8133c430-ffffffff8133c442: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813448e2)
Location: fs/dcache.c:1840
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
Direct callers:
  - fs/nsfs.c:__ns_get_path
```
**Symbols:**

```
ffffffff813428c0-ffffffff813428d2: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813923d2)
Location: fs/dcache.c:1841
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
Direct callers:
  - fs/nsfs.c:__ns_get_path
```
**Symbols:**

```
ffffffff813901e0-ffffffff813901f2: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81414091)
Location: fs/dcache.c:1866
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
Direct callers:
  - fs/nsfs.c:__ns_get_path
```
**Symbols:**

```
ffffffff81411e50-ffffffff81411e6a: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149f4e1)
Location: fs/dcache.c:1866
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
Direct callers:
  - fs/nsfs.c:__ns_get_path
```
**Symbols:**

```
ffffffff8149cbd0-ffffffff8149cbea: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d4801)
Location: fs/dcache.c:1866
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
Direct callers:
  - fs/nsfs.c:__ns_get_path
```
**Symbols:**

```
ffffffff814d1ff0-ffffffff814d200a: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81506a03)
Location: fs/dcache.c:1720
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffff81504a30-ffffffff81504a4a: d_alloc_anon (STB_GLOBAL)
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
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103aa1b0)
Location: fs/dcache.c:1785
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffff8000103aa0c0-ffff8000103aa0f0: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058b1ac)
Location: fs/dcache.c:1785
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
Direct callers:
  - fs/nsfs.c:__ns_get_path
```
**Symbols:**

```
c058b0f0-c058b110: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a5040)
Location: fs/dcache.c:1785
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
c0000000004a4f00-c0000000004a4f18: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026ff44)
Location: fs/dcache.c:1785
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffe00026fe70-ffffffe00026fe9c: d_alloc_anon (STB_GLOBAL)
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
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f3470)
Location: fs/dcache.c:1785
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffff812f33c0-ffffffff812f33d2: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e40a0)
Location: fs/dcache.c:1785
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffff812e3ff0-ffffffff812e4002: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1280)
Location: fs/dcache.c:1785
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffff812f11d0-ffffffff812f11e2: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_alloc_anon(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81302440)
Location: fs/dcache.c:1785
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffff81302390-ffffffff813023a2: d_alloc_anon (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
