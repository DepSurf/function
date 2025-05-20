# Function: <code>tcp_identify_packet_loss</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fd670)
Location: net/ipv4/tcp_input.c:2736
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff818fd670-ffffffff818fd6dc: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192b770)
Location: net/ipv4/tcp_input.c:2727
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff8192b770-ffffffff8192b7dc: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198ea00)
Location: net/ipv4/tcp_input.c:2747
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff8198ea00-ffffffff8198ea6c: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c5970)
Location: net/ipv4/tcp_input.c:2753
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff819c5970-ffffffff819c59dc: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab0850)
Location: net/ipv4/tcp_input.c:2738
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81ab0850-ffffffff81ab08c0: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abb890)
Location: net/ipv4/tcp_input.c:2850
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81abb890-ffffffff81abb90a: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa6850)
Location: net/ipv4/tcp_input.c:2861
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81aa6850-ffffffff81aa68ca: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b62c40)
Location: net/ipv4/tcp_input.c:2895
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81b62c40-ffffffff81b62cba: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf19b0)
Location: net/ipv4/tcp_input.c:2911
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81cf19b0-ffffffff81cf1a4d: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb61e0)
Location: net/ipv4/tcp_input.c:2922
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81eb61e0-ffffffff81eb627d: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f14600)
Location: net/ipv4/tcp_input.c:2921
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81f14600-ffffffff81f1469d: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd8ae0)
Location: net/ipv4/tcp_input.c:2968
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff81fd8ae0-ffffffff81fd8b7d: tcp_identify_packet_loss (STB_LOCAL)
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
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c77aa0)
Location: net/ipv4/tcp_input.c:2753
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffff800010c77aa0-ffff800010c77b34: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d86810)
Location: net/ipv4/tcp_input.c:2753
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
c0d86810-c0d86884: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d80d30)
Location: net/ipv4/tcp_input.c:2753
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
c000000000d80d30-c000000000d80e04: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007db442)
Location: net/ipv4/tcp_input.c:2753
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffe0007db442-ffffffe0007db4c0: tcp_identify_packet_loss (STB_LOCAL)
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
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819657e0)
Location: net/ipv4/tcp_input.c:2753
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff819657e0-ffffffff8196584c: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191f2d0)
Location: net/ipv4/tcp_input.c:2753
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff8191f2d0-ffffffff8191f33c: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cffb0)
Location: net/ipv4/tcp_input.c:2753
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff819cffb0-ffffffff819d001c: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_identify_packet_loss(struct sock *sk, int *ack_flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d9b40)
Location: net/ipv4/tcp_input.c:2753
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
```
**Symbols:**

```
ffffffff819d9b40-ffffffff819d9bac: tcp_identify_packet_loss (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
