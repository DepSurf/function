# Function: <code>btf_type_show</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void btf_type_show(const struct btf *btf, u32 type_id, void *obj, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812250a0)
Location: kernel/bpf/btf.c:5486
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_type_snprintf_show
  - kernel/bpf/btf.c:btf_type_seq_show_flags
```
**Symbols:**

```
ffffffff812250a0-ffffffff81225134: btf_type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void btf_type_show(const struct btf *btf, u32 type_id, void *obj, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81229b20)
Location: kernel/bpf/btf.c:5679
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_type_snprintf_show
  - kernel/bpf/btf.c:btf_type_seq_show_flags
```
**Symbols:**

```
ffffffff81229b20-ffffffff81229bb4: btf_type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void btf_type_show(const struct btf *btf, u32 type_id, void *obj, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81261f20)
Location: kernel/bpf/btf.c:5732
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_type_snprintf_show
  - kernel/bpf/btf.c:btf_type_seq_show_flags
```
**Symbols:**

```
ffffffff81261f20-ffffffff81261fec: btf_type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void btf_type_show(const struct btf *btf, u32 type_id, void *obj, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ac890)
Location: kernel/bpf/btf.c:6465
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_type_snprintf_show
  - kernel/bpf/btf.c:btf_type_seq_show_flags
```
**Symbols:**

```
ffffffff812ac890-ffffffff812ac97a: btf_type_show (STB_LOCAL)
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
In kernel/bpf/btf.c (ffffffff813189cd)
Location: kernel/bpf/btf.c:6956
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_snprintf_show
  - kernel/bpf/btf.c:btf_type_seq_show_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void btf_type_show(const struct btf *btf, u32 type_id, void *obj, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133b8e0)
Location: kernel/bpf/btf.c:7058
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_type_snprintf_show
  - kernel/bpf/btf.c:btf_type_seq_show_flags
```
**Symbols:**

```
ffffffff8133b8e0-ffffffff8133b9ca: btf_type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void btf_type_show(const struct btf *btf, u32 type_id, void *obj, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81361aa0)
Location: kernel/bpf/btf.c:7122
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_type_snprintf_show
  - kernel/bpf/btf.c:btf_type_seq_show_flags
```
**Symbols:**

```
ffffffff81361aa0-ffffffff81361b8a: btf_type_show (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
