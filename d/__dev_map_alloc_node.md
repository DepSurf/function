# Function: <code>__dev_map_alloc_node</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, u32 ifindex, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ff390)
Location: kernel/bpf/devmap.c:584
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff811ff390-ffffffff811ff481: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, struct bpf_devmap_val *val, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812266c0)
Location: kernel/bpf/devmap.c:598
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff812266c0-ffffffff812267cd: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, struct bpf_devmap_val *val, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8122d2b0)
Location: kernel/bpf/devmap.c:583
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff8122d2b0-ffffffff8122d3b7: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, struct bpf_devmap_val *val, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81232080)
Location: kernel/bpf/devmap.c:576
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff81232080-ffffffff81232185: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, struct bpf_devmap_val *val, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126b2d0)
Location: kernel/bpf/devmap.c:848
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff8126b2d0-ffffffff8126b3da: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, struct bpf_devmap_val *val, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812b9ef0)
Location: kernel/bpf/devmap.c:839
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff812b9ef0-ffffffff812ba01e: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, struct bpf_devmap_val *val, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131d240)
Location: kernel/bpf/devmap.c:839
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff8131d240-ffffffff8131d36e: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, struct bpf_devmap_val *val, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134cff0)
Location: kernel/bpf/devmap.c:848
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_update_elem
```
**Symbols:**

```
ffffffff8134cff0-ffffffff8134d11e: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, struct bpf_devmap_val *val, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81374520)
Location: kernel/bpf/devmap.c:857
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_update_elem
```
**Symbols:**

```
ffffffff81374520-ffffffff8137463c: __dev_map_alloc_node (STB_LOCAL)
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
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, u32 ifindex, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffff800010286658)
Location: kernel/bpf/devmap.c:584
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffff800010286658-ffff80001028676c: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, u32 ifindex, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c04b6a30)
Location: kernel/bpf/devmap.c:584
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
c04b6a30-c04b6b38: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, u32 ifindex, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c000000000331850)
Location: kernel/bpf/devmap.c:584
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
c000000000331850-c0000000003319e0: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, u32 ifindex, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffe0001bb69c)
Location: kernel/bpf/devmap.c:584
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffe0001bb69c-ffffffe0001bb7a4: __dev_map_alloc_node (STB_LOCAL)
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
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, u32 ifindex, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f79b0)
Location: kernel/bpf/devmap.c:584
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff811f79b0-ffffffff811f7aa1: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, u32 ifindex, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ea700)
Location: kernel/bpf/devmap.c:584
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff811ea700-ffffffff811ea7f1: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, u32 ifindex, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f5780)
Location: kernel/bpf/devmap.c:584
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff811f5780-ffffffff811f5871: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_dtab_netdev *__dev_map_alloc_node(struct net *net, struct bpf_dtab *dtab, u32 ifindex, unsigned int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81203ce0)
Location: kernel/bpf/devmap.c:584
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
```
**Symbols:**

```
ffffffff81203ce0-ffffffff81203dd1: __dev_map_alloc_node (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_devmap_val *val</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 ifindex</code>
</li>
</ul>
</details>
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
