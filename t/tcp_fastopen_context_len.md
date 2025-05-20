# Function: <code>tcp_fastopen_context_len</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:1669
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/tcp.h:1669
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/net/tcp.h:1669
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81accf3d)
Location: include/net/tcp.h:1720
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8f3d)
Location: include/net/tcp.h:1734
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_cookie_gen_check
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ac439c)
Location: include/net/tcp.h:1738
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81b82ad2)
Location: include/net/tcp.h:1731
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81d130d5)
Location: include/net/tcp.h:1792
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ed9045)
Location: include/net/tcp.h:1812
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81f38144)
Location: include/net/tcp.h:1825
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe204)
Location: include/net/tcp.h:1927
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_get_cipher
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d81c00)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (c0da21b0)
Location: include/net/tcp.h:1691
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd1f34)
Location: include/net/tcp.h:1691
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/net/tcp.h:1691
Inline: True
```
</details>
</li>
</ul>

## Differences
