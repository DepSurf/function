# Function: <code>netdev_reg_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff814152a4)
Location: include/linux/netdevice.h:3962
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81719a1f)
Location: include/linux/netdevice.h:3962
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8145cfa4)
Location: include/linux/netdevice.h:4256
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff8178735c)
Location: include/linux/netdevice.h:4256
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8147baa4)
Location: include/linux/netdevice.h:4210
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff817b491c)
Location: include/linux/netdevice.h:4210
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81484e0a)
Location: include/linux/netdevice.h:4273
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff817d2c32)
Location: include/linux/netdevice.h:4273
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff817c7bd0-ffffffff817c7c62: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff814c0e4a)
Location: include/linux/netdevice.h:4307
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff8184d9b5)
Location: include/linux/netdevice.h:4307
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff814f0e6e)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81898942)
Location: include/linux/netdevice.h:4414
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8150582e)
Location: include/linux/netdevice.h:4656
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff818bada2)
Location: include/linux/netdevice.h:4656
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8153386e)
Location: include/linux/netdevice.h:4682
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81906701)
Location: include/linux/netdevice.h:4682
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
```
**Symbols:**

```
ffffffff818f8b00-ffffffff818f8b50: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff815546ae)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81938cc0)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
```
**Symbols:**

```
ffffffff8192aca0-ffffffff8192acf0: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff815dda9e)
Location: include/linux/netdevice.h:4888
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81a0deb3)
Location: include/linux/netdevice.h:4888
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_sync_lower_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffff81a0e842-ffffffff81a0e88d: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff815fb78e)
Location: include/linux/netdevice.h:5089
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81a0ec93)
Location: include/linux/netdevice.h:5089
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_sync_lower_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffff81c30b36-ffffffff81c30b81: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff815de40b)
Location: include/linux/netdevice.h:5220
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff819f5a3f)
Location: include/linux/netdevice.h:5220
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffff81c22e1c-ffffffff81c22e67: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81649e8b)
Location: include/linux/netdevice.h:5268
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81aa741e)
Location: include/linux/netdevice.h:5268
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffff81d35916-ffffffff81d35988: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8175f584)
Location: include/linux/netdevice.h:5088
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81c1fb11)
Location: include/linux/netdevice.h:5088
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
```
In net/core/dev_addr_lists.c (ffffffff81c21444)
Location: include/linux/netdevice.h:5088
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_addr_check
```
**Symbols:**

```
ffffffff81f01f2b-ffffffff81f01fab: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8188d164)
Location: include/linux/netdevice.h:5127
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81dc351f)
Location: include/linux/netdevice.h:5127
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
```
```
In net/core/dev_addr_lists.c (ffffffff81dd353a)
Location: include/linux/netdevice.h:5127
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_addr_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff818cf6d4)
Location: include/linux/netdevice.h:5171
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81e329bf)
Location: include/linux/netdevice.h:5171
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
```
```
In net/core/dev_addr_lists.c (ffffffff81e440fa)
Location: include/linux/netdevice.h:5171
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_addr_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8192156c)
Location: include/linux/netdevice.h:5252
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81ef0dbf)
Location: include/linux/netdevice.h:5252
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/core/dev.c:dev_disable_lro
```
```
In net/core/dev_addr_lists.c (ffffffff81f02d4a)
Location: include/linux/netdevice.h:5252
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_addr_check
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffff800010660e8c)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffff800010bd7638)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffff800010bc7550-ffff800010bc75c4: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (c0809f00)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (c0cf27e8)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
c0ce2828-c0ce28b0: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (c0000000008130e4)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (c000000000cb75d4)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
c000000000ca2a10-c000000000ca2aa0: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffe00048da7e)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffe000760c64)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
Direct callers:
  - net/core/dev.c:__netdev_printk
  - net/core/dev.c:__netdev_printk
```
**Symbols:**

```
ffffffe000753ac6-ffffffe000753b28: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8154cc8e)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff818d8c90)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
```
**Symbols:**

```
ffffffff818caca0-ffffffff818cacf0: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8153cf6e)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81892ad0)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
```
**Symbols:**

```
ffffffff81884be0-ffffffff81884c30: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff815489ce)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff81929cc0)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
```
**Symbols:**

```
ffffffff8191bca0-ffffffff8191bcf0: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const char *netdev_reg_state(const struct net_device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8156281e)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
  - lib/dynamic_debug.c:__dynamic_netdev_dbg
```
```
In net/core/dev.c (ffffffff8194b38b)
Location: include/linux/netdevice.h:4695
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:dev_disable_lro
```
**Symbols:**

```
ffffffff8193d180-ffffffff8193d1d0: netdev_reg_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
