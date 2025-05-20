# Function: <code>ipv6_mcast_join_leave</code>

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
int ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5e5e0)
Location: net/ipv6/ipv6_sockglue.c:278
Inline: False
```
**Symbols:**

```
ffffffff81b5e5e0-ffffffff81b5e698: ipv6_mcast_join_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4c930)
Location: net/ipv6/ipv6_sockglue.c:278
Inline: False
```
**Symbols:**

```
ffffffff81b4c930-ffffffff81b4c9e8: ipv6_mcast_join_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81c13c40)
Location: net/ipv6/ipv6_sockglue.c:278
Inline: False
```
**Symbols:**

```
ffffffff81c13c40-ffffffff81c13cf8: ipv6_mcast_join_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81daf280)
Location: net/ipv6/ipv6_sockglue.c:280
Inline: False
```
**Symbols:**

```
ffffffff81daf280-ffffffff81daf35a: ipv6_mcast_join_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81f7ebc0)
Location: net/ipv6/ipv6_sockglue.c:280
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff81f7ebc0-ffffffff81f7ec9a: ipv6_mcast_join_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81fdede0)
Location: net/ipv6/ipv6_sockglue.c:280
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff81fdede0-ffffffff81fdeebd: ipv6_mcast_join_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff820ac920)
Location: net/ipv6/ipv6_sockglue.c:280
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff820ac920-ffffffff820ac9fd: ipv6_mcast_join_leave (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
