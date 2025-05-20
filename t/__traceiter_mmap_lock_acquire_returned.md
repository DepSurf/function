# Function: <code>__traceiter_mmap_lock_acquire_returned</code>

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
int __traceiter_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff81295a90)
Location: include/trace/events/mmap_lock.h:44
Inline: False
```
**Symbols:**

```
ffffffff81295a90-ffffffff81295aed: __traceiter_mmap_lock_acquire_returned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff8129b3d0)
Location: include/trace/events/mmap_lock.h:44
Inline: False
```
**Symbols:**

```
ffffffff8129b3d0-ffffffff8129b42b: __traceiter_mmap_lock_acquire_returned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff812dbe40)
Location: include/trace/events/mmap_lock.h:44
Inline: False
```
**Symbols:**

```
ffffffff812dbe40-ffffffff812dbe9b: __traceiter_mmap_lock_acquire_returned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff8133bc40)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff8133bc40-ffffffff8133bcaa: __traceiter_mmap_lock_acquire_returned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff813b3850)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff813b3850-ffffffff813b38ba: __traceiter_mmap_lock_acquire_returned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff813e8490)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff813e8490-ffffffff813e84fa: __traceiter_mmap_lock_acquire_returned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_mmap_lock_acquire_returned(void *__data, struct mm_struct *mm, const char *memcg_path, bool write, bool success);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff81413100)
Location: include/trace/events/mmap_lock.h:52
Inline: False
```
**Symbols:**

```
ffffffff81413100-ffffffff8141316a: __traceiter_mmap_lock_acquire_returned (STB_GLOBAL)
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
