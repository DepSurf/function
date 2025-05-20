# Function: <code>halt</code>

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
In arch/x86/kernel/process.c (ffffffff81039667)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e17f)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/reboot.c (ffffffff810501fc)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff81063b24)
Location: arch/x86/include/asm/paravirt.h:120
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
In arch/x86/kernel/process.c (ffffffff8103864c)
Location: arch/x86/include/asm/paravirt.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/tboot.c (ffffffff8103df9a)
Location: arch/x86/include/asm/paravirt.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/reboot.c (ffffffff8105037c)
Location: arch/x86/include/asm/paravirt.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff81063744)
Location: arch/x86/include/asm/paravirt.h:110
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff81fa07da)
Location: arch/x86/include/asm/paravirt.h:110
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/process.c (ffffffff8103801b)
Location: arch/x86/include/asm/paravirt.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/tboot.c (ffffffff8103d84e)
Location: arch/x86/include/asm/paravirt.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/reboot.c (ffffffff81052bec)
Location: arch/x86/include/asm/paravirt.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff81066bf4)
Location: arch/x86/include/asm/paravirt.h:101
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff81fdbd4b)
Location: arch/x86/include/asm/paravirt.h:101
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/process.c (ffffffff810361ab)
Location: arch/x86/include/asm/paravirt.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/tboot.c (ffffffff8103b8b0)
Location: arch/x86/include/asm/paravirt.h:101
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff810526fc)
Location: arch/x86/include/asm/paravirt.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff81065ed5)
Location: arch/x86/include/asm/paravirt.h:101
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff820bcd28)
Location: arch/x86/include/asm/paravirt.h:101
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff8103e2d3)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/reboot.c (ffffffff81056532)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a226)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff826c3924)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff8103f863)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff810592e2)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff8106cd89)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff826edba9)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff81040e63)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff8105efe2)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff81072f59)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828a4741)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff81043553)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff810623f2)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff81076ae7)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828bcc11)
Location: arch/x86/include/asm/paravirt.h:159
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff81043ca3)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81062c62)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff81077b37)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828c30ac)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff81047628)
Location: arch/x86/include/asm/paravirt.h:153
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81068d02)
Location: arch/x86/include/asm/paravirt.h:153
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f158)
Location: arch/x86/include/asm/paravirt.h:153
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff82ce64a8)
Location: arch/x86/include/asm/paravirt.h:153
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff81046e58)
Location: arch/x86/include/asm/paravirt.h:153
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff8106a952)
Location: arch/x86/include/asm/paravirt.h:153
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ed88)
Location: arch/x86/include/asm/paravirt.h:153
Inline: True
```
```
In arch/x86/kernel/sev-es.c (ffffffff82fd1691)
Location: arch/x86/include/asm/paravirt.h:153
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
```
```
In arch/x86/mm/extable.c (ffffffff82fd3e19)
Location: arch/x86/include/asm/paravirt.h:153
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff810487fe)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b392)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff8107fede)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff831dc346)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
```
```
In arch/x86/mm/extable.c (ffffffff831de95a)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff8104f148)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81075ef2)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff8108ed1e)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff832bf3fc)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
```
```
In arch/x86/mm/extable.c (ffffffff832c1cd0)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff8105a3b7)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81084ad1)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff8109ed1a)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff834743e2)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff81068167)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81097ea5)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff810b63e2)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff83e9c184)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff810699e6)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff8109af4e)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff810b94e2)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff836bfc24)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff81070b87)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff810a262c)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0902)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff838f0744)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/tboot.c (ffffffff81043e23)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81062752)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff81076b37)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828ae082)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff81033448)
Location: arch/x86/include/asm/irqflags.h:110
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81052aec)
Location: arch/x86/include/asm/irqflags.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff81066437)
Location: arch/x86/include/asm/irqflags.h:110
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828a626f)
Location: arch/x86/include/asm/irqflags.h:110
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff81043c63)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81062c02)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff81076ae7)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828c0f81)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
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
In arch/x86/kernel/tboot.c (ffffffff81045063)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff810641c2)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/kvm.c (ffffffff81078c47)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828c40cc)
Location: arch/x86/include/asm/paravirt.h:147
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
</details>
</li>
</ul>

## Differences
