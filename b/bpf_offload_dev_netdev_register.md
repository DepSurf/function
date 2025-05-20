# Function: <code>bpf_offload_dev_netdev_register</code>

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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811df760)
Location: kernel/bpf/offload.c:559
Inline: False
```
**Symbols:**

```
ffffffff811df760-ffffffff811dfa29: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffffffff811f5f8f-ffffffff811f5f99: bpf_offload_dev_netdev_register.cold (STB_LOCAL)
ffffffff811f51e0-ffffffff811f5471: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffffffff81202f53-ffffffff81202f5d: bpf_offload_dev_netdev_register.cold (STB_LOCAL)
ffffffff812021e0-ffffffff81202471: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81229930)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffffffff81229930-ffffffff81229a24: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812314c0)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffffffff812314c0-ffffffff812315b4: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81235640)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffffffff81235640-ffffffff81235734: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8126f7e0)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffffffff8126f7e0-ffffffff8126f8d4: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812be1f0)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffffffff812be1f0-ffffffff812be2e9: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81321e50)
Location: kernel/bpf/offload.c:592
Inline: False
```
**Symbols:**

```
ffffffff81321e50-ffffffff81321f61: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81351540)
Location: kernel/bpf/offload.c:749
Inline: False
```
**Symbols:**

```
ffffffff81351540-ffffffff81351586: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff813789d0)
Location: kernel/bpf/offload.c:759
Inline: False
```
**Symbols:**

```
ffffffff813789d0-ffffffff81378a16: bpf_offload_dev_netdev_register (STB_GLOBAL)
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
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffff800010289d40)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffff800010289d40-ffff80001028a0cc: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04b9d30)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
c04b9d30-c04ba130: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c000000000335bb0)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
c000000000335bb0-c000000000336060: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001bddf6)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffffffe0001bddf6-ffffffe0001be0e4: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffffffff811fb573-ffffffff811fb57d: bpf_offload_dev_netdev_register.cold (STB_LOCAL)
ffffffff811fa800-ffffffff811faa91: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffffffff811ee2c3-ffffffff811ee2cd: bpf_offload_dev_netdev_register.cold (STB_LOCAL)
ffffffff811ed550-ffffffff811ed7e1: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffffffff811f9343-ffffffff811f934d: bpf_offload_dev_netdev_register.cold (STB_LOCAL)
ffffffff811f85d0-ffffffff811f8861: bpf_offload_dev_netdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int bpf_offload_dev_netdev_register(struct bpf_offload_dev *offdev, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:595
Inline: False
```
**Symbols:**

```
ffffffff81207de3-ffffffff81207ded: bpf_offload_dev_netdev_register.cold (STB_LOCAL)
ffffffff81206cf0-ffffffff81207032: bpf_offload_dev_netdev_register (STB_GLOBAL)
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
