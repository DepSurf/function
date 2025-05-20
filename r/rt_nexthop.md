# Function: <code>rt_nexthop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81757751)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_get_source
```
```
In net/ipv4/ip_output.c (ffffffff8175d07d)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c3c68)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_output.c (ffffffff817c9e3d)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f378e)
Location: include/net/route.h:84
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_output.c (ffffffff817f9123)
Location: include/net/route.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81811381)
Location: include/net/route.h:84
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_output.c (ffffffff8181953a)
Location: include/net/route.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81890961)
Location: include/net/route.h:84
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81897b4a)
Location: include/net/route.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e406d)
Location: include/net/route.h:83
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_output.c (ffffffff818ebe64)
Location: include/net/route.h:83
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81910f74)
Location: include/net/route.h:83
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_output.c (ffffffff81919c04)
Location: include/net/route.h:83
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819736ba)
Location: include/net/route.h:84
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819aa03d)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
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
In net/ipv4/route.c (ffffffff81a9472d)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
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
In net/ipv4/route.c (ffffffff81a9e6d9)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
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
In net/ipv4/route.c (ffffffff81a89649)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
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
In net/ipv4/route.c (ffffffff81b44197)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
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
In net/ipv4/route.c (ffffffff81cd0d30)
Location: include/net/route.h:99
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
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
In net/ipv4/route.c (ffffffff81e90f60)
Location: include/net/route.h:99
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
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
In net/ipv4/route.c (ffffffff81eef713)
Location: include/net/route.h:93
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
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
In net/ipv4/route.c (ffffffff81fb3873)
Location: include/net/route.h:93
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5a15c)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d697d8)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5bbc8)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c3766)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81949ead)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
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
In net/ipv4/route.c (ffffffff8190399d)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967964)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b467d)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bdd94)
Location: include/net/route.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/route.c:ip_rt_send_redirect
  - net/ipv4/route.c:ip_rt_send_redirect
```
</details>
</li>
</ul>

## Differences
