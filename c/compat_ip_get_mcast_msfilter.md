# Function: <code>compat_ip_get_mcast_msfilter</code>

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
int compat_ip_get_mcast_msfilter(struct sock *sk, void *optval, int *optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa9910)
Location: net/ipv4/ip_sockglue.c:1482
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81aa9910-ffffffff81aa9b04: compat_ip_get_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_ip_get_mcast_msfilter(struct sock *sk, void *optval, int *optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a94ae0)
Location: net/ipv4/ip_sockglue.c:1482
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81a94ae0-ffffffff81a94cd2: compat_ip_get_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compat_ip_get_mcast_msfilter(struct sock *sk, void *optval, int *optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b4ff40)
Location: net/ipv4/ip_sockglue.c:1482
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81b4ff40-ffffffff81b50132: compat_ip_get_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compat_ip_get_mcast_msfilter(struct sock *sk, void *optval, int *optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81cdd9c0)
Location: net/ipv4/ip_sockglue.c:1493
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81cdd9c0-ffffffff81cddc13: compat_ip_get_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compat_ip_get_mcast_msfilter(struct sock *sk, sockptr_t optval, sockptr_t optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81e9f160)
Location: net/ipv4/ip_sockglue.c:1495
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81e9f160-ffffffff81e9f491: compat_ip_get_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compat_ip_get_mcast_msfilter(struct sock *sk, sockptr_t optval, sockptr_t optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81efd960)
Location: net/ipv4/ip_sockglue.c:1517
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81efd960-ffffffff81efdc76: compat_ip_get_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compat_ip_get_mcast_msfilter(struct sock *sk, sockptr_t optval, sockptr_t optlen, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc1b40)
Location: net/ipv4/ip_sockglue.c:1468
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
**Symbols:**

```
ffffffff81fc1b40-ffffffff81fc1e56: compat_ip_get_mcast_msfilter (STB_LOCAL)
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
