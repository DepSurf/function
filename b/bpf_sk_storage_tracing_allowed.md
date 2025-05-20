# Function: <code>bpf_sk_storage_tracing_allowed</code>

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
bool bpf_sk_storage_tracing_allowed(const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a69780)
Location: net/core/bpf_sk_storage.c:382
Inline: True
```
**Symbols:**

```
ffffffff81a69780-ffffffff81a697ff: bpf_sk_storage_tracing_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sk_storage_tracing_allowed(const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a51f20)
Location: net/core/bpf_sk_storage.c:382
Inline: True
```
**Symbols:**

```
ffffffff81a51f20-ffffffff81a51f9d: bpf_sk_storage_tracing_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sk_storage_tracing_allowed(const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81b0abb0)
Location: net/core/bpf_sk_storage.c:382
Inline: True
```
**Symbols:**

```
ffffffff81b0abb0-ffffffff81b0ac2d: bpf_sk_storage_tracing_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bpf_sk_storage_tracing_allowed(const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81c90fb0)
Location: net/core/bpf_sk_storage.c:387
Inline: False
```
**Symbols:**

```
ffffffff81c90fb0-ffffffff81c9106e: bpf_sk_storage_tracing_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_sk_storage_tracing_allowed(const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81e4c3b0)
Location: net/core/bpf_sk_storage.c:357
Inline: False
```
**Symbols:**

```
ffffffff81e4c3b0-ffffffff81e4c46e: bpf_sk_storage_tracing_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_sk_storage_tracing_allowed(const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81ea7ac0)
Location: net/core/bpf_sk_storage.c:352
Inline: False
```
**Symbols:**

```
ffffffff81ea7ac0-ffffffff81ea7b88: bpf_sk_storage_tracing_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bpf_sk_storage_tracing_allowed(const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81f6a570)
Location: net/core/bpf_sk_storage.c:353
Inline: False
```
**Symbols:**

```
ffffffff81f6a570-ffffffff81f6a638: bpf_sk_storage_tracing_allowed (STB_LOCAL)
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
