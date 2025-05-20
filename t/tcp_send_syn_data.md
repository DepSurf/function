# Function: <code>tcp_send_syn_data</code>

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
In net/ipv4/tcp_output.c (ffffffff81777c72)
Location: net/ipv4/tcp_output.c:3149
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff817e4c96)
Location: net/ipv4/tcp_output.c:3201
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff818150e6)
Location: net/ipv4/tcp_output.c:3325
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff818353fc)
Location: net/ipv4/tcp_output.c:3351
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff818b48f2)
Location: net/ipv4/tcp_output.c:3404
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff81909f2f)
Location: net/ipv4/tcp_output.c:3386
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
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
In net/ipv4/tcp_output.c (ffffffff819381e0)
Location: net/ipv4/tcp_output.c:3418
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199afb0)
Location: net/ipv4/tcp_output.c:3452
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff8199afb0-ffffffff8199b3ca: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d19d0)
Location: net/ipv4/tcp_output.c:3484
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff819d19d0-ffffffff819d1df0: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abe930)
Location: net/ipv4/tcp_output.c:3557
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81abe930-ffffffff81abed2d: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81aca290)
Location: net/ipv4/tcp_output.c:3737
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81aca290-ffffffff81aca694: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab5110)
Location: net/ipv4/tcp_output.c:3734
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81ab5110-ffffffff81ab551c: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b72100)
Location: net/ipv4/tcp_output.c:3735
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81b72100-ffffffff81b72514: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d017f0)
Location: net/ipv4/tcp_output.c:3742
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81d017f0-ffffffff81d01c07: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec6960)
Location: net/ipv4/tcp_output.c:3744
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81ec6960-ffffffff81ec6d77: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3826
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81f250f0-ffffffff81f2563d: tcp_send_syn_data (STB_LOCAL)
ffffffff82130995-ffffffff821309aa: tcp_send_syn_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:3925
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81fe99d0-ffffffff81fe9efd: tcp_send_syn_data (STB_LOCAL)
ffffffff82212169-ffffffff8221217e: tcp_send_syn_data.cold (STB_LOCAL)
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
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c845c8)
Location: net/ipv4/tcp_output.c:3484
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffff800010c845c8-ffff800010c849d8: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d938a4)
Location: net/ipv4/tcp_output.c:3484
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
c0d938a4-c0d93c80: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d90280)
Location: net/ipv4/tcp_output.c:3484
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
c000000000d90280-c000000000d90838: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e6022)
Location: net/ipv4/tcp_output.c:3484
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffe0007e6022-ffffffe0007e63ca: tcp_send_syn_data (STB_LOCAL)
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
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81971840)
Location: net/ipv4/tcp_output.c:3484
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff81971840-ffffffff81971c60: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192b310)
Location: net/ipv4/tcp_output.c:3484
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff8192b310-ffffffff8192b730: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819dc010)
Location: net/ipv4/tcp_output.c:3484
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff819dc010-ffffffff819dc430: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_send_syn_data(struct sock *sk, struct sk_buff *syn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e5c90)
Location: net/ipv4/tcp_output.c:3484
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
**Symbols:**

```
ffffffff819e5c90-ffffffff819e60b0: tcp_send_syn_data (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
