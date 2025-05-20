# Function: <code>__getnstimeofday64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __getnstimeofday64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f58d0)
Location: kernel/time/timekeeping.c:643
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
```
**Symbols:**

```
ffffffff810f58d0-ffffffff810f5996: __getnstimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __getnstimeofday64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fc9f0)
Location: kernel/time/timekeeping.c:648
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_gettimeofday
```
**Symbols:**

```
ffffffff810fc9f0-ffffffff810fcabc: __getnstimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __getnstimeofday64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810ff910)
Location: kernel/time/timekeeping.c:677
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_gettimeofday
```
**Symbols:**

```
ffffffff810ff910-ffffffff810ff9dc: __getnstimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __getnstimeofday64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81101a60)
Location: kernel/time/timekeeping.c:709
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_gettimeofday
  - fs/pstore/platform.c:pstore_record_init
```
**Symbols:**

```
ffffffff81101a60-ffffffff81101b2b: __getnstimeofday64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __getnstimeofday64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110c960)
Location: kernel/time/timekeeping.c:713
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_gettimeofday
```
**Symbols:**

```
ffffffff8110c960-ffffffff8110ca2e: __getnstimeofday64 (STB_GLOBAL)
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
