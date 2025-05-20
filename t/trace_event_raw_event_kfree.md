# Function: <code>trace_event_raw_event_kfree</code>

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
void trace_event_raw_event_kfree(void *__data, long unsigned int call_site, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128d700)
Location: include/trace/events/kmem.h:118
Inline: False
```
**Symbols:**

```
ffffffff8128d700-ffffffff8128d7b2: trace_event_raw_event_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_event_raw_event_kfree(void *__data, long unsigned int call_site, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812cd540)
Location: include/trace/events/kmem.h:118
Inline: False
```
**Symbols:**

```
ffffffff812cd540-ffffffff812cd5f2: trace_event_raw_event_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_event_raw_event_kfree(void *__data, long unsigned int call_site, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81329f40)
Location: include/trace/events/kmem.h:118
Inline: False
```
**Symbols:**

```
ffffffff81329f40-ffffffff81329fe8: trace_event_raw_event_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_kfree(void *__data, long unsigned int call_site, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8139f1e0)
Location: include/trace/events/kmem.h:94
Inline: False
```
**Symbols:**

```
ffffffff8139f1e0-ffffffff8139f288: trace_event_raw_event_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_kfree(void *__data, long unsigned int call_site, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d24a0)
Location: include/trace/events/kmem.h:94
Inline: False
```
**Symbols:**

```
ffffffff813d24a0-ffffffff813d2548: trace_event_raw_event_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_kfree(void *__data, long unsigned int call_site, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fcea0)
Location: include/trace/events/kmem.h:94
Inline: False
```
**Symbols:**

```
ffffffff813fcea0-ffffffff813fcf48: trace_event_raw_event_kfree (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
