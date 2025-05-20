# Function: <code>__cgroup_bpf_run_filter_setsockopt</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f7f40)
Location: kernel/bpf/cgroup.c:977
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff811f7f40-ffffffff811f81d3: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812051b0)
Location: kernel/bpf/cgroup.c:986
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff812051b0-ffffffff8120546c: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122e860)
Location: kernel/bpf/cgroup.c:1303
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff8122e860-ffffffff8122eb2a: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81236dd0)
Location: kernel/bpf/cgroup.c:1327
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff81236dd0-ffffffff812370c9: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8123b160)
Location: kernel/bpf/cgroup.c:1350
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff8123b160-ffffffff8123b598: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81275c90)
Location: kernel/bpf/cgroup.c:1380
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff81275c90-ffffffff81276022: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c5730)
Location: kernel/bpf/cgroup.c:1548
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff812c5730-ffffffff812c5a8a: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8132ac90)
Location: kernel/bpf/cgroup.c:1787
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff8132ac90-ffffffff8132afea: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1787
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff820e13a2-ffffffff820e13b7: __cgroup_bpf_run_filter_setsockopt.cold (STB_LOCAL)
ffffffff8135add0-ffffffff8135b192: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, sockptr_t optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1802
Inline: False
Direct callers:
  - net/socket.c:do_sock_setsockopt
```
**Symbols:**

```
ffffffff821bddb1-ffffffff821bddc6: __cgroup_bpf_run_filter_setsockopt.cold (STB_LOCAL)
ffffffff813839c0-ffffffff81383d8f: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028ec28)
Location: kernel/bpf/cgroup.c:986
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_setsockopt
```
**Symbols:**

```
ffff80001028ec28-ffff80001028ef0c: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04be350)
Location: kernel/bpf/cgroup.c:986
Inline: False
Direct callers:
  - net/socket.c:__se_sys_setsockopt
```
**Symbols:**

```
c04be350-c04be76c: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033b690)
Location: kernel/bpf/cgroup.c:986
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
c00000000033b690-c00000000033baa4: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c1e0c)
Location: kernel/bpf/cgroup.c:986
Inline: False
Direct callers:
  - net/socket.c:__se_sys_setsockopt
```
**Symbols:**

```
ffffffe0001c1e0c-ffffffe0001c20a4: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fd7d0)
Location: kernel/bpf/cgroup.c:986
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff811fd7d0-ffffffff811fda8c: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f0520)
Location: kernel/bpf/cgroup.c:986
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff811f0520-ffffffff811f07dc: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fb5a0)
Location: kernel/bpf/cgroup.c:986
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff811fb5a0-ffffffff811fb85c: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_setsockopt(struct sock *sk, int *level, int *optname, char *optval, int *optlen, char **kernel_optval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8120a130)
Location: kernel/bpf/cgroup.c:986
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff8120a130-ffffffff8120a410: __cgroup_bpf_run_filter_setsockopt (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
