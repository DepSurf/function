# Function: <code>bpf_local_storage_alloc</code>

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
int bpf_local_storage_alloc(void *owner, struct bpf_local_storage_map *smap, struct bpf_local_storage_elem *first_selem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8122fd80)
Location: kernel/bpf/bpf_local_storage.c:256
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff8122fd80-ffffffff8122feb3: bpf_local_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_local_storage_alloc(void *owner, struct bpf_local_storage_map *smap, struct bpf_local_storage_elem *first_selem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81225340)
Location: kernel/bpf/bpf_local_storage.c:261
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff81225340-ffffffff81225473: bpf_local_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_local_storage_alloc(void *owner, struct bpf_local_storage_map *smap, struct bpf_local_storage_elem *first_selem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d330)
Location: kernel/bpf/bpf_local_storage.c:261
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff8125d330-ffffffff8125d463: bpf_local_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_local_storage_alloc(void *owner, struct bpf_local_storage_map *smap, struct bpf_local_storage_elem *first_selem, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812a74a0)
Location: kernel/bpf/bpf_local_storage.c:292
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff812a74a0-ffffffff812a75f1: bpf_local_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_local_storage_alloc(void *owner, struct bpf_local_storage_map *smap, struct bpf_local_storage_elem *first_selem, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81305bb0)
Location: kernel/bpf/bpf_local_storage.c:302
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff81305bb0-ffffffff81305d01: bpf_local_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_local_storage_alloc(void *owner, struct bpf_local_storage_map *smap, struct bpf_local_storage_elem *first_selem, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:474
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff820e0d60-ffffffff820e0d90: bpf_local_storage_alloc.cold (STB_LOCAL)
ffffffff81334890-ffffffff81334a43: bpf_local_storage_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_local_storage_alloc(void *owner, struct bpf_local_storage_map *smap, struct bpf_local_storage_elem *first_selem, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:474
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff821bd515-ffffffff821bd545: bpf_local_storage_alloc.cold (STB_LOCAL)
ffffffff81358fa0-ffffffff81359153: bpf_local_storage_alloc (STB_GLOBAL)
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
<code>gfp_t gfp_flags</code>
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
