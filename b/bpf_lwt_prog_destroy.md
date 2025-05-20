# Function: <code>bpf_lwt_prog_destroy</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bpf_lwt_prog_destroy(struct bpf_lwt_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817d9b10)
Location: net/core/lwt_bpf.c:181
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
```
**Symbols:**

```
ffffffff817d9b10-ffffffff817d9b36: bpf_lwt_prog_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_lwt_prog_destroy(struct bpf_lwt_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817f8d50)
Location: net/core/lwt_bpf.c:181
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
```
**Symbols:**

```
ffffffff817f8d50-ffffffff817f8d76: bpf_lwt_prog_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_lwt_prog_destroy(struct bpf_lwt_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81876630)
Location: net/core/lwt_bpf.c:181
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
```
**Symbols:**

```
ffffffff81876630-ffffffff81876656: bpf_lwt_prog_destroy (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff818c7d61)
Location: net/core/lwt_bpf.c:181
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff818f0ec1)
Location: net/core/lwt_bpf.c:180
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff81942891)
Location: net/core/lwt_bpf.c:307
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff819777e1)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff81a4d065)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff81a52d25)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff81a38525)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff81aee395)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff81c71255)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff81e292f5)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff81e9e925)
Location: net/core/lwt_bpf.c:309
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff81f61095)
Location: net/core/lwt_bpf.c:309
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffff800010c1e3bc)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_lwt_prog_destroy(struct bpf_lwt_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c0d35f40)
Location: net/core/lwt_bpf.c:310
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
```
**Symbols:**

```
c0d35f40-c0d35f74: bpf_lwt_prog_destroy (STB_LOCAL)
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
In net/core/lwt_bpf.c (c000000000d0fb38)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffe000797cf6)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff81917651)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff818d1401)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff819687e1)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
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
In net/core/lwt_bpf.c (ffffffff8198ab91)
Location: net/core/lwt_bpf.c:310
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
  - net/core/lwt_bpf.c:bpf_destroy_state
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
