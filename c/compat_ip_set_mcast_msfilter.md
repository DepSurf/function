# Function: <code>compat_ip_set_mcast_msfilter</code>

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
int compat_ip_set_mcast_msfilter(struct sock *sk, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aaa280)
Location: net/ipv4/ip_sockglue.c:800
Inline: False
```
**Symbols:**

```
ffffffff81aaa280-ffffffff81aaa3af: compat_ip_set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_ip_set_mcast_msfilter(struct sock *sk, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a95440)
Location: net/ipv4/ip_sockglue.c:800
Inline: False
```
**Symbols:**

```
ffffffff81a95440-ffffffff81a9556f: compat_ip_set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compat_ip_set_mcast_msfilter(struct sock *sk, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b508a0)
Location: net/ipv4/ip_sockglue.c:800
Inline: False
```
**Symbols:**

```
ffffffff81b508a0-ffffffff81b509cf: compat_ip_set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compat_ip_set_mcast_msfilter(struct sock *sk, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81cdeeb0)
Location: net/ipv4/ip_sockglue.c:802
Inline: False
```
**Symbols:**

```
ffffffff81cdeeb0-ffffffff81cdeffa: compat_ip_set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compat_ip_set_mcast_msfilter(struct sock *sk, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81e9ee00)
Location: net/ipv4/ip_sockglue.c:803
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
**Symbols:**

```
ffffffff81e9ee00-ffffffff81e9ef4a: compat_ip_set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compat_ip_set_mcast_msfilter(struct sock *sk, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81efd600)
Location: net/ipv4/ip_sockglue.c:810
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
**Symbols:**

```
ffffffff81efd600-ffffffff81efd76f: compat_ip_set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compat_ip_set_mcast_msfilter(struct sock *sk, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc17d0)
Location: net/ipv4/ip_sockglue.c:801
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
**Symbols:**

```
ffffffff81fc17d0-ffffffff81fc1944: compat_ip_set_mcast_msfilter (STB_LOCAL)
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
