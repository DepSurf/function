# Function: <code>__traceiter_percpu_alloc_percpu_fail</code>

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
int __traceiter_percpu_alloc_percpu_fail(void *__data, bool reserved, bool is_atomic, size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81282c70)
Location: include/trace/events/percpu.h:65
Inline: False
```
**Symbols:**

```
ffffffff81282c70-ffffffff81282ccd: __traceiter_percpu_alloc_percpu_fail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_percpu_alloc_percpu_fail(void *__data, bool reserved, bool is_atomic, size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81287d90)
Location: include/trace/events/percpu.h:65
Inline: False
```
**Symbols:**

```
ffffffff81287d90-ffffffff81287deb: __traceiter_percpu_alloc_percpu_fail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_percpu_alloc_percpu_fail(void *__data, bool reserved, bool is_atomic, size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c7530)
Location: include/trace/events/percpu.h:65
Inline: False
```
**Symbols:**

```
ffffffff812c7530-ffffffff812c758b: __traceiter_percpu_alloc_percpu_fail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_percpu_alloc_percpu_fail(void *__data, bool reserved, bool is_atomic, size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813248d0)
Location: include/trace/events/percpu.h:76
Inline: False
```
**Symbols:**

```
ffffffff813248d0-ffffffff8132493a: __traceiter_percpu_alloc_percpu_fail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_percpu_alloc_percpu_fail(void *__data, bool reserved, bool is_atomic, size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813992f0)
Location: include/trace/events/percpu.h:76
Inline: False
```
**Symbols:**

```
ffffffff813992f0-ffffffff8139935a: __traceiter_percpu_alloc_percpu_fail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_percpu_alloc_percpu_fail(void *__data, bool reserved, bool is_atomic, size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cc340)
Location: include/trace/events/percpu.h:76
Inline: False
```
**Symbols:**

```
ffffffff813cc340-ffffffff813cc3aa: __traceiter_percpu_alloc_percpu_fail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_percpu_alloc_percpu_fail(void *__data, bool reserved, bool is_atomic, size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813f6cb0)
Location: include/trace/events/percpu.h:76
Inline: False
```
**Symbols:**

```
ffffffff813f6cb0-ffffffff813f6d1a: __traceiter_percpu_alloc_percpu_fail (STB_GLOBAL)
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
