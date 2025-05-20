# Function: <code>bpf_selem_alloc</code>

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
struct bpf_local_storage_elem *bpf_selem_alloc(struct bpf_local_storage_map *smap, void *owner, void *value, bool charge_mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8122f8b0)
Location: kernel/bpf/bpf_local_storage.c:62
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff8122f8b0-ffffffff8122f987: bpf_selem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_local_storage_elem *bpf_selem_alloc(struct bpf_local_storage_map *smap, void *owner, void *value, bool charge_mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81224e50)
Location: kernel/bpf/bpf_local_storage.c:62
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff81224e50-ffffffff81224f27: bpf_selem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_local_storage_elem *bpf_selem_alloc(struct bpf_local_storage_map *smap, void *owner, void *value, bool charge_mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8125cd90)
Location: kernel/bpf/bpf_local_storage.c:62
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff8125cd90-ffffffff8125ce67: bpf_selem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_local_storage_elem *bpf_selem_alloc(struct bpf_local_storage_map *smap, void *owner, void *value, bool charge_mem, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812a6e40)
Location: kernel/bpf/bpf_local_storage.c:65
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff812a6e40-ffffffff812a6f0d: bpf_selem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_local_storage_elem *bpf_selem_alloc(struct bpf_local_storage_map *smap, void *owner, void *value, bool charge_mem, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81305790)
Location: kernel/bpf/bpf_local_storage.c:65
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff81305790-ffffffff81305868: bpf_selem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct bpf_local_storage_elem *bpf_selem_alloc(struct bpf_local_storage_map *smap, void *owner, void *value, bool charge_mem, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:75
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff820e0cda-ffffffff820e0cf5: bpf_selem_alloc.cold (STB_LOCAL)
ffffffff81334120-ffffffff81334236: bpf_selem_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct bpf_local_storage_elem *bpf_selem_alloc(struct bpf_local_storage_map *smap, void *owner, void *value, bool charge_mem, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:75
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff821bd48f-ffffffff821bd4aa: bpf_selem_alloc.cold (STB_LOCAL)
ffffffff81358810-ffffffff81358926: bpf_selem_alloc (STB_GLOBAL)
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
