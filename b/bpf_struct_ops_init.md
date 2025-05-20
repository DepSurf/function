# Function: <code>bpf_struct_ops_init</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void bpf_struct_ops_init(struct btf *btf, struct bpf_verifier_log *log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (0)
Location: kernel/bpf/bpf_struct_ops.c:99
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
```
**Symbols:**

```
ffffffff812301cf-ffffffff812302c6: bpf_struct_ops_init.cold (STB_LOCAL)
ffffffff8122fdf0-ffffffff8123000d: bpf_struct_ops_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void bpf_struct_ops_init(struct btf *btf, struct bpf_verifier_log *log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (0)
Location: kernel/bpf/bpf_struct_ops.c:99
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
```
**Symbols:**

```
ffffffff81be661e-ffffffff81be6715: bpf_struct_ops_init.cold (STB_LOCAL)
ffffffff812382a0-ffffffff812384bd: bpf_struct_ops_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void bpf_struct_ops_init(struct btf *btf, struct bpf_verifier_log *log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (0)
Location: kernel/bpf/bpf_struct_ops.c:99
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
```
**Symbols:**

```
ffffffff81bd831e-ffffffff81bd8415: bpf_struct_ops_init.cold (STB_LOCAL)
ffffffff8123ca90-ffffffff8123ccad: bpf_struct_ops_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bpf_struct_ops_init(struct btf *btf, struct bpf_verifier_log *log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (0)
Location: kernel/bpf/bpf_struct_ops.c:100
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
```
**Symbols:**

```
ffffffff81cb976f-ffffffff81cb9866: bpf_struct_ops_init.cold (STB_LOCAL)
ffffffff812774e0-ffffffff8127772b: bpf_struct_ops_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bpf_struct_ops_init(struct btf *btf, struct bpf_verifier_log *log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (0)
Location: kernel/bpf/bpf_struct_ops.c:104
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
```
**Symbols:**

```
ffffffff81e6abbc-ffffffff81e6acce: bpf_struct_ops_init.cold (STB_LOCAL)
ffffffff812c7050-ffffffff812c7309: bpf_struct_ops_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_struct_ops_init(struct btf *btf, struct bpf_verifier_log *log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c8d0)
Location: kernel/bpf/bpf_struct_ops.c:104
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
```
**Symbols:**

```
ffffffff8132c8d0-ffffffff8132cc88: bpf_struct_ops_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_struct_ops_init(struct btf *btf, struct bpf_verifier_log *log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135cd10)
Location: kernel/bpf/bpf_struct_ops.c:113
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
```
**Symbols:**

```
ffffffff8135cd10-ffffffff8135d0c8: bpf_struct_ops_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_struct_ops_init(struct btf *btf, struct bpf_verifier_log *log);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81385420)
Location: kernel/bpf/bpf_struct_ops.c:113
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
```
**Symbols:**

```
ffffffff81385420-ffffffff813857d8: bpf_struct_ops_init (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
