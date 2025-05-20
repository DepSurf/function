# Function: <code>xfrm6_beet_make_header</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff819f4ba8)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819f5e7c)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81a2b858)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2cafc)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1d6eb)
Location: net/xfrm/xfrm_inout.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f6d0)
Location: net/xfrm/xfrm_inout.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b2bf0d)
Location: net/xfrm/xfrm_inout.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2dfa0)
Location: net/xfrm/xfrm_inout.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_beet_encap_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b19b7b)
Location: net/xfrm/xfrm_inout.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b81b)
Location: net/xfrm/xfrm_inout.h:41
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81bdde4b)
Location: net/xfrm/xfrm_inout.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81bdfa8b)
Location: net/xfrm/xfrm_inout.h:41
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81d74fb2)
Location: net/xfrm/xfrm_inout.h:41
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/xfrm/xfrm_output.c (ffffffff81d7694b)
Location: net/xfrm/xfrm_inout.h:41
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
void xfrm6_beet_make_header(struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81f416c0)
Location: net/xfrm/xfrm_inout.h:41
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f430a0)
Location: net/xfrm/xfrm_inout.h:41
Inline: False
```
**Symbols:**

```
ffffffff81f416c0-ffffffff81f41718: xfrm6_beet_make_header (STB_LOCAL)
ffffffff81f430a0-ffffffff81f430f8: xfrm6_beet_make_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
void xfrm6_beet_make_header(struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81fa0f60)
Location: net/xfrm/xfrm_inout.h:41
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa28c0)
Location: net/xfrm/xfrm_inout.h:41
Inline: False
```
**Symbols:**

```
ffffffff81fa0f60-ffffffff81fa0fb8: xfrm6_beet_make_header (STB_LOCAL)
ffffffff81fa28c0-ffffffff81fa2918: xfrm6_beet_make_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
void xfrm6_beet_make_header(struct sk_buff *skb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8206e2c0)
Location: net/xfrm/xfrm_inout.h:41
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8206fbc0)
Location: net/xfrm/xfrm_inout.h:41
Inline: False
```
**Symbols:**

```
ffffffff8206e2c0-ffffffff8206e318: xfrm6_beet_make_header (STB_LOCAL)
ffffffff8206fbc0-ffffffff8206fc18: xfrm6_beet_make_header (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffff800010cea2e0)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb770)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (c0df26ac)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_output.c (c0df3650)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (c000000000e0dddc)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
```
```
In net/xfrm/xfrm_output.c (c000000000e0f774)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffe000837f14)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffe0008390e8)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff819caee8)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc18c)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81987cd8)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81988f7c)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81a35968)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36c0c)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81a412d3)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4259c)
Location: net/xfrm/xfrm_inout.h:9
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
