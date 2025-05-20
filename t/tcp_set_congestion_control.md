# Function: <code>tcp_set_congestion_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81780c40)
Location: net/ipv4/tcp_cong.c:338
Inline: False
```
**Symbols:**

```
ffffffff81780c40-ffffffff81780cf6: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff817ee130)
Location: net/ipv4/tcp_cong.c:338
Inline: False
```
**Symbols:**

```
ffffffff817ee130-ffffffff817ee1e0: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8181eae0)
Location: net/ipv4/tcp_cong.c:341
Inline: False
```
**Symbols:**

```
ffffffff8181eae0-ffffffff8181ebda: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8183f2b0)
Location: net/ipv4/tcp_cong.c:341
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
ffffffff8183f2b0-ffffffff8183f402: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff818bea10)
Location: net/ipv4/tcp_cong.c:335
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
ffffffff818bea10-ffffffff818beb62: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81914600)
Location: net/ipv4/tcp_cong.c:335
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
ffffffff81914600-ffffffff8191474d: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81942db0)
Location: net/ipv4/tcp_cong.c:335
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
ffffffff81942db0-ffffffff81942efd: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819a7380)
Location: net/ipv4/tcp_cong.c:336
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
ffffffff819a7380-ffffffff819a74ba: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819de040)
Location: net/ipv4/tcp_cong.c:336
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
ffffffff819de040-ffffffff819de17a: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81acb3f0)
Location: net/ipv4/tcp_cong.c:342
Inline: False
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
```
**Symbols:**

```
ffffffff81acb3f0-ffffffff81acb584: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ad7300)
Location: net/ipv4/tcp_cong.c:348
Inline: False
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
```
**Symbols:**

```
ffffffff81ad7300-ffffffff81ad757b: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81ac23f0)
Location: net/ipv4/tcp_cong.c:352
Inline: False
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff81ac23f0-ffffffff81ac2665: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:352
Inline: False
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff81d3bc7a-ffffffff81d3bd0c: tcp_set_congestion_control.cold (STB_LOCAL)
ffffffff81b80160-ffffffff81b80418: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:362
Inline: False
Direct callers:
  - net/core/filter.c:_bpf_setsockopt
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff81f084b8-ffffffff81f08543: tcp_set_congestion_control.cold (STB_LOCAL)
ffffffff81d104d0-ffffffff81d10782: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:362
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff820aff59-ffffffff820affe4: tcp_set_congestion_control.cold (STB_LOCAL)
ffffffff81ed61f0-ffffffff81ed64a2: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:414
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff82131218-ffffffff82131295: tcp_set_congestion_control.cold (STB_LOCAL)
ffffffff81f35120-ffffffff81f353ba: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_cong.c (0)
Location: net/ipv4/tcp_cong.c:414
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff82212b79-ffffffff82212bf6: tcp_set_congestion_control.cold (STB_LOCAL)
ffffffff81ffb2a0-ffffffff81ffb53a: tcp_set_congestion_control (STB_GLOBAL)
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
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffff800010c91620)
Location: net/ipv4/tcp_cong.c:336
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
ffff800010c91620-ffff800010c91760: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (c0da0224)
Location: net/ipv4/tcp_cong.c:336
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
c0da0224-c0da0360: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (c000000000da1180)
Location: net/ipv4/tcp_cong.c:336
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
c000000000da1180-c000000000da1580: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffe0007f131e)
Location: net/ipv4/tcp_cong.c:336
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
ffffffe0007f131e-ffffffe0007f141c: tcp_set_congestion_control (STB_GLOBAL)
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
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8197deb0)
Location: net/ipv4/tcp_cong.c:336
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
ffffffff8197deb0-ffffffff8197dfea: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81937970)
Location: net/ipv4/tcp_cong.c:336
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
ffffffff81937970-ffffffff81937aaa: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819e8680)
Location: net/ipv4/tcp_cong.c:336
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
ffffffff819e8680-ffffffff819e87ba: tcp_set_congestion_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_set_congestion_control(struct sock *sk, const char *name, bool load, bool reinit, bool cap_net_admin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff819f23e0)
Location: net/ipv4/tcp_cong.c:336
Inline: False
Direct callers:
  - net/core/filter.c:bpf_setsockopt
```
**Symbols:**

```
ffffffff819f23e0-ffffffff819f2525: tcp_set_congestion_control (STB_GLOBAL)
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
<b>Param added. </b>
<code>bool load</code>
</li>
<li>
<b>Param added. </b>
<code>bool reinit</code>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool cap_net_admin</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>bool reinit</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, name, load, reinit, cap_net_admin</code> ➡️ <code>sk, name, load, cap_net_admin</code>
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
