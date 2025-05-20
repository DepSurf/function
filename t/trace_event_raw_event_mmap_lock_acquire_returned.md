# Function: <code>trace_event_raw_event_mmap_lock_acquire_returned</code>

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
void trace_event_raw_event_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff81295de0)
Location: include/trace/events/mmap_lock.h:44
Inline: False
```
**Symbols:**

```
ffffffff81295de0-ffffffff81295f0a: trace_event_raw_event_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_event_raw_event_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff8129b700)
Location: include/trace/events/mmap_lock.h:44
Inline: False
```
**Symbols:**

```
ffffffff8129b700-ffffffff8129b826: trace_event_raw_event_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_event_raw_event_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff812dc1f0)
Location: include/trace/events/mmap_lock.h:44
Inline: False
```
**Symbols:**

```
ffffffff812dc1f0-ffffffff812dc316: trace_event_raw_event_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_event_raw_event_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff8133c740)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff8133c740-ffffffff8133c86c: trace_event_raw_event_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff813b4460)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff813b4460-ffffffff813b458c: trace_event_raw_event_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff813e90e0)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff813e90e0-ffffffff813e920c: trace_event_raw_event_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff81413d90)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff81413d90-ffffffff81413ebc: trace_event_raw_event_mmap_lock_acquire_returned (STB_LOCAL)
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
