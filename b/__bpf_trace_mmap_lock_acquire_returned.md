# Function: <code>__bpf_trace_mmap_lock_acquire_returned</code>

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
void __bpf_trace_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff81295cc0)
Location: include/trace/events/mmap_lock.h:44
Inline: False
```
**Symbols:**

```
ffffffff81295cc0-ffffffff81295cd2: __bpf_trace_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff8129b5f0)
Location: include/trace/events/mmap_lock.h:44
Inline: False
```
**Symbols:**

```
ffffffff8129b5f0-ffffffff8129b602: __bpf_trace_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff812dbf00)
Location: include/trace/events/mmap_lock.h:44
Inline: False
```
**Symbols:**

```
ffffffff812dbf00-ffffffff812dbf12: __bpf_trace_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff8133bcd0)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff8133bcd0-ffffffff8133bcf1: __bpf_trace_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff813b3900)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff813b3900-ffffffff813b3921: __bpf_trace_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff813e8560)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff813e8560-ffffffff813e8581: __bpf_trace_mmap_lock_acquire_returned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff814131d0)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff814131d0-ffffffff814131f1: __bpf_trace_mmap_lock_acquire_returned (STB_LOCAL)
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
