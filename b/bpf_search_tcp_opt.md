# Function: <code>bpf_search_tcp_opt</code>

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
const u8 *bpf_search_tcp_opt(const u8 *op, const u8 *opend, u8 search_kind, const u8 *magic, u8 magic_len, bool *eol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2b300)
Location: net/core/filter.c:6642
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_store_hdr_opt
  - net/core/filter.c:bpf_sock_ops_load_hdr_opt
```
**Symbols:**

```
ffffffff81a2b300-ffffffff81a2b3fe: bpf_search_tcp_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const u8 *bpf_search_tcp_opt(const u8 *op, const u8 *opend, u8 search_kind, const u8 *magic, u8 magic_len, bool *eol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a12620)
Location: net/core/filter.c:6744
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_store_hdr_opt
  - net/core/filter.c:bpf_sock_ops_load_hdr_opt
```
**Symbols:**

```
ffffffff81a12620-ffffffff81a1271e: bpf_search_tcp_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const u8 *bpf_search_tcp_opt(const u8 *op, const u8 *opend, u8 search_kind, const u8 *magic, u8 magic_len, bool *eol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac32f0)
Location: net/core/filter.c:6868
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_store_hdr_opt
  - net/core/filter.c:bpf_sock_ops_load_hdr_opt
```
**Symbols:**

```
ffffffff81ac32f0-ffffffff81ac33ee: bpf_search_tcp_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const u8 *bpf_search_tcp_opt(const u8 *op, const u8 *opend, u8 search_kind, const u8 *magic, u8 magic_len, bool *eol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3e0f0)
Location: net/core/filter.c:7207
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_store_hdr_opt
  - net/core/filter.c:bpf_sock_ops_load_hdr_opt
```
**Symbols:**

```
ffffffff81c3e0f0-ffffffff81c3e203: bpf_search_tcp_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const u8 *bpf_search_tcp_opt(const u8 *op, const u8 *opend, u8 search_kind, const u8 *magic, u8 magic_len, bool *eol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df2330)
Location: net/core/filter.c:7219
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_store_hdr_opt
  - net/core/filter.c:bpf_sock_ops_load_hdr_opt
```
**Symbols:**

```
ffffffff81df2330-ffffffff81df2443: bpf_search_tcp_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const u8 *bpf_search_tcp_opt(const u8 *op, const u8 *opend, u8 search_kind, const u8 *magic, u8 magic_len, bool *eol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e642c0)
Location: net/core/filter.c:7377
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_store_hdr_opt
  - net/core/filter.c:bpf_sock_ops_load_hdr_opt
```
**Symbols:**

```
ffffffff81e642c0-ffffffff81e643d2: bpf_search_tcp_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const u8 *bpf_search_tcp_opt(const u8 *op, const u8 *opend, u8 search_kind, const u8 *magic, u8 magic_len, bool *eol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f23470)
Location: net/core/filter.c:7462
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_ops_store_hdr_opt
  - net/core/filter.c:bpf_sock_ops_load_hdr_opt
```
**Symbols:**

```
ffffffff81f23470-ffffffff81f23582: bpf_search_tcp_opt (STB_LOCAL)
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
