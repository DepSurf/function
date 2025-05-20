# Function: <code>bpf_btf_find_by_name_kind</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_btf_find_by_name_kind(u64 name, u64 name_sz, u64 kind, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6154
Inline: False
```
**Symbols:**

```
ffffffff81cb9430-ffffffff81cb944b: bpf_btf_find_by_name_kind.cold (STB_LOCAL)
ffffffff81266600-ffffffff812667c7: bpf_btf_find_by_name_kind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_btf_find_by_name_kind(u64 name, u64 name_sz, u64 kind, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6947
Inline: False
```
**Symbols:**

```
ffffffff81e6a7a8-ffffffff81e6a7bc: bpf_btf_find_by_name_kind.cold (STB_LOCAL)
ffffffff812b3680-ffffffff812b379c: bpf_btf_find_by_name_kind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_btf_find_by_name_kind(u64 name, u64 name_sz, u64 kind, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7426
Inline: False
```
**Symbols:**

```
ffffffff820618e1-ffffffff820618f5: bpf_btf_find_by_name_kind.cold (STB_LOCAL)
ffffffff81313b30-ffffffff81313c4c: bpf_btf_find_by_name_kind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_btf_find_by_name_kind(u64 name, u64 name_sz, u64 kind, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7528
Inline: False
```
**Symbols:**

```
ffffffff820e0f97-ffffffff820e0fab: bpf_btf_find_by_name_kind.cold (STB_LOCAL)
ffffffff813437e0-ffffffff813438f7: bpf_btf_find_by_name_kind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_btf_find_by_name_kind(u64 name, u64 name_sz, u64 kind, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7592
Inline: False
```
**Symbols:**

```
ffffffff821bd7df-ffffffff821bd7f3: bpf_btf_find_by_name_kind.cold (STB_LOCAL)
ffffffff81369430-ffffffff81369547: bpf_btf_find_by_name_kind (STB_GLOBAL)
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
