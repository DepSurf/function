# Function: <code>inet_csk_wait_for_connect</code>

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
In net/ipv4/inet_connection_sock.c (ffffffff81764f9b)
Location: net/ipv4/inet_connection_sock.c:255
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff817d151b)
Location: net/ipv4/inet_connection_sock.c:250
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff818013db)
Location: net/ipv4/inet_connection_sock.c:254
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff818218ad)
Location: net/ipv4/inet_connection_sock.c:380
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff818a0635)
Location: net/ipv4/inet_connection_sock.c:382
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff818f5405)
Location: net/ipv4/inet_connection_sock.c:377
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff81922d45)
Location: net/ipv4/inet_connection_sock.c:393
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff819856fc)
Location: net/ipv4/inet_connection_sock.c:389
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff819bc3ef)
Location: net/ipv4/inet_connection_sock.c:389
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet_csk_wait_for_connect(struct sock *sk, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5830)
Location: net/ipv4/inet_connection_sock.c:415
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff81aa5830-ffffffff81aa594d: inet_csk_wait_for_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet_csk_wait_for_connect(struct sock *sk, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aafe50)
Location: net/ipv4/inet_connection_sock.c:415
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
**Symbols:**

```
ffffffff81aafe50-ffffffff81aaff83: inet_csk_wait_for_connect (STB_LOCAL)
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
In net/ipv4/inet_connection_sock.c (ffffffff81a9bfc6)
Location: net/ipv4/inet_connection_sock.c:415
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff81b57866)
Location: net/ipv4/inet_connection_sock.c:423
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff81ce584d)
Location: net/ipv4/inet_connection_sock.c:427
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff81ea8a4d)
Location: net/ipv4/inet_connection_sock.c:588
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff81f072cd)
Location: net/ipv4/inet_connection_sock.c:609
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff81fcb612)
Location: net/ipv4/inet_connection_sock.c:606
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffff800010c6ddb4)
Location: net/ipv4/inet_connection_sock.c:389
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (c0d7c9c8)
Location: net/ipv4/inet_connection_sock.c:389
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (c000000000d7451c)
Location: net/ipv4/inet_connection_sock.c:389
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffe0007d34cc)
Location: net/ipv4/inet_connection_sock.c:389
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff8195c25f)
Location: net/ipv4/inet_connection_sock.c:389
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff81915d4f)
Location: net/ipv4/inet_connection_sock.c:389
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff819c6a2f)
Location: net/ipv4/inet_connection_sock.c:389
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
In net/ipv4/inet_connection_sock.c (ffffffff819d057f)
Location: net/ipv4/inet_connection_sock.c:389
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
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
