# Function: <code>__bpf_map_offload_destroy</code>

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
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811cb5b0)
Location: kernel/bpf/offload.c:336
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_notification
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff811cb5b0-ffffffff811cb614: __bpf_map_offload_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811def70)
Location: kernel/bpf/offload.c:375
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff811def70-ffffffff811defd4: __bpf_map_offload_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff811f48e0-ffffffff811f4944: __bpf_map_offload_destroy (STB_LOCAL)
ffffffff811f5f56-ffffffff811f5f69: __bpf_map_offload_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812018e0)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff812018e0-ffffffff81201944: __bpf_map_offload_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81228cc0)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff81228cc0-ffffffff81228d27: __bpf_map_offload_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81230800)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff81230800-ffffffff81230867: __bpf_map_offload_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812349b0)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff812349b0-ffffffff81234a17: __bpf_map_offload_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8126f590)
Location: kernel/bpf/offload.c:411
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812be8c9)
Location: kernel/bpf/offload.c:411
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81321b65)
Location: kernel/bpf/offload.c:408
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81352808)
Location: kernel/bpf/offload.c:135
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81379ce8)
Location: kernel/bpf/offload.c:136
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffff800010289a90)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffff800010289a90-ffff800010289af4: __bpf_map_offload_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04b92e8)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
c04b92e8-c04b9360: __bpf_map_offload_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c000000000335200)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
c000000000335200-c000000000335284: __bpf_map_offload_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001bdcd4)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffe0001bdcd4-ffffffe0001bdd26: __bpf_map_offload_destroy (STB_LOCAL)
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
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f9f00)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff811f9f00-ffffffff811f9f64: __bpf_map_offload_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811ecc50)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff811ecc50-ffffffff811eccb4: __bpf_map_offload_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f7cd0)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff811f7cd0-ffffffff811f7d34: __bpf_map_offload_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_map_offload_destroy(struct bpf_offloaded_map *offmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81206250)
Location: kernel/bpf/offload.c:411
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff81206250-ffffffff812062b4: __bpf_map_offload_destroy (STB_LOCAL)
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
