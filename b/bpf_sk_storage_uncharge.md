# Function: <code>bpf_sk_storage_uncharge</code>

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
void bpf_sk_storage_uncharge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a69280)
Location: net/core/bpf_sk_storage.c:320
Inline: False
```
**Symbols:**

```
ffffffff81a69280-ffffffff81a69292: bpf_sk_storage_uncharge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_sk_storage_uncharge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a51a00)
Location: net/core/bpf_sk_storage.c:320
Inline: False
```
**Symbols:**

```
ffffffff81a51a00-ffffffff81a51a12: bpf_sk_storage_uncharge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_sk_storage_uncharge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81b0a540)
Location: net/core/bpf_sk_storage.c:320
Inline: False
```
**Symbols:**

```
ffffffff81b0a540-ffffffff81b0a552: bpf_sk_storage_uncharge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_sk_storage_uncharge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81c90ac0)
Location: net/core/bpf_sk_storage.c:326
Inline: False
```
**Symbols:**

```
ffffffff81c90ac0-ffffffff81c90ada: bpf_sk_storage_uncharge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_sk_storage_uncharge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81e4bf60)
Location: net/core/bpf_sk_storage.c:297
Inline: False
```
**Symbols:**

```
ffffffff81e4bf60-ffffffff81e4bf7a: bpf_sk_storage_uncharge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_sk_storage_uncharge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81ea7660)
Location: net/core/bpf_sk_storage.c:291
Inline: False
```
**Symbols:**

```
ffffffff81ea7660-ffffffff81ea767a: bpf_sk_storage_uncharge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_sk_storage_uncharge(struct bpf_local_storage_map *smap, void *owner, u32 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81f6a110)
Location: net/core/bpf_sk_storage.c:292
Inline: False
```
**Symbols:**

```
ffffffff81f6a110-ffffffff81f6a12a: bpf_sk_storage_uncharge (STB_LOCAL)
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
