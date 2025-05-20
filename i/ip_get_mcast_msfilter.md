# Function: <code>ip_get_mcast_msfilter</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_get_mcast_msfilter(struct sock *sk, void *optval, int *optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa9b10)
Location: net/ipv4/ip_sockglue.c:1456
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81aa9b10-ffffffff81aa9bfd: ip_get_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_get_mcast_msfilter(struct sock *sk, void *optval, int *optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a94ce0)
Location: net/ipv4/ip_sockglue.c:1456
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81a94ce0-ffffffff81a94dcb: ip_get_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_get_mcast_msfilter(struct sock *sk, void *optval, int *optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b50140)
Location: net/ipv4/ip_sockglue.c:1456
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81b50140-ffffffff81b5022b: ip_get_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_get_mcast_msfilter(struct sock *sk, void *optval, int *optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81cddc20)
Location: net/ipv4/ip_sockglue.c:1467
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81cddc20-ffffffff81cddd23: ip_get_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_get_mcast_msfilter(struct sock *sk, sockptr_t optval, sockptr_t optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81e9ef60)
Location: net/ipv4/ip_sockglue.c:1468
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81e9ef60-ffffffff81e9f143: ip_get_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_get_mcast_msfilter(struct sock *sk, sockptr_t optval, sockptr_t optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81efd780)
Location: net/ipv4/ip_sockglue.c:1490
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81efd780-ffffffff81efd950: ip_get_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_get_mcast_msfilter(struct sock *sk, sockptr_t optval, sockptr_t optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc1960)
Location: net/ipv4/ip_sockglue.c:1441
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81fc1960-ffffffff81fc1b30: ip_get_mcast_msfilter (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
<li>
<b>Param type changed. </b>
<code>int *optlen</code> ➡️ <code>sockptr_t optlen</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
