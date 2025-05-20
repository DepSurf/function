# Function: <code>btf_int128_print</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void btf_int128_print(struct seq_file *m, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ee1a0)
Location: kernel/bpf/btf.c:1323
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_bitfield_seq_show
```
**Symbols:**

```
ffffffff811ee1a0-ffffffff811ee1d4: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void btf_int128_print(struct seq_file *m, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fa8b0)
Location: kernel/bpf/btf.c:1323
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_bitfield_seq_show
```
**Symbols:**

```
ffffffff811fa8b0-ffffffff811fa8e4: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812204df)
Location: kernel/bpf/btf.c:1429
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_bitfield_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void btf_int128_print(struct btf_show *show, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81226120)
Location: kernel/bpf/btf.c:2058
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_bitfield_show
```
**Symbols:**

```
ffffffff81226120-ffffffff81226344: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void btf_int128_print(struct btf_show *show, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122ac30)
Location: kernel/bpf/btf.c:2060
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_bitfield_show
```
**Symbols:**

```
ffffffff8122ac30-ffffffff8122ae4c: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void btf_int128_print(struct btf_show *show, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812633b0)
Location: kernel/bpf/btf.c:2060
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_bitfield_show
```
**Symbols:**

```
ffffffff812633b0-ffffffff812635cc: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void btf_int128_print(struct btf_show *show, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812af850)
Location: kernel/bpf/btf.c:2189
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_bitfield_show
```
**Symbols:**

```
ffffffff812af850-ffffffff812afa94: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void btf_int128_print(struct btf_show *show, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130f5e0)
Location: kernel/bpf/btf.c:2213
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_bitfield_show
```
**Symbols:**

```
ffffffff8130f5e0-ffffffff8130f824: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void btf_int128_print(struct btf_show *show, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133ef60)
Location: kernel/bpf/btf.c:2243
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_bitfield_show
```
**Symbols:**

```
ffffffff8133ef60-ffffffff8133f1ae: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void btf_int128_print(struct btf_show *show, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81364f70)
Location: kernel/bpf/btf.c:2244
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_show
  - kernel/bpf/btf.c:btf_bitfield_show
```
**Symbols:**

```
ffffffff81364f70-ffffffff813651be: btf_int128_print (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void btf_int128_print(struct seq_file *m, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010280830)
Location: kernel/bpf/btf.c:1323
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_bitfield_seq_show
```
**Symbols:**

```
ffff800010280830-ffff800010280894: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void btf_int128_print(struct seq_file *m, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b16c0)
Location: kernel/bpf/btf.c:1323
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_bitfield_seq_show
```
**Symbols:**

```
c04b16c0-c04b171c: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void btf_int128_print(struct seq_file *m, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032abe0)
Location: kernel/bpf/btf.c:1323
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_bitfield_seq_show
```
**Symbols:**

```
c00000000032abe0-c00000000032ac50: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void btf_int128_print(struct seq_file *m, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b6f88)
Location: kernel/bpf/btf.c:1323
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_bitfield_seq_show
```
**Symbols:**

```
ffffffe0001b6f88-ffffffe0001b6fe6: btf_int128_print (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void btf_int128_print(struct seq_file *m, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f2ed0)
Location: kernel/bpf/btf.c:1323
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_bitfield_seq_show
```
**Symbols:**

```
ffffffff811f2ed0-ffffffff811f2f04: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void btf_int128_print(struct seq_file *m, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e5c20)
Location: kernel/bpf/btf.c:1323
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_bitfield_seq_show
```
**Symbols:**

```
ffffffff811e5c20-ffffffff811e5c54: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void btf_int128_print(struct seq_file *m, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f0ca0)
Location: kernel/bpf/btf.c:1323
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_bitfield_seq_show
```
**Symbols:**

```
ffffffff811f0ca0-ffffffff811f0cd4: btf_int128_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void btf_int128_print(struct seq_file *m, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ff1b0)
Location: kernel/bpf/btf.c:1323
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_bitfield_seq_show
```
**Symbols:**

```
ffffffff811ff1b0-ffffffff811ff1e4: btf_int128_print (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
