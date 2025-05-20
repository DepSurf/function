# Function: <code>btf_check_sec_info</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c89f1)
Location: kernel/bpf/btf.c:2017
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (ffffffff811dca4a)
Location: kernel/bpf/btf.c:2674
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (ffffffff811ef756)
Location: kernel/bpf/btf.c:3164
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (ffffffff811fbe76)
Location: kernel/bpf/btf.c:3163
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int btf_check_sec_info(struct btf_verifier_env *env, u32 btf_data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812209a0)
Location: kernel/bpf/btf.c:3273
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
```
**Symbols:**

```
ffffffff812209a0-ffffffff81220aa3: btf_check_sec_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int btf_check_sec_info(struct btf_verifier_env *env, u32 btf_data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812238b0)
Location: kernel/bpf/btf.c:4064
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
```
**Symbols:**

```
ffffffff812238b0-ffffffff812239b3: btf_check_sec_info (STB_LOCAL)
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
In kernel/bpf/btf.c (ffffffff81228588)
Location: kernel/bpf/btf.c:4137
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (ffffffff81260858)
Location: kernel/bpf/btf.c:4186
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (ffffffff812ab86a)
Location: kernel/bpf/btf.c:4687
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (ffffffff8130b27a)
Location: kernel/bpf/btf.c:5118
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (ffffffff81339b6b)
Location: kernel/bpf/btf.c:5188
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (ffffffff8135fc9b)
Location: kernel/bpf/btf.c:5196
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (ffff80001028233c)
Location: kernel/bpf/btf.c:3163
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (c04b1fa0)
Location: kernel/bpf/btf.c:3163
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (c00000000032c988)
Location: kernel/bpf/btf.c:3163
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (ffffffe0001b843a)
Location: kernel/bpf/btf.c:3163
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (ffffffff811f4496)
Location: kernel/bpf/btf.c:3163
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (ffffffff811e71e6)
Location: kernel/bpf/btf.c:3163
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (ffffffff811f2266)
Location: kernel/bpf/btf.c:3163
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
In kernel/bpf/btf.c (ffffffff81200776)
Location: kernel/bpf/btf.c:3163
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
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
</ul>
