# Function: <code>__traceiter_percpu_free_percpu</code>

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
int __traceiter_percpu_free_percpu(void *__data, void *base_addr, int off, void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81282c10)
Location: include/trace/events/percpu.h:43
Inline: False
```
**Symbols:**

```
ffffffff81282c10-ffffffff81282c61: __traceiter_percpu_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_percpu_free_percpu(void *__data, void *base_addr, int off, void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81287d40)
Location: include/trace/events/percpu.h:43
Inline: False
```
**Symbols:**

```
ffffffff81287d40-ffffffff81287d8f: __traceiter_percpu_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_percpu_free_percpu(void *__data, void *base_addr, int off, void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c74e0)
Location: include/trace/events/percpu.h:43
Inline: False
```
**Symbols:**

```
ffffffff812c74e0-ffffffff812c752f: __traceiter_percpu_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_percpu_free_percpu(void *__data, void *base_addr, int off, void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81324870)
Location: include/trace/events/percpu.h:54
Inline: False
```
**Symbols:**

```
ffffffff81324870-ffffffff813248cb: __traceiter_percpu_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_percpu_free_percpu(void *__data, void *base_addr, int off, void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81399280)
Location: include/trace/events/percpu.h:54
Inline: False
```
**Symbols:**

```
ffffffff81399280-ffffffff813992db: __traceiter_percpu_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_percpu_free_percpu(void *__data, void *base_addr, int off, void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cc2b0)
Location: include/trace/events/percpu.h:54
Inline: False
```
**Symbols:**

```
ffffffff813cc2b0-ffffffff813cc30b: __traceiter_percpu_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_percpu_free_percpu(void *__data, void *base_addr, int off, void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813f6c20)
Location: include/trace/events/percpu.h:54
Inline: False
```
**Symbols:**

```
ffffffff813f6c20-ffffffff813f6c7b: __traceiter_percpu_free_percpu (STB_GLOBAL)
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
