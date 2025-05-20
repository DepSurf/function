# Function: <code>xdp_do_generic_redirect_map</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xdp_do_generic_redirect_map(struct net_device *dev, struct sk_buff *skb, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81868470)
Location: net/core/filter.c:2689
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81868470-ffffffff8186864d: xdp_do_generic_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b50d0)
Location: net/core/filter.c:3315
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d9c5a)
Location: net/core/filter.c:3514
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819278ba)
Location: net/core/filter.c:3643
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195ab4a)
Location: net/core/filter.c:3649
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xdp_do_generic_redirect_map(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog, struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2e7a0)
Location: net/core/filter.c:3609
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81a2e7a0-ffffffff81a2e93f: xdp_do_generic_redirect_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xdp_do_generic_redirect_map(struct net_device *dev, struct sk_buff *skb, struct xdp_buff *xdp, struct bpf_prog *xdp_prog, struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2fbb0)
Location: net/core/filter.c:4016
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81a2fbb0-ffffffff81a2fd06: xdp_do_generic_redirect_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a1bbf0)
Location: net/core/filter.c:3976
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acf360)
Location: net/core/filter.c:4022
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4cabd)
Location: net/core/filter.c:4303
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e018ff)
Location: net/core/filter.c:4317
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e73bd2)
Location: net/core/filter.c:4368
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f3338f)
Location: net/core/filter.c:4442
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c01c44)
Location: net/core/filter.c:3649
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d157d8)
Location: net/core/filter.c:3649
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce483c)
Location: net/core/filter.c:3649
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077dcea)
Location: net/core/filter.c:3649
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fab1a)
Location: net/core/filter.c:3649
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b494a)
Location: net/core/filter.c:3649
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194bb4a)
Location: net/core/filter.c:3649
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196d45a)
Location: net/core/filter.c:3649
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
