# Function: <code>__kfence_free</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (0)
Location: include/linux/kfence.h:213
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __kfence_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff8133c840)
Location: mm/kfence/core.c:803
Inline: False
Direct callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff8133c840-ffffffff8133c8e7: __kfence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __kfence_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff813afc10)
Location: mm/kfence/core.c:1068
Inline: False
Direct callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff813afc10-ffffffff813afce6: __kfence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __kfence_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff81430200)
Location: mm/kfence/core.c:1054
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81430200-ffffffff814302d6: __kfence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __kfence_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff81465b90)
Location: mm/kfence/core.c:1092
Inline: False
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81465b90-ffffffff81465c66: __kfence_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __kfence_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff81494e10)
Location: mm/kfence/core.c:1138
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff81494e10-ffffffff81494ec4: __kfence_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
