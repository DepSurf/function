# Function: <code>proto_handlers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff817b03e6)
Location: net/ipv4/xfrm4_protocol.c:30
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff817fd466)
Location: net/ipv6/xfrm6_protocol.c:30
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff8181d646)
Location: net/ipv4/xfrm4_protocol.c:30
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff8186d156)
Location: net/ipv6/xfrm6_protocol.c:30
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff8184eef6)
Location: net/ipv4/xfrm4_protocol.c:30
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff8189ff36)
Location: net/ipv6/xfrm6_protocol.c:30
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81872aaf)
Location: net/ipv4/xfrm4_protocol.c:30
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff818c654f)
Location: net/ipv6/xfrm6_protocol.c:30
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff818f34df)
Location: net/ipv4/xfrm4_protocol.c:30
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff8194991f)
Location: net/ipv6/xfrm6_protocol.c:30
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81949d9c)
Location: net/ipv4/xfrm4_protocol.c:30
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff819a292c)
Location: net/ipv6/xfrm6_protocol.c:30
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff8197ba8c)
Location: net/ipv4/xfrm4_protocol.c:30
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff819d95cc)
Location: net/ipv6/xfrm6_protocol.c:30
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff819e4f75)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81a47e95)
Location: net/ipv6/xfrm6_protocol.c:26
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81a1bfa5)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81a7ea45)
Location: net/ipv6/xfrm6_protocol.c:26
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81b0cf85)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b79695)
Location: net/ipv6/xfrm6_protocol.c:27
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81b1b2c5)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b88625)
Location: net/ipv6/xfrm6_protocol.c:27
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81b08f75)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b77355)
Location: net/ipv6/xfrm6_protocol.c:27
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81bcbe65)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81c41e25)
Location: net/ipv6/xfrm6_protocol.c:27
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81d619e5)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81de06d5)
Location: net/ipv6/xfrm6_protocol.c:27
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81f2c395)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81fb2a95)
Location: net/ipv6/xfrm6_protocol.c:27
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81f8bed5)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff82013035)
Location: net/ipv6/xfrm6_protocol.c:27
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff820537d5)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_encap
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff820e2195)
Location: net/ipv6/xfrm6_protocol.c:27
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffff800010cd81bc)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffff800010d49e44)
Location: net/ipv6/xfrm6_protocol.c:26
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (c0de1c00)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (c0e4b0c8)
Location: net/ipv6/xfrm6_protocol.c:26
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (c000000000df8464)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (c000000000e7f7c4)
Location: net/ipv6/xfrm6_protocol.c:26
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffe0008286ae)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffe0008830d6)
Location: net/ipv6/xfrm6_protocol.c:26
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff819bb635)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81a1e0d5)
Location: net/ipv6/xfrm6_protocol.c:26
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81978425)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff819dae95)
Location: net/ipv6/xfrm6_protocol.c:26
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81a260b5)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81a88b55)
Location: net/ipv6/xfrm6_protocol.c:26
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_protocol.c (ffffffff81a31565)
Location: net/ipv4/xfrm4_protocol.c:26
Inline: True
Inline callers:
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_deregister
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_protocol_register
  - net/ipv4/xfrm4_protocol.c:xfrm4_rcv_cb
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81a957b5)
Location: net/ipv6/xfrm6_protocol.c:26
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_deregister
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_protocol_register
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_cb
```
</details>
</li>
</ul>

## Differences
