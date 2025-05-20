# Function: <code>mark_map_reg</code>

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
In kernel/bpf/verifier.c (ffffffff8118df89)
Location: kernel/bpf/verifier.c:1971
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_map_regs
  - kernel/bpf/verifier.c:mark_map_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mark_map_reg(struct bpf_reg_state *regs, u32 regno, u32 id, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81193b80)
Location: kernel/bpf/verifier.c:2384
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_map_regs
  - kernel/bpf/verifier.c:mark_map_regs
```
**Symbols:**

```
ffffffff81193b80-ffffffff81193be1: mark_map_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mark_map_reg(struct bpf_reg_state *regs, u32 regno, u32 id, bool is_null);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a1780)
Location: kernel/bpf/verifier.c:2835
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_map_regs
  - kernel/bpf/verifier.c:mark_map_regs
```
**Symbols:**

```
ffffffff811a1780-ffffffff811a1853: mark_map_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mark_map_reg(struct bpf_reg_state *regs, u32 regno, u32 id, bool is_null);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b6950)
Location: kernel/bpf/verifier.c:3626
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_map_regs
  - kernel/bpf/verifier.c:mark_map_regs
```
**Symbols:**

```
ffffffff811b6950-ffffffff811b6a1f: mark_map_reg (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_null</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_reg_type type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
