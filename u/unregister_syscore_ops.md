# Function: <code>unregister_syscore_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8154c220)
Location: drivers/base/syscore.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - drivers/acpi/processor_idle.c:acpi_processor_syscore_exit
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_exit
```
**Symbols:**

```
ffffffff8154c220-ffffffff8154c271: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8159e010)
Location: drivers/base/syscore.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - drivers/base/firmware_class.c:firmware_class_exit
```
**Symbols:**

```
ffffffff8159e010-ffffffff8159e061: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff815cc5c0)
Location: drivers/base/syscore.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_class.c:firmware_class_exit
```
**Symbols:**

```
ffffffff815cc5c0-ffffffff815cc611: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff815e1170)
Location: drivers/base/syscore.c:34
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_class.c:firmware_class_exit
```
**Symbols:**

```
ffffffff815e1170-ffffffff815e11bd: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81648290)
Location: drivers/base/syscore.c:34
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_class.c:firmware_class_exit
```
**Symbols:**

```
ffffffff81648290-ffffffff816482dd: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81683860)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff81683860-ffffffff816838ad: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff816a3530)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff816a3530-ffffffff816a357d: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff816dc440)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff816dc440-ffffffff816dc48b: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff817004d0)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff817004d0-ffffffff8170051b: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff817ba410)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff817ba410-ffffffff817ba45e: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff817cf120)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff817cf120-ffffffff817cf16e: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff817b2b30)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff817b2b30-ffffffff817b2b7e: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8183bfd0)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff8183bfd0-ffffffff8183c01e: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8197e760)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_cleanup
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff8197e760-ffffffff8197e7b8: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81aebd20)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff81aebd20-ffffffff81aebd78: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81b39f60)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff81b39f60-ffffffff81b39fb8: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81b91a20)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff81b91a20-ffffffff81b91a78: unregister_syscore_ops (STB_GLOBAL)
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
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffff8000108eb780)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffff8000108eb780-ffff8000108eb7dc: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (c09d9788)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
c09d9788-c09d97d8: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (c000000000982e30)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - arch/powerpc/sysdev/mpic.c:mpic_init_sys
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
c000000000982e30-c000000000982ec8: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffe00057f312)
Location: drivers/base/syscore.c:33
Inline: False
```
**Symbols:**

```
ffffffe00057f312-ffffffe00057f366: unregister_syscore_ops (STB_GLOBAL)
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
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff816c5cc0)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff816c5cc0-ffffffff816c5d0b: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff816a0f40)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
  - drivers/hv/vmbus_drv.c:vmbus_exit
```
**Symbols:**

```
ffffffff816a0f40-ffffffff816a0f8b: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff816f4190)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff816f4190-ffffffff816f41db: unregister_syscore_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unregister_syscore_ops(struct syscore_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8170e9c0)
Location: drivers/base/syscore.c:33
Inline: False
Direct callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/base/firmware_loader/main.c:firmware_class_exit
  - drivers/base/firmware_loader/main.c:firmware_class_init
```
**Symbols:**

```
ffffffff8170e9c0-ffffffff8170ea0b: unregister_syscore_ops (STB_GLOBAL)
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
