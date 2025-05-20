# Function: <code>btf_parse_kptr</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81319444)
Location: kernel/bpf/btf.c:3525
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_fields
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int btf_parse_kptr(const struct btf *btf, struct btf_field *field, struct btf_field_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:3563
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_fields
```
**Symbols:**

```
ffffffff81348ea0-ffffffff813491b8: btf_parse_kptr (STB_LOCAL)
ffffffff820e10de-ffffffff820e1108: btf_parse_kptr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int btf_parse_kptr(const struct btf *btf, struct btf_field *field, struct btf_field_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:3573
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_fields
```
**Symbols:**

```
ffffffff8136f5d0-ffffffff8136f8e8: btf_parse_kptr (STB_LOCAL)
ffffffff821bd8eb-ffffffff821bd915: btf_parse_kptr.cold (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
