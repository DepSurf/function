# Function: <code>tcp_cookie_time</code>

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
In net/ipv4/syncookies.c (ffffffff817aaf5f)
Location: include/net/tcp.h:517
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff817ff09f)
Location: include/net/tcp.h:517
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_check
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
In net/ipv4/syncookies.c (ffffffff81818b26)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff8186eafa)
Location: include/net/tcp.h:510
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In net/ipv4/syncookies.c (ffffffff8184a386)
Location: include/net/tcp.h:508
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff818a1a4a)
Location: include/net/tcp.h:508
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In net/ipv4/syncookies.c (ffffffff8186dd47)
Location: include/net/tcp.h:514
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff818c8017)
Location: include/net/tcp.h:514
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In net/ipv4/syncookies.c (ffffffff818ee697)
Location: include/net/tcp.h:485
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff8194b5c7)
Location: include/net/tcp.h:485
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In net/ipv4/syncookies.c (ffffffff81945065)
Location: include/net/tcp.h:491
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff819a48b2)
Location: include/net/tcp.h:491
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In net/ipv4/syncookies.c (ffffffff81975355)
Location: include/net/tcp.h:518
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff819db3c2)
Location: include/net/tcp.h:518
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff819deef0)
Location: include/net/tcp.h:519
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a4a02d)
Location: include/net/tcp.h:519
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81a15f90)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a80bed)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81b07000)
Location: include/net/tcp.h:546
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81b7b76a)
Location: include/net/tcp.h:546
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81b151f0)
Location: include/net/tcp.h:551
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81b8a7aa)
Location: include/net/tcp.h:551
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81b02ff7)
Location: include/net/tcp.h:552
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81b79606)
Location: include/net/tcp.h:552
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81bc5227)
Location: include/net/tcp.h:545
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81c44286)
Location: include/net/tcp.h:545
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81d5a3ad)
Location: include/net/tcp.h:556
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81de31f0)
Location: include/net/tcp.h:556
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In net/ipv4/syncookies.c (ffffffff81f247bd)
Location: include/net/tcp.h:566
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81fb5840)
Location: include/net/tcp.h:566
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In net/ipv4/syncookies.c (ffffffff81f84352)
Location: include/net/tcp.h:560
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff82015f60)
Location: include/net/tcp.h:560
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In net/ipv4/syncookies.c (ffffffff8204aa09)
Location: include/net/tcp.h:572
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff820e50ae)
Location: include/net/tcp.h:572
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffff800010cd1bd8)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffff800010d4c44c)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (c0ddbc30)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (c0e4d690)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (c000000000defea0)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (c000000000e82aa4)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffe000822ff0)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffe000885188)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff819b5620)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a2027d)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In net/ipv4/syncookies.c (ffffffff81972410)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff819dd03d)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81a1fec0)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a8acfd)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff81a2b3c0)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a9795d)
Location: include/net/tcp.h:540
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
</ul>

## Differences
