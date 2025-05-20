# Function: <code>rsk_drop_req</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9cd7)
Location: include/net/mptcp.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5c1f)
Location: include/net/mptcp.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/syncookies.c (ffffffff81b15328)
Location: include/net/mptcp.h:77
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
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
In net/ipv4/tcp_minisocks.c (ffffffff81ac0c7f)
Location: include/net/mptcp.h:91
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/syncookies.c (ffffffff81b03138)
Location: include/net/mptcp.h:91
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
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
In net/ipv4/tcp_minisocks.c (ffffffff81b7ea9f)
Location: include/net/mptcp.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/syncookies.c (ffffffff81bc5378)
Location: include/net/mptcp.h:110
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
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
In net/ipv4/tcp_minisocks.c (ffffffff81d0f2cd)
Location: include/net/mptcp.h:113
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/syncookies.c (ffffffff81d5a53e)
Location: include/net/mptcp.h:113
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
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
In net/ipv4/tcp_minisocks.c (ffffffff81ed4e2d)
Location: include/net/mptcp.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/syncookies.c (ffffffff81f2496e)
Location: include/net/mptcp.h:112
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
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
In net/ipv4/tcp_minisocks.c (ffffffff81f33b18)
Location: include/net/mptcp.h:112
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/syncookies.c (ffffffff81f844fe)
Location: include/net/mptcp.h:112
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9c8c)
Location: include/net/mptcp.h:133
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/syncookies.c (ffffffff8204aea2)
Location: include/net/mptcp.h:133
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
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
