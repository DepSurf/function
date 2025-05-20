# Function: <code>C_SYSC_rt_tgsigqueueinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_rt_tgsigqueueinfo(compat_pid_t tgid, compat_pid_t pid, int sig, struct compat_siginfo *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f5a0)
Location: kernel/signal.c:3012
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff8108f5a0-ffffffff8108f62c: C_SYSC_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_rt_tgsigqueueinfo(compat_pid_t tgid, compat_pid_t pid, int sig, struct compat_siginfo *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092620)
Location: kernel/signal.c:3012
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff81092620-ffffffff810926ac: C_SYSC_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_rt_tgsigqueueinfo(compat_pid_t tgid, compat_pid_t pid, int sig, struct compat_siginfo *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810975b0)
Location: kernel/signal.c:3025
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810975b0-ffffffff8109763c: C_SYSC_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_rt_tgsigqueueinfo(compat_pid_t tgid, compat_pid_t pid, int sig, struct compat_siginfo *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810948c0)
Location: kernel/signal.c:3080
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810948c0-ffffffff8109494a: C_SYSC_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_rt_tgsigqueueinfo(compat_pid_t tgid, compat_pid_t pid, int sig, struct compat_siginfo *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b760)
Location: kernel/signal.c:3101
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff8109b760-ffffffff8109b7ea: C_SYSC_rt_tgsigqueueinfo (STB_LOCAL)
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
