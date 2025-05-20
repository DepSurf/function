# Function: <code>bpf_sk_storage_charge</code>

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
int bpf_sk_storage_charge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a69240)
Location: net/core/bpf_sk_storage.c:305
Inline: False
```
**Symbols:**

```
ffffffff81a69240-ffffffff81a69271: bpf_sk_storage_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_sk_storage_charge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a519c0)
Location: net/core/bpf_sk_storage.c:305
Inline: False
```
**Symbols:**

```
ffffffff81a519c0-ffffffff81a519f1: bpf_sk_storage_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_sk_storage_charge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81b0a500)
Location: net/core/bpf_sk_storage.c:305
Inline: False
```
**Symbols:**

```
ffffffff81b0a500-ffffffff81b0a531: bpf_sk_storage_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_sk_storage_charge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81c90a70)
Location: net/core/bpf_sk_storage.c:310
Inline: False
```
**Symbols:**

```
ffffffff81c90a70-ffffffff81c90ab5: bpf_sk_storage_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_sk_storage_charge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81e4bf00)
Location: net/core/bpf_sk_storage.c:281
Inline: False
```
**Symbols:**

```
ffffffff81e4bf00-ffffffff81e4bf45: bpf_sk_storage_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_sk_storage_charge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81ea7600)
Location: net/core/bpf_sk_storage.c:275
Inline: False
```
**Symbols:**

```
ffffffff81ea7600-ffffffff81ea7645: bpf_sk_storage_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_sk_storage_charge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81f6a0b0)
Location: net/core/bpf_sk_storage.c:275
Inline: False
```
**Symbols:**

```
ffffffff81f6a0b0-ffffffff81f6a0f9: bpf_sk_storage_charge (STB_LOCAL)
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
