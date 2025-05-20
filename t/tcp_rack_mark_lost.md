# Function: <code>tcp_rack_mark_lost</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81782ec0)
Location: net/ipv4/tcp_recovery.c:22
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81782ec0-ffffffff8178304c: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff817f0450)
Location: net/ipv4/tcp_recovery.c:22
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff817f0450-ffffffff817f05dc: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff818211c0)
Location: net/ipv4/tcp_recovery.c:22
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff818211c0-ffffffff8182134c: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81841be0)
Location: net/ipv4/tcp_recovery.c:104
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81841be0-ffffffff81841cbb: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff818c1420)
Location: net/ipv4/tcp_recovery.c:93
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff818c1420-ffffffff818c14fb: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81916fb0)
Location: net/ipv4/tcp_recovery.c:112
Inline: False
```
**Symbols:**

```
ffffffff81916fb0-ffffffff8191708b: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819457c0)
Location: net/ipv4/tcp_recovery.c:113
Inline: False
```
**Symbols:**

```
ffffffff819457c0-ffffffff8194589b: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819a9dc0)
Location: net/ipv4/tcp_recovery.c:113
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_identify_packet_loss
```
**Symbols:**

```
ffffffff819a9dc0-ffffffff819a9ea0: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819e0a80)
Location: net/ipv4/tcp_recovery.c:113
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_identify_packet_loss
```
**Symbols:**

```
ffffffff819e0a80-ffffffff819e0b60: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ace070)
Location: net/ipv4/tcp_recovery.c:113
Inline: False
```
**Symbols:**

```
ffffffff81ace070-ffffffff81ace150: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ada060)
Location: net/ipv4/tcp_recovery.c:99
Inline: False
```
**Symbols:**

```
ffffffff81ada060-ffffffff81ada14f: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ac50b0)
Location: net/ipv4/tcp_recovery.c:99
Inline: False
```
**Symbols:**

```
ffffffff81ac50b0-ffffffff81ac51a5: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81b838c0)
Location: net/ipv4/tcp_recovery.c:99
Inline: False
```
**Symbols:**

```
ffffffff81b838c0-ffffffff81b839b2: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81d13fb0)
Location: net/ipv4/tcp_recovery.c:95
Inline: False
```
**Symbols:**

```
ffffffff81d13fb0-ffffffff81d140b0: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81ed9ff0)
Location: net/ipv4/tcp_recovery.c:95
Inline: False
```
**Symbols:**

```
ffffffff81ed9ff0-ffffffff81eda0f0: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81f390d0)
Location: net/ipv4/tcp_recovery.c:95
Inline: False
```
**Symbols:**

```
ffffffff81f390d0-ffffffff81f391d0: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff81fff1b0)
Location: net/ipv4/tcp_recovery.c:95
Inline: False
```
**Symbols:**

```
ffffffff81fff1b0-ffffffff81fff2b4: tcp_rack_mark_lost (STB_GLOBAL)
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
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffff800010c94880)
Location: net/ipv4/tcp_recovery.c:113
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_identify_packet_loss
```
**Symbols:**

```
ffff800010c94880-ffff800010c94970: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (c0da3110)
Location: net/ipv4/tcp_recovery.c:113
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_identify_packet_loss
```
**Symbols:**

```
c0da3110-c0da3214: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (c000000000da50a0)
Location: net/ipv4/tcp_recovery.c:113
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_identify_packet_loss
```
**Symbols:**

```
c000000000da50a0-c000000000da51e8: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffe0007f3c60)
Location: net/ipv4/tcp_recovery.c:113
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_identify_packet_loss
```
**Symbols:**

```
ffffffe0007f3c60-ffffffe0007f3d28: tcp_rack_mark_lost (STB_GLOBAL)
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
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819808f0)
Location: net/ipv4/tcp_recovery.c:113
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_identify_packet_loss
```
**Symbols:**

```
ffffffff819808f0-ffffffff819809d0: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff8193a3b0)
Location: net/ipv4/tcp_recovery.c:113
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_identify_packet_loss
```
**Symbols:**

```
ffffffff8193a3b0-ffffffff8193a490: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819eb0c0)
Location: net/ipv4/tcp_recovery.c:113
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_identify_packet_loss
```
**Symbols:**

```
ffffffff819eb0c0-ffffffff819eb1a0: tcp_rack_mark_lost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_rack_mark_lost(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_recovery.c (ffffffff819f4f40)
Location: net/ipv4/tcp_recovery.c:113
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_identify_packet_loss
```
**Symbols:**

```
ffffffff819f4f40-ffffffff819f5020: tcp_rack_mark_lost (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
