# Function: <code>get_mm_memcg_path</code>

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
const char *get_mm_memcg_path(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff81295f10)
Location: mm/mmap_lock.c:157
Inline: False
Direct callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
**Symbols:**

```
ffffffff81295f10-ffffffff81295fc6: get_mm_memcg_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *get_mm_memcg_path(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff8129b830)
Location: mm/mmap_lock.c:168
Inline: False
Direct callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
**Symbols:**

```
ffffffff8129b830-ffffffff8129b8e3: get_mm_memcg_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *get_mm_memcg_path(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff812dc320)
Location: mm/mmap_lock.c:199
Inline: False
Direct callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
**Symbols:**

```
ffffffff812dc320-ffffffff812dc3d3: get_mm_memcg_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *get_mm_memcg_path(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff8133c280)
Location: mm/mmap_lock.c:199
Inline: False
Direct callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
**Symbols:**

```
ffffffff8133c280-ffffffff8133c360: get_mm_memcg_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *get_mm_memcg_path(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff813b3dc0)
Location: mm/mmap_lock.c:199
Inline: False
Direct callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
**Symbols:**

```
ffffffff813b3dc0-ffffffff813b3ea0: get_mm_memcg_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *get_mm_memcg_path(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff813e8710)
Location: mm/mmap_lock.c:199
Inline: False
Direct callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
**Symbols:**

```
ffffffff813e8710-ffffffff813e87f0: get_mm_memcg_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *get_mm_memcg_path(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap_lock.c (ffffffff814133a0)
Location: mm/mmap_lock.c:199
Inline: False
Direct callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
**Symbols:**

```
ffffffff814133a0-ffffffff81413480: get_mm_memcg_path (STB_LOCAL)
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
