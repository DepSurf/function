# Function: <code>register_prot_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81803d30)
Location: net/packet/af_packet.c:340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_set_ring
Direct callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81803d30-ffffffff81803d6e: register_prot_hook.part.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81875e92)
Location: net/packet/af_packet.c:341
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff81874cf0-ffffffff81874d2e: register_prot_hook.part.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff818aa37b)
Location: net/packet/af_packet.c:340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff818a91b0-ffffffff818a91ee: register_prot_hook.part.52 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff818d0eae)
Location: net/packet/af_packet.c:340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff818cfc00-ffffffff818cfc3e: register_prot_hook.part.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (ffffffff81955db3)
Location: net/packet/af_packet.c:335
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
Direct callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_do_bind
```
**Symbols:**

```
ffffffff81954ac0-ffffffff81954b04: register_prot_hook.part.51 (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff819b14e7)
Location: net/packet/af_packet.c:319
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff819e88d0)
Location: net/packet/af_packet.c:320
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff81a58a21)
Location: net/packet/af_packet.c:312
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff81a8eb18)
Location: net/packet/af_packet.c:312
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff81b89bec)
Location: net/packet/af_packet.c:312
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff81b99707)
Location: net/packet/af_packet.c:316
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff81b88bd0)
Location: net/packet/af_packet.c:316
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff81c54cd1)
Location: net/packet/af_packet.c:317
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff81df4edb)
Location: net/packet/af_packet.c:353
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff81fc7863)
Location: net/packet/af_packet.c:353
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff82028899)
Location: net/packet/af_packet.c:351
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff820f82d1)
Location: net/packet/af_packet.c:351
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffff800010d5bc98)
Location: net/packet/af_packet.c:312
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (c0e5bde8)
Location: net/packet/af_packet.c:312
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (c000000000e97640)
Location: net/packet/af_packet.c:312
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffe000891ff6)
Location: net/packet/af_packet.c:312
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff81a2e1a8)
Location: net/packet/af_packet.c:312
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff819eb398)
Location: net/packet/af_packet.c:312
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff81a99d58)
Location: net/packet/af_packet.c:312
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
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
In net/packet/af_packet.c (ffffffff81aa6a87)
Location: net/packet/af_packet.c:312
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
```
</details>
</li>
</ul>

## Differences
