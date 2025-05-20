# Function: <code>__genradix_ptr_alloc</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8150e6b0)
Location: lib/generic-radix-tree.c:82
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff8150e6b0-ffffffff8150e866: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8152c560)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff8152c560-ffffffff8152c716: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8158fec0)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff8158fec0-ffffffff81590082: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff815aca30)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff815aca30-ffffffff815acbf2: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff815b76a0)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff815b76a0-ffffffff815b7865: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/generic-radix-tree.c (0)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff81cdae1e-ffffffff81cdae5c: __genradix_ptr_alloc.cold (STB_LOCAL)
ffffffff8161db90-ffffffff8161dd91: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/generic-radix-tree.c (0)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff81e936da-ffffffff81e93719: __genradix_ptr_alloc.cold (STB_LOCAL)
ffffffff816eb760-ffffffff816eb927: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/generic-radix-tree.c (0)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff820788a2-ffffffff820788e1: __genradix_ptr_alloc.cold (STB_LOCAL)
ffffffff817dbeb0-ffffffff817dc077: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/generic-radix-tree.c (0)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff820f8e77-ffffffff820f8ec0: __genradix_ptr_alloc.cold (STB_LOCAL)
ffffffff8181b270-ffffffff8181b490: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/generic-radix-tree.c (0)
Location: lib/generic-radix-tree.c:105
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff821d6b00-ffffffff821d6b49: __genradix_ptr_alloc.cold (STB_LOCAL)
ffffffff81860b40-ffffffff81860d60: __genradix_ptr_alloc (STB_GLOBAL)
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
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffff800010638560)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffff800010638560-ffff800010638794: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (c07dde94)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
c07dde94-c07de0b0: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (c0000000007de840)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
c0000000007de840-c0000000007deb5c: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffe000465282)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffe000465282-ffffffe000465494: __genradix_ptr_alloc (STB_GLOBAL)
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
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff81524b40)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff81524b40-ffffffff81524cf6: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff81514e20)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff81514e20-ffffffff81514fd6: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff81520bd0)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff81520bd0-ffffffff81520d86: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__genradix_ptr_alloc(struct __genradix *radix, size_t offset, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8153a550)
Location: lib/generic-radix-tree.c:104
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
  - lib/generic-radix-tree.c:__genradix_prealloc
```
**Symbols:**

```
ffffffff8153a550-ffffffff8153a706: __genradix_ptr_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
