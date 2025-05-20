# Function: <code>bpf_mptcp_sock_from_subflow</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mptcp_sock *bpf_mptcp_sock_from_subflow(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/bpf.c (0)
Location: net/mptcp/bpf.c:15
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skc_to_mptcp_sock
```
**Symbols:**

```
ffffffff81f10c4d-ffffffff81f10c82: bpf_mptcp_sock_from_subflow.cold (STB_LOCAL)
ffffffff81e36550-ffffffff81e365f2: bpf_mptcp_sock_from_subflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mptcp_sock *bpf_mptcp_sock_from_subflow(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/bpf.c (0)
Location: net/mptcp/bpf.c:15
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skc_to_mptcp_sock
```
**Symbols:**

```
ffffffff820b6f33-ffffffff820b6f68: bpf_mptcp_sock_from_subflow.cold (STB_LOCAL)
ffffffff8200f550-ffffffff8200f5f2: bpf_mptcp_sock_from_subflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mptcp_sock *bpf_mptcp_sock_from_subflow(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/bpf.c (0)
Location: net/mptcp/bpf.c:15
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skc_to_mptcp_sock
```
**Symbols:**

```
ffffffff82138261-ffffffff8213828f: bpf_mptcp_sock_from_subflow.cold (STB_LOCAL)
ffffffff8208c140-ffffffff8208c1d2: bpf_mptcp_sock_from_subflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mptcp_sock *bpf_mptcp_sock_from_subflow(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/bpf.c (0)
Location: net/mptcp/bpf.c:15
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skc_to_mptcp_sock
```
**Symbols:**

```
ffffffff8221a0fe-ffffffff8221a12c: bpf_mptcp_sock_from_subflow.cold (STB_LOCAL)
ffffffff82162600-ffffffff82162692: bpf_mptcp_sock_from_subflow (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
