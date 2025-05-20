# Function: <code>__bpf_setsockopt</code>

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
int __bpf_setsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5279
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
  - net/core/filter.c:bpf_unlocked_sk_setsockopt
  - net/core/filter.c:bpf_sk_setsockopt
```
**Symbols:**

```
ffffffff81dfcdb0-ffffffff81dfcec4: __bpf_setsockopt (STB_LOCAL)
ffffffff820ac50f-ffffffff820ac52f: __bpf_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __bpf_setsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5333
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
  - net/core/filter.c:bpf_unlocked_sk_setsockopt
  - net/core/filter.c:bpf_sk_setsockopt
```
**Symbols:**

```
ffffffff81e6d500-ffffffff81e6d5c6: __bpf_setsockopt (STB_LOCAL)
ffffffff8212dad1-ffffffff8212daef: __bpf_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __bpf_setsockopt(struct sock *sk, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5407
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_setsockopt
  - net/core/filter.c:bpf_sock_addr_setsockopt
  - net/core/filter.c:bpf_unlocked_sk_setsockopt
  - net/core/filter.c:bpf_sk_setsockopt
```
**Symbols:**

```
ffffffff81f2cbb0-ffffffff81f2cc76: __bpf_setsockopt (STB_LOCAL)
ffffffff8220f82f-ffffffff8220f84d: __bpf_setsockopt.cold (STB_LOCAL)
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
