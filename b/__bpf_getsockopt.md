# Function: <code>__bpf_getsockopt</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __bpf_getsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5305
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
  - net/core/filter.c:bpf_unlocked_sk_getsockopt
  - net/core/filter.c:bpf_sk_getsockopt
```
**Symbols:**

```
ffffffff81dfe0a0-ffffffff81dfe1c4: __bpf_getsockopt (STB_LOCAL)
ffffffff820ac6a6-ffffffff820ac6c6: __bpf_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __bpf_getsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5359
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
  - net/core/filter.c:bpf_unlocked_sk_getsockopt
  - net/core/filter.c:bpf_sk_getsockopt
```
**Symbols:**

```
ffffffff81e6f580-ffffffff81e6f676: __bpf_getsockopt (STB_LOCAL)
ffffffff8212dd42-ffffffff8212dd61: __bpf_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __bpf_getsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5433
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
  - net/core/filter.c:bpf_unlocked_sk_getsockopt
  - net/core/filter.c:bpf_sk_getsockopt
```
**Symbols:**

```
ffffffff81f2ed50-ffffffff81f2ee46: __bpf_getsockopt (STB_LOCAL)
ffffffff8220faa8-ffffffff8220fac7: __bpf_getsockopt.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
