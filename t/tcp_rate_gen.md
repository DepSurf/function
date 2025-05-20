# Function: <code>tcp_rate_gen</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, struct skb_mstamp *now, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81820fc0)
Location: net/ipv4/tcp_rate.c:108
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81820fc0-ffffffff81821147: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81841900)
Location: net/ipv4/tcp_rate.c:108
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81841900-ffffffff81841a47: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff818c1120)
Location: net/ipv4/tcp_rate.c:108
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff818c1120-ffffffff818c1268: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81916c70)
Location: net/ipv4/tcp_rate.c:108
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81916c70-ffffffff81916db7: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81945440)
Location: net/ipv4/tcp_rate.c:109
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81945440-ffffffff8194559e: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819a9a40)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819a9a40-ffffffff819a9b99: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819e0700)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819e0700-ffffffff819e0859: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81acdcd0)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81acdcd0-ffffffff81acde2d: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81ad9d30)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ad9d30-ffffffff81ad9e8d: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81ac4d80)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81ac4d80-ffffffff81ac4ed7: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_rate.c (0)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81d3be94-ffffffff81d3bed5: tcp_rate_gen.cold (STB_LOCAL)
ffffffff81b83530-ffffffff81b836e3: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_rate.c (0)
Location: net/ipv4/tcp_rate.c:117
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81f086b1-ffffffff81f086f2: tcp_rate_gen.cold (STB_LOCAL)
ffffffff81d13bb0-ffffffff81d13da2: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_rate.c (0)
Location: net/ipv4/tcp_rate.c:117
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff820b0192-ffffffff820b01d3: tcp_rate_gen.cold (STB_LOCAL)
ffffffff81ed9bc0-ffffffff81ed9db2: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_rate.c (0)
Location: net/ipv4/tcp_rate.c:117
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8213141e-ffffffff8213145f: tcp_rate_gen.cold (STB_LOCAL)
ffffffff81f38ca0-ffffffff81f38e92: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_rate.c (0)
Location: net/ipv4/tcp_rate.c:117
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff82212d62-ffffffff82212da3: tcp_rate_gen.cold (STB_LOCAL)
ffffffff81ffed80-ffffffff81ffef72: tcp_rate_gen (STB_GLOBAL)
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
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffff800010c94478)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffff800010c94478-ffff800010c945e0: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (c0da2c78)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c0da2c78-c0da2e14: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (c000000000da4ba0)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
c000000000da4ba0-c000000000da4d4c: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffe0007f3904)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffe0007f3904-ffffffe0007f3a32: tcp_rate_gen (STB_GLOBAL)
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
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff81980570)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff81980570-ffffffff819806c9: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff8193a030)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff8193a030-ffffffff8193a189: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819ead40)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819ead40-ffffffff819eae99: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_rate_gen(struct sock *sk, u32 delivered, u32 lost, bool is_sack_reneg, struct rate_sample *rs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_rate.c (ffffffff819f4bc0)
Location: net/ipv4/tcp_rate.c:110
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_ack
```
**Symbols:**

```
ffffffff819f4bc0-ffffffff819f4d19: tcp_rate_gen (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct skb_mstamp *now</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, delivered, lost, now, rs</code> ➡️ <code>sk, delivered, lost, rs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_sack_reneg</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, delivered, lost, rs</code> ➡️ <code>sk, delivered, lost, is_sack_reneg, rs</code>
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
