# Function: <code>ida_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813ea5b0)
Location: lib/idr.c:1059
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/rtc/class.c:rtc_exit
  - drivers/watchdog/watchdog_core.c:watchdog_exit
```
**Symbols:**

```
ffffffff813ea5b0-ffffffff813ea5c9: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81430960)
Location: lib/idr.c:1059
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/watchdog/watchdog_core.c:watchdog_exit
```
**Symbols:**

```
ffffffff81430960-ffffffff81430979: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144cb30)
Location: lib/idr.c:1062
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/watchdog/watchdog_core.c:watchdog_exit
```
**Symbols:**

```
ffffffff8144cb30-ffffffff8144cb49: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff818ecf70)
Location: lib/idr.c:396
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/watchdog/watchdog_core.c:watchdog_exit
```
**Symbols:**

```
ffffffff818ecf70-ffffffff818ed04e: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81972f90)
Location: lib/idr.c:404
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/watchdog/watchdog_core.c:watchdog_exit
```
**Symbols:**

```
ffffffff81972f90-ffffffff8197306e: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff819cf530)
Location: lib/idr.c:534
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
```
**Symbols:**

```
ffffffff819cf530-ffffffff819cf610: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a086a0)
Location: lib/idr.c:534
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
```
**Symbols:**

```
ffffffff81a086a0-ffffffff81a087bd: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a78060)
Location: lib/idr.c:545
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
```
**Symbols:**

```
ffffffff81a78060-ffffffff81a78167: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81aaf910)
Location: lib/idr.c:536
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
ffffffff81aaf910-ffffffff81aafa17: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815e9150)
Location: lib/idr.c:536
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
ffffffff815e9150-ffffffff815e92cd: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8160e200)
Location: lib/idr.c:540
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
ffffffff8160e200-ffffffff8160e37d: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff815f1950)
Location: lib/idr.c:540
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
ffffffff815f1950-ffffffff815f1acd: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8165eac0)
Location: lib/idr.c:540
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
ffffffff8165eac0-ffffffff8165ec25: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81778370)
Location: lib/idr.c:541
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
ffffffff81778370-ffffffff817784ec: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82021100)
Location: lib/idr.c:541
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
ffffffff82021100-ffffffff8202127c: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff820a1120)
Location: lib/idr.c:541
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
ffffffff820a1120-ffffffff820a12a1: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff82179100)
Location: lib/idr.c:541
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/gpu/drm/drm_connector.c:drm_connector_ida_destroy
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
ffffffff82179100-ffffffff82179281: ida_destroy (STB_GLOBAL)
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
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffff800010d88cb8)
Location: lib/idr.c:536
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/firmware/arm_scmi/bus.c:scmi_bus_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
ffff800010d88cb8-ffff800010d88e18: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c0e84120)
Location: lib/idr.c:536
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/firmware/arm_scmi/bus.c:scmi_bus_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
c0e84120-c0e84268: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (c000000000ec9690)
Location: lib/idr.c:536
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
c000000000ec9690-c000000000ec9804: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffe0008b2fc0)
Location: lib/idr.c:536
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
```
**Symbols:**

```
ffffffe0008b2fc0-ffffffe0008b30a6: ida_destroy (STB_GLOBAL)
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
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a4e760)
Location: lib/idr.c:536
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/nvme/host/core.c:nvme_destroy_subsystem
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
ffffffff81a4e760-ffffffff81a4e867: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81a0b850)
Location: lib/idr.c:536
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/nvme/host/core.c:nvme_destroy_subsystem
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
```
**Symbols:**

```
ffffffff81a0b850-ffffffff81a0b957: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81abab50)
Location: lib/idr.c:536
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
```
**Symbols:**

```
ffffffff81abab50-ffffffff81abac57: ida_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ida_destroy(struct ida *ida);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81ac6fa0)
Location: lib/idr.c:536
Inline: False
Direct callers:
  - kernel/workqueue.c:rcu_free_pool
  - fs/devpts/inode.c:devpts_kill_sb
  - drivers/virtio/virtio.c:virtio_exit
  - drivers/tty/serdev/core.c:serdev_exit
  - drivers/base/swnode.c:software_node_exit
  - drivers/base/swnode.c:software_node_release
  - drivers/nvdimm/bus.c:nvdimm_bus_exit
  - drivers/nvdimm/dimm_devs.c:nvdimm_devs_exit
  - drivers/nvdimm/region_devs.c:nd_region_devs_exit
  - drivers/dax/super.c:dax_core_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/net/phy/fixed_phy.c:fixed_mdio_bus_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_core.c:watchdog_exit
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
```
**Symbols:**

```
ffffffff81ac6fa0-ffffffff81ac70a7: ida_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
