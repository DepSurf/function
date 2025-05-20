# Function: <code>bpf_iter_init_hash_map</code>

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
int bpf_iter_init_hash_map(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81219ae0)
Location: kernel/bpf/hashtab.c:1828
Inline: False
```
**Symbols:**

```
ffffffff81219ae0-ffffffff81219b4b: bpf_iter_init_hash_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_init_hash_map(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121d4c0)
Location: kernel/bpf/hashtab.c:1828
Inline: False
```
**Symbols:**

```
ffffffff8121d4c0-ffffffff8121d52b: bpf_iter_init_hash_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_init_hash_map(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81254490)
Location: kernel/bpf/hashtab.c:2008
Inline: False
```
**Symbols:**

```
ffffffff81254490-ffffffff812544fb: bpf_iter_init_hash_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_init_hash_map(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129cb70)
Location: kernel/bpf/hashtab.c:2045
Inline: False
```
**Symbols:**

```
ffffffff8129cb70-ffffffff8129cbeb: bpf_iter_init_hash_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_iter_init_hash_map(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f8ce0)
Location: kernel/bpf/hashtab.c:2076
Inline: False
```
**Symbols:**

```
ffffffff812f8ce0-ffffffff812f8d5b: bpf_iter_init_hash_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_iter_init_hash_map(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81326e70)
Location: kernel/bpf/hashtab.c:2089
Inline: False
```
**Symbols:**

```
ffffffff81326e70-ffffffff81326eeb: bpf_iter_init_hash_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_iter_init_hash_map(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134b4c0)
Location: kernel/bpf/hashtab.c:2111
Inline: False
```
**Symbols:**

```
ffffffff8134b4c0-ffffffff8134b53b: bpf_iter_init_hash_map (STB_LOCAL)
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
