# Function: <code>__bpf_redirect_neigh</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __bpf_redirect_neigh(struct sk_buff *skb, struct net_device *dev, struct bpf_nh_params *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a30fb0)
Location: net/core/filter.c:2388
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
```
**Symbols:**

```
ffffffff81a30fb0-ffffffff81a31284: __bpf_redirect_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __bpf_redirect_neigh(struct sk_buff *skb, struct net_device *dev, struct bpf_nh_params *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a17ff0)
Location: net/core/filter.c:2385
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
```
**Symbols:**

```
ffffffff81a17ff0-ffffffff81a182c4: __bpf_redirect_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __bpf_redirect_neigh(struct sk_buff *skb, struct net_device *dev, struct bpf_nh_params *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acb700)
Location: net/core/filter.c:2369
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
```
**Symbols:**

```
ffffffff81acb700-ffffffff81acba2a: __bpf_redirect_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __bpf_redirect_neigh(struct sk_buff *skb, struct net_device *dev, struct bpf_nh_params *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c47320)
Location: net/core/filter.c:2370
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
```
**Symbols:**

```
ffffffff81c47320-ffffffff81c47679: __bpf_redirect_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __bpf_redirect_neigh(struct sk_buff *skb, struct net_device *dev, struct bpf_nh_params *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfb880)
Location: net/core/filter.c:2377
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
```
**Symbols:**

```
ffffffff81dfb880-ffffffff81dfbbd9: __bpf_redirect_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __bpf_redirect_neigh(struct sk_buff *skb, struct net_device *dev, struct bpf_nh_params *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6c780)
Location: net/core/filter.c:2393
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
```
**Symbols:**

```
ffffffff81e6c780-ffffffff81e6cadc: __bpf_redirect_neigh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __bpf_redirect_neigh(struct sk_buff *skb, struct net_device *dev, struct bpf_nh_params *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2c060)
Location: net/core/filter.c:2400
Inline: False
Direct callers:
  - net/core/filter.c:skb_do_redirect
```
**Symbols:**

```
ffffffff81f2c060-ffffffff81f2c3b6: __bpf_redirect_neigh (STB_LOCAL)
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
