# Function: <code>__traceiter_memory_failure_event</code>

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
int __traceiter_memory_failure_event(void *__data, long unsigned int pfn, int type, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff819d6ec0)
Location: include/ras/ras_event.h:402
Inline: False
```
**Symbols:**

```
ffffffff819d6ec0-ffffffff819d6f11: __traceiter_memory_failure_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_memory_failure_event(void *__data, long unsigned int pfn, int type, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff819bd040)
Location: include/ras/ras_event.h:402
Inline: False
```
**Symbols:**

```
ffffffff819bd040-ffffffff819bd08f: __traceiter_memory_failure_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_memory_failure_event(void *__data, long unsigned int pfn, int type, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81a6c5d0)
Location: include/ras/ras_event.h:402
Inline: False
```
**Symbols:**

```
ffffffff81a6c5d0-ffffffff81a6c61f: __traceiter_memory_failure_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_memory_failure_event(void *__data, long unsigned int pfn, int type, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81bdd170)
Location: include/ras/ras_event.h:400
Inline: False
```
**Symbols:**

```
ffffffff81bdd170-ffffffff81bdd1cb: __traceiter_memory_failure_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_memory_failure_event(void *__data, long unsigned int pfn, int type, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81d88410)
Location: include/ras/ras_event.h:399
Inline: False
```
**Symbols:**

```
ffffffff81d88410-ffffffff81d8846b: __traceiter_memory_failure_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_memory_failure_event(void *__data, long unsigned int pfn, int type, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81df6a00)
Location: include/ras/ras_event.h:399
Inline: False
```
**Symbols:**

```
ffffffff81df6a00-ffffffff81df6a5b: __traceiter_memory_failure_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_memory_failure_event(void *__data, long unsigned int pfn, int type, int result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/ras.c (ffffffff81ead110)
Location: include/ras/ras_event.h:399
Inline: False
```
**Symbols:**

```
ffffffff81ead110-ffffffff81ead16b: __traceiter_memory_failure_event (STB_GLOBAL)
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
