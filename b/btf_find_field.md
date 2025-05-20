# Function: <code>btf_find_field</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int btf_find_field(const struct btf *btf, const struct btf_type *t, const char *name, int sz, int align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81261ff0)
Location: kernel/bpf/btf.c:3106
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_find_timer
  - kernel/bpf/btf.c:btf_find_spin_lock
```
**Symbols:**

```
ffffffff81261ff0-ffffffff812622ed: btf_find_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int btf_find_field(const struct btf *btf, const struct btf_type *t, enum btf_field_type field_type, struct btf_field_info *info, int info_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b2b10)
Location: kernel/bpf/btf.c:3351
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_kptrs
  - kernel/bpf/btf.c:btf_find_timer
  - kernel/bpf/btf.c:btf_find_spin_lock
```
**Symbols:**

```
ffffffff812b2b10-ffffffff812b2f6a: btf_find_field (STB_LOCAL)
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
In kernel/bpf/btf.c (ffffffff813190c3)
Location: kernel/bpf/btf.c:3514
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_fields
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
In kernel/bpf/btf.c (ffffffff81349214)
Location: kernel/bpf/btf.c:3552
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_fields
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
In kernel/bpf/btf.c (ffffffff8136f944)
Location: kernel/bpf/btf.c:3562
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_fields
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum btf_field_type field_type</code>
</li>
<li>
<b>Param added. </b>
<code>struct btf_field_info *info</code>
</li>
<li>
<b>Param added. </b>
<code>int info_cnt</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *name</code>
</li>
<li>
<b>Param removed. </b>
<code>int sz</code>
</li>
<li>
<b>Param removed. </b>
<code>int align</code>
</li>
</ul>
</details>
</li>
</ul>
