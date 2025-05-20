# Function: <code>btf_modifier_show</code>

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
void btf_modifier_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812280e0)
Location: kernel/bpf/btf.c:2508
Inline: False
```
**Symbols:**

```
ffffffff812280e0-ffffffff812281a6: btf_modifier_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void btf_modifier_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122cbe0)
Location: kernel/bpf/btf.c:2510
Inline: False
```
**Symbols:**

```
ffffffff8122cbe0-ffffffff8122cca7: btf_modifier_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void btf_modifier_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81265540)
Location: kernel/bpf/btf.c:2510
Inline: False
```
**Symbols:**

```
ffffffff81265540-ffffffff8126563d: btf_modifier_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void btf_modifier_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b16f0)
Location: kernel/bpf/btf.c:2647
Inline: False
```
**Symbols:**

```
ffffffff812b16f0-ffffffff812b180a: btf_modifier_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void btf_modifier_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81311a50)
Location: kernel/bpf/btf.c:2671
Inline: False
```
**Symbols:**

```
ffffffff81311a50-ffffffff81311b6a: btf_modifier_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void btf_modifier_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813412e0)
Location: kernel/bpf/btf.c:2701
Inline: False
```
**Symbols:**

```
ffffffff813412e0-ffffffff813413fa: btf_modifier_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void btf_modifier_show(const struct btf *btf, const struct btf_type *t, u32 type_id, void *data, u8 bits_offset, struct btf_show *show);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81367800)
Location: kernel/bpf/btf.c:2702
Inline: False
```
**Symbols:**

```
ffffffff81367800-ffffffff8136791a: btf_modifier_show (STB_LOCAL)
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
