# Function: <code>__find_good_pkt_pointers</code>

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
In kernel/bpf/verifier.c (ffffffff811d68b9)
Location: kernel/bpf/verifier.c:5079
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
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
In kernel/bpf/verifier.c (ffffffff811e2f99)
Location: kernel/bpf/verifier.c:5089
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __find_good_pkt_pointers(struct bpf_func_state *state, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, u16 new_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81201f50)
Location: kernel/bpf/verifier.c:6160
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
```
**Symbols:**

```
ffffffff81201f50-ffffffff8120202d: __find_good_pkt_pointers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __find_good_pkt_pointers(struct bpf_func_state *state, struct bpf_reg_state *dst_reg, enum bpf_reg_type type, int new_range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812019e0)
Location: kernel/bpf/verifier.c:6764
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
```
**Symbols:**

```
ffffffff812019e0-ffffffff81201ab7: __find_good_pkt_pointers (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81202a64)
Location: kernel/bpf/verifier.c:7927
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
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
In kernel/bpf/verifier.c (ffffffff81234aa7)
Location: kernel/bpf/verifier.c:8220
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
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
In kernel/bpf/verifier.c (ffffffff8127833c)
Location: kernel/bpf/verifier.c:9208
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010266ec4)
Location: kernel/bpf/verifier.c:5089
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
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
In kernel/bpf/verifier.c (c04982f8)
Location: kernel/bpf/verifier.c:5089
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
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
In kernel/bpf/verifier.c (c00000000030c3f4)
Location: kernel/bpf/verifier.c:5089
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
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
In kernel/bpf/verifier.c (ffffffe0001a237a)
Location: kernel/bpf/verifier.c:5089
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
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
In kernel/bpf/verifier.c (ffffffff811db5b9)
Location: kernel/bpf/verifier.c:5089
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
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
In kernel/bpf/verifier.c (ffffffff811ce379)
Location: kernel/bpf/verifier.c:5089
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
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
In kernel/bpf/verifier.c (ffffffff811d9389)
Location: kernel/bpf/verifier.c:5089
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
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
In kernel/bpf/verifier.c (ffffffff811e7799)
Location: kernel/bpf/verifier.c:5089
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:find_good_pkt_pointers
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u16 new_range</code> ➡️ <code>int new_range</code>
</li>
</ul>
</details>
</li>
</ul>
