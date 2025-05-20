# Function: <code>dev_xdp_install</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d2877)
Location: net/core/dev.c:6965
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184cbc0)
Location: net/core/dev.c:7129
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81896eed)
Location: net/core/dev.c:7301
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_xdp_uninstall
  - net/core/dev.c:dev_xdp_uninstall
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dev_xdp_install(struct net_device *dev, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ba374)
Location: net/core/dev.c:7917
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
```
**Symbols:**

```
ffffffff818accd0-ffffffff818acd35: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f8450)
Location: net/core/dev.c:8014
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
```
**Symbols:**

```
ffffffff818f8450-ffffffff818f84b4: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a5f0)
Location: net/core/dev.c:8313
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
```
**Symbols:**

```
ffffffff8192a5f0-ffffffff8192a654: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dev_xdp_install(struct net_device *dev, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0d407)
Location: net/core/dev.c:8726
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_uninstall
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_xdp_uninstall
  - net/core/dev.c:dev_xdp_uninstall
```
**Symbols:**

```
ffffffff81a00630-ffffffff81a0077c: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ffcf0)
Location: net/core/dev.c:9099
Inline: False
Direct callers:
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_uninstall
```
**Symbols:**

```
ffffffff819ffcf0-ffffffff819ffdda: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e6430)
Location: net/core/dev.c:9358
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff819e6430-ffffffff819e651a: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a96960)
Location: net/core/dev.c:9349
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff81a96960-ffffffff81a96a4a: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0d7e0)
Location: net/core/dev.c:9087
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff81c0d7e0-ffffffff81c0d914: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbd440)
Location: net/core/dev.c:9074
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff81dbd440-ffffffff81dbd574: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2dc70)
Location: net/core/dev.c:9082
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff81e2dc70-ffffffff81e2dda4: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, enum bpf_xdp_mode mode, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eebfc0)
Location: net/core/dev.c:9200
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:bpf_xdp_link_update
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff81eebfc0-ffffffff81eec0f4: dev_xdp_install (STB_LOCAL)
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
int dev_xdp_install(struct net_device *dev, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc7018)
Location: net/core/dev.c:8313
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
```
**Symbols:**

```
ffff800010bc7018-ffff800010bc70a0: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce23b8)
Location: net/core/dev.c:8313
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
```
**Symbols:**

```
c0ce23b8-c0ce242c: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca1d00)
Location: net/core/dev.c:8313
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
```
**Symbols:**

```
c000000000ca1d00-c000000000ca1d8c: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007534fa)
Location: net/core/dev.c:8313
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
```
**Symbols:**

```
ffffffe0007534fa-ffffffe000753560: dev_xdp_install (STB_LOCAL)
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
int dev_xdp_install(struct net_device *dev, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ca5f0)
Location: net/core/dev.c:8313
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
```
**Symbols:**

```
ffffffff818ca5f0-ffffffff818ca654: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81884530)
Location: net/core/dev.c:8313
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
```
**Symbols:**

```
ffffffff81884530-ffffffff81884594: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191b5f0)
Location: net/core/dev.c:8313
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
```
**Symbols:**

```
ffffffff8191b5f0-ffffffff8191b654: dev_xdp_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_xdp_install(struct net_device *dev, bpf_op_t bpf_op, struct netlink_ext_ack *extack, u32 flags, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193c7f0)
Location: net/core/dev.c:8313
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
```
**Symbols:**

```
ffffffff8193c7f0-ffffffff8193c854: dev_xdp_install (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum bpf_xdp_mode mode</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, bpf_op, extack, flags, prog</code> ➡️ <code>dev, mode, bpf_op, extack, flags, prog</code>
</li>
</ul>
</details>
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
