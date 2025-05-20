# Function: <code>do_mcast_group_source</code>

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
int do_mcast_group_source(struct sock *sk, int optname, struct group_source_req *greqs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a9f9a0)
Location: net/ipv4/ip_sockglue.c:682
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_setsockopt
```
**Symbols:**

```
ffffffff81a9f9a0-ffffffff81a9fa8c: do_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aab0d0)
Location: net/ipv4/ip_sockglue.c:721
Inline: False
```
**Symbols:**

```
ffffffff81aab0d0-ffffffff81aab1ea: do_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a95840)
Location: net/ipv4/ip_sockglue.c:721
Inline: False
```
**Symbols:**

```
ffffffff81a95840-ffffffff81a9595a: do_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b50ca0)
Location: net/ipv4/ip_sockglue.c:720
Inline: False
```
**Symbols:**

```
ffffffff81b50ca0-ffffffff81b50dba: do_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81cdf2f0)
Location: net/ipv4/ip_sockglue.c:722
Inline: False
```
**Symbols:**

```
ffffffff81cdf2f0-ffffffff81cdf440: do_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81e9f7b0)
Location: net/ipv4/ip_sockglue.c:723
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
**Symbols:**

```
ffffffff81e9f7b0-ffffffff81e9f900: do_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81efdf90)
Location: net/ipv4/ip_sockglue.c:730
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
**Symbols:**

```
ffffffff81efdf90-ffffffff81efe0e0: do_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc2170)
Location: net/ipv4/ip_sockglue.c:721
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
**Symbols:**

```
ffffffff81fc2170-ffffffff81fc22c0: do_mcast_group_source (STB_LOCAL)
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
<b>Param added. </b>
<code>sockptr_t optval</code>
</li>
<li>
<b>Param added. </b>
<code>int optlen</code>
</li>
<li>
<b>Param removed. </b>
<code>struct group_source_req *greqs</code>
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
