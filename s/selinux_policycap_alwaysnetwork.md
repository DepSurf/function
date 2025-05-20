# Function: <code>selinux_policycap_alwaysnetwork</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fe391)
Location: security/selinux/include/security.h:158
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8141a221)
Location: security/selinux/include/security.h:158
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff81447caa)
Location: security/selinux/include/security.h:159
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff8146183a)
Location: security/selinux/include/security.h:159
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff814b4dca)
Location: security/selinux/include/security.h:198
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff814d2a3c)
Location: security/selinux/include/security.h:195
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff814d8f9c)
Location: security/selinux/include/security.h:195
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff815320a2)
Location: security/selinux/include/security.h:195
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff815c9491)
Location: security/selinux/include/security.h:199
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff81676681)
Location: security/selinux/include/security.h:199
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff816ae9a1)
Location: security/selinux/include/security.h:171
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff816e8e15)
Location: security/selinux/include/security.h:164
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_peerlbl_enabled
  - security/selinux/hooks.c:selinux_secmark_enabled
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
In security/selinux/hooks.c (ffff80001054efac)
Location: security/selinux/include/security.h:159
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (c070897c)
Location: security/selinux/include/security.h:159
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (c0000000006b0248)
Location: security/selinux/include/security.h:159
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffe0003a8f32)
Location: security/selinux/include/security.h:159
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff81459e1a)
Location: security/selinux/include/security.h:159
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff8144a84a)
Location: security/selinux/include/security.h:159
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff81455eba)
Location: security/selinux/include/security.h:159
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
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
In security/selinux/hooks.c (ffffffff814711aa)
Location: security/selinux/include/security.h:159
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
```
</details>
</li>
</ul>

## Differences
