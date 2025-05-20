# Function: <code>bpf_map_offload_ndo</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811cb460)
Location: kernel/bpf/offload.c:278
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff811cb460-ffffffff811cb51d: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811deeb0)
Location: kernel/bpf/offload.c:310
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff811deeb0-ffffffff811def6d: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f47f0)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff811f47f0-ffffffff811f48ad: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81201820)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff81201820-ffffffff812018dd: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81228c00)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff81228c00-ffffffff81228cbd: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81230740)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff81230740-ffffffff812307fd: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812348f0)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff812348f0-ffffffff812349ad: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff8126ea50-ffffffff8126eb20: bpf_map_offload_ndo (STB_LOCAL)
ffffffff81cb9624-ffffffff81cb9639: bpf_map_offload_ndo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff812bd9b0-ffffffff812bda8d: bpf_map_offload_ndo (STB_LOCAL)
ffffffff81e6aa48-ffffffff81e6aa5d: bpf_map_offload_ndo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:343
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff81320eb0-ffffffff81320f8d: bpf_map_offload_ndo (STB_LOCAL)
ffffffff82061add-ffffffff82061af2: bpf_map_offload_ndo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:119
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
**Symbols:**

```
ffffffff81350bd0-ffffffff81350cad: bpf_map_offload_ndo (STB_LOCAL)
ffffffff820e1171-ffffffff820e1186: bpf_map_offload_ndo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:120
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
**Symbols:**

```
ffffffff81378000-ffffffff813780da: bpf_map_offload_ndo (STB_LOCAL)
ffffffff821bd9d0-ffffffff821bd9e5: bpf_map_offload_ndo.cold (STB_LOCAL)
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
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffff8000102899d8)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffff8000102899d8-ffff800010289a90: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04b9214)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
c04b9214-c04b92e8: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c000000000335100)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
c000000000335100-c0000000003351f8: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001bdc48)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffe0001bdc48-ffffffe0001bdcd4: bpf_map_offload_ndo (STB_LOCAL)
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
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f9e40)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff811f9e40-ffffffff811f9efd: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811ecb90)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff811ecb90-ffffffff811ecc4d: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f7c10)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff811f7c10-ffffffff811f7ccd: bpf_map_offload_ndo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_map_offload_ndo(struct bpf_offloaded_map *offmap, enum bpf_netdev_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81206190)
Location: kernel/bpf/offload.c:346
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
```
**Symbols:**

```
ffffffff81206190-ffffffff8120624d: bpf_map_offload_ndo (STB_LOCAL)
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
