# Function: <code>sol_ipv6_sockopt</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
int sol_ipv6_sockopt(struct sock *sk, int optname, char *optval, int *optlen, bool getopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81deb2a0)
Location: net/core/filter.c:5253
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_getsockopt
  - net/core/filter.c:__bpf_setsockopt
```
**Symbols:**

```
ffffffff81deb2a0-ffffffff81deb370: sol_ipv6_sockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sol_ipv6_sockopt(struct sock *sk, int optname, char *optval, int *optlen, bool getopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e5caa0)
Location: net/core/filter.c:5307
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_getsockopt
  - net/core/filter.c:__bpf_setsockopt
```
**Symbols:**

```
ffffffff81e5caa0-ffffffff81e5cb70: sol_ipv6_sockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sol_ipv6_sockopt(struct sock *sk, int optname, char *optval, int *optlen, bool getopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f1be90)
Location: net/core/filter.c:5381
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_getsockopt
  - net/core/filter.c:__bpf_setsockopt
```
**Symbols:**

```
ffffffff81f1be90-ffffffff81f1bf60: sol_ipv6_sockopt (STB_LOCAL)
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
