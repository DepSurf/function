# Function: <code>bpf_out_neigh_v6</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2168
Inline: True
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
**Symbols:**

```
ffffffff81a2e8d0-ffffffff81a2ebfe: bpf_out_neigh_v6.constprop.0 (STB_LOCAL)
ffffffff81c3176d-ffffffff81c3177e: bpf_out_neigh_v6.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2165
Inline: True
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
**Symbols:**

```
ffffffff81a15f20-ffffffff81a16254: bpf_out_neigh_v6.constprop.0 (STB_LOCAL)
ffffffff81c23a76-ffffffff81c23a87: bpf_out_neigh_v6.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_out_neigh_v6(struct net *net, struct sk_buff *skb, struct net_device *dev, struct bpf_nh_params *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2166
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
**Symbols:**

```
ffffffff81ac7580-ffffffff81ac7996: bpf_out_neigh_v6 (STB_LOCAL)
ffffffff81d370a8-ffffffff81d370eb: bpf_out_neigh_v6.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_out_neigh_v6(struct net *net, struct sk_buff *skb, struct net_device *dev, struct bpf_nh_params *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2167
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
**Symbols:**

```
ffffffff81c43e00-ffffffff81c44135: bpf_out_neigh_v6 (STB_LOCAL)
ffffffff81f03a10-ffffffff81f03a4a: bpf_out_neigh_v6.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_out_neigh_v6(struct net *net, struct sk_buff *skb, struct net_device *dev, struct bpf_nh_params *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2174
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
**Symbols:**

```
ffffffff81df8150-ffffffff81df8496: bpf_out_neigh_v6 (STB_LOCAL)
ffffffff820ac0af-ffffffff820ac0d8: bpf_out_neigh_v6.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_out_neigh_v6(struct net *net, struct sk_buff *skb, struct net_device *dev, struct bpf_nh_params *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2186
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
**Symbols:**

```
ffffffff81e697c0-ffffffff81e69b05: bpf_out_neigh_v6 (STB_LOCAL)
ffffffff8212d800-ffffffff8212d829: bpf_out_neigh_v6.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_out_neigh_v6(struct net *net, struct sk_buff *skb, struct net_device *dev, struct bpf_nh_params *nh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:2193
Inline: False
Direct callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
**Symbols:**

```
ffffffff81f28e30-ffffffff81f2916f: bpf_out_neigh_v6 (STB_LOCAL)
ffffffff8220f545-ffffffff8220f56e: bpf_out_neigh_v6.cold (STB_LOCAL)
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
