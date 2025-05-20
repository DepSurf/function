# Function: <code>__cgroup_bpf_run_filter_getsockopt_kern</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock *sk, int level, int optname, void *optval, int *optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8123b960)
Location: kernel/bpf/cgroup.c:1535
Inline: False
```
**Symbols:**

```
ffffffff8123b960-ffffffff8123bb9e: __cgroup_bpf_run_filter_getsockopt_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock *sk, int level, int optname, void *optval, int *optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81276380)
Location: kernel/bpf/cgroup.c:1565
Inline: False
```
**Symbols:**

```
ffffffff81276380-ffffffff81276527: __cgroup_bpf_run_filter_getsockopt_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock *sk, int level, int optname, void *optval, int *optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c5db0)
Location: kernel/bpf/cgroup.c:1703
Inline: False
```
**Symbols:**

```
ffffffff812c5db0-ffffffff812c5f58: __cgroup_bpf_run_filter_getsockopt_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock *sk, int level, int optname, void *optval, int *optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8132b330)
Location: kernel/bpf/cgroup.c:1942
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
**Symbols:**

```
ffffffff8132b330-ffffffff8132b4d8: __cgroup_bpf_run_filter_getsockopt_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock *sk, int level, int optname, void *optval, int *optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8135b550)
Location: kernel/bpf/cgroup.c:1960
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
**Symbols:**

```
ffffffff8135b550-ffffffff8135b6f8: __cgroup_bpf_run_filter_getsockopt_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_getsockopt_kern(struct sock *sk, int level, int optname, void *optval, int *optlen, int retval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813841e0)
Location: kernel/bpf/cgroup.c:1978
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
**Symbols:**

```
ffffffff813841e0-ffffffff81384388: __cgroup_bpf_run_filter_getsockopt_kern (STB_GLOBAL)
```
</details>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
