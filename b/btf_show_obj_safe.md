# Function: <code>btf_show_obj_safe</code>

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
void *btf_show_obj_safe(struct btf_show *show, const struct btf_type *t, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225c20)
Location: kernel/bpf/btf.c:1091
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff81225c20-ffffffff81225d47: btf_show_obj_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122a730)
Location: kernel/bpf/btf.c:1092
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff8122a730-ffffffff8122a855: btf_show_obj_safe.constprop.0 (STB_LOCAL)
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
In kernel/bpf/btf.c (ffffffff81262eb0)
Location: kernel/bpf/btf.c:1092
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff81262eb0-ffffffff81262fd5: btf_show_obj_safe.constprop.0 (STB_LOCAL)
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
In kernel/bpf/btf.c (ffffffff812aea30)
Location: kernel/bpf/btf.c:1187
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff812aea30-ffffffff812aeb66: btf_show_obj_safe.constprop.0 (STB_LOCAL)
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
In kernel/bpf/btf.c (ffffffff8130dd30)
Location: kernel/bpf/btf.c:1191
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff8130dd30-ffffffff8130de66: btf_show_obj_safe.constprop.0 (STB_LOCAL)
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
In kernel/bpf/btf.c (ffffffff8133d5b0)
Location: kernel/bpf/btf.c:1210
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff8133d5b0-ffffffff8133d6f7: btf_show_obj_safe.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813635c0)
Location: kernel/bpf/btf.c:1211
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff813635c0-ffffffff81363707: btf_show_obj_safe.constprop.0 (STB_LOCAL)
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
