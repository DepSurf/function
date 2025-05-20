# Function: <code>selem_unlink_sk</code>

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
void selem_unlink_sk(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81952ca0)
Location: net/core/bpf_sk_storage.c:193
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
```
**Symbols:**

```
ffffffff81952ca0-ffffffff81952d22: selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void selem_unlink_sk(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81988ff0)
Location: net/core/bpf_sk_storage.c:196
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
```
**Symbols:**

```
ffffffff81988ff0-ffffffff81989072: selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void selem_unlink_sk(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a60c90)
Location: net/core/bpf_sk_storage.c:197
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
**Symbols:**

```
ffffffff81a60c90-ffffffff81a60d12: selem_unlink_sk (STB_LOCAL)
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
void selem_unlink_sk(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffff800010c316d0)
Location: net/core/bpf_sk_storage.c:196
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
```
**Symbols:**

```
ffff800010c316d0-ffff800010c317cc: selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void selem_unlink_sk(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c0d480e8)
Location: net/core/bpf_sk_storage.c:196
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
```
**Symbols:**

```
c0d480e8-c0d48174: selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void selem_unlink_sk(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c000000000d2a310)
Location: net/core/bpf_sk_storage.c:196
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
```
**Symbols:**

```
c000000000d2a310-c000000000d2a3e0: selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void selem_unlink_sk(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffe0007a70cc)
Location: net/core/bpf_sk_storage.c:196
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
```
**Symbols:**

```
ffffffe0007a70cc-ffffffe0007a714a: selem_unlink_sk (STB_LOCAL)
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
void selem_unlink_sk(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81928e60)
Location: net/core/bpf_sk_storage.c:196
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
```
**Symbols:**

```
ffffffff81928e60-ffffffff81928ee2: selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void selem_unlink_sk(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff818e2c10)
Location: net/core/bpf_sk_storage.c:196
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
```
**Symbols:**

```
ffffffff818e2c10-ffffffff818e2c92: selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void selem_unlink_sk(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81979ff0)
Location: net/core/bpf_sk_storage.c:196
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
```
**Symbols:**

```
ffffffff81979ff0-ffffffff8197a072: selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void selem_unlink_sk(struct bpf_sk_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8199c520)
Location: net/core/bpf_sk_storage.c:196
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
  - net/core/bpf_sk_storage.c:sk_storage_delete
```
**Symbols:**

```
ffffffff8199c520-ffffffff8199c5a2: selem_unlink_sk (STB_LOCAL)
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
