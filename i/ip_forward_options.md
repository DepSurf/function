# Function: <code>ip_forward_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff8175c0a0)
Location: net/ipv4/ip_options.c:560
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff8175c0a0-ffffffff8175c241: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff817c8340)
Location: net/ipv4/ip_options.c:558
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff817c8340-ffffffff817c84e1: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff817f7e30)
Location: net/ipv4/ip_options.c:558
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff817f7e30-ffffffff817f7fd1: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81818230)
Location: net/ipv4/ip_options.c:558
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff81818230-ffffffff818183c2: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81897390)
Location: net/ipv4/ip_options.c:556
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff81897390-ffffffff81897522: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:556
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff818eb7f3-ffffffff818eb80b: ip_forward_options.cold.7 (STB_LOCAL)
ffffffff818eb670-ffffffff818eb7f3: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:568
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
**Symbols:**

```
ffffffff81918d13-ffffffff81918d2b: ip_forward_options.cold.8 (STB_LOCAL)
ffffffff81918b90-ffffffff81918d13: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:569
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
**Symbols:**

```
ffffffff8197ac53-ffffffff8197ac6b: ip_forward_options.cold (STB_LOCAL)
ffffffff8197aac0-ffffffff8197ac53: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:569
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff819b15c3-ffffffff819b15db: ip_forward_options.cold (STB_LOCAL)
ffffffff819b1430-ffffffff819b15c3: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:569
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff81a9b55e-ffffffff81a9b576: ip_forward_options.cold (STB_LOCAL)
ffffffff81a9b3c0-ffffffff81a9b55e: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:551
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff81c3256b-ffffffff81c32583: ip_forward_options.cold (STB_LOCAL)
ffffffff81aa5250-ffffffff81aa53ee: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:551
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff81c24856-ffffffff81c2486e: ip_forward_options.cold (STB_LOCAL)
ffffffff81a90330-ffffffff81a904cf: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:551
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff81d3a0b6-ffffffff81d3a0ce: ip_forward_options.cold (STB_LOCAL)
ffffffff81b4b5a0-ffffffff81b4b73f: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:538
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff81f06838-ffffffff81f06850: ip_forward_options.cold (STB_LOCAL)
ffffffff81cd8ab0-ffffffff81cd8c72: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81e991b0)
Location: net/ipv4/ip_options.c:538
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff81e991b0-ffffffff81e9936d: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81ef7aa0)
Location: net/ipv4/ip_options.c:538
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff81ef7aa0-ffffffff81ef7c5d: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81fbb9c0)
Location: net/ipv4/ip_options.c:538
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff81fbb9c0-ffffffff81fbbb7d: ip_forward_options (STB_GLOBAL)
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
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffff800010c61990)
Location: net/ipv4/ip_options.c:569
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffff800010c61990-ffff800010c61b68: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (c0d712c8)
Location: net/ipv4/ip_options.c:569
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
**Symbols:**

```
c0d712c8-c0d714d0: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (c000000000d64ee0)
Location: net/ipv4/ip_options.c:569
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
c000000000d64ee0-c000000000d65140: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffe0007c99ec)
Location: net/ipv4/ip_options.c:569
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffe0007c99ec-ffffffe0007c9ba6: ip_forward_options (STB_GLOBAL)
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
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:569
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff81951433-ffffffff8195144b: ip_forward_options.cold (STB_LOCAL)
ffffffff819512a0-ffffffff81951433: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:569
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff8190af23-ffffffff8190af3b: ip_forward_options.cold (STB_LOCAL)
ffffffff8190ad90-ffffffff8190af23: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:569
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff819bbc03-ffffffff819bbc1b: ip_forward_options.cold (STB_LOCAL)
ffffffff819bba70-ffffffff819bbc03: ip_forward_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ip_forward_options(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_options.c (0)
Location: net/ipv4/ip_options.c:569
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward_finish
```
**Symbols:**

```
ffffffff819c5513-ffffffff819c552b: ip_forward_options.cold (STB_LOCAL)
ffffffff819c5380-ffffffff819c5513: ip_forward_options (STB_GLOBAL)
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
