# Function: <code>tcp_send_loss_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817789a0)
Location: net/ipv4/tcp_output.c:2224
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff817789a0-ffffffff81778b99: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e5ae0)
Location: net/ipv4/tcp_output.c:2242
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff817e5ae0-ffffffff817e5cde: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81815f60)
Location: net/ipv4/tcp_output.c:2362
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81815f60-ffffffff8181615e: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81836320)
Location: net/ipv4/tcp_output.c:2439
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81836320-ffffffff818364f9: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b5980)
Location: net/ipv4/tcp_output.c:2495
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff818b5980-ffffffff818b5b50: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8190b110)
Location: net/ipv4/tcp_output.c:2476
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff8190b110-ffffffff8190b2e0: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819393a0)
Location: net/ipv4/tcp_output.c:2504
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff819393a0-ffffffff81939584: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2531
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff8199ec10-ffffffff8199ec36: tcp_send_loss_probe.cold (STB_LOCAL)
ffffffff8199d680-ffffffff8199d873: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d4150)
Location: net/ipv4/tcp_output.c:2558
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff819d4150-ffffffff819d4347: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac09c0)
Location: net/ipv4/tcp_output.c:2620
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81ac09c0-ffffffff81ac0bd0: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acc430)
Location: net/ipv4/tcp_output.c:2792
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81acc430-ffffffff81acc640: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab7620)
Location: net/ipv4/tcp_output.c:2797
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81ab7620-ffffffff81ab77fa: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2797
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81d3b395-ffffffff81d3b3aa: tcp_send_loss_probe.cold (STB_LOCAL)
ffffffff81b74820-ffffffff81b74a11: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2798
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81f07c7c-ffffffff81f07c91: tcp_send_loss_probe.cold (STB_LOCAL)
ffffffff81d03f80-ffffffff81d04174: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2800
Inline: False
```
**Symbols:**

```
ffffffff820af6e4-ffffffff820af6f9: tcp_send_loss_probe.cold (STB_LOCAL)
ffffffff81ec8ed0-ffffffff81ec90c4: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2842
Inline: False
```
**Symbols:**

```
ffffffff82130aad-ffffffff82130ac2: tcp_send_loss_probe.cold (STB_LOCAL)
ffffffff81f279f0-ffffffff81f27be4: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2900
Inline: False
```
**Symbols:**

```
ffffffff82212281-ffffffff82212296: tcp_send_loss_probe.cold (STB_LOCAL)
ffffffff81fec480-ffffffff81fec674: tcp_send_loss_probe (STB_GLOBAL)
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
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c86c40)
Location: net/ipv4/tcp_output.c:2558
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffff800010c86c40-ffff800010c86e24: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d9600c)
Location: net/ipv4/tcp_output.c:2558
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
c0d9600c-c0d9623c: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d93400)
Location: net/ipv4/tcp_output.c:2558
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
c000000000d93400-c000000000d936bc: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e81a2)
Location: net/ipv4/tcp_output.c:2558
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffe0007e81a2-ffffffe0007e8342: tcp_send_loss_probe (STB_GLOBAL)
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
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81973fc0)
Location: net/ipv4/tcp_output.c:2558
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff81973fc0-ffffffff819741b7: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192da90)
Location: net/ipv4/tcp_output.c:2558
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff8192da90-ffffffff8192dc87: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819de790)
Location: net/ipv4/tcp_output.c:2558
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff819de790-ffffffff819de987: tcp_send_loss_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_send_loss_probe(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e8430)
Location: net/ipv4/tcp_output.c:2558
Inline: False
Direct callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
**Symbols:**

```
ffffffff819e8430-ffffffff819e8627: tcp_send_loss_probe (STB_GLOBAL)
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
