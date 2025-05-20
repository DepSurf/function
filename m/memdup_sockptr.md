# Function: <code>memdup_sockptr</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aac08e)
Location: include/linux/sockptr.h:67
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2626c)
Location: include/linux/sockptr.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5fe1c)
Location: include/linux/sockptr.h:67
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a97384)
Location: include/linux/sockptr.h:67
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81b13e0c)
Location: include/linux/sockptr.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4e100)
Location: include/linux/sockptr.h:67
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b5281b)
Location: include/linux/sockptr.h:67
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd7f0c)
Location: include/linux/sockptr.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c15439)
Location: include/linux/sockptr.h:67
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81ce0c2c)
Location: include/linux/sockptr.h:67
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6ede0)
Location: include/linux/sockptr.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db0c36)
Location: include/linux/sockptr.h:67
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81ea103c)
Location: include/linux/sockptr.h:72
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3a6e0)
Location: include/linux/sockptr.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f80cd9)
Location: include/linux/sockptr.h:72
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81eff805)
Location: include/linux/sockptr.h:72
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a100)
Location: include/linux/sockptr.h:72
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe104c)
Location: include/linux/sockptr.h:72
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *memdup_sockptr(sockptr_t src, size_t len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc1670)
Location: include/linux/sockptr.h:95
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_set_mcast_msfilter
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/xfrm/xfrm_state.c (ffffffff82067460)
Location: include/linux/sockptr.h:95
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820adc95)
Location: include/linux/sockptr.h:95
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/ipv6_sockglue.c:ipv6_set_mcast_msfilter
```
**Symbols:**

```
ffffffff81fc1550-ffffffff81fc1611: memdup_sockptr (STB_LOCAL)
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
</ul>
