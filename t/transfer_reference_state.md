# Function: <code>transfer_reference_state</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int transfer_reference_state(struct bpf_func_state *dst, struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c6aa0)
Location: kernel/bpf/verifier.c:649
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811c6aa0-ffffffff811c6add: transfer_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int transfer_reference_state(struct bpf_func_state *dst, struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d8c80)
Location: kernel/bpf/verifier.c:655
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811d8c80-ffffffff811d8cbd: transfer_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int transfer_reference_state(struct bpf_func_state *dst, struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e5370)
Location: kernel/bpf/verifier.c:655
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811e5370-ffffffff811e53ad: transfer_reference_state (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff8120cf1b)
Location: kernel/bpf/verifier.c:782
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_func_call
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
In kernel/bpf/verifier.c (ffffffff8120b1bb)
Location: kernel/bpf/verifier.c:808
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_func_call
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
In kernel/bpf/verifier.c (ffffffff81210466)
Location: kernel/bpf/verifier.c:857
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int transfer_reference_state(struct bpf_func_state *dst, struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010268618)
Location: kernel/bpf/verifier.c:655
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffff800010268618-ffff800010268668: transfer_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int transfer_reference_state(struct bpf_func_state *dst, struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049aa7c)
Location: kernel/bpf/verifier.c:655
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
c049aa7c-c049aabc: transfer_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int transfer_reference_state(struct bpf_func_state *dst, struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030e260)
Location: kernel/bpf/verifier.c:655
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
c00000000030e260-c00000000030e2e4: transfer_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int transfer_reference_state(struct bpf_func_state *dst, struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a382a)
Location: kernel/bpf/verifier.c:655
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffe0001a382a-ffffffe0001a387a: transfer_reference_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int transfer_reference_state(struct bpf_func_state *dst, struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dd990)
Location: kernel/bpf/verifier.c:655
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811dd990-ffffffff811dd9cd: transfer_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int transfer_reference_state(struct bpf_func_state *dst, struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d0750)
Location: kernel/bpf/verifier.c:655
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811d0750-ffffffff811d078d: transfer_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int transfer_reference_state(struct bpf_func_state *dst, struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db760)
Location: kernel/bpf/verifier.c:655
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811db760-ffffffff811db79d: transfer_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int transfer_reference_state(struct bpf_func_state *dst, struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e9b70)
Location: kernel/bpf/verifier.c:655
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811e9b70-ffffffff811e9bad: transfer_reference_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
