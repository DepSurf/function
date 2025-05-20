# Function: <code>bpf_sk_storage_delete</code>

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
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81953710)
Location: net/core/bpf_sk_storage.c:773
Inline: False
```
**Symbols:**

```
ffffffff81953710-ffffffff81953787: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81989ab0)
Location: net/core/bpf_sk_storage.c:872
Inline: False
```
**Symbols:**

```
ffffffff81989ab0-ffffffff81989b27: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a61160)
Location: net/core/bpf_sk_storage.c:876
Inline: False
```
**Symbols:**

```
ffffffff81a61160-ffffffff81a61240: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a69e70)
Location: net/core/bpf_sk_storage.c:289
Inline: False
```
**Symbols:**

```
ffffffff81a69e70-ffffffff81a69f6e: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a52370)
Location: net/core/bpf_sk_storage.c:289
Inline: False
```
**Symbols:**

```
ffffffff81a52370-ffffffff81a5246a: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:289
Inline: False
```
**Symbols:**

```
ffffffff81d38c1b-ffffffff81d38c3b: bpf_sk_storage_delete.cold (STB_LOCAL)
ffffffff81b0b450-ffffffff81b0b565: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:293
Inline: False
```
**Symbols:**

```
ffffffff81f05497-ffffffff81f054b7: bpf_sk_storage_delete.cold (STB_LOCAL)
ffffffff81c91ce0-ffffffff81c91e25: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:264
Inline: False
```
**Symbols:**

```
ffffffff820ad4a4-ffffffff820ad4c4: bpf_sk_storage_delete.cold (STB_LOCAL)
ffffffff81e4d2c0-ffffffff81e4d405: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:258
Inline: False
```
**Symbols:**

```
ffffffff8212e614-ffffffff8212e62d: bpf_sk_storage_delete.cold (STB_LOCAL)
ffffffff81ea8990-ffffffff81ea8aca: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:258
Inline: False
```
**Symbols:**

```
ffffffff822103c7-ffffffff822103e0: bpf_sk_storage_delete.cold (STB_LOCAL)
ffffffff81f6b450-ffffffff81f6b58a: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffff800010c31838)
Location: net/core/bpf_sk_storage.c:872
Inline: False
```
**Symbols:**

```
ffff800010c31838-ffff800010c318c4: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c0d48bdc)
Location: net/core/bpf_sk_storage.c:872
Inline: False
```
**Symbols:**

```
c0d48bdc-c0d48c50: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c000000000d2a980)
Location: net/core/bpf_sk_storage.c:872
Inline: False
```
**Symbols:**

```
c000000000d2a980-c000000000d2aa60: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffe0007a7af2)
Location: net/core/bpf_sk_storage.c:872
Inline: False
```
**Symbols:**

```
ffffffe0007a7af2-ffffffe0007a7b78: bpf_sk_storage_delete (STB_GLOBAL)
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
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81929920)
Location: net/core/bpf_sk_storage.c:872
Inline: False
```
**Symbols:**

```
ffffffff81929920-ffffffff81929997: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff818e36d0)
Location: net/core/bpf_sk_storage.c:872
Inline: False
```
**Symbols:**

```
ffffffff818e36d0-ffffffff818e3747: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8197aab0)
Location: net/core/bpf_sk_storage.c:872
Inline: False
```
**Symbols:**

```
ffffffff8197aab0-ffffffff8197ab27: bpf_sk_storage_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_sk_storage_delete(u64 map, u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8199cfe0)
Location: net/core/bpf_sk_storage.c:872
Inline: False
```
**Symbols:**

```
ffffffff8199cfe0-ffffffff8199d057: bpf_sk_storage_delete (STB_GLOBAL)
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
