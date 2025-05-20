# Function: <code>netif_rx_internal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81719540)
Location: net/core/dev.c:3533
Inline: False
Direct callers:
  - net/core/dev.c:dev_forward_skb
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx_ni
```
**Symbols:**

```
ffffffff81719540-ffffffff8171964d: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81781a20)
Location: net/core/dev.c:3786
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81781a20-ffffffff81781b22: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817af330)
Location: net/core/dev.c:3782
Inline: True
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff817af330-ffffffff817af432: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cdc40)
Location: net/core/dev.c:3868
Inline: True
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff817cdc40-ffffffff817cdd48: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184a8e0)
Location: net/core/dev.c:4050
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff8184a8e0-ffffffff8184aa11: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81894cb0)
Location: net/core/dev.c:4171
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81894cb0-ffffffff81894de3: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b5710)
Location: net/core/dev.c:4480
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff818b5710-ffffffff818b5843: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ff0a0)
Location: net/core/dev.c:4494
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff818ff0a0-ffffffff818ff1a3: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81931410)
Location: net/core/dev.c:4396
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81931410-ffffffff81931513: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a06b90)
Location: net/core/dev.c:4758
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81a06b90-ffffffff81a06c93: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a08160)
Location: net/core/dev.c:4787
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81a08160-ffffffff81a08257: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ee8c0)
Location: net/core/dev.c:4895
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb_nomtu
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff819ee8c0-ffffffff819ee9b7: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9fc00)
Location: net/core/dev.c:4886
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb_nomtu
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81a9fc00-ffffffff81a9fcee: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c155d0)
Location: net/core/dev.c:4927
Inline: False
Direct callers:
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:dev_forward_skb_nomtu
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81c155d0-ffffffff81c156fe: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc6940)
Location: net/core/dev.c:4914
Inline: False
Direct callers:
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:dev_forward_skb_nomtu
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81dc6940-ffffffff81dc6a80: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e35ce0)
Location: net/core/dev.c:4889
Inline: False
Direct callers:
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:dev_forward_skb_nomtu
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81e35ce0-ffffffff81e35e15: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef3fa0)
Location: net/core/dev.c:5037
Inline: False
Direct callers:
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:dev_forward_skb_nomtu
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81ef3fa0-ffffffff81ef40d5: netif_rx_internal (STB_LOCAL)
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
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcfb88)
Location: net/core/dev.c:4396
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffff800010bcfb88-ffff800010bcfcd8: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce5f4c)
Location: net/core/dev.c:4396
Inline: True
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
c0ce5f4c-c0ce60c8: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cac7b0)
Location: net/core/dev.c:4396
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
c000000000cac7b0-c000000000cac924: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000759d66)
Location: net/core/dev.c:4396
Inline: True
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffe000759d66-ffffffe000759e64: netif_rx_internal (STB_LOCAL)
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
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d1410)
Location: net/core/dev.c:4396
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff818d1410-ffffffff818d1513: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b2a0)
Location: net/core/dev.c:4396
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff8188b2a0-ffffffff8188b3a3: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81922410)
Location: net/core/dev.c:4396
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81922410-ffffffff81922513: netif_rx_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81943500)
Location: net/core/dev.c:4396
Inline: False
Direct callers:
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81943500-ffffffff81943663: netif_rx_internal (STB_LOCAL)
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
