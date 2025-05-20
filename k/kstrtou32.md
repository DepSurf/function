# Function: <code>kstrtou32</code>

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
In security/device_cgroup.c (ffffffff81395c09)
Location: include/linux/kernel.h:345
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In drivers/xen/sys-hypervisor.c (ffffffff814d3719)
Location: include/linux/kernel.h:345
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/thermal/thermal_core.c (ffffffff816848cf)
Location: include/linux/kernel.h:345
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff81736af5)
Location: include/linux/kernel.h:345
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
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
In security/device_cgroup.c (ffffffff813d195f)
Location: include/linux/kernel.h:352
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81524a59)
Location: include/linux/kernel.h:352
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/thermal/thermal_core.c (ffffffff816e5e4f)
Location: include/linux/kernel.h:352
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff817a2cc5)
Location: include/linux/kernel.h:352
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
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
In security/device_cgroup.c (ffffffff813e9085)
Location: include/linux/kernel.h:354
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81550f19)
Location: include/linux/kernel.h:354
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8171931f)
Location: include/linux/kernel.h:354
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff817d1725)
Location: include/linux/kernel.h:354
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff813f5493)
Location: include/linux/kernel.h:367
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815621df)
Location: include/linux/kernel.h:367
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff815656e9)
Location: include/linux/kernel.h:367
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817315bf)
Location: include/linux/kernel.h:367
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff817f0b11)
Location: include/linux/kernel.h:367
Inline: True
Inline callers:
  - net/core/net-sysfs.c:set_tx_maxrate
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
In security/device_cgroup.c (ffffffff8141d753)
Location: include/linux/kernel.h:404
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815c64e9)
Location: include/linux/kernel.h:404
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff815c9889)
Location: include/linux/kernel.h:404
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817a265f)
Location: include/linux/kernel.h:404
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff8186c115)
Location: include/linux/kernel.h:404
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
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
In security/device_cgroup.c (ffffffff8144fa1f)
Location: include/linux/kernel.h:420
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815fecdd)
Location: include/linux/kernel.h:420
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81602149)
Location: include/linux/kernel.h:420
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/usb/core/port.c (ffffffff8176d611)
Location: include/linux/kernel.h:420
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817e9ccb)
Location: include/linux/kernel.h:420
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff818bc9f3)
Location: include/linux/kernel.h:420
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
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
In security/device_cgroup.c (ffffffff8146c9ff)
Location: include/linux/kernel.h:453
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-sysfs.c (ffffffff814a00c1)
Location: include/linux/kernel.h:453
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81619dad)
Location: include/linux/kernel.h:453
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8161d239)
Location: include/linux/kernel.h:453
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/usb/core/port.c (ffffffff81791c91)
Location: include/linux/kernel.h:453
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81815b7b)
Location: include/linux/kernel.h:453
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff818e3ca3)
Location: include/linux/kernel.h:453
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff810483e9)
Location: include/linux/kernel.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In security/safesetid/securityfs.c (ffffffff814995e3)
Location: include/linux/kernel.h:412
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In security/device_cgroup.c (ffffffff8149a0ec)
Location: include/linux/kernel.h:412
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-sysfs.c (ffffffff814ce641)
Location: include/linux/kernel.h:412
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164db5a)
Location: include/linux/kernel.h:412
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81650469)
Location: include/linux/kernel.h:412
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/usb/core/port.c (ffffffff817d0471)
Location: include/linux/kernel.h:412
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81857d9b)
Location: include/linux/kernel.h:412
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff81932683)
Location: include/linux/kernel.h:412
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048cb9)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In security/safesetid/securityfs.c (ffffffff814b3503)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In security/device_cgroup.c (ffffffff814b42ec)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-sysfs.c (ffffffff814e79b1)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167005e)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81672a09)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/usb/core/port.c (ffffffff81801341)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8188984b)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff819651c3)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104ce59)
Location: include/linux/kernel.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In security/safesetid/securityfs.c (ffffffff815128a1)
Location: include/linux/kernel.h:405
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:parse_policy_line
  - security/safesetid/securityfs.c:parse_policy_line
```
```
In security/device_cgroup.c (ffffffff815137be)
Location: include/linux/kernel.h:405
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
```
```
In block/blk-sysfs.c (ffffffff81546871)
Location: include/linux/kernel.h:405
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81720509)
Location: include/linux/kernel.h:405
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81723109)
Location: include/linux/kernel.h:405
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/usb/core/port.c (ffffffff818d1a91)
Location: include/linux/kernel.h:405
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8195824b)
Location: include/linux/kernel.h:405
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff81a385f3)
Location: include/linux/kernel.h:405
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104c2b9)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In security/safesetid/securityfs.c (ffffffff8152f8e1)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:parse_policy_line
  - security/safesetid/securityfs.c:parse_policy_line
```
```
In security/device_cgroup.c (ffffffff8153090e)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
```
```
In block/blk-sysfs.c (ffffffff815624d1)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173d469)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8173fd49)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/usb/core/port.c (ffffffff818dbe71)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8195d7cb)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff81a3c353)
Location: include/linux/kernel.h:257
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104ddf9)
Location: include/linux/kernel.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In security/safesetid/securityfs.c (ffffffff81535c4d)
Location: include/linux/kernel.h:267
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/device_cgroup.c (ffffffff81536b0e)
Location: include/linux/kernel.h:267
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
```
```
In block/blk-sysfs.c (ffffffff8156b321)
Location: include/linux/kernel.h:267
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81720fe9)
Location: include/linux/kernel.h:267
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81723799)
Location: include/linux/kernel.h:267
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/base/swnode.c (ffffffff817baf51)
Location: include/linux/kernel.h:267
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
```
```
In drivers/usb/core/port.c (ffffffff818bf231)
Location: include/linux/kernel.h:267
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81940a1b)
Location: include/linux/kernel.h:267
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff81a21f23)
Location: include/linux/kernel.h:267
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff810555f9)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In security/safesetid/securityfs.c (ffffffff8159424d)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/device_cgroup.c (ffffffff81595247)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
```
```
In block/blk-sysfs.c (ffffffff815cf5a1)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179fe09)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff817a25a9)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/base/swnode.c (ffffffff818451c1)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
```
```
In drivers/usb/core/port.c (ffffffff81955891)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff819da986)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819e533b)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff81ad5748)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81061590)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In security/safesetid/securityfs.c (ffffffff816362ac)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/device_cgroup.c (ffffffff8163746a)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
```
```
In block/blk-sysfs.c (ffffffff8167abc8)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d993a)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff818dc7d8)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/base/swnode.c (ffffffff819893f8)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
```
```
In drivers/usb/core/port.c (ffffffff81aaf528)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81b3e13d)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81b4a6c2)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff81c563c8)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
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
In arch/x86/kernel/cpu/umwait.c (ffffffff8106ff90)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In security/safesetid/securityfs.c (ffffffff816ed2aa)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/device_cgroup.c (ffffffff816ee71d)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
```
```
In block/blk-sysfs.c (ffffffff817372a8)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2c40a)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81a2fad8)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/base/swnode.c (ffffffff81af8678)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
```
```
In drivers/usb/core/port.c (ffffffff81c37288)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81cd439d)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81ce1fa2)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff81e0e2f8)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
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
In arch/x86/kernel/cpu/umwait.c (ffffffff81071ba0)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In kernel/trace/trace_events_user.c (ffffffff812c4865)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse_field
```
```
In security/safesetid/securityfs.c (ffffffff817276ca)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/device_cgroup.c (ffffffff81728c0d)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
```
```
In block/blk-sysfs.c (ffffffff81773a08)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a75baa)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81a792e8)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/base/swnode.c (ffffffff81b46ba8)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
```
```
In drivers/usb/core/port.c (ffffffff81c9e578)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81d3bfdf)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81d4a242)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff81e81548)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
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
In arch/x86/kernel/cpu/umwait.c (ffffffff810793c0)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1085)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse_field
```
```
In security/safesetid/securityfs.c (ffffffff817689c6)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/device_cgroup.c (ffffffff81769f6d)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
```
```
In block/blk-sysfs.c (ffffffff817b5cd8)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac7d9a)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81acb758)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/base/swnode.c (ffffffff81b9ef08)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_graph_parse_endpoint
```
```
In drivers/usb/core/port.c (ffffffff81d53178)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81df291f)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:max_vclocks_store
  - drivers/ptp/ptp_sysfs.c:n_vclocks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81e01052)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff81f42522)
Location: include/linux/kstrtox.h:84
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffff8000105ab1e0)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In security/device_cgroup.c (ffff8000105ac268)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-sysfs.c (ffff8000105e54e4)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff80001083affc)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/usb/core/port.c (ffff800010a35694)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffff800010ad7140)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffff800010c0b01c)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (c075ad90)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In security/device_cgroup.c (c075bd04)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-sysfs.c (c079251c)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/usb/core/port.c (c0b08e18)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (c0bb77b4)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (c0d22a7c)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/pseries/dlpar.c (c0000000000f3c7c)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_store
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9ad8)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_probe
```
```
In security/safesetid/securityfs.c (c000000000728ef0)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In security/device_cgroup.c (c00000000072a5d8)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-sysfs.c (c000000000779578)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/usb/core/port.c (c000000000af36f4)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (c000000000bbd864)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (c000000000cf4774)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/safesetid/securityfs.c (ffffffe0003f3dd2)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In security/device_cgroup.c (ffffffe0003f49ea)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-sysfs.c (ffffffe0004268ae)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/usb/core/port.c (ffffffe000652f10)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d1f92)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffe000788182)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048e29)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In security/safesetid/securityfs.c (ffffffff814abae3)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In security/device_cgroup.c (ffffffff814ac8cc)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-sysfs.c (ffffffff814dff91)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8163611e)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff816386f9)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/usb/core/port.c (ffffffff817b9721)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8182f6cb)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff81905193)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81038119)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In security/safesetid/securityfs.c (ffffffff8149c503)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In security/device_cgroup.c (ffffffff8149d2ec)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-sysfs.c (ffffffff814d0931)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/usb/core/port.c (ffffffff817ab151)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817f6d5b)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff818befc3)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048c69)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In security/safesetid/securityfs.c (ffffffff814a7b83)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In security/device_cgroup.c (ffffffff814a896c)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-sysfs.c (ffffffff814dc021)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81663e9e)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81666849)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/usb/core/port.c (ffffffff817f61c1)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8187ecfb)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff819561c3)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104a079)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
```
```
In security/safesetid/securityfs.c (ffffffff814c0513)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
```
```
In security/device_cgroup.c (ffffffff814c132f)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In block/blk-sysfs.c (ffffffff814f4e91)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167e45e)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81680df9)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
```
```
In drivers/usb/core/port.c (ffffffff81810401)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:quirks_store
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8189a77b)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:sustainable_power_store
```
```
In net/core/net-sysfs.c (ffffffff819783c3)
Location: include/linux/kernel.h:416
Inline: True
Inline callers:
  - net/core/net-sysfs.c:tx_maxrate_store
```
</details>
</li>
</ul>

## Differences
