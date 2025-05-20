# Function: <code>notifier_from_errno</code>

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
In arch/x86/events/amd/uncore.c (0)
Location: include/linux/notifier.h:168
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104935a)
Location: include/linux/notifier.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_cpu_callback
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: include/linux/notifier.h:168
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/notifier.h:168
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/notifier.h:168
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/notifier.h:168
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/notifier.h:168
Inline: True
```
```
In kernel/padata.c (ffffffff8118ab35)
Location: include/linux/notifier.h:168
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_callback
```
```
In kernel/jump_label.c (ffffffff8118b0d8)
Location: include/linux/notifier.h:168
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (ffffffff811ee4ac)
Location: include/linux/notifier.h:168
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
```
```
In mm/zsmalloc.c (ffffffff81205203)
Location: include/linux/notifier.h:168
Inline: True
```
```
In drivers/base/topology.c (ffffffff81550e8b)
Location: include/linux/notifier.h:168
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_cpu_callback
```
```
In drivers/base/cacheinfo.c (ffffffff81552974)
Location: include/linux/notifier.h:168
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_callback
```
```
In arch/x86/power/cpu.c (ffffffff816faed5)
Location: include/linux/notifier.h:168
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
```
```
In net/core/flow.c (ffffffff81735157)
Location: include/linux/notifier.h:168
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_cpu
```
```
In net/ipv4/devinet.c (ffffffff8179216e)
Location: include/linux/notifier.h:168
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff817d176d)
Location: include/linux/notifier.h:168
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104950a)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_cpu_callback
```
```
In kernel/relay.c (0)
Location: include/linux/notifier.h:170
Inline: True
```
```
In kernel/padata.c (ffffffff8119cf61)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_callback
```
```
In kernel/jump_label.c (ffffffff8119d7e8)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:170
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/notifier.h:170
Inline: True
```
```
In drivers/base/topology.c (ffffffff815a2c6b)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_cpu_callback
```
```
In drivers/base/cacheinfo.c (ffffffff815a4910)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_callback
```
```
In arch/x86/power/cpu.c (ffffffff81760031)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
```
```
In net/core/flow.c (ffffffff817a12cc)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_cpu
```
```
In net/ipv4/devinet.c (ffffffff81800043)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff8183efa7)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In kernel/jump_label.c (ffffffff811ad208)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:170
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8178d031)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
```
```
In net/ipv4/devinet.c (ffffffff81830fa3)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81870bbb)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In kernel/jump_label.c (ffffffff811b4694)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:170
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff817ab1c1)
Location: include/linux/notifier.h:170
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8185253b)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff8189591c)
Location: include/linux/notifier.h:170
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In kernel/jump_label.c (ffffffff811c84a4)
Location: include/linux/notifier.h:171
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:171
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff818226b1)
Location: include/linux/notifier.h:171
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff818d2349)
Location: include/linux/notifier.h:171
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81916dc2)
Location: include/linux/notifier.h:171
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In kernel/jump_label.c (ffffffff811e8a2b)
Location: include/linux/notifier.h:195
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:195
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8186c99b)
Location: include/linux/notifier.h:195
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81928844)
Location: include/linux/notifier.h:195
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff8196e47b)
Location: include/linux/notifier.h:195
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In kernel/jump_label.c (ffffffff811f9702)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8188c9ab)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81957b21)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff819a3f38)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In kernel/jump_label.c (ffffffff81211652)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff818d7888)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819bc54e)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81a10258)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In kernel/jump_label.c (ffffffff8121ea12)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81909bc8)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819f324d)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81a46f98)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In kernel/jump_label.c (ffffffff8124b300)
Location: include/linux/notifier.h:190
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:190
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ae1b8c)
Location: include/linux/notifier.h:190
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81b3de67)
Location: include/linux/notifier.h:190
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81bba4dc)
Location: include/linux/notifier.h:190
Inline: True
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
In kernel/tracepoint.c (ffffffff811a8cf9)
Location: include/linux/notifier.h:189
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff811e6e66)
Location: include/linux/notifier.h:189
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff81229478)
Location: include/linux/notifier.h:189
Inline: True
```
```
In kernel/static_call.c (ffffffff81239e40)
Location: include/linux/notifier.h:189
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_module_notify
```
```
In kernel/jump_label.c (ffffffff81255760)
Location: include/linux/notifier.h:189
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:189
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81aeea2c)
Location: include/linux/notifier.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81b4c9f7)
Location: include/linux/notifier.h:189
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81c34b0c)
Location: include/linux/notifier.h:189
Inline: True
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
In kernel/tracepoint.c (ffffffff811a9599)
Location: include/linux/notifier.h:189
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff811e8206)
Location: include/linux/notifier.h:189
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8122dd18)
Location: include/linux/notifier.h:189
Inline: True
```
```
In kernel/static_call.c (ffffffff8123e472)
Location: include/linux/notifier.h:189
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_module_notify
```
```
In kernel/jump_label.c (ffffffff81259c68)
Location: include/linux/notifier.h:189
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:189
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ada12a)
Location: include/linux/notifier.h:189
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81b3a6ab)
Location: include/linux/notifier.h:189
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81c27011)
Location: include/linux/notifier.h:189
Inline: True
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
In kernel/tracepoint.c (ffffffff811d3189)
Location: include/linux/notifier.h:187
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff81218e86)
Location: include/linux/notifier.h:187
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff81266918)
Location: include/linux/notifier.h:187
Inline: True
```
```
In kernel/static_call.c (ffffffff81278f52)
Location: include/linux/notifier.h:187
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_module_notify
```
```
In kernel/jump_label.c (ffffffff812959d8)
Location: include/linux/notifier.h:187
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:187
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/notifier.h:187
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81b99276)
Location: include/linux/notifier.h:187
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81c00e4f)
Location: include/linux/notifier.h:187
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81d44f9c)
Location: include/linux/notifier.h:187
Inline: True
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
In kernel/tracepoint.c (ffffffff81207bd8)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In kernel/trace/bpf_trace.c (ffffffff8125818d)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_event_notify
```
```
In kernel/bpf/btf.c (ffffffff812b3336)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_module_notify
```
```
In kernel/static_call_inline.c (ffffffff812cbdc2)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_module_notify
```
```
In kernel/jump_label.c (ffffffff812eb668)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81d2b114)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81d9ab03)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/mctp/device.c (ffffffff81e38ab2)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_notify
```
```
In arch/x86/power/cpu.c (ffffffff81f11dd3)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
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
In kernel/tracepoint.c (ffffffff8125003b)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In kernel/trace/bpf_trace.c (ffffffff812a7ddd)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_event_notify
```
```
In kernel/bpf/btf.c (ffffffff81313786)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_module_notify
```
```
In kernel/static_call_inline.c (ffffffff81333777)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_module_notify
```
```
In kernel/jump_label.c (ffffffff81355738)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ef2d2e)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81f69976)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/mctp/device.c (ffffffff82011d6f)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_notify
```
```
In arch/x86/power/cpu.c (ffffffff8201c762)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
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
In kernel/tracepoint.c (ffffffff812674b2)
Location: include/linux/notifier.h:207
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In kernel/trace/bpf_trace.c (ffffffff812ca06d)
Location: include/linux/notifier.h:207
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_event_notify
```
```
In kernel/bpf/btf.c (ffffffff81343399)
Location: include/linux/notifier.h:207
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_module_notify
```
```
In kernel/static_call_inline.c (ffffffff813644bf)
Location: include/linux/notifier.h:207
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_module_notify
```
```
In kernel/jump_label.c (ffffffff81386db0)
Location: include/linux/notifier.h:207
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:207
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/notifier.h:207
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff818cf31c)
Location: include/linux/notifier.h:207
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_module_notify
```
```
In net/ipv4/devinet.c (ffffffff81f527e2)
Location: include/linux/notifier.h:207
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81fc9a6f)
Location: include/linux/notifier.h:207
Inline: True
```
```
In net/mctp/device.c (ffffffff8208eb4b)
Location: include/linux/notifier.h:207
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_notify
```
```
In arch/x86/power/cpu.c (ffffffff8209cdf2)
Location: include/linux/notifier.h:207
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
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
In kernel/tracepoint.c (ffffffff81281471)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In kernel/trace/bpf_trace.c (ffffffff812e71bd)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_event_notify
```
```
In kernel/bpf/btf.c (ffffffff813695e9)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_module_notify
```
```
In kernel/static_call_inline.c (ffffffff8138d3ef)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_module_notify
```
```
In kernel/jump_label.c (ffffffff813b02c0)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:196
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/notifier.h:196
Inline: True
```
```
In lib/dynamic_debug.c (ffffffff8192117c)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_module_notify
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf1fb9)
Location: include/linux/notifier.h:196
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff82018ac4)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff8209720f)
Location: include/linux/notifier.h:196
Inline: True
```
```
In net/mctp/device.c (ffffffff8216503b)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_notify
```
```
In arch/x86/power/cpu.c (ffffffff821745f2)
Location: include/linux/notifier.h:196
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
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
In kernel/jump_label.c (ffff8000102aabcc)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/clk/rockchip/clk.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/clk/rockchip/clk-cpu.c (ffff8000107ee788)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
```
```
In drivers/clk/sunxi-ng/ccu_common.c (ffff8000107f4924)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_mux.c (ffff8000107f65bc)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_notifier_cb
```
```
In drivers/spi/spi.c (ffff8000109c4398)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (ffff800010ab6cb4)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4d270)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:sdei_pm_notifier
```
```
In drivers/of/platform.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/ipv4/devinet.c (ffff800010ca9540)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffff800010d09ba0)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/clk/meson/meson8b.c (c0903238)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/clk/rockchip/clk.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/clk/rockchip/clk-cpu.c (c0907fc4)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
```
```
In drivers/clk/samsung/clk-cpu.c (c090b5c4)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-cpu.c:exynos5433_cpuclk_notifier_cb
  - drivers/clk/samsung/clk-cpu.c:exynos_cpuclk_notifier_cb
```
```
In drivers/spi/spi.c (c0ab0fd4)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (c0b96e48)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/of/platform.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/memory/tegra/tegra20-emc.c (c0c751fc)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_clk_change_notify
```
```
In net/ipv4/devinet.c (c0db5d10)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (c0e103c0)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000fa410)
Location: include/linux/notifier.h:194
Inline: True
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fb47c)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_notifier
```
```
In kernel/jump_label.c (c00000000035f1d8)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/spi/spi.c (c000000000a88dc0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (c000000000b99c9c)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/of/platform.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/ipv4/devinet.c (c000000000dbe924)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (c000000000e345e4)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In drivers/spi/spi.c (ffffffe0006186d8)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/i2c/i2c-core-of.c (ffffffe0006bc868)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/of/platform.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/ipv4/devinet.c (ffffffe00080416a)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffe000851890)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In kernel/jump_label.c (ffffffff81217062)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff818a8f88)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81992fed)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff819e6628)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In kernel/jump_label.c (ffffffff81209dc2)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In drivers/net/vxlan.c (ffffffff8176f85b)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_switchdev_event
```
```
In arch/x86/power/cpu.c (ffffffff81863bf8)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8194caad)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff819a33e8)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In kernel/jump_label.c (ffffffff81214e02)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff818fa5e8)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819fd88d)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81a510a8)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In kernel/jump_label.c (ffffffff81223db2)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
```
```
In mm/slub.c (0)
Location: include/linux/notifier.h:194
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8191b748)
Location: include/linux/notifier.h:194
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81a07c1d)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv6/addrconf.c (ffffffff81a5cff8)
Location: include/linux/notifier.h:194
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
</ul>

## Differences
