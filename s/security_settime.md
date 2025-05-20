# Function: <code>security_settime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_settime(const struct timespec *ts, const struct timezone *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133cf50)
Location: security/security.c:211
Inline: False
Direct callers:
  - kernel/time/time.c:SyS_stime
  - kernel/compat.c:compat_SyS_stime
```
**Symbols:**

```
ffffffff8133cf50-ffffffff8133cf9f: security_settime (STB_GLOBAL)
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
In kernel/time/time.c (ffffffff810f1ed5)
Location: include/linux/security.h:212
Inline: True
Inline callers:
  - kernel/time/time.c:SyS_stime
```
```
In kernel/compat.c (ffffffff811191e8)
Location: include/linux/security.h:212
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_stime
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
In kernel/time/time.c (ffffffff810f9055)
Location: include/linux/security.h:212
Inline: True
Inline callers:
  - kernel/time/time.c:SyS_stime
```
```
In kernel/compat.c (ffffffff81120b68)
Location: include/linux/security.h:212
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_stime
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
In kernel/time/time.c (ffffffff810fb408)
Location: include/linux/security.h:226
Inline: True
Inline callers:
  - kernel/time/time.c:compat_SyS_stime
  - kernel/time/time.c:SyS_stime
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
<b>Regular</b>
<ul>
</ul>
