# Function: <code>btf_verifier_log_hdr</code>

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
In kernel/bpf/btf.c (ffffffff811c89b6)
Location: kernel/bpf/btf.c:566
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
In kernel/bpf/btf.c (ffffffff811dc927)
Location: kernel/bpf/btf.c:694
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
In kernel/bpf/btf.c (ffffffff811ef6f9)
Location: kernel/bpf/btf.c:795
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
In kernel/bpf/btf.c (ffffffff811fbe19)
Location: kernel/bpf/btf.c:795
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
void btf_verifier_log_hdr(struct btf_verifier_env *env, u32 btf_data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81220da0)
Location: kernel/bpf/btf.c:821
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
```
**Symbols:**

```
ffffffff81220da0-ffffffff81220ea2: btf_verifier_log_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void btf_verifier_log_hdr(struct btf_verifier_env *env, u32 btf_data_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223cc0)
Location: kernel/bpf/btf.c:1406
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_hdr
```
**Symbols:**

```
ffffffff81223cc0-ffffffff81223dca: btf_verifier_log_hdr (STB_LOCAL)
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
In kernel/bpf/btf.c (ffffffff81228459)
Location: kernel/bpf/btf.c:1407
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
In kernel/bpf/btf.c (ffffffff81260729)
Location: kernel/bpf/btf.c:1407
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
In kernel/bpf/btf.c (ffffffff812ab738)
Location: kernel/bpf/btf.c:1502
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
In kernel/bpf/btf.c (ffffffff8130b148)
Location: kernel/bpf/btf.c:1505
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
In kernel/bpf/btf.c (ffffffff81339a68)
Location: kernel/bpf/btf.c:1537
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
In kernel/bpf/btf.c (ffffffff8135fb98)
Location: kernel/bpf/btf.c:1538
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
In kernel/bpf/btf.c (ffff800010282300)
Location: kernel/bpf/btf.c:795
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
In kernel/bpf/btf.c (c04b1f60)
Location: kernel/bpf/btf.c:795
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
In kernel/bpf/btf.c (c00000000032c938)
Location: kernel/bpf/btf.c:795
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
In kernel/bpf/btf.c (ffffffe0001b840c)
Location: kernel/bpf/btf.c:795
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
In kernel/bpf/btf.c (ffffffff811f4439)
Location: kernel/bpf/btf.c:795
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
In kernel/bpf/btf.c (ffffffff811e7189)
Location: kernel/bpf/btf.c:795
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
In kernel/bpf/btf.c (ffffffff811f2209)
Location: kernel/bpf/btf.c:795
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
In kernel/bpf/btf.c (ffffffff81200719)
Location: kernel/bpf/btf.c:795
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
