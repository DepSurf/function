# Function: <code>SYSC_rt_tgsigqueueinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int SYSC_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f510)
Location: kernel/signal.c:3000
Inline: False
Direct callers:
  - kernel/signal.c:SyS_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff8108f510-ffffffff8108f593: SYSC_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int SYSC_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092590)
Location: kernel/signal.c:3000
Inline: False
Direct callers:
  - kernel/signal.c:SyS_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff81092590-ffffffff81092613: SYSC_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int SYSC_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097520)
Location: kernel/signal.c:3013
Inline: False
Direct callers:
  - kernel/signal.c:SyS_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff81097520-ffffffff810975a3: SYSC_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int SYSC_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094830)
Location: kernel/signal.c:3068
Inline: False
Direct callers:
  - kernel/signal.c:SyS_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff81094830-ffffffff810948b1: SYSC_rt_tgsigqueueinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int SYSC_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b6d0)
Location: kernel/signal.c:3089
Inline: False
Direct callers:
  - kernel/signal.c:SyS_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff8109b6d0-ffffffff8109b751: SYSC_rt_tgsigqueueinfo (STB_LOCAL)
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
