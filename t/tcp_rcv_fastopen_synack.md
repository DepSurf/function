# Function: <code>tcp_rcv_fastopen_synack</code>

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
In net/ipv4/tcp_input.c (ffffffff81773fa0)
Location: net/ipv4/tcp_input.c:5463
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
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
In net/ipv4/tcp_input.c (ffffffff817e0e1d)
Location: net/ipv4/tcp_input.c:5523
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
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
In net/ipv4/tcp_input.c (ffffffff81811226)
Location: net/ipv4/tcp_input.c:5609
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
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
In net/ipv4/tcp_input.c (ffffffff8183123e)
Location: net/ipv4/tcp_input.c:5597
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
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
In net/ipv4/tcp_input.c (ffffffff818b0685)
Location: net/ipv4/tcp_input.c:5494
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
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
In net/ipv4/tcp_input.c (ffffffff81905ca8)
Location: net/ipv4/tcp_input.c:5652
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
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
In net/ipv4/tcp_input.c (ffffffff81933e49)
Location: net/ipv4/tcp_input.c:5701
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
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
In net/ipv4/tcp_input.c (ffffffff819974ef)
Location: net/ipv4/tcp_input.c:5732
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
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
In net/ipv4/tcp_input.c (ffffffff819ce077)
Location: net/ipv4/tcp_input.c:5783
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tcp_rcv_fastopen_synack(struct sock *sk, struct sk_buff *synack, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab8180)
Location: net/ipv4/tcp_input.c:5825
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81ab8180-ffffffff81ab838e: tcp_rcv_fastopen_synack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcp_rcv_fastopen_synack(struct sock *sk, struct sk_buff *synack, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac3370)
Location: net/ipv4/tcp_input.c:5961
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81ac3370-ffffffff81ac357e: tcp_rcv_fastopen_synack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_rcv_fastopen_synack(struct sock *sk, struct sk_buff *synack, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aaba20)
Location: net/ipv4/tcp_input.c:5969
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81aaba20-ffffffff81aabc22: tcp_rcv_fastopen_synack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tcp_rcv_fastopen_synack(struct sock *sk, struct sk_buff *synack, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b67e60)
Location: net/ipv4/tcp_input.c:6004
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81b67e60-ffffffff81b68062: tcp_rcv_fastopen_synack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tcp_rcv_fastopen_synack(struct sock *sk, struct sk_buff *synack, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf6f80)
Location: net/ipv4/tcp_input.c:6070
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81cf6f80-ffffffff81cf71ad: tcp_rcv_fastopen_synack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcp_rcv_fastopen_synack(struct sock *sk, struct sk_buff *synack, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebb9f0)
Location: net/ipv4/tcp_input.c:6092
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81ebb9f0-ffffffff81ebbc1d: tcp_rcv_fastopen_synack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcp_rcv_fastopen_synack(struct sock *sk, struct sk_buff *synack, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f19e70)
Location: net/ipv4/tcp_input.c:6099
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81f19e70-ffffffff81f1a09c: tcp_rcv_fastopen_synack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcp_rcv_fastopen_synack(struct sock *sk, struct sk_buff *synack, struct tcp_fastopen_cookie *cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fde640)
Location: net/ipv4/tcp_input.c:6246
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
```
**Symbols:**

```
ffffffff81fde640-ffffffff81fde86e: tcp_rcv_fastopen_synack (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffff800010c80b0c)
Location: net/ipv4/tcp_input.c:5783
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
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
In net/ipv4/tcp_input.c (c0d8fd38)
Location: net/ipv4/tcp_input.c:5783
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
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
In net/ipv4/tcp_input.c (c000000000d8b850)
Location: net/ipv4/tcp_input.c:5783
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
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
In net/ipv4/tcp_input.c (ffffffe0007e2a80)
Location: net/ipv4/tcp_input.c:5783
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
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
In net/ipv4/tcp_input.c (ffffffff8196dee7)
Location: net/ipv4/tcp_input.c:5783
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
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
In net/ipv4/tcp_input.c (ffffffff819279d7)
Location: net/ipv4/tcp_input.c:5783
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
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
In net/ipv4/tcp_input.c (ffffffff819d86b7)
Location: net/ipv4/tcp_input.c:5783
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
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
In net/ipv4/tcp_input.c (ffffffff819e22fa)
Location: net/ipv4/tcp_input.c:5783
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
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
