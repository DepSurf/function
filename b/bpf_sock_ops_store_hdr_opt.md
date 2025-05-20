# Function: <code>bpf_sock_ops_store_hdr_opt</code>

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
u64 bpf_sock_ops_store_hdr_opt(u64 bpf_sock, u64 from, u64 len, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2cbe0)
Location: net/core/filter.c:6764
Inline: False
```
**Symbols:**

```
ffffffff81a2cbe0-ffffffff81a2cd82: bpf_sock_ops_store_hdr_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sock_ops_store_hdr_opt(u64 bpf_sock, u64 from, u64 len, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a12720)
Location: net/core/filter.c:6866
Inline: False
```
**Symbols:**

```
ffffffff81a12720-ffffffff81a128c2: bpf_sock_ops_store_hdr_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_store_hdr_opt(u64 bpf_sock, u64 from, u64 len, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6990
Inline: False
```
**Symbols:**

```
ffffffff81d36fb2-ffffffff81d36fc7: bpf_sock_ops_store_hdr_opt.cold (STB_LOCAL)
ffffffff81ac4270-ffffffff81ac4416: bpf_sock_ops_store_hdr_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_store_hdr_opt(u64 bpf_sock, u64 from, u64 len, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:7329
Inline: False
```
**Symbols:**

```
ffffffff81f038f6-ffffffff81f0390b: bpf_sock_ops_store_hdr_opt.cold (STB_LOCAL)
ffffffff81c3f780-ffffffff81c3f950: bpf_sock_ops_store_hdr_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_store_hdr_opt(u64 bpf_sock, u64 from, u64 len, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:7341
Inline: False
```
**Symbols:**

```
ffffffff820abfe9-ffffffff820abffe: bpf_sock_ops_store_hdr_opt.cold (STB_LOCAL)
ffffffff81df3f70-ffffffff81df4140: bpf_sock_ops_store_hdr_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_store_hdr_opt(u64 bpf_sock, u64 from, u64 len, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:7499
Inline: False
```
**Symbols:**

```
ffffffff8212d738-ffffffff8212d74d: bpf_sock_ops_store_hdr_opt.cold (STB_LOCAL)
ffffffff81e65b80-ffffffff81e65d50: bpf_sock_ops_store_hdr_opt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_store_hdr_opt(u64 bpf_sock, u64 from, u64 len, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:7584
Inline: False
```
**Symbols:**

```
ffffffff8220f485-ffffffff8220f49a: bpf_sock_ops_store_hdr_opt.cold (STB_LOCAL)
ffffffff81f24d30-ffffffff81f24f00: bpf_sock_ops_store_hdr_opt (STB_GLOBAL)
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
