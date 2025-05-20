# Function: <code>verbose_invalid_scalar</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120ff00)
Location: kernel/bpf/verifier.c:406
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:prepare_func_exit
```
**Symbols:**

```
ffffffff8120ff00-ffffffff8120ffd9: verbose_invalid_scalar.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81244600)
Location: kernel/bpf/verifier.c:407
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:prepare_func_exit
```
**Symbols:**

```
ffffffff81244600-ffffffff812446d9: verbose_invalid_scalar.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8128a110)
Location: kernel/bpf/verifier.c:410
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:prepare_func_exit
```
**Symbols:**

```
ffffffff8128a110-ffffffff8128a1ff: verbose_invalid_scalar.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e2560)
Location: kernel/bpf/verifier.c:412
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:prepare_func_exit
```
**Symbols:**

```
ffffffff812e2560-ffffffff812e264f: verbose_invalid_scalar.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812faf30)
Location: kernel/bpf/verifier.c:408
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:prepare_func_exit
```
**Symbols:**

```
ffffffff812faf30-ffffffff812fb01f: verbose_invalid_scalar.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void verbose_invalid_scalar(struct bpf_verifier_env *env, struct bpf_reg_state *reg, struct bpf_retval_range range, const char *ctx, const char *reg_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81315c50)
Location: kernel/bpf/verifier.c:365
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:prepare_func_exit
```
**Symbols:**

```
ffffffff81315c50-ffffffff81315d0d: verbose_invalid_scalar (STB_LOCAL)
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
</ul>
