# Function: <code>is_ptr_cast_function</code>

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
In kernel/bpf/verifier.c (ffffffff811e20c5)
Location: kernel/bpf/verifier.c:376
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff811ee8d1)
Location: kernel/bpf/verifier.c:376
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff81211a42)
Location: kernel/bpf/verifier.c:475
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff8121265a)
Location: kernel/bpf/verifier.c:490
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:529
Inline: True
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
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:530
Inline: True
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
In kernel/bpf/verifier.c (ffffffff81291e2a)
Location: kernel/bpf/verifier.c:509
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool is_ptr_cast_function(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812ce4a0)
Location: kernel/bpf/verifier.c:509
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff812ce4a0-ffffffff812ce4d5: is_ptr_cast_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool is_ptr_cast_function(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f5a30)
Location: kernel/bpf/verifier.c:526
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff812f5a30-ffffffff812f5a65: is_ptr_cast_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_ptr_cast_function(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81314830)
Location: kernel/bpf/verifier.c:486
Inline: False
```
**Symbols:**

```
ffffffff81314830-ffffffff81314865: is_ptr_cast_function (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff8000102721bc)
Location: kernel/bpf/verifier.c:376
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (c04a45f8)
Location: kernel/bpf/verifier.c:376
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (c0000000003197fc)
Location: kernel/bpf/verifier.c:376
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffe0001ab30e)
Location: kernel/bpf/verifier.c:376
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff811e6ef1)
Location: kernel/bpf/verifier.c:376
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff811d9cb1)
Location: kernel/bpf/verifier.c:376
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff811e4cc1)
Location: kernel/bpf/verifier.c:376
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
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
In kernel/bpf/verifier.c (ffffffff811f3091)
Location: kernel/bpf/verifier.c:376
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
