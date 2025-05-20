# Function: <code>bpf_ksym_del</code>

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
void bpf_ksym_del(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa090)
Location: kernel/bpf/core.c:628
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
**Symbols:**

```
ffffffff811fa090-ffffffff811fa128: bpf_ksym_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_ksym_del(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f90c0)
Location: kernel/bpf/core.c:624
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
```
**Symbols:**

```
ffffffff811f90c0-ffffffff811f9158: bpf_ksym_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_ksym_del(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9ea0)
Location: kernel/bpf/core.c:630
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
```
**Symbols:**

```
ffffffff811f9ea0-ffffffff811f9f38: bpf_ksym_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_ksym_del(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122b570)
Location: kernel/bpf/core.c:631
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
```
**Symbols:**

```
ffffffff8122b570-ffffffff8122b608: bpf_ksym_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_ksym_del(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126cfd0)
Location: kernel/bpf/core.c:640
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff8126cfd0-ffffffff8126d074: bpf_ksym_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_ksym_del(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c2110)
Location: kernel/bpf/core.c:648
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff812c2110-ffffffff812c21b4: bpf_ksym_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_ksym_del(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e8fd0)
Location: kernel/bpf/core.c:649
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
```
**Symbols:**

```
ffffffff812e8fd0-ffffffff812e9074: bpf_ksym_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_ksym_del(struct bpf_ksym *ksym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81307340)
Location: kernel/bpf/core.c:670
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
  - kernel/bpf/core.c:bpf_prog_kallsyms_del_all
```
**Symbols:**

```
ffffffff81307340-ffffffff813073e4: bpf_ksym_del (STB_GLOBAL)
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
