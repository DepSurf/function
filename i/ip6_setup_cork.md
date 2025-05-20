# Function: <code>ip6_setup_cork</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, int hlimit, int tclass, struct ipv6_txoptions *opt, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff817c55e0)
Location: net/ipv6/ip6_output.c:1185
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_make_skb
```
**Symbols:**

```
ffffffff817c55e0-ffffffff817c58f1: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff818326f0)
Location: net/ipv6/ip6_output.c:1187
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff818326f0-ffffffff81832a02: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81864170)
Location: net/ipv6/ip6_output.c:1214
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81864170-ffffffff8186448a: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81889750)
Location: net/ipv6/ip6_output.c:1212
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81889750-ffffffff81889a8b: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81909d30)
Location: net/ipv6/ip6_output.c:1168
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81909d30-ffffffff8190a0ce: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819610a0)
Location: net/ipv6/ip6_output.c:1159
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff819610a0-ffffffff81961497: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81995950)
Location: net/ipv6/ip6_output.c:1168
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81995950-ffffffff81995d8f: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1232
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81a01670-ffffffff81a01aa9: ip6_setup_cork (STB_LOCAL)
ffffffff81a04d80-ffffffff81a04db2: ip6_setup_cork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a38230)
Location: net/ipv6/ip6_output.c:1235
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81a38230-ffffffff81a3866d: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2e0c0)
Location: net/ipv6/ip6_output.c:1305
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81b2e0c0-ffffffff81b2e51c: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3cb10)
Location: net/ipv6/ip6_output.c:1344
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81b3cb10-ffffffff81b3cf6c: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b29f80)
Location: net/ipv6/ip6_output.c:1375
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81b29f80-ffffffff81b2a400: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1354
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81befb50-ffffffff81bf0023: ip6_setup_cork (STB_LOCAL)
ffffffff81d3f32e-ffffffff81d3f356: ip6_setup_cork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1375
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81d87cb0-ffffffff81d8812c: ip6_setup_cork (STB_LOCAL)
ffffffff81f0bc64-ffffffff81f0bc84: ip6_setup_cork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1393
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81f55a50-ffffffff81f55eca: ip6_setup_cork (STB_LOCAL)
ffffffff820b3464-ffffffff820b3484: ip6_setup_cork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1394
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81fb5430-ffffffff81fb589a: ip6_setup_cork (STB_LOCAL)
ffffffff821345f6-ffffffff8213460f: ip6_setup_cork.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1335
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff82082b10-ffffffff82082f67: ip6_setup_cork (STB_LOCAL)
ffffffff822161b4-ffffffff822161cd: ip6_setup_cork.cold (STB_LOCAL)
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
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cf8888)
Location: net/ipv6/ip6_output.c:1235
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffff800010cf8888-ffff800010cf8be4: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0dfff78)
Location: net/ipv6/ip6_output.c:1235
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
c0dfff78-c0e002f4: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e219f0)
Location: net/ipv6/ip6_output.c:1235
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
c000000000e219f0-c000000000e21df8: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe0008445cc)
Location: net/ipv6/ip6_output.c:1235
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffe0008445cc-ffffffe0008448cc: ip6_setup_cork (STB_LOCAL)
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
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819d78c0)
Location: net/ipv6/ip6_output.c:1235
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff819d78c0-ffffffff819d7cfd: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81994680)
Location: net/ipv6/ip6_output.c:1235
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81994680-ffffffff81994abd: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a42340)
Location: net/ipv6/ip6_output.c:1235
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81a42340-ffffffff81a4277d: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_setup_cork(struct sock *sk, struct inet_cork_full *cork, struct inet6_cork *v6_cork, struct ipcm6_cookie *ipc6, struct rt6_info *rt, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a4dfd0)
Location: net/ipv6/ip6_output.c:1235
Inline: False
Direct callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
```
**Symbols:**

```
ffffffff81a4dfd0-ffffffff81a4e40d: ip6_setup_cork (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ipcm6_cookie *ipc6</code>
</li>
<li>
<b>Param removed. </b>
<code>int hlimit</code>
</li>
<li>
<b>Param removed. </b>
<code>int tclass</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ipv6_txoptions *opt</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, cork, v6_cork, hlimit, tclass, opt, rt, fl6</code> ➡️ <code>sk, cork, v6_cork, ipc6, rt, fl6</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct flowi6 *fl6</code>
</li>
</ul>
</details>
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
