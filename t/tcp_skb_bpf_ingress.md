# Function: <code>tcp_skb_bpf_ingress</code>

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
In net/core/skmsg.c (ffffffff818e5f82)
Location: include/net/tcp.h:861
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81935b83)
Location: include/net/tcp.h:862
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81968993)
Location: include/net/tcp.h:883
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81a3c9fd)
Location: include/net/tcp.h:894
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81a3f79f)
Location: include/net/tcp.h:900
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffff800010c0f494)
Location: include/net/tcp.h:883
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (c0d269d0)
Location: include/net/tcp.h:883
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (c000000000cfa0c0)
Location: include/net/tcp.h:883
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffe00078b03e)
Location: include/net/tcp.h:883
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81908963)
Location: include/net/tcp.h:883
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff818c2773)
Location: include/net/tcp.h:883
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81959993)
Location: include/net/tcp.h:883
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff8197bbbc)
Location: include/net/tcp.h:883
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_backlog
```
</details>
</li>
</ul>

## Differences
