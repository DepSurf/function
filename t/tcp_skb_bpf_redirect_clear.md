# Function: <code>tcp_skb_bpf_redirect_clear</code>

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
In net/core/skmsg.c (ffffffff818e5eb2)
Location: include/net/tcp.h:871
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
In net/core/skmsg.c (ffffffff81935ac4)
Location: include/net/tcp.h:872
Inline: True
Inline callers:
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
In net/core/skmsg.c (ffffffff819688d4)
Location: include/net/tcp.h:893
Inline: True
Inline callers:
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
In net/core/skmsg.c (ffffffff81a3d365)
Location: include/net/tcp.h:904
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
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
In net/core/skmsg.c (ffffffff81a3f652)
Location: include/net/tcp.h:910
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
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
In net/core/skmsg.c (ffff800010c0f3e0)
Location: include/net/tcp.h:893
Inline: True
Inline callers:
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
In net/core/skmsg.c (c0d26908)
Location: include/net/tcp.h:893
Inline: True
Inline callers:
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
In net/core/skmsg.c (c000000000cf9fb0)
Location: include/net/tcp.h:893
Inline: True
Inline callers:
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
In net/core/skmsg.c (ffffffe00078afa0)
Location: include/net/tcp.h:893
Inline: True
Inline callers:
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
In net/core/skmsg.c (ffffffff819088a4)
Location: include/net/tcp.h:893
Inline: True
Inline callers:
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
In net/core/skmsg.c (ffffffff818c26b4)
Location: include/net/tcp.h:893
Inline: True
Inline callers:
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
In net/core/skmsg.c (ffffffff819598d4)
Location: include/net/tcp.h:893
Inline: True
Inline callers:
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
In net/core/skmsg.c (ffffffff8197baea)
Location: include/net/tcp.h:893
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
</details>
</li>
</ul>

## Differences
