# Function: <code>sock_hash_alloc</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811ccb20)
Location: kernel/bpf/sockmap.c:2139
Inline: True
```
**Symbols:**

```
ffffffff811ccb20-ffffffff811cccd3: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f1960)
Location: net/core/sock_map.c:786
Inline: True
```
**Symbols:**

```
ffffffff818f1960-ffffffff818f1ace: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81943cf0)
Location: net/core/sock_map.c:793
Inline: True
```
**Symbols:**

```
ffffffff81943cf0-ffffffff81943e6c: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81978ce0)
Location: net/core/sock_map.c:803
Inline: True
```
**Symbols:**

```
ffffffff81978ce0-ffffffff81978e5c: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4e110)
Location: net/core/sock_map.c:994
Inline: True
```
**Symbols:**

```
ffffffff81a4e110-ffffffff81a4e2ac: sock_hash_alloc.part.0 (STB_LOCAL)
ffffffff81a4e2b0-ffffffff81a4e2e5: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81a54100)
Location: net/core/sock_map.c:1094
Inline: True
```
**Symbols:**

```
ffffffff81a54100-ffffffff81a54255: sock_hash_alloc.part.0 (STB_LOCAL)
ffffffff81a54260-ffffffff81a54295: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4fc10)
Location: net/core/sock_map.c:1079
Inline: True
```
**Symbols:**

```
ffffffff81a4fc10-ffffffff81a4fd62: sock_hash_alloc.part.0 (STB_LOCAL)
ffffffff81a4fd70-ffffffff81a4fda5: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81b08950)
Location: net/core/sock_map.c:1070
Inline: True
```
**Symbols:**

```
ffffffff81b087e0-ffffffff81b08943: sock_hash_alloc.part.0 (STB_LOCAL)
ffffffff81d38af3-ffffffff81d38b11: sock_hash_alloc.part.0.cold (STB_LOCAL)
ffffffff81b08950-ffffffff81b08985: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8e960)
Location: net/core/sock_map.c:1072
Inline: True
```
**Symbols:**

```
ffffffff81c8e7c0-ffffffff81c8e95c: sock_hash_alloc.part.0 (STB_LOCAL)
ffffffff81f0534d-ffffffff81f0536b: sock_hash_alloc.part.0.cold (STB_LOCAL)
ffffffff81c8e960-ffffffff81c8e99a: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81e49670)
Location: net/core/sock_map.c:1074
Inline: True
```
**Symbols:**

```
ffffffff81e494d0-ffffffff81e4965c: sock_hash_alloc.part.0 (STB_LOCAL)
ffffffff820ad35a-ffffffff820ad378: sock_hash_alloc.part.0.cold (STB_LOCAL)
ffffffff81e49670-ffffffff81e496aa: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea4c41)
Location: net/core/sock_map.c:1079
Inline: True
```
**Symbols:**

```
ffffffff81ea4be0-ffffffff81ea4d6c: sock_hash_alloc (STB_LOCAL)
ffffffff8212e509-ffffffff8212e527: sock_hash_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81f67760)
Location: net/core/sock_map.c:1083
Inline: True
```
**Symbols:**

```
ffffffff81f67600-ffffffff81f6774d: sock_hash_alloc.part.0 (STB_LOCAL)
ffffffff822102ee-ffffffff8221030c: sock_hash_alloc.part.0.cold (STB_LOCAL)
ffffffff81f67760-ffffffff81f677c1: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c1f890)
Location: net/core/sock_map.c:803
Inline: True
```
**Symbols:**

```
ffff800010c1f890-ffff800010c1fa28: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d374ac)
Location: net/core/sock_map.c:803
Inline: True
```
**Symbols:**

```
c0d374ac-c0d37654: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d12a80)
Location: net/core/sock_map.c:803
Inline: True
```
**Symbols:**

```
c000000000d12a80-c000000000d12c60: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe0007996a6)
Location: net/core/sock_map.c:803
Inline: True
```
**Symbols:**

```
ffffffe0007996a6-ffffffe000799846: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81918b50)
Location: net/core/sock_map.c:803
Inline: True
```
**Symbols:**

```
ffffffff81918b50-ffffffff81918ccc: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d2900)
Location: net/core/sock_map.c:803
Inline: True
```
**Symbols:**

```
ffffffff818d2900-ffffffff818d2a7c: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81969ce0)
Location: net/core/sock_map.c:803
Inline: True
```
**Symbols:**

```
ffffffff81969ce0-ffffffff81969e5c: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *sock_hash_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198c100)
Location: net/core/sock_map.c:803
Inline: True
```
**Symbols:**

```
ffffffff8198c100-ffffffff8198c27c: sock_hash_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
