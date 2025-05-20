# Function: <code>compat_ipv6_mcast_join_leave</code>

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
int compat_ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5e6a0)
Location: net/ipv6/ipv6_sockglue.c:298
Inline: False
```
**Symbols:**

```
ffffffff81b5e6a0-ffffffff81b5e780: compat_ipv6_mcast_join_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4c850)
Location: net/ipv6/ipv6_sockglue.c:298
Inline: False
```
**Symbols:**

```
ffffffff81b4c850-ffffffff81b4c930: compat_ipv6_mcast_join_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compat_ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81c13b60)
Location: net/ipv6/ipv6_sockglue.c:298
Inline: False
```
**Symbols:**

```
ffffffff81c13b60-ffffffff81c13c40: compat_ipv6_mcast_join_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compat_ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81daf360)
Location: net/ipv6/ipv6_sockglue.c:300
Inline: False
```
**Symbols:**

```
ffffffff81daf360-ffffffff81daf48f: compat_ipv6_mcast_join_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compat_ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81f7ea80)
Location: net/ipv6/ipv6_sockglue.c:300
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff81f7ea80-ffffffff81f7ebaf: compat_ipv6_mcast_join_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compat_ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81fdec90)
Location: net/ipv6/ipv6_sockglue.c:300
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff81fdec90-ffffffff81fdedc2: compat_ipv6_mcast_join_leave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compat_ipv6_mcast_join_leave(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff820aca10)
Location: net/ipv6/ipv6_sockglue.c:300
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff820aca10-ffffffff820acb42: compat_ipv6_mcast_join_leave (STB_LOCAL)
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
