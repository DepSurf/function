# Function: <code>__dev_forward_skb2</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __dev_forward_skb2(struct net_device *dev, struct sk_buff *skb, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e70b0)
Location: net/core/dev.c:2282
Inline: False
Direct callers:
  - net/core/dev.c:dev_forward_skb_nomtu
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff819e70b0-ffffffff819e722f: __dev_forward_skb2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __dev_forward_skb2(struct net_device *dev, struct sk_buff *skb, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a97a60)
Location: net/core/dev.c:2157
Inline: False
Direct callers:
  - net/core/dev.c:dev_forward_skb_nomtu
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81a97a60-ffffffff81a97bdf: __dev_forward_skb2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __dev_forward_skb2(struct net_device *dev, struct sk_buff *skb, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c11650)
Location: net/core/dev.c:2134
Inline: False
Direct callers:
  - net/core/dev.c:dev_forward_skb_nomtu
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81c11650-ffffffff81c117ff: __dev_forward_skb2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dev_forward_skb2(struct net_device *dev, struct sk_buff *skb, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc1200)
Location: net/core/dev.c:2119
Inline: False
Direct callers:
  - net/core/dev.c:dev_forward_skb_nomtu
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81dc1200-ffffffff81dc13a8: __dev_forward_skb2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dev_forward_skb2(struct net_device *dev, struct sk_buff *skb, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e31020)
Location: net/core/dev.c:2145
Inline: False
Direct callers:
  - net/core/dev.c:dev_forward_skb_nomtu
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81e31020-ffffffff81e311c8: __dev_forward_skb2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dev_forward_skb2(struct net_device *dev, struct sk_buff *skb, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eed530)
Location: net/core/dev.c:2149
Inline: False
Direct callers:
  - net/core/dev.c:dev_forward_skb_nomtu
  - net/core/dev.c:dev_forward_skb
```
**Symbols:**

```
ffffffff81eed530-ffffffff81eed6bf: __dev_forward_skb2 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
