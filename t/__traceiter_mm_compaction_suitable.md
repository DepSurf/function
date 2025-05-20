# Function: <code>__traceiter_mm_compaction_suitable</code>

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
int __traceiter_mm_compaction_suitable(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81289250)
Location: include/trace/events/compaction.h:235
Inline: False
```
**Symbols:**

```
ffffffff81289250-ffffffff812892a1: __traceiter_mm_compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_mm_compaction_suitable(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128e8d0)
Location: include/trace/events/compaction.h:235
Inline: False
```
**Symbols:**

```
ffffffff8128e8d0-ffffffff8128e91f: __traceiter_mm_compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_mm_compaction_suitable(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812ce810)
Location: include/trace/events/compaction.h:235
Inline: False
```
**Symbols:**

```
ffffffff812ce810-ffffffff812ce85f: __traceiter_mm_compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_mm_compaction_suitable(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8132c900)
Location: include/trace/events/compaction.h:219
Inline: False
```
**Symbols:**

```
ffffffff8132c900-ffffffff8132c95b: __traceiter_mm_compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_mm_compaction_suitable(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a2e10)
Location: include/trace/events/compaction.h:219
Inline: False
```
**Symbols:**

```
ffffffff813a2e10-ffffffff813a2e6b: __traceiter_mm_compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_mm_compaction_suitable(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813d63a0)
Location: include/trace/events/compaction.h:230
Inline: False
```
**Symbols:**

```
ffffffff813d63a0-ffffffff813d63fb: __traceiter_mm_compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_mm_compaction_suitable(void *__data, struct zone *zone, int order, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81400070)
Location: include/trace/events/compaction.h:230
Inline: False
```
**Symbols:**

```
ffffffff81400070-ffffffff814000cb: __traceiter_mm_compaction_suitable (STB_GLOBAL)
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
