# Function: <code>bpf_sk_storage_delete_tracing</code>

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
u64 bpf_sk_storage_delete_tracing(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a69f70)
Location: net/core/bpf_sk_storage.c:425
Inline: False
```
**Symbols:**

```
ffffffff81a69f70-ffffffff81a6a094: bpf_sk_storage_delete_tracing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sk_storage_delete_tracing(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a52470)
Location: net/core/bpf_sk_storage.c:425
Inline: False
```
**Symbols:**

```
ffffffff81a52470-ffffffff81a52595: bpf_sk_storage_delete_tracing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_delete_tracing(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:425
Inline: False
```
**Symbols:**

```
ffffffff81d38c3b-ffffffff81d38c5b: bpf_sk_storage_delete_tracing.cold (STB_LOCAL)
ffffffff81b0b570-ffffffff81b0b697: bpf_sk_storage_delete_tracing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_delete_tracing(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:435
Inline: False
```
**Symbols:**

```
ffffffff81f05477-ffffffff81f05497: bpf_sk_storage_delete_tracing.cold (STB_LOCAL)
ffffffff81c91b70-ffffffff81c91cd1: bpf_sk_storage_delete_tracing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_delete_tracing(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:405
Inline: False
```
**Symbols:**

```
ffffffff820ad484-ffffffff820ad4a4: bpf_sk_storage_delete_tracing.cold (STB_LOCAL)
ffffffff81e4d140-ffffffff81e4d2a1: bpf_sk_storage_delete_tracing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_delete_tracing(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:400
Inline: False
```
**Symbols:**

```
ffffffff8212e5f4-ffffffff8212e614: bpf_sk_storage_delete_tracing.cold (STB_LOCAL)
ffffffff81ea8860-ffffffff81ea8980: bpf_sk_storage_delete_tracing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_delete_tracing(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:401
Inline: False
```
**Symbols:**

```
ffffffff822103a7-ffffffff822103c7: bpf_sk_storage_delete_tracing.cold (STB_LOCAL)
ffffffff81f6b320-ffffffff81f6b440: bpf_sk_storage_delete_tracing (STB_GLOBAL)
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
