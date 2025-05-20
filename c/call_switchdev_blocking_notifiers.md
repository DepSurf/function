# Function: <code>call_switchdev_blocking_notifiers</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fc534)
Location: net/switchdev/switchdev.c:583
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff819fc4c0-ffffffff819fc4e1: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a6b506)
Location: net/switchdev/switchdev.c:437
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff81a6b490-ffffffff81a6b4b1: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aa1ef4)
Location: net/switchdev/switchdev.c:437
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff81aa1e80-ffffffff81aa1ea1: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9d8bd)
Location: net/switchdev/switchdev.c:437
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff81b9d850-ffffffff81b9d871: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81bad1cd)
Location: net/switchdev/switchdev.c:436
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff81bad160-ffffffff81bad181: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9c446)
Location: net/switchdev/switchdev.c:370
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff81b9c3f0-ffffffff81b9c411: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81c699eb)
Location: net/switchdev/switchdev.c:370
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff81c692a0-ffffffff81c692c1: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81e0cb01)
Location: net/switchdev/switchdev.c:371
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff81e0c530-ffffffff81e0c55d: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81fe2cb1)
Location: net/switchdev/switchdev.c:371
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff81fe2630-ffffffff81fe265d: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8205efd1)
Location: net/switchdev/switchdev.c:371
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff8205e950-ffffffff8205e97d: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff82131f0a)
Location: net/switchdev/switchdev.c:444
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_bridge_port_replay
  - net/switchdev/switchdev.c:switchdev_bridge_port_unoffload
  - net/switchdev/switchdev.c:switchdev_bridge_port_offload
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff82131630-ffffffff8213165d: call_switchdev_blocking_notifiers (STB_GLOBAL)
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
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffff800010d73400)
Location: net/switchdev/switchdev.c:437
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffff800010d73358-ffff800010d733a8: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c0e7042c)
Location: net/switchdev/switchdev.c:437
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
c0e703a8-c0e703dc: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c000000000eb28e4)
Location: net/switchdev/switchdev.c:437
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
c000000000eb2840-c000000000eb2890: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffe0008a3900)
Location: net/switchdev/switchdev.c:437
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffe0008a388c-ffffffe0008a38da: call_switchdev_blocking_notifiers (STB_GLOBAL)
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
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a41284)
Location: net/switchdev/switchdev.c:437
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff81a41210-ffffffff81a41231: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fde74)
Location: net/switchdev/switchdev.c:437
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff819fde00-ffffffff819fde21: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aad134)
Location: net/switchdev/switchdev.c:437
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff81aad0c0-ffffffff81aad0e1: call_switchdev_blocking_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int call_switchdev_blocking_notifiers(long unsigned int val, struct net_device *dev, struct switchdev_notifier_info *info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81ab94a4)
Location: net/switchdev/switchdev.c:437
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_notify
```
**Symbols:**

```
ffffffff81ab9430-ffffffff81ab9451: call_switchdev_blocking_notifiers (STB_GLOBAL)
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
