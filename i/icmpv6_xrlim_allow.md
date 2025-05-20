# Function: <code>icmpv6_xrlim_allow</code>

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
In net/ipv6/icmp.c (ffffffff817e7a56)
Location: net/ipv6/icmp.c:173
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv6/icmp.c (ffffffff81855ee7)
Location: net/ipv6/icmp.c:173
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv6/icmp.c (ffffffff81887d3c)
Location: net/ipv6/icmp.c:174
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv6/icmp.c (ffffffff818ae399)
Location: net/ipv6/icmp.c:196
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv6/icmp.c (ffffffff8193103b)
Location: net/ipv6/icmp.c:196
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv6/icmp.c (ffffffff81989cdd)
Location: net/ipv6/icmp.c:196
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
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
In net/ipv6/icmp.c (ffffffff819c0593)
Location: net/ipv6/icmp.c:198
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a2eac0)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a2eac0-ffffffff81a2ec03: icmpv6_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a65610)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a65610-ffffffff81a65753: icmpv6_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81b5de20)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81b5de20-ffffffff81b5df59: icmpv6_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81b6c5f0)
Location: net/ipv6/icmp.c:199
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81b6c5f0-ffffffff81b6c729: icmpv6_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81b5a950)
Location: net/ipv6/icmp.c:199
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81b5a950-ffffffff81b5aa8d: icmpv6_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/icmp.c (0)
Location: net/ipv6/icmp.c:200
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81c22050-ffffffff81c2219d: icmpv6_xrlim_allow (STB_LOCAL)
ffffffff81d40922-ffffffff81d40944: icmpv6_xrlim_allow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/icmp.c (0)
Location: net/ipv6/icmp.c:192
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81dbf090-ffffffff81dbf1ec: icmpv6_xrlim_allow (STB_LOCAL)
ffffffff81f0d30b-ffffffff81f0d32d: icmpv6_xrlim_allow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/icmp.c (0)
Location: net/ipv6/icmp.c:192
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81f8f2e0-ffffffff81f8f442: icmpv6_xrlim_allow (STB_LOCAL)
ffffffff820b477d-ffffffff820b479f: icmpv6_xrlim_allow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/icmp.c (0)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81fefae0-ffffffff81fefc78: icmpv6_xrlim_allow (STB_LOCAL)
ffffffff82135800-ffffffff82135822: icmpv6_xrlim_allow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/icmp.c (0)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff820bd6b0-ffffffff820bd848: icmpv6_xrlim_allow (STB_LOCAL)
ffffffff822172db-ffffffff822172fd: icmpv6_xrlim_allow.cold (STB_LOCAL)
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
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffff800010d2b858)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffff800010d2b858-ffff800010d2b9d4: icmpv6_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (c0e2f444)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
c0e2f444-c0e2f654: icmpv6_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (c000000000e5cd90)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
c000000000e5cd90-c000000000e5cf78: icmpv6_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffe00086ba28)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffe00086ba28-ffffffe00086bb74: icmpv6_xrlim_allow (STB_LOCAL)
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
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a04ca0)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a04ca0-ffffffff81a04de3: icmpv6_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff819c1a60)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff819c1a60-ffffffff819c1ba3: icmpv6_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a6f720)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a6f720-ffffffff81a6f863: icmpv6_xrlim_allow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock *sk, u8 type, struct flowi6 *fl6);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a7bd50)
Location: net/ipv6/icmp.c:193
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a7bd50-ffffffff81a7be93: icmpv6_xrlim_allow (STB_LOCAL)
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
