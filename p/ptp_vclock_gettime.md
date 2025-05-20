# Function: <code>ptp_vclock_gettime</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ptp_vclock_gettime(struct ptp_clock_info *ptp, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff819db2f5)
Location: drivers/ptp/ptp_vclock.c:45
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
```
**Symbols:**

```
ffffffff819db030-ffffffff819db092: ptp_vclock_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ptp_vclock_gettime(struct ptp_clock_info *ptp, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81b3ec25)
Location: drivers/ptp/ptp_vclock.c:72
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
```
**Symbols:**

```
ffffffff81b3e820-ffffffff81b3e888: ptp_vclock_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ptp_vclock_gettime(struct ptp_clock_info *ptp, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81cd4fb5)
Location: drivers/ptp/ptp_vclock.c:72
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
```
**Symbols:**

```
ffffffff81cd4b30-ffffffff81cd4ba1: ptp_vclock_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ptp_vclock_gettime(struct ptp_clock_info *ptp, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81d3cc35)
Location: drivers/ptp/ptp_vclock.c:72
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
```
**Symbols:**

```
ffffffff81d3c790-ffffffff81d3c801: ptp_vclock_gettime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ptp_vclock_gettime(struct ptp_clock_info *ptp, struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81df3575)
Location: drivers/ptp/ptp_vclock.c:72
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
```
**Symbols:**

```
ffffffff81df30d0-ffffffff81df3141: ptp_vclock_gettime (STB_LOCAL)
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
