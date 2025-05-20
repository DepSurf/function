# Function: <code>btf_ptr_show</code>

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
void btf_ptr_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81226a10)
Location: kernel/bpf/btf.c:2530
Inline: False
```
**Symbols:**

```
ffffffff81226a10-ffffffff81226c91: btf_ptr_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void btf_ptr_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122b510)
Location: kernel/bpf/btf.c:2532
Inline: False
```
**Symbols:**

```
ffffffff8122b510-ffffffff8122b789: btf_ptr_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void btf_ptr_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81263d50)
Location: kernel/bpf/btf.c:2532
Inline: False
```
**Symbols:**

```
ffffffff81263d50-ffffffff81263fc9: btf_ptr_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void btf_ptr_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b05c0)
Location: kernel/bpf/btf.c:2669
Inline: False
```
**Symbols:**

```
ffffffff812b05c0-ffffffff812b0848: btf_ptr_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void btf_ptr_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813100b0)
Location: kernel/bpf/btf.c:2693
Inline: False
```
**Symbols:**

```
ffffffff813100b0-ffffffff81310338: btf_ptr_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void btf_ptr_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133fa40)
Location: kernel/bpf/btf.c:2723
Inline: False
```
**Symbols:**

```
ffffffff8133fa40-ffffffff8133fcd2: btf_ptr_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void btf_ptr_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81365a50)
Location: kernel/bpf/btf.c:2724
Inline: False
```
**Symbols:**

```
ffffffff81365a50-ffffffff81365ce2: btf_ptr_show (STB_LOCAL)
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
