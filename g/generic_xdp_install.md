# Function: <code>generic_xdp_install</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_xdp *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d3200)
Location: net/core/dev.c:4343
Inline: True
```
**Symbols:**

```
ffffffff817d3200-ffffffff817d3292: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184d5f0)
Location: net/core/dev.c:4569
Inline: True
```
**Symbols:**

```
ffffffff8184d5f0-ffffffff8184d682: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81897b80)
Location: net/core/dev.c:4698
Inline: True
Direct callers:
  - net/core/dev.c:dev_xdp_uninstall
```
**Symbols:**

```
ffffffff81897b80-ffffffff81897caa: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b9fb0)
Location: net/core/dev.c:5118
Inline: True
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818b9fb0-ffffffff818ba0d3: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81906160)
Location: net/core/dev.c:5157
Inline: True
```
**Symbols:**

```
ffffffff81906160-ffffffff8190628c: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81938850)
Location: net/core/dev.c:5059
Inline: True
```
**Symbols:**

```
ffffffff81938850-ffffffff8193897c: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0d220)
Location: net/core/dev.c:5430
Inline: False
Direct callers:
  - net/core/dev.c:dev_xdp_uninstall
  - net/core/dev.c:dev_xdp_uninstall
  - net/core/dev.c:dev_xdp_uninstall
```
**Symbols:**

```
ffffffff81a0d220-ffffffff81a0d3de: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0f0b0)
Location: net/core/dev.c:5484
Inline: False
```
**Symbols:**

```
ffffffff81a0f0b0-ffffffff81a0f2b0: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f5de0)
Location: net/core/dev.c:5608
Inline: False
```
**Symbols:**

```
ffffffff819f5de0-ffffffff819f5fe0: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5597
Inline: False
```
**Symbols:**

```
ffffffff81aa77f0-ffffffff81aa7960: generic_xdp_install (STB_LOCAL)
ffffffff81d368a2-ffffffff81d368b7: generic_xdp_install.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5634
Inline: False
```
**Symbols:**

```
ffffffff81c1f730-ffffffff81c1f8a5: generic_xdp_install (STB_LOCAL)
ffffffff81f03110-ffffffff81f03125: generic_xdp_install.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5625
Inline: False
```
**Symbols:**

```
ffffffff81dd0510-ffffffff81dd0685: generic_xdp_install (STB_LOCAL)
ffffffff820ab972-ffffffff820ab987: generic_xdp_install.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5601
Inline: False
```
**Symbols:**

```
ffffffff81e41110-ffffffff81e41285: generic_xdp_install (STB_LOCAL)
ffffffff8212d0af-ffffffff8212d0c4: generic_xdp_install.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5683
Inline: False
```
**Symbols:**

```
ffffffff81effa40-ffffffff81effbd1: generic_xdp_install (STB_LOCAL)
ffffffff8220edc7-ffffffff8220eddc: generic_xdp_install.cold (STB_LOCAL)
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
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd7218)
Location: net/core/dev.c:5059
Inline: True
```
**Symbols:**

```
ffff800010bd7218-ffff800010bd739c: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf2138)
Location: net/core/dev.c:5059
Inline: True
```
**Symbols:**

```
c0cf2138-c0cf239c: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb7040)
Location: net/core/dev.c:5059
Inline: True
```
**Symbols:**

```
c000000000cb7040-c000000000cb7244: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000760884)
Location: net/core/dev.c:5059
Inline: True
```
**Symbols:**

```
ffffffe000760884-ffffffe000760a3a: generic_xdp_install (STB_LOCAL)
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
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d8820)
Location: net/core/dev.c:5059
Inline: True
```
**Symbols:**

```
ffffffff818d8820-ffffffff818d894c: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81892660)
Location: net/core/dev.c:5059
Inline: True
```
**Symbols:**

```
ffffffff81892660-ffffffff8189278c: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81929850)
Location: net/core/dev.c:5059
Inline: True
```
**Symbols:**

```
ffffffff81929850-ffffffff8192997c: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int generic_xdp_install(struct net_device *dev, struct netdev_bpf *xdp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194af20)
Location: net/core/dev.c:5059
Inline: True
```
**Symbols:**

```
ffffffff8194af20-ffffffff8194b04c: generic_xdp_install (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct netdev_xdp *xdp</code> ➡️ <code>struct netdev_bpf *xdp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
