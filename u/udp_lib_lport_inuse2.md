# Function: <code>udp_lib_lport_inuse2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk, int (*saddr_comp)(const struct sock *, const struct sock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81785f60)
Location: net/ipv4/udp.c:169
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81785f60-ffffffff81786044: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk, int (*saddr_comp)(const struct sock *, const struct sock *, bool));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f34b0)
Location: net/ipv4/udp.c:171
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff817f34b0-ffffffff817f35a3: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk, int (*saddr_comp)(const struct sock *, const struct sock *, bool));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818242a0)
Location: net/ipv4/udp.c:172
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff818242a0-ffffffff81824393: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81844fb0)
Location: net/ipv4/udp.c:184
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81844fb0-ffffffff818450a2: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c4a40)
Location: net/ipv4/udp.c:184
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff818c4a40-ffffffff818c4b32: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191ce70)
Location: net/ipv4/udp.c:178
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff8191ce70-ffffffff8191cf62: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194bf30)
Location: net/ipv4/udp.c:180
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff8194bf30-ffffffff8194c022: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b0700)
Location: net/ipv4/udp.c:164
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819b0700-ffffffff819b0812: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e7390)
Location: net/ipv4/udp.c:164
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819e7390-ffffffff819e74a2: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad3c70)
Location: net/ipv4/udp.c:167
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81ad3c70-ffffffff81ad3d82: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81adfdd0)
Location: net/ipv4/udp.c:168
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81adfdd0-ffffffff81adfee2: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81acc050)
Location: net/ipv4/udp.c:168
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81acc050-ffffffff81acc162: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b8a8e0)
Location: net/ipv4/udp.c:168
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81b8a8e0-ffffffff81b8a9f2: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d18080)
Location: net/ipv4/udp.c:168
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81d18080-ffffffff81d18177: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ede970)
Location: net/ipv4/udp.c:175
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81ede970-ffffffff81edea67: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f3ddb0)
Location: net/ipv4/udp.c:177
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81f3ddb0-ffffffff81f3dea7: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82003ee0)
Location: net/ipv4/udp.c:177
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff82003ee0-ffffffff82003fd7: udp_lib_lport_inuse2 (STB_LOCAL)
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
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9b400)
Location: net/ipv4/udp.c:164
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffff800010c9b400-ffff800010c9b564: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da6adc)
Location: net/ipv4/udp.c:164
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
c0da6adc-c0da6c20: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000dadbc0)
Location: net/ipv4/udp.c:164
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
c000000000dadbc0-c000000000dadd90: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f9852)
Location: net/ipv4/udp.c:164
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffe0007f9852-ffffffe0007f9972: udp_lib_lport_inuse2 (STB_LOCAL)
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
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81987200)
Location: net/ipv4/udp.c:164
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81987200-ffffffff81987312: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81940cc0)
Location: net/ipv4/udp.c:164
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff81940cc0-ffffffff81940dd2: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f19d0)
Location: net/ipv4/udp.c:164
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819f19d0-ffffffff819f1ae2: udp_lib_lport_inuse2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int udp_lib_lport_inuse2(struct net *net, __u16 num, struct udp_hslot *hslot2, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f8920)
Location: net/ipv4/udp.c:164
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
**Symbols:**

```
ffffffff819f8920-ffffffff819f8a2d: udp_lib_lport_inuse2 (STB_LOCAL)
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
