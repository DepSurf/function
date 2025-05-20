# Function: <code>__rhashtable_walk_find_next</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814cc1d0)
Location: lib/rhashtable.c:799
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff814cc1d0-ffffffff814cc303: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814e0a40)
Location: lib/rhashtable.c:791
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff814e0a40-ffffffff814e0b7c: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8150ca00)
Location: lib/rhashtable.c:780
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff8150ca00-ffffffff8150cb7c: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8152a850)
Location: lib/rhashtable.c:780
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff8152a850-ffffffff8152a9cc: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8158ee60)
Location: lib/rhashtable.c:787
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff8158ee60-ffffffff8158efa0: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815ab9d0)
Location: lib/rhashtable.c:787
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff815ab9d0-ffffffff815abb10: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815b5eb0)
Location: lib/rhashtable.c:787
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff815b5eb0-ffffffff815b5ff9: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:787
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff8161c350-ffffffff8161c4ad: __rhashtable_walk_find_next (STB_LOCAL)
ffffffff81cdabef-ffffffff81cdac0c: __rhashtable_walk_find_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:787
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff816e9ad0-ffffffff816e9c66: __rhashtable_walk_find_next (STB_LOCAL)
ffffffff81e934bf-ffffffff81e934dc: __rhashtable_walk_find_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:791
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff817d9c90-ffffffff817d9e26: __rhashtable_walk_find_next (STB_LOCAL)
ffffffff8207862b-ffffffff82078648: __rhashtable_walk_find_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:791
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff81819010-ffffffff818191a6: __rhashtable_walk_find_next (STB_LOCAL)
ffffffff820f8ba7-ffffffff820f8bc4: __rhashtable_walk_find_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (0)
Location: lib/rhashtable.c:791
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff8185e360-ffffffff8185e4f6: __rhashtable_walk_find_next (STB_LOCAL)
ffffffff821d66c8-ffffffff821d66e5: __rhashtable_walk_find_next.cold (STB_LOCAL)
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
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffff800010636290)
Location: lib/rhashtable.c:780
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffff800010636290-ffff8000106363fc: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c07dc1c8)
Location: lib/rhashtable.c:780
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
c07dc1c8-c07dc370: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c0000000007db8f0)
Location: lib/rhashtable.c:780
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
c0000000007db8f0-c0000000007dbb50: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffe000463486)
Location: lib/rhashtable.c:780
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffe000463486-ffffffe0004635ac: __rhashtable_walk_find_next (STB_LOCAL)
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
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81522e30)
Location: lib/rhashtable.c:780
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff81522e30-ffffffff81522fac: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81513110)
Location: lib/rhashtable.c:780
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff81513110-ffffffff8151328c: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8151eec0)
Location: lib/rhashtable.c:780
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff8151eec0-ffffffff8151f03c: __rhashtable_walk_find_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__rhashtable_walk_find_next(struct rhashtable_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff815388e0)
Location: lib/rhashtable.c:780
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_walk_next
```
**Symbols:**

```
ffffffff815388e0-ffffffff81538a5c: __rhashtable_walk_find_next (STB_LOCAL)
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
