# Function: <code>bpf_skc_lookup</code>

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
In net/core/filter.c (ffffffff81927415)
Location: net/core/filter.c:5310
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (ffffffff81959ad5)
Location: net/core/filter.c:5318
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (ffffffff81a2e455)
Location: net/core/filter.c:5445
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
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
In net/core/filter.c (ffffffff81a2f9c9)
Location: net/core/filter.c:5997
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
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
In net/core/filter.c (ffffffff81a16aa9)
Location: net/core/filter.c:6099
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
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
In net/core/filter.c (ffffffff81acbe29)
Location: net/core/filter.c:6223
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
  - net/core/filter.c:bpf_skc_lookup_tcp
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
In net/core/filter.c (ffffffff81c45809)
Location: net/core/filter.c:6542
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (ffffffff81df99a9)
Location: net/core/filter.c:6554
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (ffffffff81e6b3b9)
Location: net/core/filter.c:6635
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (ffffffff81f2a349)
Location: net/core/filter.c:6725
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (ffff800010bfb2f8)
Location: net/core/filter.c:5318
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (c0d152f0)
Location: net/core/filter.c:5318
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (c000000000ce36b8)
Location: net/core/filter.c:5318
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (ffffffe00077cc6a)
Location: net/core/filter.c:5318
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (ffffffff818f9aa5)
Location: net/core/filter.c:5318
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (ffffffff818b38d5)
Location: net/core/filter.c:5318
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (ffffffff8194aad5)
Location: net/core/filter.c:5318
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
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
In net/core/filter.c (ffffffff8196c3e5)
Location: net/core/filter.c:5318
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skc_lookup_tcp
  - net/core/filter.c:bpf_sk_lookup
```
</details>
</li>
</ul>

## Differences
