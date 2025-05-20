# Function: <code>bpf_sk_storage_get_tracing</code>

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
u64 bpf_sk_storage_get_tracing(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a699d0)
Location: net/core/bpf_sk_storage.c:416
Inline: False
```
**Symbols:**

```
ffffffff81a699d0-ffffffff81a69aed: bpf_sk_storage_get_tracing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sk_storage_get_tracing(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a52170)
Location: net/core/bpf_sk_storage.c:416
Inline: False
```
**Symbols:**

```
ffffffff81a52170-ffffffff81a5228e: bpf_sk_storage_get_tracing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_get_tracing(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:416
Inline: False
```
**Symbols:**

```
ffffffff81d38bfb-ffffffff81d38c1b: bpf_sk_storage_get_tracing.cold (STB_LOCAL)
ffffffff81b0ae00-ffffffff81b0af30: bpf_sk_storage_get_tracing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_get_tracing(u64 map, u64 sk, u64 value, u64 flags, u64 gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:424
Inline: False
```
**Symbols:**

```
ffffffff81f0544f-ffffffff81f05477: bpf_sk_storage_get_tracing.cold (STB_LOCAL)
ffffffff81c91480-ffffffff81c915d6: bpf_sk_storage_get_tracing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_get_tracing(u64 map, u64 sk, u64 value, u64 flags, u64 gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:394
Inline: False
```
**Symbols:**

```
ffffffff820ad45c-ffffffff820ad484: bpf_sk_storage_get_tracing.cold (STB_LOCAL)
ffffffff81e4c9f0-ffffffff81e4cb46: bpf_sk_storage_get_tracing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_get_tracing(u64 map, u64 sk, u64 value, u64 flags, u64 gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:389
Inline: False
```
**Symbols:**

```
ffffffff8212e5db-ffffffff8212e5f4: bpf_sk_storage_get_tracing.cold (STB_LOCAL)
ffffffff81ea8110-ffffffff81ea8262: bpf_sk_storage_get_tracing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_get_tracing(u64 map, u64 sk, u64 value, u64 flags, u64 gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:390
Inline: False
```
**Symbols:**

```
ffffffff8221038e-ffffffff822103a7: bpf_sk_storage_get_tracing.cold (STB_LOCAL)
ffffffff81f6abd0-ffffffff81f6ad22: bpf_sk_storage_get_tracing (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 gfp_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 __ur_1</code>
</li>
</ul>
</details>
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
