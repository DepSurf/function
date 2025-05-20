# Function: <code>sk_msg_compute_data_pointers</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d945d)
Location: include/linux/skmsg.h:226
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff818e5cb9)
Location: include/linux/skmsg.h:226
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192b5b2)
Location: include/linux/skmsg.h:226
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff819355d2)
Location: include/linux/skmsg.h:226
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff8195d8e5)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81968392)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff81a2caa9)
Location: include/linux/skmsg.h:231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a3bdd2)
Location: include/linux/skmsg.h:231
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff81a2e059)
Location: include/linux/skmsg.h:231
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a3feb2)
Location: include/linux/skmsg.h:231
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff81a14d1f)
Location: include/linux/skmsg.h:234
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a4e752)
Location: include/linux/skmsg.h:234
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff81ac83fb)
Location: include/linux/skmsg.h:233
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81b050ff)
Location: include/linux/skmsg.h:233
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff81c44935)
Location: include/linux/skmsg.h:227
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81c8d3e2)
Location: include/linux/skmsg.h:227
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff81dfeef1)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81e45a22)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff81e709c1)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81ea1032)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff81f3009c)
Location: include/linux/skmsg.h:235
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81f63712)
Location: include/linux/skmsg.h:235
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffff800010bfd9fc)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffff800010c0e2a4)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (c0d19eb4)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (c0d265e8)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (c000000000ce95f4)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (c000000000cf9b70)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffe00077d154)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffe00078ad10)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff818fd8b5)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81908362)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff818b76e5)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff818c2172)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff8194e8e5)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81959392)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
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
In net/core/filter.c (ffffffff819702b5)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff8197b4b5)
Location: include/linux/skmsg.h:229
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
```
</details>
</li>
</ul>

## Differences
