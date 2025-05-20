# Function: <code>tcp_skb_bpf_redirect_fetch</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e5eed)
Location: include/net/tcp.h:866
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff81935adc)
Location: include/net/tcp.h:867
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff819688ec)
Location: include/net/tcp.h:888
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff81a3d3ae)
Location: include/net/tcp.h:899
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_skb_redirect
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
In net/core/skmsg.c (ffffffff81a3f694)
Location: include/net/tcp.h:905
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_skb_redirect
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/core/skmsg.c (ffff800010c0f3f8)
Location: include/net/tcp.h:888
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (c0d26920)
Location: include/net/tcp.h:888
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (c000000000cf9fc8)
Location: include/net/tcp.h:888
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffe00078afb2)
Location: include/net/tcp.h:888
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff819088bc)
Location: include/net/tcp.h:888
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818c26cc)
Location: include/net/tcp.h:888
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff819598ec)
Location: include/net/tcp.h:888
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/skmsg.c (ffffffff8197bb02)
Location: include/net/tcp.h:888
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
```
</details>
</li>
</ul>

## Differences
