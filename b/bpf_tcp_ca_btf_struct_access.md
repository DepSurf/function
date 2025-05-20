# Function: <code>bpf_tcp_ca_btf_struct_access</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log *log, const struct btf_type *t, int off, int size, enum bpf_access_type atype, u32 *next_btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpf_tcp_ca.c (ffffffff81b0d3d0)
Location: net/ipv4/bpf_tcp_ca.c:125
Inline: False
```
**Symbols:**

```
ffffffff81b0d3d0-ffffffff81b0d4a4: bpf_tcp_ca_btf_struct_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, enum bpf_access_type atype, u32 *next_btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpf_tcp_ca.c (ffffffff81b1b740)
Location: net/ipv4/bpf_tcp_ca.c:97
Inline: False
```
**Symbols:**

```
ffffffff81b1b740-ffffffff81b1b826: bpf_tcp_ca_btf_struct_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, enum bpf_access_type atype, u32 *next_btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpf_tcp_ca.c (ffffffff81b09420)
Location: net/ipv4/bpf_tcp_ca.c:98
Inline: False
```
**Symbols:**

```
ffffffff81b09420-ffffffff81b09514: bpf_tcp_ca_btf_struct_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, enum bpf_access_type atype, u32 *next_btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpf_tcp_ca.c (ffffffff81bcc310)
Location: net/ipv4/bpf_tcp_ca.c:101
Inline: False
```
**Symbols:**

```
ffffffff81bcc310-ffffffff81bcc404: bpf_tcp_ca_btf_struct_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, enum bpf_access_type atype, u32 *next_btf_id, enum bpf_type_flag *flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpf_tcp_ca.c (ffffffff81d61f50)
Location: net/ipv4/bpf_tcp_ca.c:95
Inline: False
```
**Symbols:**

```
ffffffff81d61f50-ffffffff81d6206f: bpf_tcp_ca_btf_struct_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log *log, const struct bpf_reg_state *reg, int off, int size, enum bpf_access_type atype, u32 *next_btf_id, enum bpf_type_flag *flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpf_tcp_ca.c (ffffffff81f2c970)
Location: net/ipv4/bpf_tcp_ca.c:73
Inline: False
```
**Symbols:**

```
ffffffff81f2c970-ffffffff81f2cad8: bpf_tcp_ca_btf_struct_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log *log, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpf_tcp_ca.c (ffffffff81f8c640)
Location: net/ipv4/bpf_tcp_ca.c:73
Inline: False
```
**Symbols:**

```
ffffffff81f8c640-ffffffff81f8c77e: bpf_tcp_ca_btf_struct_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_tcp_ca_btf_struct_access(struct bpf_verifier_log *log, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpf_tcp_ca.c (ffffffff82059e40)
Location: net/ipv4/bpf_tcp_ca.c:71
Inline: False
```
**Symbols:**

```
ffffffff82059e40-ffffffff82059f7e: bpf_tcp_ca_btf_struct_access (STB_LOCAL)
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct btf *btf</code>
</li>
<li>
<b>Param reordered. </b>
<code>log, t, off, size, atype, next_btf_id</code> ➡️ <code>log, btf, t, off, size, atype, next_btf_id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum bpf_type_flag *flag</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_reg_state *reg</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct btf *btf</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct btf_type *t</code>
</li>
<li>
<b>Param reordered. </b>
<code>log, btf, t, off, size, atype, next_btf_id, flag</code> ➡️ <code>log, reg, off, size, atype, next_btf_id, flag</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum bpf_access_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *next_btf_id</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_type_flag *flag</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
