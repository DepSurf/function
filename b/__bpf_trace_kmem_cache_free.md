# Function: <code>__bpf_trace_kmem_cache_free</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128ca10)
Location: include/trace/events/kmem.h:138
Inline: False
```
**Symbols:**

```
ffffffff8128ca10-ffffffff8128ca1b: __bpf_trace_kmem_cache_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812cc7d0)
Location: include/trace/events/kmem.h:138
Inline: False
```
**Symbols:**

```
ffffffff812cc7d0-ffffffff812cc7db: __bpf_trace_kmem_cache_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132aed0)
Location: include/trace/events/kmem.h:138
Inline: False
```
**Symbols:**

```
ffffffff8132aed0-ffffffff8132aee7: __bpf_trace_kmem_cache_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr, const struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a02e0)
Location: include/trace/events/kmem.h:114
Inline: False
```
**Symbols:**

```
ffffffff813a02e0-ffffffff813a02f7: __bpf_trace_kmem_cache_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr, const struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d35a0)
Location: include/trace/events/kmem.h:114
Inline: False
```
**Symbols:**

```
ffffffff813d35a0-ffffffff813d35b7: __bpf_trace_kmem_cache_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_kmem_cache_free(void *__data, long unsigned int call_site, const void *ptr, const struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fdfa0)
Location: include/trace/events/kmem.h:114
Inline: False
```
**Symbols:**

```
ffffffff813fdfa0-ffffffff813fdfb7: __bpf_trace_kmem_cache_free (STB_LOCAL)
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
