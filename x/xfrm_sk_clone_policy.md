# Function: <code>xfrm_sk_clone_policy</code>

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
In net/core/sock.c (ffffffff81703f19)
Location: include/net/xfrm.h:1147
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff8176a9af)
Location: include/net/xfrm.h:1143
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff81797acf)
Location: include/net/xfrm.h:1143
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff817b56cc)
Location: include/net/xfrm.h:1202
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff8182db8c)
Location: include/net/xfrm.h:1208
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff81877f4f)
Location: include/net/xfrm.h:1240
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff8189842f)
Location: include/net/xfrm.h:1245
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff818e29c8)
Location: include/net/xfrm.h:1170
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff81914b9c)
Location: include/net/xfrm.h:1170
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff819e70fe)
Location: include/net/xfrm.h:1169
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff819e6942)
Location: include/net/xfrm.h:1172
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff819cc73e)
Location: include/net/xfrm.h:1172
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff81a7be09)
Location: include/net/xfrm.h:1193
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff81befc6a)
Location: include/net/xfrm.h:1196
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9cabd)
Location: include/net/xfrm.h:1246
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed1366)
Location: include/net/xfrm.h:1246
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0b315)
Location: include/net/xfrm.h:1252
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2fa97)
Location: include/net/xfrm.h:1252
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec7d05)
Location: include/net/xfrm.h:1252
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff5979)
Location: include/net/xfrm.h:1252
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
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
In net/core/sock.c (ffff800010bad8cc)
Location: include/net/xfrm.h:1170
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (c0ccb458)
Location: include/net/xfrm.h:1170
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (c000000000c831b4)
Location: include/net/xfrm.h:1170
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffe00073faa0)
Location: include/net/xfrm.h:1170
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff818b4b9c)
Location: include/net/xfrm.h:1170
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff8186eaec)
Location: include/net/xfrm.h:1170
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff81905b9c)
Location: include/net/xfrm.h:1170
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
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
In net/core/sock.c (ffffffff81926bd1)
Location: include/net/xfrm.h:1170
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
</details>
</li>
</ul>

## Differences
