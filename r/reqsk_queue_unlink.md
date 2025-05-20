# Function: <code>reqsk_queue_unlink</code>

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
In net/ipv4/inet_connection_sock.c (ffffffff817651b3)
Location: net/ipv4/inet_connection_sock.c:522
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffff817d1733)
Location: net/ipv4/inet_connection_sock.c:513
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
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
In net/ipv4/inet_connection_sock.c (ffffffff818015e3)
Location: net/ipv4/inet_connection_sock.c:517
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
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
In net/ipv4/inet_connection_sock.c (ffffffff81821503)
Location: net/ipv4/inet_connection_sock.c:643
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
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
In net/ipv4/inet_connection_sock.c (ffffffff818a08c3)
Location: net/ipv4/inet_connection_sock.c:642
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
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
In net/ipv4/inet_connection_sock.c (ffffffff818f4d95)
Location: net/ipv4/inet_connection_sock.c:637
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
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
In net/ipv4/inet_connection_sock.c (ffffffff81922fc5)
Location: net/ipv4/inet_connection_sock.c:656
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
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
In net/ipv4/inet_connection_sock.c (ffffffff81985965)
Location: net/ipv4/inet_connection_sock.c:652
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffff819bbe05)
Location: net/ipv4/inet_connection_sock.c:672
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool reqsk_queue_unlink(struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6890)
Location: net/ipv4/inet_connection_sock.c:692
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
**Symbols:**

```
ffffffff81aa6890-ffffffff81aa69dd: reqsk_queue_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool reqsk_queue_unlink(struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0ee0)
Location: net/ipv4/inet_connection_sock.c:691
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
**Symbols:**

```
ffffffff81ab0ee0-ffffffff81ab102d: reqsk_queue_unlink (STB_LOCAL)
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
In net/ipv4/inet_connection_sock.c (ffffffff81a9c255)
Location: net/ipv4/inet_connection_sock.c:691
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffff81b57b15)
Location: net/ipv4/inet_connection_sock.c:760
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffff81ce5b15)
Location: net/ipv4/inet_connection_sock.c:764
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffff81ea8d25)
Location: net/ipv4/inet_connection_sock.c:925
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffff81f075a5)
Location: net/ipv4/inet_connection_sock.c:949
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffff81fcb905)
Location: net/ipv4/inet_connection_sock.c:950
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffff800010c6d2c0)
Location: net/ipv4/inet_connection_sock.c:672
Inline: True
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
In net/ipv4/inet_connection_sock.c (c0d7c284)
Location: net/ipv4/inet_connection_sock.c:672
Inline: True
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
In net/ipv4/inet_connection_sock.c (c000000000d73258)
Location: net/ipv4/inet_connection_sock.c:672
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffe0007d2fa0)
Location: net/ipv4/inet_connection_sock.c:672
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffff8195bc75)
Location: net/ipv4/inet_connection_sock.c:672
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffff81915765)
Location: net/ipv4/inet_connection_sock.c:672
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffff819c6445)
Location: net/ipv4/inet_connection_sock.c:672
Inline: True
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
In net/ipv4/inet_connection_sock.c (ffffffff819cff65)
Location: net/ipv4/inet_connection_sock.c:672
Inline: True
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
