# Function: <code>tcp_send_challenge_ack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_send_challenge_ack(struct sock *sk, const struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81771f80)
Location: net/ipv4/tcp_input.c:3424
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
**Symbols:**

```
ffffffff81771f80-ffffffff8177200f: tcp_send_challenge_ack (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff817d82e0)
Location: net/ipv4/tcp_input.c:3462
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff817d82e0-ffffffff817d83b4: tcp_send_challenge_ack.isra.51 (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff81808700)
Location: net/ipv4/tcp_input.c:3468
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81808700-ffffffff818087d4: tcp_send_challenge_ack.isra.52 (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff81828d10)
Location: net/ipv4/tcp_input.c:3431
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81828d10-ffffffff81828de5: tcp_send_challenge_ack.isra.51 (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff818a8220)
Location: net/ipv4/tcp_input.c:3376
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff818a8220-ffffffff818a82fd: tcp_send_challenge_ack.isra.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fd580)
Location: net/ipv4/tcp_input.c:3434
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff818fd580-ffffffff818fd670: tcp_send_challenge_ack.isra.57 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192b680)
Location: net/ipv4/tcp_input.c:3427
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8192b680-ffffffff8192b770: tcp_send_challenge_ack.isra.66 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198e910)
Location: net/ipv4/tcp_input.c:3447
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8198e910-ffffffff8198e9fd: tcp_send_challenge_ack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c5650)
Location: net/ipv4/tcp_input.c:3454
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819c5650-ffffffff819c573d: tcp_send_challenge_ack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab09a0)
Location: net/ipv4/tcp_input.c:3438
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ab09a0-ffffffff81ab0a8d: tcp_send_challenge_ack.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abb970)
Location: net/ipv4/tcp_input.c:3558
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81abb970-ffffffff81abba5d: tcp_send_challenge_ack.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa6930)
Location: net/ipv4/tcp_input.c:3565
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81aa6930-ffffffff81aa6a1d: tcp_send_challenge_ack.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b62d20)
Location: net/ipv4/tcp_input.c:3599
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81b62d20-ffffffff81b62e0d: tcp_send_challenge_ack.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_send_challenge_ack(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf13b0)
Location: net/ipv4/tcp_input.c:3616
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81cf13b0-ffffffff81cf14c3: tcp_send_challenge_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_send_challenge_ack(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb5710)
Location: net/ipv4/tcp_input.c:3627
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81eb5710-ffffffff81eb5824: tcp_send_challenge_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_send_challenge_ack(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f13b40)
Location: net/ipv4/tcp_input.c:3632
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81f13b40-ffffffff81f13c54: tcp_send_challenge_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_send_challenge_ack(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd8020)
Location: net/ipv4/tcp_input.c:3706
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81fd8020-ffffffff81fd8135: tcp_send_challenge_ack (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7a288)
Location: net/ipv4/tcp_input.c:3454
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffff800010c7a288-ffff800010c7a3b4: tcp_send_challenge_ack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (c0d86afc)
Location: net/ipv4/tcp_input.c:3454
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c0d86afc-c0d86bc8: tcp_send_challenge_ack.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d80be0)
Location: net/ipv4/tcp_input.c:3454
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c000000000d80be0-c000000000d80d30: tcp_send_challenge_ack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007db34c)
Location: net/ipv4/tcp_input.c:3454
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffe0007db34c-ffffffe0007db442: tcp_send_challenge_ack.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819654c0)
Location: net/ipv4/tcp_input.c:3454
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819654c0-ffffffff819655ad: tcp_send_challenge_ack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191efb0)
Location: net/ipv4/tcp_input.c:3454
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8191efb0-ffffffff8191f09d: tcp_send_challenge_ack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cfc90)
Location: net/ipv4/tcp_input.c:3454
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819cfc90-ffffffff819cfd7d: tcp_send_challenge_ack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d9820)
Location: net/ipv4/tcp_input.c:3454
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819d9820-ffffffff819d990e: tcp_send_challenge_ack.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
