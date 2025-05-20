# Function: <code>bpf_sk_assign</code>

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
u64 bpf_sk_assign(u64 skb, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2d0a0)
Location: net/core/filter.c:6060
Inline: False
```
**Symbols:**

```
ffffffff81a2d0a0-ffffffff81a2d1ae: bpf_sk_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_sk_assign(u64 skb, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2ee20)
Location: net/core/filter.c:6612
Inline: False
```
**Symbols:**

```
ffffffff81a2ee20-ffffffff81a2ef35: bpf_sk_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sk_assign(u64 skb, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a163d0)
Location: net/core/filter.c:6714
Inline: False
```
**Symbols:**

```
ffffffff81a163d0-ffffffff81a164e1: bpf_sk_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_assign(u64 skb, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6838
Inline: False
```
**Symbols:**

```
ffffffff81d37677-ffffffff81d376b7: bpf_sk_assign.cold (STB_LOCAL)
ffffffff81accc60-ffffffff81accd9b: bpf_sk_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_assign(u64 skb, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:7177
Inline: False
```
**Symbols:**

```
ffffffff81f03fcb-ffffffff81f0400b: bpf_sk_assign.cold (STB_LOCAL)
ffffffff81c49940-ffffffff81c49ab9: bpf_sk_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_assign(u64 skb, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:7189
Inline: False
```
**Symbols:**

```
ffffffff820ac79c-ffffffff820ac7dc: bpf_sk_assign.cold (STB_LOCAL)
ffffffff81dfeb70-ffffffff81dfecec: bpf_sk_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_assign(u64 skb, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:7345
Inline: False
```
**Symbols:**

```
ffffffff8212de01-ffffffff8212de33: bpf_sk_assign.cold (STB_LOCAL)
ffffffff81e70130-ffffffff81e70298: bpf_sk_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_assign(u64 skb, u64 sk, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:7432
Inline: False
```
**Symbols:**

```
ffffffff8220f61d-ffffffff8220f636: bpf_sk_assign.cold (STB_LOCAL)
ffffffff81f2a3b0-ffffffff81f2a4e6: bpf_sk_assign (STB_GLOBAL)
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
