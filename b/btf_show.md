# Function: <code>btf_show</code>

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
void btf_show(struct btf_show *show, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812232c0)
Location: kernel/bpf/btf.c:997
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_df_show
  - kernel/bpf/btf.c:btf_show_end_aggr_type
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff812232c0-ffffffff81223336: btf_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void btf_show(struct btf_show *show, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81227d70)
Location: kernel/bpf/btf.c:998
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_df_show
  - kernel/bpf/btf.c:btf_show_end_aggr_type
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff81227d70-ffffffff81227de6: btf_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void btf_show(struct btf_show *show, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81260060)
Location: kernel/bpf/btf.c:998
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_df_show
  - kernel/bpf/btf.c:btf_show_end_aggr_type
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff81260060-ffffffff812600d6: btf_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void btf_show(struct btf_show *show, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812aa8e0)
Location: kernel/bpf/btf.c:1093
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_df_show
  - kernel/bpf/btf.c:btf_show_end_aggr_type
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff812aa8e0-ffffffff812aa984: btf_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void btf_show(struct btf_show *show, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130a110)
Location: kernel/bpf/btf.c:1096
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_df_show
  - kernel/bpf/btf.c:btf_show_end_aggr_type
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff8130a110-ffffffff8130a1b4: btf_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void btf_show(struct btf_show *show, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81339620)
Location: kernel/bpf/btf.c:1115
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_df_show
  - kernel/bpf/btf.c:btf_show_end_aggr_type
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff81339620-ffffffff813396c4: btf_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void btf_show(struct btf_show *show, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8135f750)
Location: kernel/bpf/btf.c:1116
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_ptr_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_int128_print
  - kernel/bpf/btf.c:btf_df_show
  - kernel/bpf/btf.c:btf_show_end_aggr_type
  - kernel/bpf/btf.c:btf_show_start_aggr_type
```
**Symbols:**

```
ffffffff8135f750-ffffffff8135f7f4: btf_show (STB_LOCAL)
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
