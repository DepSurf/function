# Function: <code>tcp_disconnect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81767fd0)
Location: net/ipv4/tcp.c:2201
Inline: False
```
**Symbols:**

```
ffffffff81767fd0-ffffffff817683dc: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d4890)
Location: net/ipv4/tcp.c:2210
Inline: False
```
**Symbols:**

```
ffffffff817d4890-ffffffff817d4ccf: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818045d0)
Location: net/ipv4/tcp.c:2248
Inline: False
```
**Symbols:**

```
ffffffff818045d0-ffffffff818049e2: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818248a0)
Location: net/ipv4/tcp.c:2292
Inline: False
```
**Symbols:**

```
ffffffff818248a0-ffffffff81824d22: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a6760)
Location: net/ipv4/tcp.c:2366
Inline: False
```
**Symbols:**

```
ffffffff818a6760-ffffffff818a6b41: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818fb800)
Location: net/ipv4/tcp.c:2536
Inline: False
```
**Symbols:**

```
ffffffff818fb800-ffffffff818fbc46: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81929760)
Location: net/ipv4/tcp.c:2539
Inline: False
```
**Symbols:**

```
ffffffff81929760-ffffffff81929bcf: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2555
Inline: False
```
**Symbols:**

```
ffffffff8198d400-ffffffff8198d413: tcp_disconnect.cold (STB_LOCAL)
ffffffff8198c820-ffffffff8198cde7: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c3190)
Location: net/ipv4/tcp.c:2558
Inline: False
```
**Symbols:**

```
ffffffff819c3190-ffffffff819c3786: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aae850)
Location: net/ipv4/tcp.c:2630
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_shutdown
```
**Symbols:**

```
ffffffff81aae850-ffffffff81aaeeef: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab8a90)
Location: net/ipv4/tcp.c:2883
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
```
**Symbols:**

```
ffffffff81ab8a90-ffffffff81ab914d: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa3d40)
Location: net/ipv4/tcp.c:2937
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
```
**Symbols:**

```
ffffffff81aa3d40-ffffffff81aa4400: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2962
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
```
**Symbols:**

```
ffffffff81d3a622-ffffffff81d3a675: tcp_disconnect.cold (STB_LOCAL)
ffffffff81b5fef0-ffffffff81b605d2: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2985
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff81f06e49-ffffffff81f06eaf: tcp_disconnect.cold (STB_LOCAL)
ffffffff81cee910-ffffffff81ceef63: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:3081
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff820ae962-ffffffff820ae9a8: tcp_disconnect.cold (STB_LOCAL)
ffffffff81eb1b80-ffffffff81eb2182: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2967
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff8212fe0d-ffffffff8212fe4d: tcp_disconnect.cold (STB_LOCAL)
ffffffff81f10220-ffffffff81f10835: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2979
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff82211af9-ffffffff82211b39: tcp_disconnect.cold (STB_LOCAL)
ffffffff81fd4420-ffffffff81fd4a13: tcp_disconnect (STB_GLOBAL)
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
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c75ef8)
Location: net/ipv4/tcp.c:2558
Inline: False
```
**Symbols:**

```
ffff800010c75ef8-ffff800010c76308: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d845b0)
Location: net/ipv4/tcp.c:2558
Inline: False
```
**Symbols:**

```
c0d845b0-c0d84a64: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7d8c0)
Location: net/ipv4/tcp.c:2558
Inline: False
```
**Symbols:**

```
c000000000d7d8c0-c000000000d7de10: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d90ea)
Location: net/ipv4/tcp.c:2558
Inline: False
```
**Symbols:**

```
ffffffe0007d90ea-ffffffe0007d94bc: tcp_disconnect (STB_GLOBAL)
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
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81963000)
Location: net/ipv4/tcp.c:2558
Inline: False
```
**Symbols:**

```
ffffffff81963000-ffffffff819635f6: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8191caf0)
Location: net/ipv4/tcp.c:2558
Inline: False
```
**Symbols:**

```
ffffffff8191caf0-ffffffff8191d0e6: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819cd7d0)
Location: net/ipv4/tcp.c:2558
Inline: False
```
**Symbols:**

```
ffffffff819cd7d0-ffffffff819cddc6: tcp_disconnect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_disconnect(struct sock *sk, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d7360)
Location: net/ipv4/tcp.c:2558
Inline: False
```
**Symbols:**

```
ffffffff819d7360-ffffffff819d7956: tcp_disconnect (STB_GLOBAL)
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
