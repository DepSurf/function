# Function: <code>proc_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127f610)
Location: fs/proc/generic.c:253
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff8127f610-ffffffff8127f62d: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ac6f0)
Location: fs/proc/generic.c:257
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff812ac6f0-ffffffff812ac70d: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c1fe0)
Location: fs/proc/generic.c:257
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff812c1fe0-ffffffff812c1ffd: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812cf2a0)
Location: fs/proc/generic.c:240
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff812cf2a0-ffffffff812cf2bd: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3a10)
Location: fs/proc/generic.c:242
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff812f3a10-ffffffff812f3a2d: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813205f0)
Location: fs/proc/generic.c:266
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff813205f0-ffffffff81320604: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813376e0)
Location: fs/proc/generic.c:266
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff813376e0-ffffffff813376f4: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135f820)
Location: fs/proc/generic.c:267
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff8135f820-ffffffff8135f834: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81377a80)
Location: fs/proc/generic.c:267
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff81377a80-ffffffff81377a94: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0920)
Location: fs/proc/generic.c:269
Inline: True
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff813c0920-ffffffff813c094d: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d2770)
Location: fs/proc/generic.c:269
Inline: True
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff813d2770-ffffffff813d279d: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d9570)
Location: fs/proc/generic.c:264
Inline: True
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff813d9570-ffffffff813d959d: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142aca0)
Location: fs/proc/generic.c:264
Inline: True
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff8142aca0-ffffffff8142accd: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a42d0)
Location: fs/proc/generic.c:264
Inline: True
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff814a42d0-ffffffff814a4311: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81539720)
Location: fs/proc/generic.c:264
Inline: True
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff81539720-ffffffff81539761: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815719a0)
Location: fs/proc/generic.c:263
Inline: True
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff815719a0-ffffffff815719e1: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aa350)
Location: fs/proc/generic.c:263
Inline: True
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff815aa350-ffffffff815aa391: proc_lookup (STB_GLOBAL)
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
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff800010443828)
Location: fs/proc/generic.c:267
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffff800010443828-ffff800010443860: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0608abc)
Location: fs/proc/generic.c:267
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
c0608abc-c0608adc: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c000000000558ef0)
Location: fs/proc/generic.c:267
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
c000000000558ef0-c000000000558f08: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002da15e)
Location: fs/proc/generic.c:267
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffe0002da15e-ffffffe0002da194: proc_lookup (STB_GLOBAL)
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
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81370060)
Location: fs/proc/generic.c:267
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff81370060-ffffffff81370074: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360af0)
Location: fs/proc/generic.c:267
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff81360af0-ffffffff81360b04: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136db30)
Location: fs/proc/generic.c:267
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff8136db30-ffffffff8136db44: proc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *proc_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81381460)
Location: fs/proc/generic.c:267
Inline: False
Direct callers:
  - fs/proc/root.c:proc_root_lookup
```
**Symbols:**

```
ffffffff81381460-ffffffff81381474: proc_lookup (STB_GLOBAL)
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
