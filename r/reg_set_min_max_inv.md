# Function: <code>reg_set_min_max_inv</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81191144)
Location: kernel/bpf/verifier.c:1925
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
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
In kernel/bpf/verifier.c (ffffffff81198272)
Location: kernel/bpf/verifier.c:2307
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
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
In kernel/bpf/verifier.c (ffffffff811a542d)
Location: kernel/bpf/verifier.c:2719
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
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
In kernel/bpf/verifier.c (ffffffff811bbe3d)
Location: kernel/bpf/verifier.c:3510
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
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
In kernel/bpf/verifier.c (ffffffff811cc03a)
Location: kernel/bpf/verifier.c:4200
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void reg_set_min_max_inv(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d6e00)
Location: kernel/bpf/verifier.c:5445
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811d6e00-ffffffff811d71e7: reg_set_min_max_inv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void reg_set_min_max_inv(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3460)
Location: kernel/bpf/verifier.c:5455
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811e3460-ffffffff811e3847: reg_set_min_max_inv (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff8120d5fa)
Location: kernel/bpf/verifier.c:6593
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
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
In kernel/bpf/verifier.c (ffffffff8120bee1)
Location: kernel/bpf/verifier.c:7261
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
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
In kernel/bpf/verifier.c (ffffffff8120da04)
Location: kernel/bpf/verifier.c:8424
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
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
In kernel/bpf/verifier.c (ffffffff81241d5e)
Location: kernel/bpf/verifier.c:8717
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
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
In kernel/bpf/verifier.c (ffffffff81287326)
Location: kernel/bpf/verifier.c:9712
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
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
In kernel/bpf/verifier.c (ffffffff812e22df)
Location: kernel/bpf/verifier.c:11635
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
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
In kernel/bpf/verifier.c (ffffffff8130fbf1)
Location: kernel/bpf/verifier.c:13566
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
</details>
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
In kernel/bpf/verifier.c (ffff80001026e840)
Location: kernel/bpf/verifier.c:5455
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void reg_set_min_max_inv(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0498d48)
Location: kernel/bpf/verifier.c:5455
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
c0498d48-c04991ec: reg_set_min_max_inv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void reg_set_min_max_inv(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030b550)
Location: kernel/bpf/verifier.c:5455
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
c00000000030b550-c00000000030ba30: reg_set_min_max_inv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void reg_set_min_max_inv(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a1acc)
Location: kernel/bpf/verifier.c:5455
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffe0001a1acc-ffffffe0001a1e18: reg_set_min_max_inv (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void reg_set_min_max_inv(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dba80)
Location: kernel/bpf/verifier.c:5455
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811dba80-ffffffff811dbe67: reg_set_min_max_inv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void reg_set_min_max_inv(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ce840)
Location: kernel/bpf/verifier.c:5455
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811ce840-ffffffff811cec27: reg_set_min_max_inv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void reg_set_min_max_inv(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d9850)
Location: kernel/bpf/verifier.c:5455
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811d9850-ffffffff811d9c37: reg_set_min_max_inv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void reg_set_min_max_inv(struct bpf_reg_state *true_reg, struct bpf_reg_state *false_reg, u64 val, u8 opcode, bool is_jmp32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e7c60)
Location: kernel/bpf/verifier.c:5455
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
**Symbols:**

```
ffffffff811e7c60-ffffffff811e8047: reg_set_min_max_inv (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
