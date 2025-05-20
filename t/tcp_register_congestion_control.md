# Function: <code>tcp_register_congestion_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81780450)
Location: net/ipv4/tcp_cong.c:67
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff81780450-ffffffff8178060d: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff817ed930)
Location: net/ipv4/tcp_cong.c:67
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff817ed930-ffffffff817edae0: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8181e270)
Location: net/ipv4/tcp_cong.c:67
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff8181e270-ffffffff8181e455: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8183e9c0)
Location: net/ipv4/tcp_cong.c:67
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff8183e9c0-ffffffff8183eba5: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff818be210)
Location: net/ipv4/tcp_cong.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff818be210-ffffffff818be3f5: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff8191474d-ffffffff81914783: tcp_register_congestion_control.cold.8 (STB_LOCAL)
ffffffff81913e30-ffffffff81913fe8: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff81942efd-ffffffff81942f33: tcp_register_congestion_control.cold.9 (STB_LOCAL)
ffffffff81942590-ffffffff81942748: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff819a74ba-ffffffff819a74f2: tcp_register_congestion_control.cold (STB_LOCAL)
ffffffff819a6b80-ffffffff819a6d3b: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff819de17a-ffffffff819de1b2: tcp_register_congestion_control.cold (STB_LOCAL)
ffffffff819dd850-ffffffff819dda0b: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_reg
```
**Symbols:**

```
ffffffff81acb584-ffffffff81acb5bc: tcp_register_congestion_control.cold (STB_LOCAL)
ffffffff81aca9f0-ffffffff81acaae3: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_reg
```
**Symbols:**

```
ffffffff81c32757-ffffffff81c327a7: tcp_register_congestion_control.cold (STB_LOCAL)
ffffffff81ad6970-ffffffff81ad6a7d: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_reg
```
**Symbols:**

```
ffffffff81c24a2c-ffffffff81c24a79: tcp_register_congestion_control.cold (STB_LOCAL)
ffffffff81ac19e0-ffffffff81ac1b02: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_reg
```
**Symbols:**

```
ffffffff81d3bb2d-ffffffff81d3bb7a: tcp_register_congestion_control.cold (STB_LOCAL)
ffffffff81b7f710-ffffffff81b7f82f: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:82
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_reg
```
**Symbols:**

```
ffffffff81f0836d-ffffffff81f083b8: tcp_register_congestion_control.cold (STB_LOCAL)
ffffffff81d0f930-ffffffff81d0fa4e: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ed5520)
Location: net/ipv4/tcp_cong.c:82
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_reg
```
**Symbols:**

```
ffffffff81ed5520-ffffffff81ed567b: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81f341d0)
Location: net/ipv4/tcp_cong.c:93
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_reg
```
**Symbols:**

```
ffffffff81f341d0-ffffffff81f342e6: tcp_register_congestion_control.part.0 (STB_LOCAL)
ffffffff81f34300-ffffffff81f34352: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ffa350)
Location: net/ipv4/tcp_cong.c:93
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_reg
```
**Symbols:**

```
ffffffff81ffa350-ffffffff81ffa466: tcp_register_congestion_control.part.0 (STB_LOCAL)
ffffffff81ffa480-ffffffff81ffa4d2: tcp_register_congestion_control (STB_GLOBAL)
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
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffff800010c90c18)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffff800010c90c18-ffff800010c90e50: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (c0d9f9ac)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
c0d9f9ac-c0d9fbb4: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (c000000000da0200)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
c000000000da0200-c000000000da04bc: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffe0007f0a88)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffe0007f0a88-ffffffe0007f0d28: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff8197dfea-ffffffff8197e022: tcp_register_congestion_control.cold (STB_LOCAL)
ffffffff8197d6c0-ffffffff8197d87b: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff81937aaa-ffffffff81937ae2: tcp_register_congestion_control.cold (STB_LOCAL)
ffffffff81937180-ffffffff8193733b: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff819e87ba-ffffffff819e87f2: tcp_register_congestion_control.cold (STB_LOCAL)
ffffffff819e7e90-ffffffff819e804b: tcp_register_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tcp_register_congestion_control(struct tcp_congestion_ops *ca);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp_cubic.c:cubictcp_register
```
**Symbols:**

```
ffffffff819f2525-ffffffff819f255d: tcp_register_congestion_control.cold (STB_LOCAL)
ffffffff819f1c00-ffffffff819f1db9: tcp_register_congestion_control (STB_GLOBAL)
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
