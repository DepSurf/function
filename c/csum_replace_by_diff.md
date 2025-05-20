# Function: <code>csum_replace_by_diff</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179c884)
Location: include/net/checksum.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff817cbb24)
Location: include/net/checksum.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff817eac04)
Location: include/net/checksum.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff81866e10)
Location: include/net/checksum.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff818b67b1)
Location: include/net/checksum.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff818db9c3)
Location: include/net/checksum.h:123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff81928e55)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff8195b535)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff81a2f9c5)
Location: include/net/checksum.h:113
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff81a32295)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff81a193f5)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff81aca1a5)
Location: include/net/checksum.h:122
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/utils.c (ffffffff81c36357)
Location: include/net/checksum.h:124
Inline: True
```
```
In net/core/filter.c (ffffffff81c46d42)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81de9a37)
Location: include/net/checksum.h:124
Inline: True
```
```
In net/core/filter.c (ffffffff81dfb282)
Location: include/net/checksum.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81e5b246)
Location: include/net/checksum.h:126
Inline: True
```
```
In net/core/filter.c (ffffffff81e6cfdd)
Location: include/net/checksum.h:126
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81f1a606)
Location: include/net/checksum.h:126
Inline: True
```
```
In net/core/filter.c (ffffffff81f2c84d)
Location: include/net/checksum.h:126
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffff800010bfc524)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (c0d17320)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (c000000000ce4e68)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffe000779238)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff818fb505)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff818b5335)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff8194c535)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
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
In net/core/filter.c (ffffffff8196def5)
Location: include/net/checksum.h:119
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
</details>
</li>
</ul>

## Differences
