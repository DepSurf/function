# Function: <code>bpf_iter_init_unix</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bpf_iter_init_unix(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d7d890)
Location: net/unix/af_unix.c:3602
Inline: True
```
**Symbols:**

```
ffffffff81d7d890-ffffffff81d7d8d9: bpf_iter_init_unix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bpf_iter_init_unix(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f4a770)
Location: net/unix/af_unix.c:3662
Inline: True
```
**Symbols:**

```
ffffffff81f4a770-ffffffff81f4a7b9: bpf_iter_init_unix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bpf_iter_init_unix(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81faa410)
Location: net/unix/af_unix.c:3582
Inline: True
```
**Symbols:**

```
ffffffff81faa410-ffffffff81faa459: bpf_iter_init_unix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_iter_init_unix(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff82077830)
Location: net/unix/af_unix.c:3599
Inline: True
```
**Symbols:**

```
ffffffff82077830-ffffffff82077879: bpf_iter_init_unix (STB_LOCAL)
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
