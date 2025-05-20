# Function: <code>bloom_map_alloc</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bpf_map *bloom_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bloom_filter.c (0)
Location: kernel/bpf/bloom_filter.c:91
Inline: False
```
**Symbols:**

```
ffffffff812a48a0-ffffffff812a4a73: bloom_map_alloc (STB_LOCAL)
ffffffff81e6a5ab-ffffffff81e6a5c9: bloom_map_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct bpf_map *bloom_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bloom_filter.c (0)
Location: kernel/bpf/bloom_filter.c:91
Inline: False
```
**Symbols:**

```
ffffffff813025e0-ffffffff813027b3: bloom_map_alloc (STB_LOCAL)
ffffffff820616fe-ffffffff8206171c: bloom_map_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct bpf_map *bloom_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bloom_filter.c (0)
Location: kernel/bpf/bloom_filter.c:83
Inline: False
```
**Symbols:**

```
ffffffff813313a0-ffffffff8133152b: bloom_map_alloc (STB_LOCAL)
ffffffff820e0ca0-ffffffff820e0cbe: bloom_map_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct bpf_map *bloom_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bloom_filter.c (0)
Location: kernel/bpf/bloom_filter.c:83
Inline: False
```
**Symbols:**

```
ffffffff81355940-ffffffff81355acb: bloom_map_alloc (STB_LOCAL)
ffffffff821bd455-ffffffff821bd473: bloom_map_alloc.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
