# Function: <code>selem_unlink_map</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void selem_unlink_map(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81952c20)
Location: net/core/bpf_sk_storage.c:220
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff81952c20-ffffffff81952c9e: selem_unlink_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void selem_unlink_map(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81988f70)
Location: net/core/bpf_sk_storage.c:222
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
**Symbols:**

```
ffffffff81988f70-ffffffff81988fee: selem_unlink_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void selem_unlink_map(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a60c10)
Location: net/core/bpf_sk_storage.c:223
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff81a60c10-ffffffff81a60c8e: selem_unlink_map (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void selem_unlink_map(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffff800010c31288)
Location: net/core/bpf_sk_storage.c:222
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
**Symbols:**

```
ffff800010c31288-ffff800010c31384: selem_unlink_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void selem_unlink_map(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c0d48064)
Location: net/core/bpf_sk_storage.c:222
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
c0d48064-c0d480e8: selem_unlink_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void selem_unlink_map(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c000000000d2a250)
Location: net/core/bpf_sk_storage.c:222
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
**Symbols:**

```
c000000000d2a250-c000000000d2a30c: selem_unlink_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void selem_unlink_map(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffe0007a7056)
Location: net/core/bpf_sk_storage.c:222
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
**Symbols:**

```
ffffffe0007a7056-ffffffe0007a70cc: selem_unlink_map (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void selem_unlink_map(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81928de0)
Location: net/core/bpf_sk_storage.c:222
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
**Symbols:**

```
ffffffff81928de0-ffffffff81928e5e: selem_unlink_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void selem_unlink_map(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff818e2b90)
Location: net/core/bpf_sk_storage.c:222
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
**Symbols:**

```
ffffffff818e2b90-ffffffff818e2c0e: selem_unlink_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void selem_unlink_map(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81979f70)
Location: net/core/bpf_sk_storage.c:222
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
**Symbols:**

```
ffffffff81979f70-ffffffff81979fee: selem_unlink_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void selem_unlink_map(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8199c4a0)
Location: net/core/bpf_sk_storage.c:222
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_alloc
```
**Symbols:**

```
ffffffff8199c4a0-ffffffff8199c51e: selem_unlink_map (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
