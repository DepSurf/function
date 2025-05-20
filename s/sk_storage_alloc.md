# Function: <code>sk_storage_alloc</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81953224)
Location: net/core/bpf_sk_storage.c:324
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:sk_storage_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sk_storage_alloc(struct sock *sk, struct bpf_sk_storage_map *smap, struct bpf_sk_storage_elem *first_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff819890d0)
Location: net/core/bpf_sk_storage.c:326
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff819890d0-ffffffff819891cd: sk_storage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a620b5)
Location: net/core/bpf_sk_storage.c:327
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff81a61430-ffffffff81a614fb: sk_storage_alloc.part.0 (STB_LOCAL)
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
int sk_storage_alloc(struct sock *sk, struct bpf_sk_storage_map *smap, struct bpf_sk_storage_elem *first_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffff800010c31a08)
Location: net/core/bpf_sk_storage.c:326
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffff800010c31a08-ffff800010c31b60: sk_storage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (c0d48e0c)
Location: net/core/bpf_sk_storage.c:326
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
c0d4869c-c0d48788: sk_storage_alloc.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sk_storage_alloc(struct sock *sk, struct bpf_sk_storage_map *smap, struct bpf_sk_storage_elem *first_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c000000000d2aa60)
Location: net/core/bpf_sk_storage.c:326
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
c000000000d2aa60-c000000000d2abf8: sk_storage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sk_storage_alloc(struct sock *sk, struct bpf_sk_storage_map *smap, struct bpf_sk_storage_elem *first_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffe0007a7212)
Location: net/core/bpf_sk_storage.c:326
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffe0007a7212-ffffffe0007a72f8: sk_storage_alloc (STB_LOCAL)
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
int sk_storage_alloc(struct sock *sk, struct bpf_sk_storage_map *smap, struct bpf_sk_storage_elem *first_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81928f40)
Location: net/core/bpf_sk_storage.c:326
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff81928f40-ffffffff8192903d: sk_storage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sk_storage_alloc(struct sock *sk, struct bpf_sk_storage_map *smap, struct bpf_sk_storage_elem *first_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff818e2cf0)
Location: net/core/bpf_sk_storage.c:326
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff818e2cf0-ffffffff818e2ded: sk_storage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sk_storage_alloc(struct sock *sk, struct bpf_sk_storage_map *smap, struct bpf_sk_storage_elem *first_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8197a0d0)
Location: net/core/bpf_sk_storage.c:326
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff8197a0d0-ffffffff8197a1cd: sk_storage_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sk_storage_alloc(struct sock *sk, struct bpf_sk_storage_map *smap, struct bpf_sk_storage_elem *first_selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8199c600)
Location: net/core/bpf_sk_storage.c:326
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff8199c600-ffffffff8199c6fd: sk_storage_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
