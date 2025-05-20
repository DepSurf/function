# Function: <code>__genradix_ptr</code>

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
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8150e500)
Location: lib/generic-radix-tree.c:53
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff8150e500-ffffffff8150e56b: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8152c420)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff8152c420-ffffffff8152c48b: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8158fd80)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff8158fd80-ffffffff8158fdeb: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff815ac8f0)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff815ac8f0-ffffffff815ac95b: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff815b7560)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff815b7560-ffffffff815b75ce: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/generic-radix-tree.c (0)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff81cdaf05-ffffffff81cdaf40: __genradix_ptr.cold (STB_LOCAL)
ffffffff8161df20-ffffffff8161dfd5: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/generic-radix-tree.c (0)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff81e937b9-ffffffff81e937f4: __genradix_ptr.cold (STB_LOCAL)
ffffffff816ebb30-ffffffff816ebbfe: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/generic-radix-tree.c (0)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff82078981-ffffffff820789bc: __genradix_ptr.cold (STB_LOCAL)
ffffffff817dc2b0-ffffffff817dc37e: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/generic-radix-tree.c (0)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff820f8f58-ffffffff820f8f93: __genradix_ptr.cold (STB_LOCAL)
ffffffff8181b750-ffffffff8181b864: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/generic-radix-tree.c (0)
Location: lib/generic-radix-tree.c:55
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff821d6ac5-ffffffff821d6b00: __genradix_ptr.cold (STB_LOCAL)
ffffffff81860a10-ffffffff81860b24: __genradix_ptr (STB_GLOBAL)
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
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffff800010638398)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffff800010638398-ffff800010638414: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (c07ddcb0)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
c07ddcb0-c07ddd38: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (c0000000007de6a0)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
c0000000007de6a0-c0000000007de738: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffe00046516c)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffe00046516c-ffffffe00046520e: __genradix_ptr (STB_GLOBAL)
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
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff81524a00)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff81524a00-ffffffff81524a6b: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff81514ce0)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff81514ce0-ffffffff81514d4b: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff81520a90)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff81520a90-ffffffff81520afb: __genradix_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__genradix_ptr(struct __genradix *radix, size_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8153a410)
Location: lib/generic-radix-tree.c:54
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_readdir
```
**Symbols:**

```
ffffffff8153a410-ffffffff8153a47b: __genradix_ptr (STB_GLOBAL)
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
