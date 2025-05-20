# Function: <code>ipv6_gso_pull_exthdrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81800b70)
Location: net/ipv6/ip6_offload.c:22
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81800b70-ffffffff81800c80: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81872320)
Location: net/ipv6/ip6_offload.c:23
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81872320-ffffffff81872408: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff818a6910)
Location: net/ipv6/ip6_offload.c:23
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff818a6910-ffffffff818a69f8: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff818cd360)
Location: net/ipv6/ip6_offload.c:23
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff818cd360-ffffffff818cd464: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81952150)
Location: net/ipv6/ip6_offload.c:23
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81952150-ffffffff81952254: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff819ab9fb)
Location: net/ipv6/ip6_offload.c:23
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff819ab6d0-ffffffff819ab7ca: ipv6_gso_pull_exthdrs.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff819e258f)
Location: net/ipv6/ip6_offload.c:40
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff819e2200-ffffffff819e22ef: ipv6_gso_pull_exthdrs.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a50ec0)
Location: net/ipv6/ip6_offload.c:36
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81a50ec0-ffffffff81a50faf: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a87ae0)
Location: net/ipv6/ip6_offload.c:36
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81a87ae0-ffffffff81a87bcf: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81b82fa0)
Location: net/ipv6/ip6_offload.c:36
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81b82fa0-ffffffff81b8307e: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81b92650)
Location: net/ipv6/ip6_offload.c:38
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81b92650-ffffffff81b9272e: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81b817a0)
Location: net/ipv6/ip6_offload.c:39
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81b817a0-ffffffff81b8187e: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81c4d7c0)
Location: net/ipv6/ip6_offload.c:39
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81c4d7c0-ffffffff81c4d8be: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81dede80)
Location: net/ipv6/ip6_offload.c:39
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81dede80-ffffffff81dedf92: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81fc1f50)
Location: net/ipv6/ip6_offload.c:39
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81fc1f50-ffffffff81fc2062: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff82022ed0)
Location: net/ipv6/ip6_offload.c:40
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff82022ed0-ffffffff82022fec: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff820f20f3)
Location: net/ipv6/ip6_offload.c:74
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffff800010d54698)
Location: net/ipv6/ip6_offload.c:36
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffff800010d54698-ffff800010d54788: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (c0e54c58)
Location: net/ipv6/ip6_offload.c:36
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
c0e54c58-c0e54d64: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (c000000000e8d090)
Location: net/ipv6/ip6_offload.c:36
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
c000000000e8d090-c000000000e8d264: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffe00088c01e)
Location: net/ipv6/ip6_offload.c:36
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffe00088c01e-ffffffe00088c0f6: ipv6_gso_pull_exthdrs (STB_LOCAL)
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
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a27170)
Location: net/ipv6/ip6_offload.c:36
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81a27170-ffffffff81a2725f: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff819e3f30)
Location: net/ipv6/ip6_offload.c:36
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff819e3f30-ffffffff819e401f: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a92d20)
Location: net/ipv6/ip6_offload.c:36
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81a92d20-ffffffff81a92e0f: ipv6_gso_pull_exthdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipv6_gso_pull_exthdrs(struct sk_buff *skb, int proto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_offload.c (ffffffff81a9ee60)
Location: net/ipv6/ip6_offload.c:36
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81a9ee60-ffffffff81a9ef4f: ipv6_gso_pull_exthdrs (STB_LOCAL)
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
