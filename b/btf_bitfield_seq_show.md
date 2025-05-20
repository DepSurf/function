# Function: <code>btf_bitfield_seq_show</code>

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
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void btf_bitfield_seq_show(void *data, u8 bits_offset, u8 nr_bits, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:1214
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
ffffffff811da350-ffffffff811da43a: btf_bitfield_seq_show (STB_LOCAL)
ffffffff811dd01e-ffffffff811dd02a: btf_bitfield_seq_show.cold.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void btf_bitfield_seq_show(void *data, u8 bits_offset, u8 nr_bits, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:1388
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
ffffffff811ef200-ffffffff811ef38c: btf_bitfield_seq_show (STB_LOCAL)
ffffffff811f266e-ffffffff811f267a: btf_bitfield_seq_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void btf_bitfield_seq_show(void *data, u8 bits_offset, u8 nr_bits, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:1388
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
ffffffff811fb940-ffffffff811fbacc: btf_bitfield_seq_show (STB_LOCAL)
ffffffff811fed8e-ffffffff811fed9a: btf_bitfield_seq_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void btf_bitfield_seq_show(void *data, u8 bits_offset, u8 nr_bits, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:1494
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
ffffffff812201b0-ffffffff81220359: btf_bitfield_seq_show (STB_LOCAL)
ffffffff8122615e-ffffffff8122616a: btf_bitfield_seq_show.cold (STB_LOCAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void btf_bitfield_seq_show(void *data, u8 bits_offset, u8 nr_bits, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010281e38)
Location: kernel/bpf/btf.c:1388
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
ffff800010281e38-ffff800010281f64: btf_bitfield_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void btf_bitfield_seq_show(void *data, u8 bits_offset, u8 nr_bits, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b1a58)
Location: kernel/bpf/btf.c:1388
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
c04b1a58-c04b1c20: btf_bitfield_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void btf_bitfield_seq_show(void *data, u8 bits_offset, u8 nr_bits, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032c340)
Location: kernel/bpf/btf.c:1388
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
c00000000032c340-c00000000032c4b0: btf_bitfield_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void btf_bitfield_seq_show(void *data, u8 bits_offset, u8 nr_bits, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b7fde)
Location: kernel/bpf/btf.c:1388
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
ffffffe0001b7fde-ffffffe0001b80ce: btf_bitfield_seq_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void btf_bitfield_seq_show(void *data, u8 bits_offset, u8 nr_bits, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:1388
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
ffffffff811f3f60-ffffffff811f40ec: btf_bitfield_seq_show (STB_LOCAL)
ffffffff811f73ae-ffffffff811f73ba: btf_bitfield_seq_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void btf_bitfield_seq_show(void *data, u8 bits_offset, u8 nr_bits, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:1388
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
ffffffff811e6cb0-ffffffff811e6e3c: btf_bitfield_seq_show (STB_LOCAL)
ffffffff811ea0fe-ffffffff811ea10a: btf_bitfield_seq_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void btf_bitfield_seq_show(void *data, u8 bits_offset, u8 nr_bits, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:1388
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
ffffffff811f1d30-ffffffff811f1ebc: btf_bitfield_seq_show (STB_LOCAL)
ffffffff811f517e-ffffffff811f518a: btf_bitfield_seq_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void btf_bitfield_seq_show(void *data, u8 bits_offset, u8 nr_bits, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:1388
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
ffffffff81200240-ffffffff812003cc: btf_bitfield_seq_show (STB_LOCAL)
ffffffff812036ae-ffffffff812036ba: btf_bitfield_seq_show.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
