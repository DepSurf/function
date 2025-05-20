# Function: <code>bpf_offload_find_netdev</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811df0f0)
Location: kernel/bpf/offload.c:70
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffff811df0f0-ffffffff811df223: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f4a80)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffff811f4a80-ffffffff811f4be8: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81201a90)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffff81201a90-ffffffff81201bf8: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81228ff0)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_match
  - kernel/bpf/offload.c:__bpf_offload_dev_match
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffff81228ff0-ffffffff8122906b: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81230a00)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_match
  - kernel/bpf/offload.c:__bpf_offload_dev_match
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffff81230a00-ffffffff81230b0a: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81234bb0)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_match
  - kernel/bpf/offload.c:__bpf_offload_dev_match
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffff81234bb0-ffffffff81234cb2: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffff8126ecc0-ffffffff8126edce: bpf_offload_find_netdev (STB_LOCAL)
ffffffff81cb964d-ffffffff81cb9661: bpf_offload_find_netdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffff812bdcc0-ffffffff812bdde5: bpf_offload_find_netdev (STB_LOCAL)
ffffffff81e6aa71-ffffffff81e6aa85: bpf_offload_find_netdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffff81321210-ffffffff81321335: bpf_offload_find_netdev (STB_LOCAL)
ffffffff82061b06-ffffffff82061b1a: bpf_offload_find_netdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81350e50)
Location: kernel/bpf/offload.c:70
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_dev_bound_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_dev_bound_destroy
  - kernel/bpf/offload.c:__bpf_prog_dev_bound_init
  - kernel/bpf/offload.c:__bpf_prog_dev_bound_init
```
**Symbols:**

```
ffffffff81350e50-ffffffff81350f95: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff813782b0)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_dev_bound_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_dev_bound_destroy
  - kernel/bpf/offload.c:__bpf_prog_dev_bound_init
  - kernel/bpf/offload.c:__bpf_prog_dev_bound_init
```
**Symbols:**

```
ffffffff813782b0-ffffffff813783f5: bpf_offload_find_netdev (STB_LOCAL)
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
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffff80001028a5c0)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffff80001028a5c0-ffff80001028a760: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04b9414)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_match
  - kernel/bpf/offload.c:__bpf_offload_dev_match
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
c04b9414-c04b95b4: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c000000000336060)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
c000000000336060-c00000000033628c: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001be5fe)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffe0001be5fe-ffffffe0001be774: bpf_offload_find_netdev (STB_LOCAL)
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
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811fa0b0)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffff811fa0b0-ffffffff811fa218: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811ece00)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffff811ece00-ffffffff811ecf68: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_offload_netdev *bpf_offload_find_netdev(struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f7e80)
Location: kernel/bpf/offload.c:71
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
**Symbols:**

```
ffffffff811f7e80-ffffffff811f7fe8: bpf_offload_find_netdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812078d4)
Location: kernel/bpf/offload.c:71
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
