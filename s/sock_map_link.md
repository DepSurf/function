# Function: <code>sock_map_link</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff818f1ed0)
Location: net/core/sock_map.c:147
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff818f1ed0-ffffffff818f21f1: sock_map_link.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81944360)
Location: net/core/sock_map.c:142
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff81944360-ffffffff8194467b: sock_map_link.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff81979360)
Location: net/core/sock_map.c:142
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff81979360-ffffffff8197967b: sock_map_link.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_map_link(struct bpf_map *map, struct sk_psock_progs *progs, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4eb90)
Location: net/core/sock_map.c:229
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff81a4eb90-ffffffff81a4ef84: sock_map_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_map_link(struct bpf_map *map, struct sk_psock_progs *progs, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a54ca0)
Location: net/core/sock_map.c:224
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff81a54ca0-ffffffff81a550ab: sock_map_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_map_link(struct bpf_map *map, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a50710)
Location: net/core/sock_map.c:216
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff81a50710-ffffffff81a50c96: sock_map_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_map_link(struct bpf_map *map, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b095d0)
Location: net/core/sock_map.c:217
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff81b095d0-ffffffff81b09abe: sock_map_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_map_link(struct bpf_map *map, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8f700)
Location: net/core/sock_map.c:217
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff81c8f700-ffffffff81c8fc9d: sock_map_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_map_link(struct bpf_map *map, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e4ab50)
Location: net/core/sock_map.c:217
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff81e4ab50-ffffffff81e4b0ed: sock_map_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_map_link(struct bpf_map *map, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea6240)
Location: net/core/sock_map.c:213
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff81ea6240-ffffffff81ea67e5: sock_map_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_map_link(struct bpf_map *map, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f68d00)
Location: net/core/sock_map.c:213
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff81f68d00-ffffffff81f692a5: sock_map_link (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffff800010c202a0)
Location: net/core/sock_map.c:142
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffff800010c202a0-ffff800010c20654: sock_map_link.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_map_link(struct bpf_map *map, struct sk_psock_progs *progs, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d37ca8)
Location: net/core/sock_map.c:142
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
c0d37ca8-c0d38000: sock_map_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (c000000000d12110)
Location: net/core/sock_map.c:142
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
c000000000d12110-c000000000d125cc: sock_map_link.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffe0007991b2)
Location: net/core/sock_map.c:142
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffe0007991b2-ffffffe0007993e8: sock_map_link.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff819191d0)
Location: net/core/sock_map.c:142
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff819191d0-ffffffff819194eb: sock_map_link.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff818d2f80)
Location: net/core/sock_map.c:142
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff818d2f80-ffffffff818d329b: sock_map_link.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff8196a360)
Location: net/core/sock_map.c:142
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff8196a360-ffffffff8196a67b: sock_map_link.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (ffffffff8198c7d0)
Location: net/core/sock_map.c:142
Inline: True
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
**Symbols:**

```
ffffffff8198c7d0-ffffffff8198cae8: sock_map_link.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct sk_psock_progs *progs</code>
</li>
<li>
<b>Param reordered. </b>
<code>map, progs, sk</code> ➡️ <code>map, sk</code>
</li>
</ul>
</details>
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
</ul>
