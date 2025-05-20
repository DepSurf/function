# Function: <code>xfrm4_remove_beet_encap</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff819f4c65)
Location: net/xfrm/xfrm_input.c:171
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff81a2b915)
Location: net/xfrm/xfrm_input.c:171
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm4_remove_beet_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1dad0)
Location: net/xfrm/xfrm_input.c:172
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81b1dad0-ffffffff81b1dcb5: xfrm4_remove_beet_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm4_remove_beet_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b2c3a0)
Location: net/xfrm/xfrm_input.c:174
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81b2c3a0-ffffffff81b2c585: xfrm4_remove_beet_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm4_remove_beet_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1a000)
Location: net/xfrm/xfrm_input.c:174
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81b1a000-ffffffff81b1a1e5: xfrm4_remove_beet_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xfrm4_remove_beet_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81bde620)
Location: net/xfrm/xfrm_input.c:174
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81bde620-ffffffff81bde805: xfrm4_remove_beet_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xfrm4_remove_beet_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81d75460)
Location: net/xfrm/xfrm_input.c:174
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81d75460-ffffffff81d75651: xfrm4_remove_beet_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xfrm4_remove_beet_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81f41a70)
Location: net/xfrm/xfrm_input.c:176
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81f41a70-ffffffff81f41c61: xfrm4_remove_beet_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xfrm4_remove_beet_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81fa1300)
Location: net/xfrm/xfrm_input.c:177
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81fa1300-ffffffff81fa14fd: xfrm4_remove_beet_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xfrm4_remove_beet_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8206e620)
Location: net/xfrm/xfrm_input.c:177
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff8206e620-ffffffff8206e81d: xfrm4_remove_beet_encap (STB_LOCAL)
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
In net/xfrm/xfrm_input.c (ffff800010cea398)
Location: net/xfrm/xfrm_input.c:171
Inline: True
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
In net/xfrm/xfrm_input.c (c0df24d8)
Location: net/xfrm/xfrm_input.c:171
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
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
In net/xfrm/xfrm_input.c (c000000000e0df44)
Location: net/xfrm/xfrm_input.c:171
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffe000837fe2)
Location: net/xfrm/xfrm_input.c:171
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff819cafa5)
Location: net/xfrm/xfrm_input.c:171
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff81987d95)
Location: net/xfrm/xfrm_input.c:171
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff81a35a25)
Location: net/xfrm/xfrm_input.c:171
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff81a41395)
Location: net/xfrm/xfrm_input.c:171
Inline: True
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
