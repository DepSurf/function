# Function: <code>do_ipv6_mcast_group_source</code>

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
int do_ipv6_mcast_group_source(struct sock *sk, int optname, struct group_source_req *greqs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4f6d0)
Location: net/ipv6/ipv6_sockglue.c:139
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_setsockopt
```
**Symbols:**

```
ffffffff81b4f6d0-ffffffff81b4f766: do_ipv6_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_ipv6_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5fa00)
Location: net/ipv6/ipv6_sockglue.c:162
Inline: False
```
**Symbols:**

```
ffffffff81b5fa00-ffffffff81b5fadd: do_ipv6_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_ipv6_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4cef0)
Location: net/ipv6/ipv6_sockglue.c:162
Inline: False
```
**Symbols:**

```
ffffffff81b4cef0-ffffffff81b4cfcd: do_ipv6_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_ipv6_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81c14200)
Location: net/ipv6/ipv6_sockglue.c:162
Inline: False
```
**Symbols:**

```
ffffffff81c14200-ffffffff81c142dd: do_ipv6_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_ipv6_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81daf9c0)
Location: net/ipv6/ipv6_sockglue.c:164
Inline: False
```
**Symbols:**

```
ffffffff81daf9c0-ffffffff81dafac6: do_ipv6_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_ipv6_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81f7f200)
Location: net/ipv6/ipv6_sockglue.c:164
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff81f7f200-ffffffff81f7f306: do_ipv6_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_ipv6_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff81fdf440)
Location: net/ipv6/ipv6_sockglue.c:164
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff81fdf440-ffffffff81fdf546: do_ipv6_mcast_group_source (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_ipv6_mcast_group_source(struct sock *sk, int optname, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ipv6_sockglue.c (ffffffff820ad250)
Location: net/ipv6/ipv6_sockglue.c:164
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff820ad250-ffffffff820ad356: do_ipv6_mcast_group_source (STB_LOCAL)
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
