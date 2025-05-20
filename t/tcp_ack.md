# Function: <code>tcp_ack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81772010)
Location: net/ipv4/tcp_input.c:3512
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
**Symbols:**

```
ffffffff81772010-ffffffff8177280b: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dd9d0)
Location: net/ipv4/tcp_input.c:3576
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff817dd9d0-ffffffff817de25d: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180db50)
Location: net/ipv4/tcp_input.c:3582
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff8180db50-ffffffff8180e5aa: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182e0b0)
Location: net/ipv4/tcp_input.c:3545
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff8182e0b0-ffffffff8182e932: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818acef0)
Location: net/ipv4/tcp_input.c:3491
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff818acef0-ffffffff818ad90e: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3565
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff81902670-ffffffff81903027: tcp_ack (STB_LOCAL)
ffffffff81906189-ffffffff819061c4: tcp_ack.cold.80 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3558
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff81930760-ffffffff8193117f: tcp_ack (STB_LOCAL)
ffffffff8193432b-ffffffff81934366: tcp_ack.cold.86 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81993d60)
Location: net/ipv4/tcp_input.c:3578
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff81993d60-ffffffff81994814: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819ca8b0)
Location: net/ipv4/tcp_input.c:3585
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff819ca8b0-ffffffff819cb362: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab7860)
Location: net/ipv4/tcp_input.c:3570
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff81ab7860-ffffffff81ab8180: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac2b10)
Location: net/ipv4/tcp_input.c:3689
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff81ac2b10-ffffffff81ac336c: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aadca0)
Location: net/ipv4/tcp_input.c:3696
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff81aadca0-ffffffff81aae6a1: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3730
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff81b6a790-ffffffff81b6b38f: tcp_ack (STB_LOCAL)
ffffffff81d3ab88-ffffffff81d3abde: tcp_ack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3747
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff81cf9950-ffffffff81cfa4a6: tcp_ack (STB_LOCAL)
ffffffff81f07430-ffffffff81f07486: tcp_ack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3760
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff81ebe460-ffffffff81ebefb3: tcp_ack (STB_LOCAL)
ffffffff820aeec4-ffffffff820aef1a: tcp_ack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:3765
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff81f1c900-ffffffff81f1d446: tcp_ack (STB_LOCAL)
ffffffff821302bc-ffffffff82130312: tcp_ack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fe10e0)
Location: net/ipv4/tcp_input.c:3839
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff81fe10e0-ffffffff81fe1a28: tcp_ack (STB_LOCAL)
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
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7d5a8)
Location: net/ipv4/tcp_input.c:3585
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffff800010c7d5a8-ffff800010c7ded8: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8c430)
Location: net/ipv4/tcp_input.c:3585
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
c0d8c430-c0d8ce08: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d87350)
Location: net/ipv4/tcp_input.c:3585
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
c000000000d87350-c000000000d87ee0: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dfb12)
Location: net/ipv4/tcp_input.c:3585
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffe0007dfb12-ffffffe0007e031e: tcp_ack (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196a720)
Location: net/ipv4/tcp_input.c:3585
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff8196a720-ffffffff8196b1d2: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81924210)
Location: net/ipv4/tcp_input.c:3585
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff81924210-ffffffff81924cc2: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d4ef0)
Location: net/ipv4/tcp_input.c:3585
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff819d4ef0-ffffffff819d59a2: tcp_ack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_ack(struct sock *sk, const struct sk_buff *skb, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dead0)
Location: net/ipv4/tcp_input.c:3585
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
**Symbols:**

```
ffffffff819dead0-ffffffff819df585: tcp_ack (STB_LOCAL)
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
