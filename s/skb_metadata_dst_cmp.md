# Function: <code>skb_metadata_dst_cmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171b29f)
Location: include/net/dst_metadata.h:47
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81783b2e)
Location: include/net/dst_metadata.h:47
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b1091)
Location: include/net/dst_metadata.h:47
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d142d)
Location: include/net/dst_metadata.h:59
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184b548)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (ffffffff8189590f)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (ffffffff818b75e0)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (ffffffff81903415)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (ffffffff819361c5)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a009bb)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a00dcb)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
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
In net/core/dev.c (ffffffff819e7579)
Location: include/net/dst_metadata.h:63
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
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
In net/core/dev.c (ffffffff81a98492)
Location: include/net/dst_metadata.h:63
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
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
In net/core/gro.c (ffffffff81c53c56)
Location: include/net/dst_metadata.h:63
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/gro.c (ffffffff81e08f70)
Location: include/net/dst_metadata.h:99
Inline: True
Direct callers:
  - net/core/gro.c:gro_list_prepare
```
**Symbols:**

```
ffffffff81e08f70-ffffffff81e0902a: skb_metadata_dst_cmp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/gro.c (ffffffff81e7b840)
Location: include/net/dst_metadata.h:99
Inline: True
Direct callers:
  - net/core/gro.c:gro_list_prepare
```
**Symbols:**

```
ffffffff81e7b840-ffffffff81e7b912: skb_metadata_dst_cmp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/gro.c (ffffffff81f3bac0)
Location: include/net/dst_metadata.h:99
Inline: True
Direct callers:
  - net/core/gro.c:gro_list_prepare
```
**Symbols:**

```
ffffffff81f3bac0-ffffffff81f3bb92: skb_metadata_dst_cmp.isra.0 (STB_LOCAL)
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
In net/core/dev.c (ffff800010bd4840)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (c0ceedf8)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (c000000000cb3920)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (ffffffe00075e656)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (ffffffff818d6195)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (ffffffff8188ffd5)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (ffffffff819271c5)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
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
In net/core/dev.c (ffffffff8194882f)
Location: include/net/dst_metadata.h:61
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
</details>
</li>
</ul>

## Differences
