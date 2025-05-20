# Function: <code>tcp_enter_recovery</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176b350)
Location: net/ipv4/tcp_input.c:2641
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_resume_early_retransmit
```
**Symbols:**

```
ffffffff8176b350-ffffffff8176b47b: tcp_enter_recovery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817d8870)
Location: net/ipv4/tcp_input.c:2639
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_resume_early_retransmit
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff817d8870-ffffffff817d899f: tcp_enter_recovery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81808c90)
Location: net/ipv4/tcp_input.c:2693
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_resume_early_retransmit
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81808c90-ffffffff81808dbf: tcp_enter_recovery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182d5f0)
Location: net/ipv4/tcp_input.c:2657
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff8182d5f0-ffffffff8182d716: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818ac490)
Location: net/ipv4/tcp_input.c:2599
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff818ac490-ffffffff818ac5c2: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81901a50)
Location: net/ipv4/tcp_input.c:2626
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81901a50-ffffffff81901b86: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192fb30)
Location: net/ipv4/tcp_input.c:2617
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff8192fb30-ffffffff8192fc63: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81993090)
Location: net/ipv4/tcp_input.c:2637
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81993090-ffffffff819931c3: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c9be0)
Location: net/ipv4/tcp_input.c:2643
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff819c9be0-ffffffff819c9d13: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab6a20)
Location: net/ipv4/tcp_input.c:2628
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81ab6a20-ffffffff81ab6b4f: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac1cc0)
Location: net/ipv4/tcp_input.c:2740
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81ac1cc0-ffffffff81ac1def: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aacdb0)
Location: net/ipv4/tcp_input.c:2740
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81aacdb0-ffffffff81aacede: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b698a0)
Location: net/ipv4/tcp_input.c:2774
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81b698a0-ffffffff81b699ce: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf8a80)
Location: net/ipv4/tcp_input.c:2790
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81cf8a80-ffffffff81cf8b9b: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebd570)
Location: net/ipv4/tcp_input.c:2801
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81ebd570-ffffffff81ebd68b: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1b9f0)
Location: net/ipv4/tcp_input.c:2800
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81f1b9f0-ffffffff81f1bb3f: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fe01d0)
Location: net/ipv4/tcp_input.c:2839
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81fe01d0-ffffffff81fe032b: tcp_enter_recovery (STB_GLOBAL)
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
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7cb40)
Location: net/ipv4/tcp_input.c:2643
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffff800010c7cb40-ffff800010c7cc58: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8baf4)
Location: net/ipv4/tcp_input.c:2643
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
c0d8baf4-c0d8bc14: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d867d0)
Location: net/ipv4/tcp_input.c:2643
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
c000000000d867d0-c000000000d86968: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007df362)
Location: net/ipv4/tcp_input.c:2643
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffe0007df362-ffffffe0007df486: tcp_enter_recovery (STB_GLOBAL)
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
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81969a50)
Location: net/ipv4/tcp_input.c:2643
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81969a50-ffffffff81969b83: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81923540)
Location: net/ipv4/tcp_input.c:2643
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff81923540-ffffffff81923673: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d4220)
Location: net/ipv4/tcp_input.c:2643
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff819d4220-ffffffff819d4353: tcp_enter_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock *sk, bool ece_ack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dde00)
Location: net/ipv4/tcp_input.c:2643
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
**Symbols:**

```
ffffffff819dde00-ffffffff819ddf33: tcp_enter_recovery (STB_GLOBAL)
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
