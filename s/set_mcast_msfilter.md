# Function: <code>set_mcast_msfilter</code>

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
int set_mcast_msfilter(struct sock *sk, int ifindex, int numsrc, int fmode, struct __kernel_sockaddr_storage *group, struct __kernel_sockaddr_storage *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a9f8b0)
Location: net/ipv4/ip_sockglue.c:645
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_setsockopt
```
**Symbols:**

```
ffffffff81a9f8b0-ffffffff81a9f998: set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_mcast_msfilter(struct sock *sk, int ifindex, int numsrc, int fmode, struct __kernel_sockaddr_storage *group, struct __kernel_sockaddr_storage *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa9800)
Location: net/ipv4/ip_sockglue.c:661
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
```
**Symbols:**

```
ffffffff81aa9800-ffffffff81aa98e8: set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_mcast_msfilter(struct sock *sk, int ifindex, int numsrc, int fmode, struct __kernel_sockaddr_storage *group, struct __kernel_sockaddr_storage *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a949d0)
Location: net/ipv4/ip_sockglue.c:661
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
```
**Symbols:**

```
ffffffff81a949d0-ffffffff81a94ab8: set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_mcast_msfilter(struct sock *sk, int ifindex, int numsrc, int fmode, struct __kernel_sockaddr_storage *group, struct __kernel_sockaddr_storage *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b4fe50)
Location: net/ipv4/ip_sockglue.c:661
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
```
**Symbols:**

```
ffffffff81b4fe50-ffffffff81b4ff38: set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_mcast_msfilter(struct sock *sk, int ifindex, int numsrc, int fmode, struct __kernel_sockaddr_storage *group, struct __kernel_sockaddr_storage *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81cdd8d0)
Location: net/ipv4/ip_sockglue.c:663
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
```
**Symbols:**

```
ffffffff81cdd8d0-ffffffff81cdd9c0: set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_mcast_msfilter(struct sock *sk, int ifindex, int numsrc, int fmode, struct __kernel_sockaddr_storage *group, struct __kernel_sockaddr_storage *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81e9e540)
Location: net/ipv4/ip_sockglue.c:664
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
```
**Symbols:**

```
ffffffff81e9e540-ffffffff81e9e630: set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_mcast_msfilter(struct sock *sk, int ifindex, int numsrc, int fmode, struct __kernel_sockaddr_storage *group, struct __kernel_sockaddr_storage *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81efcd40)
Location: net/ipv4/ip_sockglue.c:671
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
```
**Symbols:**

```
ffffffff81efcd40-ffffffff81efce30: set_mcast_msfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_mcast_msfilter(struct sock *sk, int ifindex, int numsrc, int fmode, struct __kernel_sockaddr_storage *group, struct __kernel_sockaddr_storage *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc0c00)
Location: net/ipv4/ip_sockglue.c:662
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:compat_ip_set_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_set_mcast_msfilter
```
**Symbols:**

```
ffffffff81fc0c00-ffffffff81fc0cf0: set_mcast_msfilter (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
