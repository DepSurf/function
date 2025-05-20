# Function: <code>C_SYSC_waitid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_waitid(int which, compat_pid_t pid, struct compat_siginfo *uinfo, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81110fa0)
Location: kernel/compat.c:567
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_waitid
```
**Symbols:**

```
ffffffff81110fa0-ffffffff811110d6: C_SYSC_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_waitid(int which, compat_pid_t pid, struct compat_siginfo *uinfo, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811186e0)
Location: kernel/compat.c:567
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_waitid
```
**Symbols:**

```
ffffffff811186e0-ffffffff8111880e: C_SYSC_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_waitid(int which, compat_pid_t pid, struct compat_siginfo *uinfo, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111fe00)
Location: kernel/compat.c:575
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_waitid
```
**Symbols:**

```
ffffffff8111fe00-ffffffff8111ff2e: C_SYSC_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81088610)
Location: kernel/exit.c:1718
Inline: False
Direct callers:
  - kernel/exit.c:compat_SyS_waitid
```
**Symbols:**

```
ffffffff81088610-ffffffff810887c3: C_SYSC_waitid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_waitid(int which, compat_pid_t pid, struct compat_siginfo *infop, int options, struct compat_rusage *uru);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108f370)
Location: kernel/exit.c:1715
Inline: False
Direct callers:
  - kernel/exit.c:compat_SyS_waitid
```
**Symbols:**

```
ffffffff8108f370-ffffffff8108f4f5: C_SYSC_waitid (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct compat_siginfo *infop</code>
</li>
<li>
<b>Param removed. </b>
<code>struct compat_siginfo *uinfo</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
