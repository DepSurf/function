# Function: <code>__traceiter_kmem_cache_free</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812865f0)
Location: include/trace/events/kmem.h:145
Inline: False
```
**Symbols:**

```
ffffffff812865f0-ffffffff81286637: __traceiter_kmem_cache_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128b8b0)
Location: include/trace/events/kmem.h:138
Inline: False
```
**Symbols:**

```
ffffffff8128b8b0-ffffffff8128b8ff: __traceiter_kmem_cache_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812cb670)
Location: include/trace/events/kmem.h:138
Inline: False
```
**Symbols:**

```
ffffffff812cb670-ffffffff812cb6bf: __traceiter_kmem_cache_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81329100)
Location: include/trace/events/kmem.h:138
Inline: False
```
**Symbols:**

```
ffffffff81329100-ffffffff8132915b: __traceiter_kmem_cache_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr, const struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8139e240)
Location: include/trace/events/kmem.h:114
Inline: False
```
**Symbols:**

```
ffffffff8139e240-ffffffff8139e29b: __traceiter_kmem_cache_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr, const struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d1400)
Location: include/trace/events/kmem.h:114
Inline: False
```
**Symbols:**

```
ffffffff813d1400-ffffffff813d145b: __traceiter_kmem_cache_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr, const struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fbe30)
Location: include/trace/events/kmem.h:114
Inline: False
```
**Symbols:**

```
ffffffff813fbe30-ffffffff813fbe8b: __traceiter_kmem_cache_free (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct kmem_cache *s</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
