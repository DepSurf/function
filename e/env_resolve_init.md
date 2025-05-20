# Function: <code>env_resolve_init</code>

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
In kernel/bpf/btf.c (ffffffff811c8fe8)
Location: kernel/bpf/btf.c:692
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
In kernel/bpf/btf.c (ffffffff811dc136)
Location: kernel/bpf/btf.c:820
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
In kernel/bpf/btf.c (ffffffff811f18a5)
Location: kernel/bpf/btf.c:921
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
In kernel/bpf/btf.c (ffffffff811fdfb5)
Location: kernel/bpf/btf.c:921
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
int env_resolve_init(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8121f850)
Location: kernel/bpf/btf.c:949
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
**Symbols:**

```
ffffffff8121f850-ffffffff8121f8fd: env_resolve_init (STB_LOCAL)
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
In kernel/bpf/btf.c (ffffffff8122ac56)
Location: kernel/bpf/btf.c:1540
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff8122f596)
Location: kernel/bpf/btf.c:1541
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
In kernel/bpf/btf.c (ffffffff812682f6)
Location: kernel/bpf/btf.c:1541
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
In kernel/bpf/btf.c (ffffffff812b5626)
Location: kernel/bpf/btf.c:1669
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff81315c56)
Location: kernel/bpf/btf.c:1692
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff81345c26)
Location: kernel/bpf/btf.c:1722
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff8136bbb6)
Location: kernel/bpf/btf.c:1723
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffff800010284f40)
Location: kernel/bpf/btf.c:921
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
In kernel/bpf/btf.c (c04b5554)
Location: kernel/bpf/btf.c:921
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
In kernel/bpf/btf.c (c00000000032fa1c)
Location: kernel/bpf/btf.c:921
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
In kernel/bpf/btf.c (ffffffe0001ba462)
Location: kernel/bpf/btf.c:921
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
In kernel/bpf/btf.c (ffffffff811f65d5)
Location: kernel/bpf/btf.c:921
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
In kernel/bpf/btf.c (ffffffff811e9325)
Location: kernel/bpf/btf.c:921
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
In kernel/bpf/btf.c (ffffffff811f43a5)
Location: kernel/bpf/btf.c:921
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
In kernel/bpf/btf.c (ffffffff812028b5)
Location: kernel/bpf/btf.c:921
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
</ul>
