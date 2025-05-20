# Function: <code>tcp_wfree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817749e0)
Location: net/ipv4/tcp_output.c:854
Inline: False
```
**Symbols:**

```
ffffffff817749e0-ffffffff81774aa4: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e1960)
Location: net/ipv4/tcp_output.c:852
Inline: False
```
**Symbols:**

```
ffffffff817e1960-ffffffff817e1a21: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81811e40)
Location: net/ipv4/tcp_output.c:860
Inline: False
```
**Symbols:**

```
ffffffff81811e40-ffffffff81811f2f: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81832170)
Location: net/ipv4/tcp_output.c:861
Inline: False
```
**Symbols:**

```
ffffffff81832170-ffffffff81832271: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b19b0)
Location: net/ipv4/tcp_output.c:904
Inline: False
```
**Symbols:**

```
ffffffff818b19b0-ffffffff818b1ab7: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81907040)
Location: net/ipv4/tcp_output.c:919
Inline: False
```
**Symbols:**

```
ffffffff81907040-ffffffff81907148: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81934c30)
Location: net/ipv4/tcp_output.c:917
Inline: False
```
**Symbols:**

```
ffffffff81934c30-ffffffff81934d38: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:917
Inline: False
```
**Symbols:**

```
ffffffff8199ebe5-ffffffff8199ebf8: tcp_wfree.cold (STB_LOCAL)
ffffffff819989f0-ffffffff81998b00: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819cf520)
Location: net/ipv4/tcp_output.c:921
Inline: False
```
**Symbols:**

```
ffffffff819cf520-ffffffff819cf622: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abb730)
Location: net/ipv4/tcp_output.c:984
Inline: False
```
**Symbols:**

```
ffffffff81abb730-ffffffff81abb872: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac7310)
Location: net/ipv4/tcp_output.c:1138
Inline: False
```
**Symbols:**

```
ffffffff81ac7310-ffffffff81ac7452: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab2330)
Location: net/ipv4/tcp_output.c:1138
Inline: False
```
**Symbols:**

```
ffffffff81ab2330-ffffffff81ab2475: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b6f1b0)
Location: net/ipv4/tcp_output.c:1138
Inline: False
```
**Symbols:**

```
ffffffff81b6f1b0-ffffffff81b6f2f5: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81cfe820)
Location: net/ipv4/tcp_output.c:1137
Inline: False
```
**Symbols:**

```
ffffffff81cfe820-ffffffff81cfe97a: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec3740)
Location: net/ipv4/tcp_output.c:1137
Inline: False
```
**Symbols:**

```
ffffffff81ec3740-ffffffff81ec388c: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f21980)
Location: net/ipv4/tcp_output.c:1139
Inline: False
```
**Symbols:**

```
ffffffff81f21980-ffffffff81f21acc: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fe5910)
Location: net/ipv4/tcp_output.c:1184
Inline: False
```
**Symbols:**

```
ffffffff81fe5910-ffffffff81fe5a5c: tcp_wfree (STB_GLOBAL)
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
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c82918)
Location: net/ipv4/tcp_output.c:921
Inline: False
```
**Symbols:**

```
ffff800010c82918-ffff800010c82aa4: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d91340)
Location: net/ipv4/tcp_output.c:921
Inline: False
```
**Symbols:**

```
c0d91340-c0d91480: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d8d2d0)
Location: net/ipv4/tcp_output.c:921
Inline: False
```
**Symbols:**

```
c000000000d8d2d0-c000000000d8d440: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e3eb6)
Location: net/ipv4/tcp_output.c:921
Inline: False
```
**Symbols:**

```
ffffffe0007e3eb6-ffffffe0007e3fcc: tcp_wfree (STB_GLOBAL)
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
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8196f390)
Location: net/ipv4/tcp_output.c:921
Inline: False
```
**Symbols:**

```
ffffffff8196f390-ffffffff8196f492: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81928e80)
Location: net/ipv4/tcp_output.c:921
Inline: False
```
**Symbols:**

```
ffffffff81928e80-ffffffff81928f62: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d9b60)
Location: net/ipv4/tcp_output.c:921
Inline: False
```
**Symbols:**

```
ffffffff819d9b60-ffffffff819d9c62: tcp_wfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_wfree(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e37c0)
Location: net/ipv4/tcp_output.c:921
Inline: False
```
**Symbols:**

```
ffffffff819e37c0-ffffffff819e38c2: tcp_wfree (STB_GLOBAL)
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
