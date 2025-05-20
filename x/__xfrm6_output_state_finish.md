# Function: <code>__xfrm6_output_state_finish</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff81a47560)
Location: net/ipv6/xfrm6_output.c:121
Inline: True
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
```
**Symbols:**

```
ffffffff81a47560-ffffffff81a475a8: __xfrm6_output_state_finish.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff81a7e110)
Location: net/ipv6/xfrm6_output.c:121
Inline: True
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
```
**Symbols:**

```
ffffffff81a7e110-ffffffff81a7e158: __xfrm6_output_state_finish.isra.0 (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffff800010d49500)
Location: net/ipv6/xfrm6_output.c:121
Inline: True
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
```
**Symbols:**

```
ffff800010d49500-ffff800010d4956c: __xfrm6_output_state_finish.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __xfrm6_output_state_finish(struct xfrm_state *x, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_output.c (c0e4a8f8)
Location: net/ipv6/xfrm6_output.c:121
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
```
**Symbols:**

```
c0e4a8f8-c0e4a948: __xfrm6_output_state_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __xfrm6_output_state_finish(struct xfrm_state *x, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_output.c (c000000000e7eac0)
Location: net/ipv6/xfrm6_output.c:121
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
```
**Symbols:**

```
c000000000e7eac0-c000000000e7eb54: __xfrm6_output_state_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __xfrm6_output_state_finish(struct xfrm_state *x, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffe000882988)
Location: net/ipv6/xfrm6_output.c:121
Inline: False
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
```
**Symbols:**

```
ffffffe000882988-ffffffe0008829e6: __xfrm6_output_state_finish (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff81a1d7a0)
Location: net/ipv6/xfrm6_output.c:121
Inline: True
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
```
**Symbols:**

```
ffffffff81a1d7a0-ffffffff81a1d7e8: __xfrm6_output_state_finish.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff819da560)
Location: net/ipv6/xfrm6_output.c:121
Inline: True
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
```
**Symbols:**

```
ffffffff819da560-ffffffff819da5a8: __xfrm6_output_state_finish.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff81a88220)
Location: net/ipv6/xfrm6_output.c:121
Inline: True
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
```
**Symbols:**

```
ffffffff81a88220-ffffffff81a88268: __xfrm6_output_state_finish.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff81a94e50)
Location: net/ipv6/xfrm6_output.c:121
Inline: True
Direct callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:__xfrm6_output_finish
```
**Symbols:**

```
ffffffff81a94e50-ffffffff81a94eb7: __xfrm6_output_state_finish.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
