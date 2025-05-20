# Function: <code>__traceiter_mmap_lock_released</code>

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
int __traceiter_mmap_lock_released(void *__data, struct mm_struct *mm, const char *memcg_path, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff81295af0)
Location: include/trace/events/mmap_lock.h:76
Inline: False
```
**Symbols:**

```
ffffffff81295af0-ffffffff81295b42: __traceiter_mmap_lock_released (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_mmap_lock_released(void *__data, struct mm_struct *mm, const char *memcg_path, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff8129b430)
Location: include/trace/events/mmap_lock.h:76
Inline: False
```
**Symbols:**

```
ffffffff8129b430-ffffffff8129b480: __traceiter_mmap_lock_released (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_mmap_lock_released(void *__data, struct mm_struct *mm, const char *memcg_path, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff812dbea0)
Location: include/trace/events/mmap_lock.h:76
Inline: False
```
**Symbols:**

```
ffffffff812dbea0-ffffffff812dbef0: __traceiter_mmap_lock_released (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_mmap_lock_released(void *__data, struct mm_struct *mm, const char *memcg_path, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff8133bbe0)
Location: include/trace/events/mmap_lock.h:50
Inline: False
```
**Symbols:**

```
ffffffff8133bbe0-ffffffff8133bc3c: __traceiter_mmap_lock_released (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_mmap_lock_released(void *__data, struct mm_struct *mm, const char *memcg_path, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff813b37e0)
Location: include/trace/events/mmap_lock.h:50
Inline: False
```
**Symbols:**

```
ffffffff813b37e0-ffffffff813b383c: __traceiter_mmap_lock_released (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_mmap_lock_released(void *__data, struct mm_struct *mm, const char *memcg_path, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff813e8420)
Location: include/trace/events/mmap_lock.h:50
Inline: False
```
**Symbols:**

```
ffffffff813e8420-ffffffff813e847c: __traceiter_mmap_lock_released (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_mmap_lock_released(void *__data, struct mm_struct *mm, const char *memcg_path, bool write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff81413090)
Location: include/trace/events/mmap_lock.h:50
Inline: False
```
**Symbols:**

```
ffffffff81413090-ffffffff814130ec: __traceiter_mmap_lock_released (STB_GLOBAL)
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
