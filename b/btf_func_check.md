# Function: <code>btf_func_check</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811dc42f)
Location: kernel/bpf/btf.c:2395
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_type_sec
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
In kernel/bpf/btf.c (ffffffff811f1b3e)
Location: kernel/bpf/btf.c:2879
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff811fe24e)
Location: kernel/bpf/btf.c:2878
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int btf_func_check(struct btf_verifier_env *env, const struct btf_type *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812224c0)
Location: kernel/bpf/btf.c:2988
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
**Symbols:**

```
ffffffff812224c0-ffffffff8122255a: btf_func_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int btf_func_check(struct btf_verifier_env *env, const struct btf_type *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81224ff0)
Location: kernel/bpf/btf.c:3772
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
**Symbols:**

```
ffffffff81224ff0-ffffffff8122509e: btf_func_check (STB_LOCAL)
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
In kernel/bpf/btf.c (ffffffff8122f6ca)
Location: kernel/bpf/btf.c:3844
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff8126842a)
Location: kernel/bpf/btf.c:3893
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff812adb66)
Location: kernel/bpf/btf.c:4394
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_func_resolve
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
In kernel/bpf/btf.c (ffffffff8130d1a6)
Location: kernel/bpf/btf.c:4824
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_func_resolve
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
In kernel/bpf/btf.c (ffffffff8133c866)
Location: kernel/bpf/btf.c:4894
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_func_resolve
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
In kernel/bpf/btf.c (ffffffff81362a26)
Location: kernel/bpf/btf.c:4902
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_func_resolve
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
In kernel/bpf/btf.c (ffff800010285178)
Location: kernel/bpf/btf.c:2878
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (c04b583c)
Location: kernel/bpf/btf.c:2878
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (c00000000032fcc0)
Location: kernel/bpf/btf.c:2878
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffe0001ba692)
Location: kernel/bpf/btf.c:2878
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff811f686e)
Location: kernel/bpf/btf.c:2878
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff811e95be)
Location: kernel/bpf/btf.c:2878
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff811f463e)
Location: kernel/bpf/btf.c:2878
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff81202b4e)
Location: kernel/bpf/btf.c:2878
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
