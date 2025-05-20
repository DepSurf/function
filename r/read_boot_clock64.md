# Function: <code>read_boot_clock64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void read_boot_clock64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f60f0)
Location: kernel/time/timekeeping.c:1445
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff810f60f0-ffffffff810f610a: read_boot_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void read_boot_clock64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fd310)
Location: kernel/time/timekeeping.c:1450
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff810fd310-ffffffff810fd32a: read_boot_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void read_boot_clock64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100100)
Location: kernel/time/timekeeping.c:1479
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff81100100-ffffffff8110011a: read_boot_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void read_boot_clock64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1471
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff811022d0-ffffffff811022ea: read_boot_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void read_boot_clock64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110d270)
Location: kernel/time/timekeeping.c:1506
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff8110d270-ffffffff8110d28a: read_boot_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void read_boot_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81118df0)
Location: kernel/time/timekeeping.c:1507
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff81118df0-ffffffff81118e0a: read_boot_clock64 (STB_WEAK)
```
</details>
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
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *ts</code> ➡️ <code>struct timespec64 *ts</code>
</li>
</ul>
</details>
</li>
</ul>
