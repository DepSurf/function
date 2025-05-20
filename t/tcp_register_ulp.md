# Function: <code>tcp_register_ulp</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81841e10)
Location: net/ipv4/tcp_ulp.c:57
Inline: False
```
**Symbols:**

```
ffffffff81841e10-ffffffff81841eb0: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff818c16e0)
Location: net/ipv4/tcp_ulp.c:57
Inline: False
```
**Symbols:**

```
ffffffff818c16e0-ffffffff818c1780: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff819172f0)
Location: net/ipv4/tcp_ulp.c:81
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:bpf_tcp_ulp_register
```
**Symbols:**

```
ffffffff819172f0-ffffffff8191737f: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81945b00)
Location: net/ipv4/tcp_ulp.c:57
Inline: False
```
**Symbols:**

```
ffffffff81945b00-ffffffff81945b8f: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff819aa100)
Location: net/ipv4/tcp_ulp.c:58
Inline: False
```
**Symbols:**

```
ffffffff819aa100-ffffffff819aa194: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff819e0dc0)
Location: net/ipv4/tcp_ulp.c:58
Inline: False
```
**Symbols:**

```
ffffffff819e0dc0-ffffffff819e0e54: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81ace400)
Location: net/ipv4/tcp_ulp.c:59
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff81ace400-ffffffff81ace494: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81ada410)
Location: net/ipv4/tcp_ulp.c:59
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff81ada410-ffffffff81ada4a4: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81ac5420)
Location: net/ipv4/tcp_ulp.c:59
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff81ac5420-ffffffff81ac54b4: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81b83c30)
Location: net/ipv4/tcp_ulp.c:59
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff81b83c30-ffffffff81b83cc4: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81d143e0)
Location: net/ipv4/tcp_ulp.c:59
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff81d143e0-ffffffff81d14477: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81eda480)
Location: net/ipv4/tcp_ulp.c:59
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff81eda480-ffffffff81eda517: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81f39560)
Location: net/ipv4/tcp_ulp.c:59
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff81f39560-ffffffff81f395f7: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81fff650)
Location: net/ipv4/tcp_ulp.c:59
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init
  - net/mptcp/subflow.c:mptcp_subflow_init
```
**Symbols:**

```
ffffffff81fff650-ffffffff81fff6e7: tcp_register_ulp (STB_GLOBAL)
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
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffff800010c94c68)
Location: net/ipv4/tcp_ulp.c:58
Inline: False
```
**Symbols:**

```
ffff800010c94c68-ffff800010c94d50: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (c0da34ec)
Location: net/ipv4/tcp_ulp.c:58
Inline: False
```
**Symbols:**

```
c0da34ec-c0da359c: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (c000000000da5680)
Location: net/ipv4/tcp_ulp.c:58
Inline: False
```
**Symbols:**

```
c000000000da5680-c000000000da5960: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffe0007f3fc4)
Location: net/ipv4/tcp_ulp.c:58
Inline: False
```
**Symbols:**

```
ffffffe0007f3fc4-ffffffe0007f4090: tcp_register_ulp (STB_GLOBAL)
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
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81980c30)
Location: net/ipv4/tcp_ulp.c:58
Inline: False
```
**Symbols:**

```
ffffffff81980c30-ffffffff81980cc4: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff8193a6f0)
Location: net/ipv4/tcp_ulp.c:58
Inline: False
```
**Symbols:**

```
ffffffff8193a6f0-ffffffff8193a784: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff819eb400)
Location: net/ipv4/tcp_ulp.c:58
Inline: False
```
**Symbols:**

```
ffffffff819eb400-ffffffff819eb494: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_register_ulp(struct tcp_ulp_ops *ulp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff819f5280)
Location: net/ipv4/tcp_ulp.c:58
Inline: False
```
**Symbols:**

```
ffffffff819f5280-ffffffff819f5312: tcp_register_ulp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
