# Function: <code>bpf_selem_link_storage_nolock</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_link_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8122ffbf)
Location: kernel/bpf/bpf_local_storage.c:159
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff8122fb60-ffffffff8122fb99: bpf_selem_link_storage_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_link_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81225584)
Location: kernel/bpf/bpf_local_storage.c:160
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff81225110-ffffffff81225149: bpf_selem_link_storage_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_link_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d574)
Location: kernel/bpf/bpf_local_storage.c:160
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff8125d090-ffffffff8125d0c9: bpf_selem_link_storage_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_link_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812a775c)
Location: kernel/bpf/bpf_local_storage.c:189
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff812a71c0-ffffffff812a7207: bpf_selem_link_storage_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_link_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81305e7c)
Location: kernel/bpf/bpf_local_storage.c:198
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff81305880-ffffffff813058c7: bpf_selem_link_storage_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_link_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81334bbc)
Location: kernel/bpf/bpf_local_storage.c:370
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff81334630-ffffffff81334677: bpf_selem_link_storage_nolock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_link_storage_nolock(struct bpf_local_storage *local_storage, struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81359298)
Location: kernel/bpf/bpf_local_storage.c:370
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff81358d40-ffffffff81358d87: bpf_selem_link_storage_nolock (STB_GLOBAL)
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
