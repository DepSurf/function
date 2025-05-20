# Function: <code>__dev_xdp_query</code>

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
void __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, struct netdev_bpf *xdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81896dc0)
Location: net/core/dev.c:7282
Inline: True
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_xdp_uninstall
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
**Symbols:**

```
ffffffff81896dc0-ffffffff81896e03: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818b933d)
Location: net/core/dev.c:7900
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/rtnetlink.c:rtnl_xdp_prog_hw
  - net/core/rtnetlink.c:rtnl_xdp_prog_drv
```
**Symbols:**

```
ffffffff818af7f0-ffffffff818af868: __dev_xdp_query.part.139 (STB_LOCAL)
ffffffff818b92a0-ffffffff818b92b8: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff819054b6)
Location: net/core/dev.c:7997
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/rtnetlink.c:rtnl_xdp_prog_hw
  - net/core/rtnetlink.c:rtnl_xdp_prog_drv
```
**Symbols:**

```
ffffffff818fb640-ffffffff818fb6b9: __dev_xdp_query.part.0 (STB_LOCAL)
ffffffff819071ca-ffffffff819071dd: __dev_xdp_query.part.0.cold (STB_LOCAL)
ffffffff81905420-ffffffff81905438: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81937b76)
Location: net/core/dev.c:8296
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/rtnetlink.c:rtnl_xdp_prog_hw
  - net/core/rtnetlink.c:rtnl_xdp_prog_drv
```
**Symbols:**

```
ffffffff8192d790-ffffffff8192d809: __dev_xdp_query.part.0 (STB_LOCAL)
ffffffff81937ae0-ffffffff81937af8: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a0c6b5)
Location: net/core/dev.c:8709
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_xdp_uninstall
  - net/core/dev.c:dev_xdp_uninstall
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/rtnetlink.c:rtnl_xdp_fill
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
**Symbols:**

```
ffffffff81a005b0-ffffffff81a00628: __dev_xdp_query.part.0 (STB_LOCAL)
ffffffff81a0c620-ffffffff81a0c638: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffff800010bd65f0)
Location: net/core/dev.c:8296
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/rtnetlink.c:rtnl_xdp_prog_hw
  - net/core/rtnetlink.c:rtnl_xdp_prog_drv
```
**Symbols:**

```
ffff800010bc9608-ffff800010bc9694: __dev_xdp_query.part.0 (STB_LOCAL)
ffff800010bd6540-ffff800010bd658c: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c0cf1174)
Location: net/core/dev.c:8296
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/rtnetlink.c:rtnl_xdp_prog_hw
  - net/core/rtnetlink.c:rtnl_xdp_prog_drv
```
**Symbols:**

```
c0ce6a04-c0ce6ab0: __dev_xdp_query.part.0 (STB_LOCAL)
c0cf10e0-c0cf110c: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (c000000000cb6014)
Location: net/core/dev.c:8296
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/rtnetlink.c:rtnl_xdp_prog_hw
  - net/core/rtnetlink.c:rtnl_xdp_prog_drv
```
**Symbols:**

```
c000000000ca7180-c000000000ca7238: __dev_xdp_query.part.0 (STB_LOCAL)
c000000000cb5f40-c000000000cb5f68: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffe00075fd08)
Location: net/core/dev.c:8296
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/rtnetlink.c:rtnl_xdp_prog_hw
  - net/core/rtnetlink.c:rtnl_xdp_prog_drv
```
**Symbols:**

```
ffffffe00075649a-ffffffe000756504: __dev_xdp_query.part.0 (STB_LOCAL)
ffffffe00075fc60-ffffffe00075fca0: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818d7b46)
Location: net/core/dev.c:8296
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/rtnetlink.c:rtnl_xdp_prog_hw
  - net/core/rtnetlink.c:rtnl_xdp_prog_drv
```
**Symbols:**

```
ffffffff818cd790-ffffffff818cd809: __dev_xdp_query.part.0 (STB_LOCAL)
ffffffff818d7ab0-ffffffff818d7ac8: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81891986)
Location: net/core/dev.c:8296
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/rtnetlink.c:rtnl_xdp_prog_hw
  - net/core/rtnetlink.c:rtnl_xdp_prog_drv
```
**Symbols:**

```
ffffffff818878b0-ffffffff81887929: __dev_xdp_query.part.0 (STB_LOCAL)
ffffffff818918f0-ffffffff81891908: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81928b76)
Location: net/core/dev.c:8296
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/rtnetlink.c:rtnl_xdp_prog_hw
  - net/core/rtnetlink.c:rtnl_xdp_prog_drv
```
**Symbols:**

```
ffffffff8191e790-ffffffff8191e809: __dev_xdp_query.part.0 (STB_LOCAL)
ffffffff81928ae0-ffffffff81928af8: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 __dev_xdp_query(struct net_device *dev, bpf_op_t bpf_op, enum bpf_netdev_command cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8194a246)
Location: net/core/dev.c:8296
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/rtnetlink.c:rtnl_xdp_prog_hw
  - net/core/rtnetlink.c:rtnl_xdp_prog_drv
```
**Symbols:**

```
ffffffff81940100-ffffffff81940179: __dev_xdp_query.part.0 (STB_LOCAL)
ffffffff8194a1b0-ffffffff8194a1c8: __dev_xdp_query (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum bpf_netdev_command cmd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct netdev_bpf *xdp</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
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
