# Function: <code>inet_sock_destruct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81794780)
Location: net/ipv4/af_inet.c:133
Inline: False
```
**Symbols:**

```
ffffffff81794780-ffffffff81794971: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81802100)
Location: net/ipv4/af_inet.c:133
Inline: False
```
**Symbols:**

```
ffffffff81802100-ffffffff81802312: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81833090)
Location: net/ipv4/af_inet.c:133
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff81833090-ffffffff818332a2: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818549d0)
Location: net/ipv4/af_inet.c:133
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff818549d0-ffffffff81854b63: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818d4870)
Location: net/ipv4/af_inet.c:133
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff818d4870-ffffffff818d4a03: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:134
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff8192b666-ffffffff8192b692: inet_sock_destruct.cold.26 (STB_LOCAL)
ffffffff8192aa30-ffffffff8192ab87: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:134
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff8195aaf6-ffffffff8195ab22: inet_sock_destruct.cold.31 (STB_LOCAL)
ffffffff81959f50-ffffffff8195a0a7: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:130
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff819bf746-ffffffff819bf7c0: inet_sock_destruct.cold (STB_LOCAL)
ffffffff819beb90-ffffffff819bed2b: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:130
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff819f6325-ffffffff819f6353: inet_sock_destruct.cold (STB_LOCAL)
ffffffff819f57c0-ffffffff819f596b: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:131
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81ae4805-ffffffff81ae4833: inet_sock_destruct.cold (STB_LOCAL)
ffffffff81ae3b00-ffffffff81ae3cbe: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:131
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81c32933-ffffffff81c32961: inet_sock_destruct.cold (STB_LOCAL)
ffffffff81af0a20-ffffffff81af0bde: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:131
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81c24c07-ffffffff81c24c35: inet_sock_destruct.cold (STB_LOCAL)
ffffffff81adc1d0-ffffffff81adc394: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:131
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81d3c45c-ffffffff81d3c48a: inet_sock_destruct.cold (STB_LOCAL)
ffffffff81b9b3f0-ffffffff81b9b5b4: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:132
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
**Symbols:**

```
ffffffff81f08d02-ffffffff81f08d2e: inet_sock_destruct.cold (STB_LOCAL)
ffffffff81d2d410-ffffffff81d2d5dd: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef5280)
Location: net/ipv4/af_inet.c:132
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv6/af_inet6.c:inet6_sock_destruct
```
**Symbols:**

```
ffffffff81ef5280-ffffffff81ef5488: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f54b60)
Location: net/ipv4/af_inet.c:133
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv6/af_inet6.c:inet6_sock_destruct
```
**Symbols:**

```
ffffffff81f54b60-ffffffff81f54d68: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8201add0)
Location: net/ipv4/af_inet.c:133
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv6/af_inet6.c:inet6_sock_destruct
```
**Symbols:**

```
ffffffff8201add0-ffffffff8201afd8: inet_sock_destruct (STB_GLOBAL)
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
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010cab5d0)
Location: net/ipv4/af_inet.c:130
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffff800010cab5d0-ffff800010cab774: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db8430)
Location: net/ipv4/af_inet.c:130
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
c0db8430-c0db8648: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dc1d50)
Location: net/ipv4/af_inet.c:130
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
c000000000dc1d50-c000000000dc1f88: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe000806290)
Location: net/ipv4/af_inet.c:130
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffe000806290-ffffffe0008063f8: inet_sock_destruct (STB_GLOBAL)
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
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:130
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff819960c5-ffffffff819960f3: inet_sock_destruct.cold (STB_LOCAL)
ffffffff81995560-ffffffff8199570b: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:130
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff8194fb85-ffffffff8194fbb3: inet_sock_destruct.cold (STB_LOCAL)
ffffffff8194f020-ffffffff8194f1cb: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:130
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff81a00965-ffffffff81a00993: inet_sock_destruct.cold (STB_LOCAL)
ffffffff819ffe00-ffffffff819fffab: inet_sock_destruct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void inet_sock_destruct(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:130
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff81a0ae45-ffffffff81a0ae73: inet_sock_destruct.cold (STB_LOCAL)
ffffffff81a09f30-ffffffff81a0a0db: inet_sock_destruct (STB_GLOBAL)
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
