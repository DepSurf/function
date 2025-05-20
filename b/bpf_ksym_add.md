# Function: <code>bpf_ksym_add</code>

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
void bpf_ksym_add(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9f30)
Location: kernel/bpf/core.c:610
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
**Symbols:**

```
ffffffff811f9f30-ffffffff811fa087: bpf_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_ksym_add(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8f60)
Location: kernel/bpf/core.c:606
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
```
**Symbols:**

```
ffffffff811f8f60-ffffffff811f90b7: bpf_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_ksym_add(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9d40)
Location: kernel/bpf/core.c:612
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff811f9d40-ffffffff811f9e97: bpf_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_ksym_add(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122b410)
Location: kernel/bpf/core.c:613
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff8122b410-ffffffff8122b567: bpf_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_ksym_add(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126ce60)
Location: kernel/bpf/core.c:622
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff8126ce60-ffffffff8126cfc5: bpf_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_ksym_add(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c1f90)
Location: kernel/bpf/core.c:630
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff812c1f90-ffffffff812c20f5: bpf_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_ksym_add(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e8e50)
Location: kernel/bpf/core.c:631
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff812e8e50-ffffffff812e8fb5: bpf_ksym_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_ksym_add(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff813071c0)
Location: kernel/bpf/core.c:652
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff813071c0-ffffffff81307325: bpf_ksym_add (STB_GLOBAL)
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
