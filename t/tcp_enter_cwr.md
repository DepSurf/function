# Function: <code>tcp_enter_cwr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8176b990)
Location: net/ipv4/tcp_input.c:2515
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
**Symbols:**

```
ffffffff8176b990-ffffffff8176ba3b: tcp_enter_cwr.part.29 (STB_LOCAL)
ffffffff8176ba40-ffffffff8176ba6a: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff817dd35a)
Location: net/ipv4/tcp_input.c:2515
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
**Symbols:**

```
ffffffff817d7e80-ffffffff817d7f2b: tcp_enter_cwr.part.32 (STB_LOCAL)
ffffffff817d7f30-ffffffff817d7f5a: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8180d4a9)
Location: net/ipv4/tcp_input.c:2569
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
**Symbols:**

```
ffffffff81807e20-ffffffff81807ecb: tcp_enter_cwr.part.30 (STB_LOCAL)
ffffffff81807ed0-ffffffff81807efa: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81827ad0)
Location: net/ipv4/tcp_input.c:2533
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
**Symbols:**

```
ffffffff81827ad0-ffffffff81827b92: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a70c0)
Location: net/ipv4/tcp_input.c:2478
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
**Symbols:**

```
ffffffff818a70c0-ffffffff818a718b: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81901f4d)
Location: net/ipv4/tcp_input.c:2505
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff818fcb10-ffffffff818fcbbb: tcp_enter_cwr.part.33 (STB_LOCAL)
ffffffff818fcbc0-ffffffff818fcbe9: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81930008)
Location: net/ipv4/tcp_input.c:2496
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff8192ac80-ffffffff8192ad2b: tcp_enter_cwr.part.39 (STB_LOCAL)
ffffffff8192ad30-ffffffff8192ad59: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819935e7)
Location: net/ipv4/tcp_input.c:2516
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff8198df50-ffffffff8198dffb: tcp_enter_cwr.part.0 (STB_LOCAL)
ffffffff8198e000-ffffffff8198e029: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819ca0d2)
Location: net/ipv4/tcp_input.c:2522
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff819c4b20-ffffffff819c4bcb: tcp_enter_cwr.part.0 (STB_LOCAL)
ffffffff819c4bd0-ffffffff819c4bf9: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab6f4c)
Location: net/ipv4/tcp_input.c:2507
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81ab1ab0-ffffffff81ab1b77: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac21fd)
Location: net/ipv4/tcp_input.c:2610
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81abca70-ffffffff81abcb37: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aad03f)
Location: net/ipv4/tcp_input.c:2610
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81aa7a40-ffffffff81aa7b06: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b69b2f)
Location: net/ipv4/tcp_input.c:2644
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81b63f50-ffffffff81b64016: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf8cdd)
Location: net/ipv4/tcp_input.c:2657
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81cf2ce0-ffffffff81cf2d97: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebd7e0)
Location: net/ipv4/tcp_input.c:2668
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81eb7300-ffffffff81eb73b7: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1bc8b)
Location: net/ipv4/tcp_input.c:2667
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81f15720-ffffffff81f157d7: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fe047c)
Location: net/ipv4/tcp_input.c:2706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81fd9da0-ffffffff81fd9e60: tcp_enter_cwr (STB_GLOBAL)
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
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7cde4)
Location: net/ipv4/tcp_input.c:2522
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffff800010c774a8-ffff800010c77538: tcp_enter_cwr.part.0 (STB_LOCAL)
ffff800010c77538-ffff800010c77578: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8bdfc)
Location: net/ipv4/tcp_input.c:2522
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
c0d85c84-c0d85d14: tcp_enter_cwr.part.0 (STB_LOCAL)
c0d85d14-c0d85d48: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d86bb8)
Location: net/ipv4/tcp_input.c:2522
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
c000000000d7f9c0-c000000000d7fa84: tcp_enter_cwr.part.0 (STB_LOCAL)
c000000000d7fa90-c000000000d7fabc: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007df614)
Location: net/ipv4/tcp_input.c:2522
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffe0007da630-ffffffe0007da6b2: tcp_enter_cwr.part.0 (STB_LOCAL)
ffffffe0007da6b2-ffffffe0007da6ee: tcp_enter_cwr (STB_GLOBAL)
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
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81969f42)
Location: net/ipv4/tcp_input.c:2522
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff81964990-ffffffff81964a3b: tcp_enter_cwr.part.0 (STB_LOCAL)
ffffffff81964a40-ffffffff81964a69: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81923a32)
Location: net/ipv4/tcp_input.c:2522
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff8191e480-ffffffff8191e52b: tcp_enter_cwr.part.0 (STB_LOCAL)
ffffffff8191e530-ffffffff8191e559: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d4712)
Location: net/ipv4/tcp_input.c:2522
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff819cf160-ffffffff819cf20b: tcp_enter_cwr.part.0 (STB_LOCAL)
ffffffff819cf210-ffffffff819cf239: tcp_enter_cwr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tcp_enter_cwr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819de2f2)
Location: net/ipv4/tcp_input.c:2522
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
**Symbols:**

```
ffffffff819d8cf0-ffffffff819d8d9b: tcp_enter_cwr.part.0 (STB_LOCAL)
ffffffff819d8da0-ffffffff819d8dc9: tcp_enter_cwr (STB_GLOBAL)
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
