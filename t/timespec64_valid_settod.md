# Function: <code>timespec64_valid_settod</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811272eb)
Location: include/linux/time64.h:114
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff828c849b)
Location: include/linux/time64.h:114
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113328b)
Location: include/linux/time64.h:116
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff828d0a79)
Location: include/linux/time64.h:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811425ab)
Location: include/linux/time64.h:108
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff82cf19be)
Location: include/linux/time64.h:108
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113e7bb)
Location: include/linux/time64.h:108
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff82fde448)
Location: include/linux/time64.h:108
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113f9eb)
Location: include/linux/time64.h:108
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff831e8f72)
Location: include/linux/time64.h:108
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162e7b)
Location: include/linux/time64.h:110
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff832cd526)
Location: include/linux/time64.h:110
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195ecb)
Location: include/linux/time64.h:110
Inline: True
Inline callers:
  - kernel/time/time.c:do_sys_settimeofday64
```
```
In kernel/time/timekeeping.c (ffffffff83481114)
Location: include/linux/time64.h:110
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d3e5b)
Location: include/linux/time64.h:113
Inline: True
Inline callers:
  - kernel/time/time.c:do_sys_settimeofday64
```
```
In kernel/time/timekeeping.c (ffffffff83eadf47)
Location: include/linux/time64.h:113
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e814b)
Location: include/linux/time64.h:113
Inline: True
Inline callers:
  - kernel/time/time.c:do_sys_settimeofday64
```
```
In kernel/time/timekeeping.c (ffffffff836d2f87)
Location: include/linux/time64.h:113
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fde7b)
Location: include/linux/time64.h:113
Inline: True
Inline callers:
  - kernel/time/time.c:do_sys_settimeofday64
```
```
In kernel/time/timekeeping.c (ffffffff83904d47)
Location: include/linux/time64.h:113
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019ba50)
Location: include/linux/time64.h:116
Inline: True
```
```
In kernel/time/timekeeping.c (ffff8000114489d4)
Location: include/linux/time64.h:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e56dc)
Location: include/linux/time64.h:116
Inline: True
```
```
In kernel/time/timekeeping.c (c15229f0)
Location: include/linux/time64.h:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fb434)
Location: include/linux/time64.h:116
Inline: True
```
```
In kernel/time/timekeeping.c (c00000000136db4c)
Location: include/linux/time64.h:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012aaa8)
Location: include/linux/time64.h:116
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffe000009f38)
Location: include/linux/time64.h:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112ba3b)
Location: include/linux/time64.h:116
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff828b992a)
Location: include/linux/time64.h:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111e2ab)
Location: include/linux/time64.h:116
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff828b1e7b)
Location: include/linux/time64.h:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112975b)
Location: include/linux/time64.h:116
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff828cc6ad)
Location: include/linux/time64.h:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81135dab)
Location: include/linux/time64.h:116
Inline: True
```
```
In kernel/time/timekeeping.c (ffffffff828d1aa7)
Location: include/linux/time64.h:116
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
</details>
</li>
</ul>

## Differences
