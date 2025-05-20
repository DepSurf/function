# Function: <code>__cgroup_bpf_run_filter_getsockopt</code>

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
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f81e0)
Location: kernel/bpf/cgroup.c:1040
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff811f81e0-ffffffff811f8485: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81204e90)
Location: kernel/bpf/cgroup.c:1057
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81204e90-ffffffff812051a1: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122eb30)
Location: kernel/bpf/cgroup.c:1379
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff8122eb30-ffffffff8122edf2: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812370d0)
Location: kernel/bpf/cgroup.c:1404
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff812370d0-ffffffff8123737f: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8123b5a0)
Location: kernel/bpf/cgroup.c:1444
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff8123b5a0-ffffffff8123b952: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81276030)
Location: kernel/bpf/cgroup.c:1474
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81276030-ffffffff8127637c: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c5a90)
Location: kernel/bpf/cgroup.c:1632
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff812c5a90-ffffffff812c5da4: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8132b000)
Location: kernel/bpf/cgroup.c:1871
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff8132b000-ffffffff8132b314: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1877
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff820e13b7-ffffffff820e13cb: __cgroup_bpf_run_filter_getsockopt.cold (STB_LOCAL)
ffffffff8135b1b0-ffffffff8135b533: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, sockptr_t optval, sockptr_t optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1893
Inline: False
Direct callers:
  - net/socket.c:do_sock_getsockopt
```
**Symbols:**

```
ffffffff821bddc6-ffffffff821bddda: __cgroup_bpf_run_filter_getsockopt.cold (STB_LOCAL)
ffffffff81383da0-ffffffff813841ca: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
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
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028e300)
Location: kernel/bpf/cgroup.c:1057
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_getsockopt
```
**Symbols:**

```
ffff80001028e300-ffff80001028e860: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bd2d0)
Location: kernel/bpf/cgroup.c:1057
Inline: False
Direct callers:
  - net/socket.c:__se_sys_getsockopt
```
**Symbols:**

```
c04bd2d0-c04bd7e0: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c000000000339cf0)
Location: kernel/bpf/cgroup.c:1057
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
c000000000339cf0-c00000000033a210: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c1500)
Location: kernel/bpf/cgroup.c:1057
Inline: False
Direct callers:
  - net/socket.c:__se_sys_getsockopt
```
**Symbols:**

```
ffffffe0001c1500-ffffffe0001c1804: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
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
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fd4b0)
Location: kernel/bpf/cgroup.c:1057
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff811fd4b0-ffffffff811fd7c1: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f0200)
Location: kernel/bpf/cgroup.c:1057
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff811f0200-ffffffff811f0511: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fb280)
Location: kernel/bpf/cgroup.c:1057
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff811fb280-ffffffff811fb591: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt(struct sock *sk, int level, int optname, char *optval, int *optlen, int max_optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81209df0)
Location: kernel/bpf/cgroup.c:1057
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81209df0-ffffffff8120a129: __cgroup_bpf_run_filter_getsockopt (STB_GLOBAL)
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
<li>
<b>Param type changed. </b>
<code>int *optlen</code> ➡️ <code>sockptr_t optlen</code>
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
