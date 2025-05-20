# Function: <code>bpf_skb_get_tunnel_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 r1, u64 r2, u64 size, u64 flags, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81731b00)
Location: net/core/filter.c:1555
Inline: False
```
**Symbols:**

```
ffffffff81731b00-ffffffff81731b64: bpf_skb_get_tunnel_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 r1, u64 r2, u64 size, u64 flags, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179cb30)
Location: net/core/filter.c:2059
Inline: False
```
**Symbols:**

```
ffffffff8179cb30-ffffffff8179cca7: bpf_skb_get_tunnel_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ca4d0)
Location: net/core/filter.c:2318
Inline: False
```
**Symbols:**

```
ffffffff817ca4d0-ffffffff817ca647: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e94a0)
Location: net/core/filter.c:2477
Inline: False
```
**Symbols:**

```
ffffffff817e94a0-ffffffff817e9643: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818649a0)
Location: net/core/filter.c:2875
Inline: False
```
**Symbols:**

```
ffffffff818649a0-ffffffff81864b43: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b1b60)
Location: net/core/filter.c:3494
Inline: False
```
**Symbols:**

```
ffffffff818b1b60-ffffffff818b1d1a: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d65a0)
Location: net/core/filter.c:3682
Inline: False
```
**Symbols:**

```
ffffffff818d65a0-ffffffff818d6758: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81923e20)
Location: net/core/filter.c:3819
Inline: False
```
**Symbols:**

```
ffffffff81923e20-ffffffff81923f87: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81956130)
Location: net/core/filter.c:3826
Inline: False
```
**Symbols:**

```
ffffffff81956130-ffffffff81956297: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2b830)
Location: net/core/filter.c:3798
Inline: False
```
**Symbols:**

```
ffffffff81a2b830-ffffffff81a2b99d: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2ca50)
Location: net/core/filter.c:4206
Inline: False
```
**Symbols:**

```
ffffffff81a2ca50-ffffffff81a2cbbd: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a13e00)
Location: net/core/filter.c:4145
Inline: False
```
**Symbols:**

```
ffffffff81a13e00-ffffffff81a13f76: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac57d0)
Location: net/core/filter.c:4203
Inline: False
```
**Symbols:**

```
ffffffff81ac57d0-ffffffff81ac5946: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c41320)
Location: net/core/filter.c:4484
Inline: False
```
**Symbols:**

```
ffffffff81c41320-ffffffff81c415a6: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df6a90)
Location: net/core/filter.c:4498
Inline: False
```
**Symbols:**

```
ffffffff81df6a90-ffffffff81df6cb4: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e68740)
Location: net/core/filter.c:4549
Inline: False
```
**Symbols:**

```
ffffffff81e68740-ffffffff81e6896d: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f27d20)
Location: net/core/filter.c:4623
Inline: False
```
**Symbols:**

```
ffffffff81f27d20-ffffffff81f27f4d: bpf_skb_get_tunnel_key (STB_GLOBAL)
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
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf6f50)
Location: net/core/filter.c:3826
Inline: False
```
**Symbols:**

```
ffff800010bf6f50-ffff800010bf70d0: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1177c)
Location: net/core/filter.c:3826
Inline: False
```
**Symbols:**

```
c0d1177c-c0d1192c: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cde0b0)
Location: net/core/filter.c:3826
Inline: False
```
**Symbols:**

```
c000000000cde0b0-c000000000cde288: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000778d90)
Location: net/core/filter.c:3826
Inline: False
```
**Symbols:**

```
ffffffe000778d90-ffffffe000778f7e: bpf_skb_get_tunnel_key (STB_GLOBAL)
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
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f6100)
Location: net/core/filter.c:3826
Inline: False
```
**Symbols:**

```
ffffffff818f6100-ffffffff818f6267: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818aff30)
Location: net/core/filter.c:3826
Inline: False
```
**Symbols:**

```
ffffffff818aff30-ffffffff818b0097: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81947130)
Location: net/core/filter.c:3826
Inline: False
```
**Symbols:**

```
ffffffff81947130-ffffffff81947297: bpf_skb_get_tunnel_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_skb_get_tunnel_key(u64 skb, u64 to, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81968a40)
Location: net/core/filter.c:3826
Inline: False
```
**Symbols:**

```
ffffffff81968a40-ffffffff81968ba7: bpf_skb_get_tunnel_key (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 skb</code>
</li>
<li>
<b>Param added. </b>
<code>u64 to</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
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
