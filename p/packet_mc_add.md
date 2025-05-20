# Function: <code>packet_mc_add</code>

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
In net/packet/af_packet.c (ffffffff8180651d)
Location: net/packet/af_packet.c:3404
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81876fe8)
Location: net/packet/af_packet.c:3477
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff818abedc)
Location: net/packet/af_packet.c:3442
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff818d1f18)
Location: net/packet/af_packet.c:3508
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81956ddc)
Location: net/packet/af_packet.c:3507
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff819b390c)
Location: net/packet/af_packet.c:3485
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff819ea937)
Location: net/packet/af_packet.c:3497
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81a59b55)
Location: net/packet/af_packet.c:3532
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81a8fc65)
Location: net/packet/af_packet.c:3551
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int packet_mc_add(struct sock *sk, struct packet_mreq_max *mreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b857c0)
Location: net/packet/af_packet.c:3562
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81b857c0-ffffffff81b859a3: packet_mc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int packet_mc_add(struct sock *sk, struct packet_mreq_max *mreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b951d0)
Location: net/packet/af_packet.c:3579
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81b951d0-ffffffff81b953b3: packet_mc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int packet_mc_add(struct sock *sk, struct packet_mreq_max *mreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b84230)
Location: net/packet/af_packet.c:3593
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81b84230-ffffffff81b84413: packet_mc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int packet_mc_add(struct sock *sk, struct packet_mreq_max *mreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c50320)
Location: net/packet/af_packet.c:3597
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81c50320-ffffffff81c50503: packet_mc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int packet_mc_add(struct sock *sk, struct packet_mreq_max *mreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3651
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81df0ea0-ffffffff81df109a: packet_mc_add (STB_LOCAL)
ffffffff81f0e245-ffffffff81f0e251: packet_mc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int packet_mc_add(struct sock *sk, struct packet_mreq_max *mreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc5200)
Location: net/packet/af_packet.c:3650
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81fc5200-ffffffff81fc5411: packet_mc_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int packet_mc_add(struct sock *sk, struct packet_mreq_max *mreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3663
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff82025d20-ffffffff82025fec: packet_mc_add (STB_LOCAL)
ffffffff821362b7-ffffffff821362d2: packet_mc_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int packet_mc_add(struct sock *sk, struct packet_mreq_max *mreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3664
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff820f5700-ffffffff820f59fb: packet_mc_add (STB_LOCAL)
ffffffff82217ea4-ffffffff82217ebf: packet_mc_add.cold (STB_LOCAL)
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
In net/packet/af_packet.c (ffff800010d5cd5c)
Location: net/packet/af_packet.c:3551
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (c0e5e184)
Location: net/packet/af_packet.c:3551
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (c000000000e98b58)
Location: net/packet/af_packet.c:3551
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffe000893490)
Location: net/packet/af_packet.c:3551
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81a2f2f5)
Location: net/packet/af_packet.c:3551
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff819ec4e5)
Location: net/packet/af_packet.c:3551
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81a9aea5)
Location: net/packet/af_packet.c:3551
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
In net/packet/af_packet.c (ffffffff81aa7c17)
Location: net/packet/af_packet.c:3551
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
