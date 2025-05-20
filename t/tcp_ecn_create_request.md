# Function: <code>tcp_ecn_create_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176df8e)
Location: net/ipv4/tcp_input.c:6040
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dc3ae)
Location: net/ipv4/tcp_input.c:6089
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180c2d9)
Location: net/ipv4/tcp_input.c:6181
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182c4c7)
Location: net/ipv4/tcp_input.c:6178
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818ab39a)
Location: net/ipv4/tcp_input.c:6073
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819007f3)
Location: net/ipv4/tcp_input.c:6237
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff8192e94b)
Location: net/ipv4/tcp_input.c:6288
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff81991f00)
Location: net/ipv4/tcp_input.c:6346
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff819c8b14)
Location: net/ipv4/tcp_input.c:6402
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_ecn_create_request(struct request_sock *req, const struct sk_buff *skb, const struct sock *listen_sk, const struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab3b10)
Location: net/ipv4/tcp_input.c:6461
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81ab3b10-ffffffff81ab3c6f: tcp_ecn_create_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_ecn_create_request(struct request_sock *req, const struct sk_buff *skb, const struct sock *listen_sk, const struct dst_entry *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abe480)
Location: net/ipv4/tcp_input.c:6598
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
**Symbols:**

```
ffffffff81abe480-ffffffff81abe5ce: tcp_ecn_create_request (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff81aaacf6)
Location: net/ipv4/tcp_input.c:6607
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff81b670e6)
Location: net/ipv4/tcp_input.c:6642
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff81cf6167)
Location: net/ipv4/tcp_input.c:6724
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff81ebab77)
Location: net/ipv4/tcp_input.c:6746
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff81f19007)
Location: net/ipv4/tcp_input.c:6753
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff81fdd807)
Location: net/ipv4/tcp_input.c:6913
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffff800010c7a738)
Location: net/ipv4/tcp_input.c:6402
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (c0d881ec)
Location: net/ipv4/tcp_input.c:6402
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (c000000000d853e0)
Location: net/ipv4/tcp_input.c:6402
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffe0007de4a2)
Location: net/ipv4/tcp_input.c:6402
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff81968984)
Location: net/ipv4/tcp_input.c:6402
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff81922474)
Location: net/ipv4/tcp_input.c:6402
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff819d3154)
Location: net/ipv4/tcp_input.c:6402
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
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
In net/ipv4/tcp_input.c (ffffffff819dccfa)
Location: net/ipv4/tcp_input.c:6402
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
