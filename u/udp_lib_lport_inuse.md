# Function: <code>udp_lib_lport_inuse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, int (*saddr_comp)(const struct sock *, const struct sock *), unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81786050)
Location: net/ipv4/udp.c:135
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81786050-ffffffff81786131: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, int (*saddr_comp)(const struct sock *, const struct sock *, bool), unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f35b0)
Location: net/ipv4/udp.c:136
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff817f35b0-ffffffff817f36ab: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, int (*saddr_comp)(const struct sock *, const struct sock *, bool), unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818243a0)
Location: net/ipv4/udp.c:137
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff818243a0-ffffffff8182449b: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818450b0)
Location: net/ipv4/udp.c:148
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff818450b0-ffffffff818451b5: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c4b40)
Location: net/ipv4/udp.c:148
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff818c4b40-ffffffff818c4c45: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191a7d0)
Location: net/ipv4/udp.c:142
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff8191a7d0-ffffffff8191a8eb: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81948f80)
Location: net/ipv4/udp.c:144
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81948f80-ffffffff8194909b: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819ad5d0)
Location: net/ipv4/udp.c:128
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819ad5d0-ffffffff819ad6eb: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e4280)
Location: net/ipv4/udp.c:128
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819e4280-ffffffff819e439b: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad19d0)
Location: net/ipv4/udp.c:131
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81ad19d0-ffffffff81ad1aeb: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81adda00)
Location: net/ipv4/udp.c:132
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81adda00-ffffffff81addb1b: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ac8ad0)
Location: net/ipv4/udp.c:132
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81ac8ad0-ffffffff81ac8beb: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:132
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81b87350-ffffffff81b87479: udp_lib_lport_inuse (STB_LOCAL)
ffffffff81d3bf4d-ffffffff81d3bf6b: udp_lib_lport_inuse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:132
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81d18180-ffffffff81d182a5: udp_lib_lport_inuse (STB_LOCAL)
ffffffff81f08786-ffffffff81f087a6: udp_lib_lport_inuse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:139
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81edea80-ffffffff81edeba5: udp_lib_lport_inuse (STB_LOCAL)
ffffffff820b0210-ffffffff820b0230: udp_lib_lport_inuse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:141
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81f3dec0-ffffffff81f3dfe5: udp_lib_lport_inuse (STB_LOCAL)
ffffffff8213149c-ffffffff821314bc: udp_lib_lport_inuse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (0)
Location: net/ipv4/udp.c:141
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff82003ff0-ffffffff82004115: udp_lib_lport_inuse (STB_LOCAL)
ffffffff82212de0-ffffffff82212e00: udp_lib_lport_inuse.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffff800010c99340)
Location: net/ipv4/udp.c:128
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffff800010c99340-ffff800010c994b4: udp_lib_lport_inuse.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da6c20)
Location: net/ipv4/udp.c:128
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
c0da6c20-c0da6da4: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000daa4c0)
Location: net/ipv4/udp.c:128
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
c000000000daa4c0-c000000000daa6cc: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f6d14)
Location: net/ipv4/udp.c:128
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffe0007f6d14-ffffffe0007f6e2a: udp_lib_lport_inuse (STB_LOCAL)
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
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819840f0)
Location: net/ipv4/udp.c:128
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819840f0-ffffffff8198420b: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8193dbb0)
Location: net/ipv4/udp.c:128
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff8193dbb0-ffffffff8193dccb: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819ee8c0)
Location: net/ipv4/udp.c:128
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819ee8c0-ffffffff819ee9db: udp_lib_lport_inuse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net *net, __u16 num, const struct udp_hslot *hslot, long unsigned int *bitmap, struct sock *sk, unsigned int log);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f8a30)
Location: net/ipv4/udp.c:128
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819f8a30-ffffffff819f8b4b: udp_lib_lport_inuse (STB_LOCAL)
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
<b>Param type changed. </b>
<code>int (*saddr_comp)(const struct sock *, const struct sock *)</code> ➡️ <code>int (*saddr_comp)(const struct sock *, const struct sock *, bool)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int (*saddr_comp)(const struct sock *, const struct sock *, bool)</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, num, hslot, bitmap, sk, saddr_comp, log</code> ➡️ <code>net, num, hslot, bitmap, sk, log</code>
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
