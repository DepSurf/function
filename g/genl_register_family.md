# Function: <code>genl_register_family</code>

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
In fs/quota/netlink.c (ffffffff81f90bd8)
Location: include/net/genetlink.h:135
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_init
```
```
In drivers/acpi/event.c (ffffffff81fa2541)
Location: include/net/genetlink.h:135
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81fb31c8)
Location: include/net/genetlink.h:135
Inline: True
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
In fs/quota/netlink.c (ffffffff81fbb52d)
Location: include/net/genetlink.h:135
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_init
```
```
In drivers/acpi/event.c (ffffffff81fce4e1)
Location: include/net/genetlink.h:135
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff81fdfd8c)
Location: include/net/genetlink.h:135
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817ebf20)
Location: net/netlink/genetlink.c:321
Inline: True
Direct callers:
  - fs/quota/netlink.c:quota_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
```
**Symbols:**

```
ffffffff817ebf20-ffffffff817ec539: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8180be40)
Location: net/netlink/genetlink.c:321
Inline: True
Direct callers:
  - fs/quota/netlink.c:quota_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
```
**Symbols:**

```
ffffffff8180be40-ffffffff8180c47e: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8188add0)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - fs/quota/netlink.c:quota_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
```
**Symbols:**

```
ffffffff8188add0-ffffffff8188b452: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff818de400)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_core.c:thermal_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
ffffffff818de400-ffffffff818dea28: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8190adc0)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_core.c:thermal_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
ffffffff8190adc0-ffffffff8190b3e4: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8196c92c)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
ffffffff8196cefb-ffffffff8196cf46: genl_register_family.cold (STB_LOCAL)
ffffffff8196c8a0-ffffffff8196ce8c: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819a3250)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
ffffffff819a3250-ffffffff819a3861: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a7d260)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff81a7d260-ffffffff81a7d433: genl_register_family.part.0 (STB_LOCAL)
ffffffff81a7d440-ffffffff81a7d4bc: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a86810)
Location: net/netlink/genetlink.c:392
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_netlink.c:thermal_netlink_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff81a86810-ffffffff81a869e5: genl_register_family.part.0 (STB_LOCAL)
ffffffff81a869f0-ffffffff81a86a15: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a6fa20)
Location: net/netlink/genetlink.c:392
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_netlink.c:thermal_netlink_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff81a6fa20-ffffffff81a6fcc3: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81b290a0)
Location: net/netlink/genetlink.c:384
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_netlink.c:thermal_netlink_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff81b290a0-ffffffff81b2941e: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81cb2190)
Location: net/netlink/genetlink.c:384
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_netlink.c:thermal_netlink_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff81cb2190-ffffffff81cb2574: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81e703a0)
Location: net/netlink/genetlink.c:629
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_netlink.c:thermal_netlink_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff81e703a0-ffffffff81e70598: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81ecc4b0)
Location: net/netlink/genetlink.c:629
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_netlink.c:thermal_netlink_init
  - net/core/netdev-genl.c:netdev_genl_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/netlink/genetlink.c:genl_init
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_init
  - net/devlink/core.c:devlink_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/handshake/netlink.c:handshake_init
```
**Symbols:**

```
ffffffff81ecc4b0-ffffffff81ecc6a8: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/genetlink.c (ffffffff83968a65)
Location: net/netlink/genetlink.c:778
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_init
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/regulator/event.c:reg_event_init
  - drivers/thermal/thermal_netlink.c:thermal_netlink_init
  - drivers/dpll/dpll_core.c:dpll_init
  - net/core/netdev-genl.c:netdev_genl_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/netlink/genetlink.c:genl_init
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_init
  - net/devlink/core.c:devlink_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/handshake/netlink.c:handshake_init
```
**Symbols:**

```
ffffffff81f8f9f0-ffffffff81f8fc75: genl_register_family.part.0 (STB_LOCAL)
ffffffff81f8fc90-ffffffff81f8fcba: genl_register_family (STB_GLOBAL)
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
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffff800010c51e58)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
ffff800010c51e58-ffff800010c5247c: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (c0d61c1c)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
c0d61c1c-c0d62274: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (c000000000d51350)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
c000000000d51350-c000000000d516f0: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffe0007bd09a)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
ffffffe0007bd09a-ffffffe0007bd5c4: genl_register_family (STB_GLOBAL)
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
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819430c0)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
ffffffff819430c0-ffffffff819436d1: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff818fcbb0)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
ffffffff818fcbb0-ffffffff818fd1c1: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81994250)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
ffffffff81994250-ffffffff81994861: genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819b6d50)
Location: net/netlink/genetlink.c:322
Inline: True
Direct callers:
  - kernel/taskstats.c:taskstats_init
  - fs/quota/netlink.c:quota_init
  - drivers/acpi/event.c:acpi_event_init
  - drivers/thermal/thermal_core.c:thermal_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/devlink.c:devlink_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv6/seg6.c:seg6_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
  - net/ncsi/ncsi-netlink.c:ncsi_init_netlink
```
**Symbols:**

```
ffffffff819b6d50-ffffffff819b7370: genl_register_family (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
