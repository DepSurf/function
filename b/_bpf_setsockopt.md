# Function: <code>_bpf_setsockopt</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _bpf_setsockopt(struct sock *sk, int level, int optname, char *optval, int optlen, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4288
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
```
**Symbols:**

```
ffffffff81a2a000-ffffffff81a2a40f: _bpf_setsockopt (STB_LOCAL)
ffffffff81a33215-ffffffff81a33221: _bpf_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _bpf_setsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4693
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
```
**Symbols:**

```
ffffffff81a2a950-ffffffff81a2af45: _bpf_setsockopt (STB_LOCAL)
ffffffff81c31761-ffffffff81c3176d: _bpf_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _bpf_setsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4642
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
```
**Symbols:**

```
ffffffff81a11b50-ffffffff81a12158: _bpf_setsockopt (STB_LOCAL)
ffffffff81c23a6a-ffffffff81c23a76: _bpf_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _bpf_setsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4724
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
  - net/core/filter.c:bpf_sk_setsockopt
```
**Symbols:**

```
ffffffff81acce30-ffffffff81acd496: _bpf_setsockopt (STB_LOCAL)
ffffffff81d376b7-ffffffff81d3770b: _bpf_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _bpf_setsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5017
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
  - net/core/filter.c:bpf_sk_setsockopt
```
**Symbols:**

```
ffffffff81c4a700-ffffffff81c4ada0: _bpf_setsockopt (STB_LOCAL)
ffffffff81f0400b-ffffffff81f0405f: _bpf_setsockopt.cold (STB_LOCAL)
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
In net/core/filter.c (ffffffff81dfcf3a)
Location: net/core/filter.c:5297
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
  - net/core/filter.c:bpf_sk_setsockopt
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
In net/core/filter.c (ffffffff81e6d63a)
Location: net/core/filter.c:5351
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
  - net/core/filter.c:bpf_sk_setsockopt
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
In net/core/filter.c (ffffffff81f2ccea)
Location: net/core/filter.c:5425
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
  - net/core/filter.c:bpf_sk_setsockopt
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
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
