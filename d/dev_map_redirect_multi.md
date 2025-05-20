# Function: <code>dev_map_redirect_multi</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_map_redirect_multi(struct net_device *dev, struct sk_buff *skb, struct bpf_prog *xdp_prog, struct bpf_map *map, bool exclude_ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126cd40)
Location: kernel/bpf/devmap.c:710
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff8126cd40-ffffffff8126cfd8: dev_map_redirect_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_map_redirect_multi(struct net_device *dev, struct sk_buff *skb, struct bpf_prog *xdp_prog, struct bpf_map *map, bool exclude_ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812bba70)
Location: kernel/bpf/devmap.c:701
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff812bba70-ffffffff812bbd40: dev_map_redirect_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_map_redirect_multi(struct net_device *dev, struct sk_buff *skb, struct bpf_prog *xdp_prog, struct bpf_map *map, bool exclude_ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131ee10)
Location: kernel/bpf/devmap.c:701
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff8131ee10-ffffffff8131f0e0: dev_map_redirect_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_map_redirect_multi(struct net_device *dev, struct sk_buff *skb, struct bpf_prog *xdp_prog, struct bpf_map *map, bool exclude_ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134ec30)
Location: kernel/bpf/devmap.c:708
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff8134ec30-ffffffff8134eefd: dev_map_redirect_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_map_redirect_multi(struct net_device *dev, struct sk_buff *skb, struct bpf_prog *xdp_prog, struct bpf_map *map, bool exclude_ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81376130)
Location: kernel/bpf/devmap.c:717
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81376130-ffffffff813763fd: dev_map_redirect_multi (STB_GLOBAL)
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
