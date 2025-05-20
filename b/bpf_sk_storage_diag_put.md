# Function: <code>bpf_sk_storage_diag_put</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag *diag, struct sock *sk, struct sk_buff *skb, int stg_array_type, unsigned int *res_diag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a617c0)
Location: net/core/bpf_sk_storage.c:1118
Inline: False
```
**Symbols:**

```
ffffffff81a617c0-ffffffff81a6198a: bpf_sk_storage_diag_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag *diag, struct sock *sk, struct sk_buff *skb, int stg_array_type, unsigned int *res_diag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a6a0a0)
Location: net/core/bpf_sk_storage.c:656
Inline: False
```
**Symbols:**

```
ffffffff81a6a0a0-ffffffff81a6a274: bpf_sk_storage_diag_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag *diag, struct sock *sk, struct sk_buff *skb, int stg_array_type, unsigned int *res_diag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a526e0)
Location: net/core/bpf_sk_storage.c:656
Inline: False
```
**Symbols:**

```
ffffffff81a526e0-ffffffff81a529d4: bpf_sk_storage_diag_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag *diag, struct sock *sk, struct sk_buff *skb, int stg_array_type, unsigned int *res_diag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81b0b150)
Location: net/core/bpf_sk_storage.c:655
Inline: False
```
**Symbols:**

```
ffffffff81b0b150-ffffffff81b0b444: bpf_sk_storage_diag_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag *diag, struct sock *sk, struct sk_buff *skb, int stg_array_type, unsigned int *res_diag_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81c91820)
Location: net/core/bpf_sk_storage.c:666
Inline: True
```
**Symbols:**

```
ffffffff81c91820-ffffffff81c91b62: bpf_sk_storage_diag_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag *diag, struct sock *sk, struct sk_buff *skb, int stg_array_type, unsigned int *res_diag_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81e4cde0)
Location: net/core/bpf_sk_storage.c:636
Inline: True
```
**Symbols:**

```
ffffffff81e4cde0-ffffffff81e4d122: bpf_sk_storage_diag_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag *diag, struct sock *sk, struct sk_buff *skb, int stg_array_type, unsigned int *res_diag_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81ea8500)
Location: net/core/bpf_sk_storage.c:634
Inline: True
```
**Symbols:**

```
ffffffff81ea8500-ffffffff81ea8842: bpf_sk_storage_diag_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_sk_storage_diag_put(struct bpf_sk_storage_diag *diag, struct sock *sk, struct sk_buff *skb, int stg_array_type, unsigned int *res_diag_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81f6afc0)
Location: net/core/bpf_sk_storage.c:635
Inline: True
```
**Symbols:**

```
ffffffff81f6afc0-ffffffff81f6b302: bpf_sk_storage_diag_put (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
