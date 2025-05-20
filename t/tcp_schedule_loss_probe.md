# Function: <code>tcp_schedule_loss_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81775af0)
Location: net/ipv4/tcp_output.c:2146
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81775af0-ffffffff81775c93: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e2a50)
Location: net/ipv4/tcp_output.c:2165
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff817e2a50-ffffffff817e2beb: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818130e0)
Location: net/ipv4/tcp_output.c:2285
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff818130e0-ffffffff8181327b: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81833300)
Location: net/ipv4/tcp_output.c:2376
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81833300-ffffffff8183346d: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b2650)
Location: net/ipv4/tcp_output.c:2428
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff818b2650-ffffffff818b278b: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81907b40)
Location: net/ipv4/tcp_output.c:2409
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81907b40-ffffffff81907c78: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81935dd0)
Location: net/ipv4/tcp_output.c:2437
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81935dd0-ffffffff81935f44: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199a160)
Location: net/ipv4/tcp_output.c:2464
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff8199a160-ffffffff8199a303: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d0b70)
Location: net/ipv4/tcp_output.c:2491
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff819d0b70-ffffffff819d0d21: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abf970)
Location: net/ipv4/tcp_output.c:2554
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81abc7f0-ffffffff81abc991: tcp_schedule_loss_probe.part.0 (STB_LOCAL)
ffffffff81abdd50-ffffffff81abdd73: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acb425)
Location: net/ipv4/tcp_output.c:2726
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ac7f60-ffffffff81ac8101: tcp_schedule_loss_probe.part.0 (STB_LOCAL)
ffffffff81ac9630-ffffffff81ac9653: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab64d3)
Location: net/ipv4/tcp_output.c:2727
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ab3030-ffffffff81ab31d2: tcp_schedule_loss_probe.part.0 (STB_LOCAL)
ffffffff81ab44e0-ffffffff81ab4503: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b734e4)
Location: net/ipv4/tcp_output.c:2727
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81b6fe70-ffffffff81b7000f: tcp_schedule_loss_probe.part.0 (STB_LOCAL)
ffffffff81b71450-ffffffff81b71473: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d00980)
Location: net/ipv4/tcp_output.c:2728
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81d00980-ffffffff81d00b3e: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec5ac0)
Location: net/ipv4/tcp_output.c:2730
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ec5ac0-ffffffff81ec5c7e: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f24070)
Location: net/ipv4/tcp_output.c:2772
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81f24070-ffffffff81f2422e: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fe8880)
Location: net/ipv4/tcp_output.c:2829
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81fe8880-ffffffff81fe8a81: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c83818)
Location: net/ipv4/tcp_output.c:2491
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffff800010c83818-ffff800010c839b0: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d929ec)
Location: net/ipv4/tcp_output.c:2491
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
c0d929ec-c0d92bd4: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d8f0a0)
Location: net/ipv4/tcp_output.c:2491
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
c000000000d8f0a0-c000000000d8f2c4: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e5382)
Location: net/ipv4/tcp_output.c:2491
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffe0007e5382-ffffffe0007e54f4: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819709e0)
Location: net/ipv4/tcp_output.c:2491
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff819709e0-ffffffff81970b91: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192a4b0)
Location: net/ipv4/tcp_output.c:2491
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff8192a4b0-ffffffff8192a661: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819db1b0)
Location: net/ipv4/tcp_output.c:2491
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff819db1b0-ffffffff819db361: tcp_schedule_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool tcp_schedule_loss_probe(struct sock *sk, bool advancing_rto);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e4e30)
Location: net/ipv4/tcp_output.c:2491
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff819e4e30-ffffffff819e4fe4: tcp_schedule_loss_probe (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool advancing_rto</code>
</li>
</ul>
</details>
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
