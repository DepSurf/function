# Function: <code>bpf_push_ip_encap</code>

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
In net/core/filter.c (ffffffff81924699)
Location: net/core/filter.c:4948
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff819569a9)
Location: net/core/filter.c:4957
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff81a2a4e9)
Location: net/core/filter.c:5084
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff81a2b029)
Location: net/core/filter.c:5636
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff81a12339)
Location: net/core/filter.c:5738
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff81ac3009)
Location: net/core/filter.c:5862
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff81c3dd58)
Location: net/core/filter.c:6170
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff81df1eb8)
Location: net/core/filter.c:6184
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff81e63e48)
Location: net/core/filter.c:6263
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff81f23028)
Location: net/core/filter.c:6353
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffff800010bf82b4)
Location: net/core/filter.c:4957
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (c0d11d3c)
Location: net/core/filter.c:4957
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (c000000000cded2c)
Location: net/core/filter.c:4957
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffe000779f6c)
Location: net/core/filter.c:4957
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff818f6979)
Location: net/core/filter.c:4957
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff818b07a9)
Location: net/core/filter.c:4957
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff819479a9)
Location: net/core/filter.c:4957
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
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
In net/core/filter.c (ffffffff819692b9)
Location: net/core/filter.c:4957
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
</details>
</li>
</ul>

## Differences
