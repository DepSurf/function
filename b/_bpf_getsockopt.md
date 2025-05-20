# Function: <code>_bpf_getsockopt</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _bpf_getsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a29e80)
Location: net/core/filter.c:4463
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
```
**Symbols:**

```
ffffffff81a29e80-ffffffff81a29fb3: _bpf_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _bpf_getsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2a7e0)
Location: net/core/filter.c:4923
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
```
**Symbols:**

```
ffffffff81a2a7e0-ffffffff81a2a92a: _bpf_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _bpf_getsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a11960)
Location: net/core/filter.c:4879
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
```
**Symbols:**

```
ffffffff81a11960-ffffffff81a11b27: _bpf_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _bpf_getsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4963
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
  - net/core/filter.c:bpf_sk_getsockopt
```
**Symbols:**

```
ffffffff81acd610-ffffffff81acd84c: _bpf_getsockopt (STB_LOCAL)
ffffffff81d3770b-ffffffff81d3775b: _bpf_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _bpf_getsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5263
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
  - net/core/filter.c:bpf_sk_getsockopt
```
**Symbols:**

```
ffffffff81c4b7d0-ffffffff81c4ba45: _bpf_getsockopt (STB_LOCAL)
ffffffff81f0405f-ffffffff81f040af: _bpf_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfe261)
Location: net/core/filter.c:5334
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
  - net/core/filter.c:bpf_sk_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e703c1)
Location: net/core/filter.c:5388
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
  - net/core/filter.c:bpf_sk_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2fa51)
Location: net/core/filter.c:5462
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_ops_getsockopt
  - net/core/filter.c:bpf_sock_addr_getsockopt
  - net/core/filter.c:bpf_sk_getsockopt
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
</ul>
