# Function: <code>C_SYSC_wait4</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81110eb0)
Location: kernel/compat.c:536
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_wait4
```
**Symbols:**

```
ffffffff81110eb0-ffffffff81110f96: C_SYSC_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811185f0)
Location: kernel/compat.c:536
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_wait4
```
**Symbols:**

```
ffffffff811185f0-ffffffff811186d6: C_SYSC_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111fd10)
Location: kernel/compat.c:544
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_wait4
```
**Symbols:**

```
ffffffff8111fd10-ffffffff8111fdf6: C_SYSC_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810898f0)
Location: kernel/exit.c:1703
Inline: False
Direct callers:
  - kernel/exit.c:compat_SyS_wait4
```
**Symbols:**

```
ffffffff810898f0-ffffffff81089989: C_SYSC_wait4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_wait4(compat_pid_t pid, compat_uint_t *stat_addr, int options, struct compat_rusage *ru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81090670)
Location: kernel/exit.c:1700
Inline: False
Direct callers:
  - kernel/exit.c:compat_SyS_wait4
```
**Symbols:**

```
ffffffff81090670-ffffffff81090709: C_SYSC_wait4 (STB_LOCAL)
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
