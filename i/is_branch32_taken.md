# Function: <code>is_branch32_taken</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int is_branch32_taken(struct bpf_reg_state *reg, u32 val, u8 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202680)
Location: kernel/bpf/verifier.c:6258
Inline: False
```
**Symbols:**

```
ffffffff81202680-ffffffff81202850: is_branch32_taken (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int is_branch32_taken(struct bpf_reg_state *reg, u32 val, u8 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202380)
Location: kernel/bpf/verifier.c:6861
Inline: False
```
**Symbols:**

```
ffffffff81202380-ffffffff8120255e: is_branch32_taken (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int is_branch32_taken(struct bpf_reg_state *reg, u32 val, u8 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812031a0)
Location: kernel/bpf/verifier.c:8024
Inline: False
```
**Symbols:**

```
ffffffff812031a0-ffffffff8120337e: is_branch32_taken (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int is_branch32_taken(struct bpf_reg_state *reg, u32 val, u8 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812351f0)
Location: kernel/bpf/verifier.c:8317
Inline: False
```
**Symbols:**

```
ffffffff812351f0-ffffffff812353ce: is_branch32_taken (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int is_branch32_taken(struct bpf_reg_state *reg, u32 val, u8 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81278f90)
Location: kernel/bpf/verifier.c:9305
Inline: False
```
**Symbols:**

```
ffffffff81278f90-ffffffff81279179: is_branch32_taken (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int is_branch32_taken(struct bpf_reg_state *reg, u32 val, u8 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812cf340)
Location: kernel/bpf/verifier.c:11228
Inline: False
```
**Symbols:**

```
ffffffff812cf340-ffffffff812cf529: is_branch32_taken (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int is_branch32_taken(struct bpf_reg_state *reg, u32 val, u8 opcode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f78b0)
Location: kernel/bpf/verifier.c:13151
Inline: False
```
**Symbols:**

```
ffffffff812f78b0-ffffffff812f7ab2: is_branch32_taken (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
