# Function: <code>inet_frag_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq, struct inet_frags *f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff817a1e20)
Location: net/ipv4/inet_fragment.c:276
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
**Symbols:**

```
ffffffff817a1e20-ffffffff817a1ea7: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq, struct inet_frags *f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff8180fae0)
Location: net/ipv4/inet_fragment.c:276
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
**Symbols:**

```
ffffffff8180fae0-ffffffff8180fb67: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq, struct inet_frags *f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81841030)
Location: net/ipv4/inet_fragment.c:276
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
**Symbols:**

```
ffffffff81841030-ffffffff818410b7: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq, struct inet_frags *f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff818628b0)
Location: net/ipv4/inet_fragment.c:274
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
**Symbols:**

```
ffffffff818628b0-ffffffff81862931: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq, struct inet_frags *f);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff818e29d0)
Location: net/ipv4/inet_fragment.c:277
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
**Symbols:**

```
ffffffff818e29d0-ffffffff818e2a69: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819390b0)
Location: net/ipv4/inet_fragment.c:99
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_expire_frag_queue
```
**Symbols:**

```
ffffffff819390b0-ffffffff81939286: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81968c80)
Location: net/ipv4/inet_fragment.c:100
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff81968c80-ffffffff81968e50: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819cf710)
Location: net/ipv4/inet_fragment.c:194
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff819cf710-ffffffff819cf955: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a062a0)
Location: net/ipv4/inet_fragment.c:194
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff81a062a0-ffffffff81a064e5: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81af60a0)
Location: net/ipv4/inet_fragment.c:194
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff81af60a0-ffffffff81af61b4: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81b02f10)
Location: net/ipv4/inet_fragment.c:225
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff81b02f10-ffffffff81b0302e: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81aee800)
Location: net/ipv4/inet_fragment.c:225
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff81aee800-ffffffff81aee91e: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (0)
Location: net/ipv4/inet_fragment.c:225
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff81d3db13-ffffffff81d3db28: inet_frag_kill.cold (STB_LOCAL)
ffffffff81baebc0-ffffffff81baecf0: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (0)
Location: net/ipv4/inet_fragment.c:225
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff81f0a405-ffffffff81f0a419: inet_frag_kill.cold (STB_LOCAL)
ffffffff81d41ec0-ffffffff81d42017: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (0)
Location: net/ipv4/inet_fragment.c:226
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff820b1cce-ffffffff820b1ce2: inet_frag_kill.cold (STB_LOCAL)
ffffffff81f0acf0-ffffffff81f0ae47: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (0)
Location: net/ipv4/inet_fragment.c:226
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff82132f06-ffffffff82132f1a: inet_frag_kill.cold (STB_LOCAL)
ffffffff81f6a830-ffffffff81f6a987: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (0)
Location: net/ipv4/inet_fragment.c:226
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff822148e7-ffffffff822148fb: inet_frag_kill.cold (STB_LOCAL)
ffffffff82030ee0-ffffffff82031037: inet_frag_kill (STB_GLOBAL)
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
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffff800010cbf058)
Location: net/ipv4/inet_fragment.c:194
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffff800010cbf058-ffff800010cbf334: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c0dca900)
Location: net/ipv4/inet_fragment.c:194
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
c0dca900-c0dcac64: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c000000000dd9bb0)
Location: net/ipv4/inet_fragment.c:194
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
c000000000dd9bb0-c000000000dd9f44: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffe000814f48)
Location: net/ipv4/inet_fragment.c:194
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffe000814f48-ffffffe000815150: inet_frag_kill (STB_GLOBAL)
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
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819a6040)
Location: net/ipv4/inet_fragment.c:194
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff819a6040-ffffffff819a6285: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff8195fb00)
Location: net/ipv4/inet_fragment.c:194
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff8195fb00-ffffffff8195fd45: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a108e0)
Location: net/ipv4/inet_fragment.c:194
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_expire
```
**Symbols:**

```
ffffffff81a108e0-ffffffff81a10b25: inet_frag_kill (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_frag_kill(struct inet_frag_queue *fq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a1b130)
Location: net/ipv4/inet_fragment.c:194
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_expire
```
**Symbols:**

```
ffffffff81a1b130-ffffffff81a1b3ef: inet_frag_kill (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct inet_frags *f</code>
</li>
</ul>
</details>
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
