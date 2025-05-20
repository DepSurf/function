# Function: <code>__current_kernel_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct timespec __current_kernel_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f6960)
Location: kernel/time/timekeeping.c:2148
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff810f6960-ffffffff810f6982: __current_kernel_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct timespec __current_kernel_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fdb60)
Location: kernel/time/timekeeping.c:2153
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff810fdb60-ffffffff810fdb82: __current_kernel_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct timespec __current_kernel_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100950)
Location: kernel/time/timekeeping.c:2165
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff81100950-ffffffff81100972: __current_kernel_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct timespec __current_kernel_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81102a90)
Location: kernel/time/timekeeping.c:2154
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff81102a90-ffffffff81102ab6: __current_kernel_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct timespec __current_kernel_time();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110da30)
Location: kernel/time/timekeeping.c:2183
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_summary
```
**Symbols:**

```
ffffffff8110da30-ffffffff8110da56: __current_kernel_time (STB_GLOBAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
