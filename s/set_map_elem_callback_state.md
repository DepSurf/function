# Function: <code>set_map_elem_callback_state</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_map_elem_callback_state(struct bpf_verifier_env *env, struct bpf_func_state *caller, struct bpf_func_state *callee, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120c640)
Location: kernel/bpf/verifier.c:5696
Inline: False
```
**Symbols:**

```
ffffffff8120c640-ffffffff8120c6d4: set_map_elem_callback_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_map_elem_callback_state(struct bpf_verifier_env *env, struct bpf_func_state *caller, struct bpf_func_state *callee, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81240630)
Location: kernel/bpf/verifier.c:5919
Inline: False
```
**Symbols:**

```
ffffffff81240630-ffffffff812406c4: set_map_elem_callback_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_map_elem_callback_state(struct bpf_verifier_env *env, struct bpf_func_state *caller, struct bpf_func_state *callee, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81285ae0)
Location: kernel/bpf/verifier.c:6773
Inline: False
```
**Symbols:**

```
ffffffff81285ae0-ffffffff81285b80: set_map_elem_callback_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_map_elem_callback_state(struct bpf_verifier_env *env, struct bpf_func_state *caller, struct bpf_func_state *callee, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812dc990)
Location: kernel/bpf/verifier.c:7499
Inline: False
```
**Symbols:**

```
ffffffff812dc990-ffffffff812dca4c: set_map_elem_callback_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_map_elem_callback_state(struct bpf_verifier_env *env, struct bpf_func_state *caller, struct bpf_func_state *callee, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f7760)
Location: kernel/bpf/verifier.c:8878
Inline: False
```
**Symbols:**

```
ffffffff812f7760-ffffffff812f781c: set_map_elem_callback_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_map_elem_callback_state(struct bpf_verifier_env *env, struct bpf_func_state *caller, struct bpf_func_state *callee, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81315a00)
Location: kernel/bpf/verifier.c:9524
Inline: False
```
**Symbols:**

```
ffffffff81315a00-ffffffff81315aaa: set_map_elem_callback_state (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
