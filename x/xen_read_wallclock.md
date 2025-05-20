# Function: <code>xen_read_wallclock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810234b0)
Location: arch/x86/xen/time.c:172
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/xen/time.c:xen_time_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81f8b573)
Location: arch/x86/xen/time.c:59
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81fc6956)
Location: arch/x86/xen/time.c:59
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff820a3878)
Location: arch/x86/xen/time.c:59
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff826a9d62)
Location: arch/x86/xen/time.c:60
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff826d2ec8)
Location: arch/x86/xen/time.c:60
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff82888f58)
Location: arch/x86/xen/time.c:67
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff828a0201)
Location: arch/x86/xen/time.c:67
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff828a32f1)
Location: arch/x86/xen/time.c:67
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xen_read_wallclock(struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81020500)
Location: arch/x86/xen/time.c:67
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_get_wallclock
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
```
**Symbols:**

```
ffffffff81020430-ffffffff81020462: xen_read_wallclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xen_read_wallclock(struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81020f4b)
Location: arch/x86/xen/time.c:68
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_get_wallclock
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
```
**Symbols:**

```
ffffffff81020e60-ffffffff81020e92: xen_read_wallclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xen_read_wallclock(struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810232eb)
Location: arch/x86/xen/time.c:68
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_get_wallclock
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
```
**Symbols:**

```
ffffffff81023230-ffffffff81023262: xen_read_wallclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xen_read_wallclock(struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810274bb)
Location: arch/x86/xen/time.c:68
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_get_wallclock
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
```
**Symbols:**

```
ffffffff81027440-ffffffff81027472: xen_read_wallclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xen_read_wallclock(struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8102b71b)
Location: arch/x86/xen/time.c:68
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_get_wallclock
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
```
**Symbols:**

```
ffffffff8102b670-ffffffff8102b6d1: xen_read_wallclock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff83e6abf7)
Location: arch/x86/xen/time.c:68
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8368b59a)
Location: arch/x86/xen/time.c:76
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff838bb15a)
Location: arch/x86/xen/time.c:76
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/xen/enlighten.c (ffff80001143aa38)
Location: arch/arm/xen/enlighten.c:72
Inline: True
Inline callers:
  - arch/arm/xen/enlighten.c:xen_pm_init
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff828912f1)
Location: arch/x86/xen/time.c:67
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff828a42f1)
Location: arch/x86/xen/time.c:67
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_read_wallclock(struct timespec64 *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101e340)
Location: arch/x86/xen/time.c:67
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_get_wallclock
```
**Symbols:**

```
ffffffff8101e340-ffffffff8101e389: xen_read_wallclock (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
</ul>
