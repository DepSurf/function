# Function: <code>timespec_inject_offset_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f4fbe)
Location: include/linux/time.h:144
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff810f73db)
Location: include/linux/time.h:144
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_validate_timex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fc17e)
Location: include/linux/time.h:144
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff810fe51b)
Location: include/linux/time.h:144
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_validate_timex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810ff07e)
Location: include/linux/time.h:144
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff8110130b)
Location: include/linux/time.h:144
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_validate_timex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81101705)
Location: include/linux/time.h:153
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/ntp.c (ffffffff81103408)
Location: include/linux/time.h:153
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_validate_timex
```
</details>
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
