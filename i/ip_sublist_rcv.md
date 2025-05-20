# Function: <code>ip_sublist_rcv</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81915370)
Location: net/ipv4/ip_input.c:576
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff81915370-ffffffff819155d4: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819778a0)
Location: net/ipv4/ip_input.c:575
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff819778a0-ffffffff81977b08: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819ae230)
Location: net/ipv4/ip_input.c:575
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff819ae230-ffffffff819ae498: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a982a0)
Location: net/ipv4/ip_input.c:603
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff81a982a0-ffffffff81a98336: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81aa21f0)
Location: net/ipv4/ip_input.c:603
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff81aa21f0-ffffffff81aa228b: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a8d450)
Location: net/ipv4/ip_input.c:604
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff81a8d450-ffffffff81a8d638: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (0)
Location: net/ipv4/ip_input.c:604
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff81b48610-ffffffff81b4880b: ip_sublist_rcv (STB_LOCAL)
ffffffff81d3a063-ffffffff81d3a086: ip_sublist_rcv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (0)
Location: net/ipv4/ip_input.c:628
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff81cd59d0-ffffffff81cd5bea: ip_sublist_rcv (STB_LOCAL)
ffffffff81f067f3-ffffffff81f0680e: ip_sublist_rcv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (0)
Location: net/ipv4/ip_input.c:633
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff81e95e60-ffffffff81e9607a: ip_sublist_rcv (STB_LOCAL)
ffffffff820ae301-ffffffff820ae31c: ip_sublist_rcv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (0)
Location: net/ipv4/ip_input.c:633
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff81ef46a0-ffffffff81ef48bb: ip_sublist_rcv (STB_LOCAL)
ffffffff8212f7ff-ffffffff8212f81a: ip_sublist_rcv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (0)
Location: net/ipv4/ip_input.c:634
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff81fb8620-ffffffff81fb8842: ip_sublist_rcv (STB_LOCAL)
ffffffff822115bc-ffffffff822115d7: ip_sublist_rcv.cold (STB_LOCAL)
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
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffff800010c5e710)
Location: net/ipv4/ip_input.c:575
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffff800010c5e710-ffff800010c5e978: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (c0d6dd78)
Location: net/ipv4/ip_input.c:575
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
c0d6dd78-c0d6dff0: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (c000000000d60fb0)
Location: net/ipv4/ip_input.c:575
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
c000000000d60fb0-c000000000d612e4: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffe0007c6e04)
Location: net/ipv4/ip_input.c:575
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffe0007c6e04-ffffffe0007c6fe6: ip_sublist_rcv (STB_LOCAL)
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
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff8194e0a0)
Location: net/ipv4/ip_input.c:575
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff8194e0a0-ffffffff8194e308: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81907b90)
Location: net/ipv4/ip_input.c:575
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff81907b90-ffffffff81907df8: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819b8870)
Location: net/ipv4/ip_input.c:575
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff819b8870-ffffffff819b8ad8: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip_sublist_rcv(struct list_head *head, struct net_device *dev, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819c20d0)
Location: net/ipv4/ip_input.c:575
Inline: False
Direct callers:
  - net/ipv4/ip_input.c:ip_list_rcv
  - net/ipv4/ip_input.c:ip_list_rcv
```
**Symbols:**

```
ffffffff819c20d0-ffffffff819c2360: ip_sublist_rcv (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
