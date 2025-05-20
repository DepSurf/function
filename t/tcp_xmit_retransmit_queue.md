# Function: <code>tcp_xmit_retransmit_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81778c30)
Location: net/ipv4/tcp_output.c:2713
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_resume_early_retransmit
```
**Symbols:**

```
ffffffff81778c30-ffffffff81778f2c: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e5db0)
Location: net/ipv4/tcp_output.c:2754
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_resume_early_retransmit
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
```
**Symbols:**

```
ffffffff817e5db0-ffffffff817e60ed: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81816230)
Location: net/ipv4/tcp_output.c:2874
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_resume_early_retransmit
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
```
**Symbols:**

```
ffffffff81816230-ffffffff8181653b: tcp_xmit_retransmit_queue.part.36 (STB_LOCAL)
ffffffff818167f0-ffffffff8181680b: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818365d0)
Location: net/ipv4/tcp_output.c:2919
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff818365d0-ffffffff8183682f: tcp_xmit_retransmit_queue.part.37 (STB_LOCAL)
ffffffff81836af0-ffffffff81836b0c: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b5c20)
Location: net/ipv4/tcp_output.c:2973
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff818b5c20-ffffffff818b5e69: tcp_xmit_retransmit_queue.part.41 (STB_LOCAL)
ffffffff818b61a0-ffffffff818b61bc: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8190b3b0)
Location: net/ipv4/tcp_output.c:2954
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff8190b3b0-ffffffff8190b635: tcp_xmit_retransmit_queue.part.48 (STB_LOCAL)
ffffffff8190b9e0-ffffffff8190b9fb: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81939660)
Location: net/ipv4/tcp_output.c:2985
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81939660-ffffffff819398ff: tcp_xmit_retransmit_queue.part.50 (STB_LOCAL)
ffffffff81939cb0-ffffffff81939ccb: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199d940)
Location: net/ipv4/tcp_output.c:3015
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff8199d940-ffffffff8199dbeb: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff8199df70-ffffffff8199df8b: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d4410)
Location: net/ipv4/tcp_output.c:3046
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff819d4410-ffffffff819d46af: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff819d4a30-ffffffff819d4a4b: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac0c90)
Location: net/ipv4/tcp_output.c:3115
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81ac0c90-ffffffff81ac0fd1: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff81ac1400-ffffffff81ac141b: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acc700)
Location: net/ipv4/tcp_output.c:3287
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81acc700-ffffffff81acca41: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff81acce70-ffffffff81acce8b: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab78c0)
Location: net/ipv4/tcp_output.c:3284
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81ab78c0-ffffffff81ab7c02: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff81ab8040-ffffffff81ab805b: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b74ae0)
Location: net/ipv4/tcp_output.c:3284
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81b74ae0-ffffffff81b74dc2: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff81b75200-ffffffff81b7521b: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d04250)
Location: net/ipv4/tcp_output.c:3289
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81d04250-ffffffff81d04579: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff81d04a00-ffffffff81d04a2b: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec91c0)
Location: net/ipv4/tcp_output.c:3291
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81ec91c0-ffffffff81ec94e9: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff81ec99f0-ffffffff81ec9a1b: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f27ce0)
Location: net/ipv4/tcp_output.c:3373
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81f27ce0-ffffffff81f28043: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff81f28540-ffffffff81f2856b: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fec790)
Location: net/ipv4/tcp_output.c:3437
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81fec790-ffffffff81fecab9: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff81fecfd0-ffffffff81fecffb: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c86f20)
Location: net/ipv4/tcp_output.c:3046
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffff800010c86f20-ffff800010c871c8: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffff800010c87628-ffff800010c8765c: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (c0d96340)
Location: net/ipv4/tcp_output.c:3046
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
c0d96340-c0d9662c: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
c0d96988-c0d969b0: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d937f0)
Location: net/ipv4/tcp_output.c:3046
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
c000000000d937f0-c000000000d93b9c: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
c000000000d94180-c000000000d941a0: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e841e)
Location: net/ipv4/tcp_output.c:3046
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffe0007e841e-ffffffe0007e86ac: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffe0007e89e8-ffffffe0007e8a18: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81974280)
Location: net/ipv4/tcp_output.c:3046
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81974280-ffffffff8197451f: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff819748a0-ffffffff819748bb: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192dd50)
Location: net/ipv4/tcp_output.c:3046
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff8192dd50-ffffffff8192dfef: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff8192e360-ffffffff8192e37b: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819dea50)
Location: net/ipv4/tcp_output.c:3046
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff819dea50-ffffffff819decef: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff819df070-ffffffff819df08b: tcp_xmit_retransmit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_xmit_retransmit_queue(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e86f0)
Location: net/ipv4/tcp_output.c:3046
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff819e86f0-ffffffff819e898f: tcp_xmit_retransmit_queue.part.0 (STB_LOCAL)
ffffffff819e8d10-ffffffff819e8d2b: tcp_xmit_retransmit_queue (STB_GLOBAL)
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
