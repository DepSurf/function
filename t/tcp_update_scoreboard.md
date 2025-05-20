# Function: <code>tcp_update_scoreboard</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_update_scoreboard(struct sock *sk, int fast_rexmit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176bca0)
Location: net/ipv4/tcp_input.c:2225
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_resume_early_retransmit
```
**Symbols:**

```
ffffffff8176bca0-ffffffff8176bd0a: tcp_update_scoreboard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_update_scoreboard(struct sock *sk, int fast_rexmit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817d81a0)
Location: net/ipv4/tcp_input.c:2240
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_resume_early_retransmit
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff817d81a0-ffffffff817d820a: tcp_update_scoreboard (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tcp_update_scoreboard(struct sock *sk, int fast_rexmit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81808140)
Location: net/ipv4/tcp_input.c:2294
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_resume_early_retransmit
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81808140-ffffffff818081aa: tcp_update_scoreboard (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff8182dbc2)
Location: net/ipv4/tcp_input.c:2259
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff818aca80)
Location: net/ipv4/tcp_input.c:2205
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff819021ef)
Location: net/ipv4/tcp_input.c:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff81930263)
Location: net/ipv4/tcp_input.c:2225
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff819937f0)
Location: net/ipv4/tcp_input.c:2245
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff819ca330)
Location: net/ipv4/tcp_input.c:2251
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff81ab73d1)
Location: net/ipv4/tcp_input.c:2236
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff81ac266c)
Location: net/ipv4/tcp_input.c:2340
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff81aad50c)
Location: net/ipv4/tcp_input.c:2340
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff81b69ffc)
Location: net/ipv4/tcp_input.c:2374
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff81cf9141)
Location: net/ipv4/tcp_input.c:2387
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff81ebdc30)
Location: net/ipv4/tcp_input.c:2387
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff81f1c0e0)
Location: net/ipv4/tcp_input.c:2386
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff81fe08ec)
Location: net/ipv4/tcp_input.c:2425
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffff800010c7d0fc)
Location: net/ipv4/tcp_input.c:2251
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (c0d8c168)
Location: net/ipv4/tcp_input.c:2251
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (c000000000d86fb0)
Location: net/ipv4/tcp_input.c:2251
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffe0007df8d6)
Location: net/ipv4/tcp_input.c:2251
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff8196a1a0)
Location: net/ipv4/tcp_input.c:2251
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff81923c90)
Location: net/ipv4/tcp_input.c:2251
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff819d4970)
Location: net/ipv4/tcp_input.c:2251
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
In net/ipv4/tcp_input.c (ffffffff819de550)
Location: net/ipv4/tcp_input.c:2251
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
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
</ul>
