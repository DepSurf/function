# Function: <code>bpf_offload_dev_netdev_unregister</code>

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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811df2e0)
Location: kernel/bpf/offload.c:592
Inline: False
```
**Symbols:**

```
ffffffff811df2e0-ffffffff811df760: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffffffff811f5f69-ffffffff811f5f8f: bpf_offload_dev_netdev_unregister.cold (STB_LOCAL)
ffffffff811f4cb0-ffffffff811f51d8: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81201cc0)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffffffff81201cc0-ffffffff812021de: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81229460)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffffffff81229460-ffffffff8122975b: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81230ff0)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffffffff81230ff0-ffffffff812312d5: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81235180)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffffffff81235180-ffffffff81235465: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffffffff81cb9690-ffffffff81cb96a4: bpf_offload_dev_netdev_unregister.cold (STB_LOCAL)
ffffffff8126f2c0-ffffffff8126f605: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffffffff81e6aab4-ffffffff81e6aac8: bpf_offload_dev_netdev_unregister.cold (STB_LOCAL)
ffffffff812be570-ffffffff812be947: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:625
Inline: False
```
**Symbols:**

```
ffffffff82061b49-ffffffff82061b5d: bpf_offload_dev_netdev_unregister.cold (STB_LOCAL)
ffffffff813218b0-ffffffff81321bdf: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81351dc0)
Location: kernel/bpf/offload.c:761
Inline: False
```
**Symbols:**

```
ffffffff81351dc0-ffffffff81351e02: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff813792a0)
Location: kernel/bpf/offload.c:771
Inline: False
```
**Symbols:**

```
ffffffff813792a0-ffffffff813792e2: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffff80001028a0d0)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffff80001028a0d0-ffff80001028a5c0: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04b9694)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
c04b9694-c04b9d30: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c000000000335460)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
c000000000335460-c000000000335a48: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001be234)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffffffe0001be234-ffffffe0001be5fe: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
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
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811fa2e0)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffffffff811fa2e0-ffffffff811fa7fe: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811ed030)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffffffff811ed030-ffffffff811ed54e: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f80b0)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffffffff811f80b0-ffffffff811f85ce: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_offload_dev_netdev_unregister(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81206400)
Location: kernel/bpf/offload.c:628
Inline: False
```
**Symbols:**

```
ffffffff81206400-ffffffff81206998: bpf_offload_dev_netdev_unregister (STB_GLOBAL)
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
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
