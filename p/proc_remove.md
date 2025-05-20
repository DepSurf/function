# Function: <code>proc_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127fc00)
Location: fs/proc/generic.c:637
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_device
  - drivers/pci/proc.c:pci_proc_detach_bus
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff8127fc00-ffffffff8127fc21: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812acc50)
Location: fs/proc/generic.c:642
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff812acc50-ffffffff812acc71: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c2540)
Location: fs/proc/generic.c:644
Inline: False
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff812c2540-ffffffff812c2561: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812cf7d0)
Location: fs/proc/generic.c:628
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff812cf7d0-ffffffff812cf7f2: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3f30)
Location: fs/proc/generic.c:638
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff812f3f30-ffffffff812f3f52: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81321000)
Location: fs/proc/generic.c:740
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff81321000-ffffffff81321021: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81338110)
Location: fs/proc/generic.c:742
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff81338110-ffffffff81338131: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360290)
Location: fs/proc/generic.c:743
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff81360290-ffffffff813602b1: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813784f0)
Location: fs/proc/generic.c:743
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff813784f0-ffffffff81378511: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c15e0)
Location: fs/proc/generic.c:772
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff813c15e0-ffffffff813c1601: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d34d0)
Location: fs/proc/generic.c:792
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff813d34d0-ffffffff813d34f1: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813da300)
Location: fs/proc/generic.c:787
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff813da300-ffffffff813da321: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142ba30)
Location: fs/proc/generic.c:787
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff8142ba30-ffffffff8142ba51: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a51e0)
Location: fs/proc/generic.c:790
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff814a51e0-ffffffff814a5215: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8153a750)
Location: fs/proc/generic.c:790
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff8153a750-ffffffff8153a785: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81572a30)
Location: fs/proc/generic.c:789
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff81572a30-ffffffff81572a65: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815ab3e0)
Location: fs/proc/generic.c:789
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - drivers/video/fbdev/core/fb_procfs.c:fb_cleanup_procfs
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff815ab3e0-ffffffff815ab415: proc_remove (STB_GLOBAL)
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
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff8000104446e8)
Location: fs/proc/generic.c:743
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffff8000104446e8-ffff80001044471c: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c0609700)
Location: fs/proc/generic.c:743
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - sound/core/info.c:snd_info_disconnect
  - sound/core/info.c:snd_info_card_disconnect
  - sound/core/info.c:snd_info_card_id_change
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
c0609700-c060972c: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c000000000559ea0)
Location: fs/proc/generic.c:743
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
c000000000559ea0-c000000000559ec4: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002d9ff0)
Location: fs/proc/generic.c:743
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffe0002d9ff0-ffffffe0002da01e: proc_remove (STB_GLOBAL)
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
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81370ad0)
Location: fs/proc/generic.c:743
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff81370ad0-ffffffff81370af1: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81361560)
Location: fs/proc/generic.c:743
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff81361560-ffffffff81361581: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136e5a0)
Location: fs/proc/generic.c:743
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff8136e5a0-ffffffff8136e5c1: proc_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void proc_remove(struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81381ef0)
Location: fs/proc/generic.c:743
Inline: True
Direct callers:
  - kernel/irq/proc.c:unregister_handler_proc
  - fs/proc/vmcore.c:vmcore_cleanup
  - drivers/pci/proc.c:pci_proc_detach_bus
  - drivers/pci/proc.c:pci_proc_detach_device
  - net/ipv6/proc.c:snmp6_unregister_dev
```
**Symbols:**

```
ffffffff81381ef0-ffffffff81381f11: proc_remove (STB_GLOBAL)
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
