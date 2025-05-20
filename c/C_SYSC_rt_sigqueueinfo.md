# Function: <code>C_SYSC_rt_sigqueueinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_rt_sigqueueinfo(compat_pid_t pid, int sig, struct compat_siginfo *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108fb80)
Location: kernel/signal.c:2969
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8108fb80-ffffffff8108fbf7: C_SYSC_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_rt_sigqueueinfo(compat_pid_t pid, int sig, struct compat_siginfo *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092c00)
Location: kernel/signal.c:2969
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff81092c00-ffffffff81092c77: C_SYSC_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_rt_sigqueueinfo(compat_pid_t pid, int sig, struct compat_siginfo *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097b90)
Location: kernel/signal.c:2982
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff81097b90-ffffffff81097c07: C_SYSC_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_rt_sigqueueinfo(compat_pid_t pid, int sig, struct compat_siginfo *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094ed0)
Location: kernel/signal.c:3037
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff81094ed0-ffffffff81094f47: C_SYSC_rt_sigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_rt_sigqueueinfo(compat_pid_t pid, int sig, struct compat_siginfo *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109bd70)
Location: kernel/signal.c:3058
Inline: False
Direct callers:
  - kernel/signal.c:compat_SyS_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8109bd70-ffffffff8109bde7: C_SYSC_rt_sigqueueinfo (STB_LOCAL)
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
