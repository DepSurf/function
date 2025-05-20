# Function: <code>btf_show_name</code>

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
const char *btf_show_name(struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225d50)
Location: kernel/bpf/btf.c:807
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff81225d50-ffffffff81226115: btf_show_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *btf_show_name(struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122a860)
Location: kernel/bpf/btf.c:808
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff8122a860-ffffffff8122ac22: btf_show_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *btf_show_name(struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81262fe0)
Location: kernel/bpf/btf.c:808
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff81262fe0-ffffffff812633a2: btf_show_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const char *btf_show_name(struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:903
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff812af3b0-ffffffff812af84a: btf_show_name (STB_LOCAL)
ffffffff81e6a6a0-ffffffff81e6a6b8: btf_show_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *btf_show_name(struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130f100)
Location: kernel/bpf/btf.c:905
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff8130f100-ffffffff8130f5c5: btf_show_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *btf_show_name(struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133e9b0)
Location: kernel/bpf/btf.c:924
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff8133e9b0-ffffffff8133ef4c: btf_show_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *btf_show_name(struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813649c0)
Location: kernel/bpf/btf.c:925
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff813649c0-ffffffff81364f5c: btf_show_name (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
