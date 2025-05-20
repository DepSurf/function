# Function: <code>tcp4_gro_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81783160)
Location: net/ipv4/tcp_offload.c:304
Inline: False
```
**Symbols:**

```
ffffffff81783160-ffffffff817831d5: tcp4_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff817f06f0)
Location: net/ipv4/tcp_offload.c:308
Inline: False
```
**Symbols:**

```
ffffffff817f06f0-ffffffff817f077a: tcp4_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81821460)
Location: net/ipv4/tcp_offload.c:309
Inline: False
```
**Symbols:**

```
ffffffff81821460-ffffffff818214ea: tcp4_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81842140)
Location: net/ipv4/tcp_offload.c:309
Inline: False
```
**Symbols:**

```
ffffffff81842140-ffffffff818421c8: tcp4_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff818c1a20)
Location: net/ipv4/tcp_offload.c:320
Inline: False
```
**Symbols:**

```
ffffffff818c1a20-ffffffff818c1aa8: tcp4_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff819176f0)
Location: net/ipv4/tcp_offload.c:318
Inline: False
```
**Symbols:**

```
ffffffff819176f0-ffffffff81917778: tcp4_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81945e30)
Location: net/ipv4/tcp_offload.c:323
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff81945e30-ffffffff81945eb5: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff819aa460)
Location: net/ipv4/tcp_offload.c:319
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff819aa460-ffffffff819aa4e6: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff819e1130)
Location: net/ipv4/tcp_offload.c:319
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff819e1130-ffffffff819e11b6: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81ace720)
Location: net/ipv4/tcp_offload.c:319
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff81ace720-ffffffff81ace7f2: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81ada740)
Location: net/ipv4/tcp_offload.c:319
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff81ada740-ffffffff81ada812: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81ac57c0)
Location: net/ipv4/tcp_offload.c:322
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff81ac57c0-ffffffff81ac5846: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81b83fd0)
Location: net/ipv4/tcp_offload.c:322
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff81b83fd0-ffffffff81b84056: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81d14790)
Location: net/ipv4/tcp_offload.c:323
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff81d14790-ffffffff81d14820: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81eda8c0)
Location: net/ipv4/tcp_offload.c:333
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff81eda8c0-ffffffff81eda950: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81f399a0)
Location: net/ipv4/tcp_offload.c:331
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff81f399a0-ffffffff81f39a32: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81fffa90)
Location: net/ipv4/tcp_offload.c:331
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff81fffa90-ffffffff81fffb22: tcp4_gro_complete (STB_GLOBAL)
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
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffff800010c95148)
Location: net/ipv4/tcp_offload.c:319
Inline: False
```
**Symbols:**

```
ffff800010c95148-ffff800010c951f4: tcp4_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (c0da38a0)
Location: net/ipv4/tcp_offload.c:319
Inline: False
```
**Symbols:**

```
c0da38a0-c0da3924: tcp4_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (c000000000da60e0)
Location: net/ipv4/tcp_offload.c:319
Inline: False
```
**Symbols:**

```
c000000000da60e0-c000000000da6180: tcp4_gro_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffe0007f4374)
Location: net/ipv4/tcp_offload.c:319
Inline: False
```
**Symbols:**

```
ffffffe0007f4374-ffffffe0007f4414: tcp4_gro_complete (STB_LOCAL)
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
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81980fa0)
Location: net/ipv4/tcp_offload.c:319
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff81980fa0-ffffffff81981026: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff8193aa60)
Location: net/ipv4/tcp_offload.c:319
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff8193aa60-ffffffff8193aae6: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff819eb770)
Location: net/ipv4/tcp_offload.c:319
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff819eb770-ffffffff819eb7f6: tcp4_gro_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp4_gro_complete(struct sk_buff *skb, int thoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff819f5620)
Location: net/ipv4/tcp_offload.c:319
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
**Symbols:**

```
ffffffff819f5620-ffffffff819f56a6: tcp4_gro_complete (STB_GLOBAL)
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
