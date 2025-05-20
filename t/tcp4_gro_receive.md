# Function: <code>tcp4_gro_receive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff **tcp4_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81783a50)
Location: net/ipv4/tcp_offload.c:291
Inline: False
```
**Symbols:**

```
ffffffff81783a50-ffffffff81783c1b: tcp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff **tcp4_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff817f1010)
Location: net/ipv4/tcp_offload.c:295
Inline: False
```
**Symbols:**

```
ffffffff817f1010-ffffffff817f11c9: tcp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff **tcp4_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81821da0)
Location: net/ipv4/tcp_offload.c:296
Inline: False
```
**Symbols:**

```
ffffffff81821da0-ffffffff81821f59: tcp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff **tcp4_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81842a20)
Location: net/ipv4/tcp_offload.c:296
Inline: False
```
**Symbols:**

```
ffffffff81842a20-ffffffff81842bc0: tcp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff **tcp4_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff818c2380)
Location: net/ipv4/tcp_offload.c:307
Inline: False
```
**Symbols:**

```
ffffffff818c2380-ffffffff818c2520: tcp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff **tcp4_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81917fd0)
Location: net/ipv4/tcp_offload.c:305
Inline: False
```
**Symbols:**

```
ffffffff81917fd0-ffffffff81918162: tcp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81946720)
Location: net/ipv4/tcp_offload.c:310
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81946720-ffffffff819468b3: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff819aad80)
Location: net/ipv4/tcp_offload.c:306
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff819aad80-ffffffff819aaf16: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff819e1a50)
Location: net/ipv4/tcp_offload.c:306
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff819e1a50-ffffffff819e1be6: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81acf0c0)
Location: net/ipv4/tcp_offload.c:306
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81acf0c0-ffffffff81acf25b: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81adb0d0)
Location: net/ipv4/tcp_offload.c:306
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81adb0d0-ffffffff81adb260: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81ac6110)
Location: net/ipv4/tcp_offload.c:309
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81ac6110-ffffffff81ac62bf: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81b84920)
Location: net/ipv4/tcp_offload.c:309
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81b84920-ffffffff81b84acf: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81d15190)
Location: net/ipv4/tcp_offload.c:310
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81d15190-ffffffff81d15332: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81edb370)
Location: net/ipv4/tcp_offload.c:320
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81edb370-ffffffff81edb512: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff81f3a430)
Location: net/ipv4/tcp_offload.c:318
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff81f3a430-ffffffff81f3a5d1: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff82000520)
Location: net/ipv4/tcp_offload.c:318
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff82000520-ffffffff820006c1: tcp4_gro_receive (STB_GLOBAL)
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
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffff800010c95a60)
Location: net/ipv4/tcp_offload.c:306
Inline: False
```
**Symbols:**

```
ffff800010c95a60-ffff800010c95c08: tcp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (c0da41d4)
Location: net/ipv4/tcp_offload.c:306
Inline: False
```
**Symbols:**

```
c0da41d4-c0da4360: tcp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (c000000000da6d80)
Location: net/ipv4/tcp_offload.c:306
Inline: False
```
**Symbols:**

```
c000000000da6d80-c000000000da6f90: tcp4_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffe0007f4c6e)
Location: net/ipv4/tcp_offload.c:306
Inline: False
```
**Symbols:**

```
ffffffe0007f4c6e-ffffffe0007f4dde: tcp4_gro_receive (STB_LOCAL)
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
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff819818c0)
Location: net/ipv4/tcp_offload.c:306
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff819818c0-ffffffff81981a56: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff8193b380)
Location: net/ipv4/tcp_offload.c:306
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff8193b380-ffffffff8193b516: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff819ec090)
Location: net/ipv4/tcp_offload.c:306
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff819ec090-ffffffff819ec226: tcp4_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *tcp4_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_offload.c (ffffffff819f5f40)
Location: net/ipv4/tcp_offload.c:306
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
**Symbols:**

```
ffffffff819f5f40-ffffffff819f60d6: tcp4_gro_receive (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sk_buff **head</code> ➡️ <code>struct list_head *head</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct sk_buff **</code> ➡️ <code>struct sk_buff *</code>
</li>
</ul>
</details>
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
