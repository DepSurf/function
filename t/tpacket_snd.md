# Function: <code>tpacket_snd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818072b0)
Location: net/packet/af_packet.c:2472
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff818072b0-ffffffff81807ef7: tpacket_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81878b30)
Location: net/packet/af_packet.c:2606
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81878b30-ffffffff8187990c: tpacket_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818ad0b0)
Location: net/packet/af_packet.c:2559
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff818ad0b0-ffffffff818adfef: tpacket_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818d2680)
Location: net/packet/af_packet.c:2629
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff818d2680-ffffffff818d35dd: tpacket_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819575b0)
Location: net/packet/af_packet.c:2618
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff819575b0-ffffffff8195851f: tpacket_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2592
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff819af430-ffffffff819b0197: tpacket_snd (STB_LOCAL)
ffffffff819b3f45-ffffffff819b3fb8: tpacket_snd.cold.81 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2595
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff819e6950-ffffffff819e7981: tpacket_snd (STB_LOCAL)
ffffffff819eaf77-ffffffff819eafea: tpacket_snd.cold.83 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2600
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81a55e40-ffffffff81a56de8: tpacket_snd (STB_LOCAL)
ffffffff81a5a0fe-ffffffff81a5a181: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2619
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81a8d320-ffffffff81a8e2c8: tpacket_snd (STB_LOCAL)
ffffffff81a90d6c-ffffffff81a90def: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2630
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81b88070-ffffffff81b8896c: tpacket_snd (STB_LOCAL)
ffffffff81b8c22d-ffffffff81b8c288: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2647
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81b97b50-ffffffff81b98450: tpacket_snd (STB_LOCAL)
ffffffff81c3321e-ffffffff81c33279: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2656
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81b86b50-ffffffff81b873cb: tpacket_snd (STB_LOCAL)
ffffffff81c25520-ffffffff81c25573: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2662
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81c53410-ffffffff81c53dcd: tpacket_snd (STB_LOCAL)
ffffffff81d41975-ffffffff81d41a16: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2713
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81df6bf0-ffffffff81df75ce: tpacket_snd (STB_LOCAL)
ffffffff81f0e354-ffffffff81f0e3c6: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2713
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81fcb200-ffffffff81fcbbda: tpacket_snd (STB_LOCAL)
ffffffff820b5437-ffffffff820b544c: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2725
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff8202c4e0-ffffffff8202cee6: tpacket_snd (STB_LOCAL)
ffffffff82136332-ffffffff82136347: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2719
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff820fbf80-ffffffff820fc97d: tpacket_snd (STB_LOCAL)
ffffffff82217f1f-ffffffff82217f34: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d58ed0)
Location: net/packet/af_packet.c:2619
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffff800010d58ed0-ffff800010d59b84: tpacket_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e5a840)
Location: net/packet/af_packet.c:2619
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
c0e5a840-c0e5b5b4: tpacket_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e949d0)
Location: net/packet/af_packet.c:2619
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
c000000000e949d0-c000000000e959f4: tpacket_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe0008911fa)
Location: net/packet/af_packet.c:2619
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffe0008911fa-ffffffe000891d12: tpacket_snd (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2619
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81a2c9b0-ffffffff81a2d958: tpacket_snd (STB_LOCAL)
ffffffff81a303fc-ffffffff81a3047f: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2619
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff819e9ba0-ffffffff819eab48: tpacket_snd (STB_LOCAL)
ffffffff819ed5ec-ffffffff819ed66f: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2619
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81a98560-ffffffff81a99508: tpacket_snd (STB_LOCAL)
ffffffff81a9bfac-ffffffff81a9c02f: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpacket_snd(struct packet_sock *po, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:2619
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81aa4bf0-ffffffff81aa5ba2: tpacket_snd (STB_LOCAL)
ffffffff81aa8198-ffffffff81aa821b: tpacket_snd.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
