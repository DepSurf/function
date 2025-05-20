# Function: <code>check_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff81f70a26)
Location: arch/x86/kernel/mpparse.c:709
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff814abd11)
Location: drivers/acpi/pci_slot.c:71
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff81f99160)
Location: arch/x86/kernel/mpparse.c:708
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff814fb0a9)
Location: drivers/acpi/pci_slot.c:53
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff81fd4629)
Location: arch/x86/kernel/mpparse.c:711
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff8151dd3e)
Location: drivers/acpi/pci_slot.c:53
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff820b5306)
Location: arch/x86/kernel/mpparse.c:711
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff8152ed66)
Location: drivers/acpi/pci_slot.c:53
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff826bba8e)
Location: arch/x86/kernel/mpparse.c:728
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff8158fa36)
Location: drivers/acpi/pci_slot.c:53
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff826e5775)
Location: arch/x86/kernel/mpparse.c:732
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
```
In drivers/acpi/pci_slot.c (ffffffff815c6e1f)
Location: drivers/acpi/pci_slot.c:53
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff8289c2b0)
Location: arch/x86/kernel/mpparse.c:731
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
```
In drivers/acpi/pci_slot.c (ffffffff815e03df)
Location: drivers/acpi/pci_slot.c:53
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff828b3f71)
Location: arch/x86/kernel/mpparse.c:729
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
```
In drivers/acpi/pci_slot.c (ffffffff81611f6f)
Location: drivers/acpi/pci_slot.c:45
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff828b73c8)
Location: arch/x86/kernel/mpparse.c:729
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
```
In drivers/acpi/pci_slot.c (ffffffff8163341f)
Location: drivers/acpi/pci_slot.c:45
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int check_slot(long unsigned int mpc_new_phys, long unsigned int mpc_new_length, int count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff82cdc586)
Location: arch/x86/kernel/mpparse.c:729
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff816e0240)
Location: drivers/acpi/pci_slot.c:45
Inline: False
Direct callers:
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff816e0240-ffffffff816e039b: check_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
int check_slot(long unsigned int mpc_new_phys, long unsigned int mpc_new_length, int count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff82fc8877)
Location: arch/x86/kernel/mpparse.c:711
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff816fe0a0)
Location: drivers/acpi/pci_slot.c:42
Inline: False
Direct callers:
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff816fe0a0-ffffffff816fe1fb: check_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int check_slot(long unsigned int mpc_new_phys, long unsigned int mpc_new_length, int count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff831d31d8)
Location: arch/x86/kernel/mpparse.c:711
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff816dfdc0)
Location: drivers/acpi/pci_slot.c:42
Inline: False
Direct callers:
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff816dfdc0-ffffffff816dff1b: check_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int check_slot(long unsigned int mpc_new_phys, long unsigned int mpc_new_length, int count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff832b5cce)
Location: arch/x86/kernel/mpparse.c:712
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff81758010)
Location: drivers/acpi/pci_slot.c:42
Inline: False
Direct callers:
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff81758010-ffffffff81758165: check_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
int check_slot(long unsigned int mpc_new_phys, long unsigned int mpc_new_length, int count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff83467641)
Location: arch/x86/kernel/mpparse.c:712
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff8188b5a0)
Location: drivers/acpi/pci_slot.c:42
Inline: False
Direct callers:
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff8188b5a0-ffffffff8188b6fc: check_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int check_slot(long unsigned int mpc_new_phys, long unsigned int mpc_new_length, int count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff83e8b253)
Location: arch/x86/kernel/mpparse.c:712
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff819d22d0)
Location: drivers/acpi/pci_slot.c:42
Inline: False
Direct callers:
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff819d22d0-ffffffff819d242c: check_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int check_slot(long unsigned int mpc_new_phys, long unsigned int mpc_new_length, int count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff836ae9d8)
Location: arch/x86/kernel/mpparse.c:712
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff81a198f0)
Location: drivers/acpi/pci_slot.c:42
Inline: False
Direct callers:
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff81a198f0-ffffffff81a19a4c: check_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int check_slot(long unsigned int mpc_new_phys, long unsigned int mpc_new_length, int count);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff838def58)
Location: arch/x86/kernel/mpparse.c:700
Inline: True
```
```
In drivers/acpi/pci_slot.c (ffffffff81a64bc0)
Location: drivers/acpi/pci_slot.c:42
Inline: False
Direct callers:
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff81a64bc0-ffffffff81a64d1c: check_slot (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_slot.c (ffff8000107a19a4)
Location: drivers/acpi/pci_slot.c:45
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
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
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff828a53cf)
Location: arch/x86/kernel/mpparse.c:729
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
```
In drivers/acpi/pci_slot.c (ffffffff81602fbf)
Location: drivers/acpi/pci_slot.c:45
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff8289d511)
Location: arch/x86/kernel/mpparse.c:729
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff828b82df)
Location: arch/x86/kernel/mpparse.c:729
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
```
In drivers/acpi/pci_slot.c (ffffffff816276ff)
Location: drivers/acpi/pci_slot.c:45
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff828b83e0)
Location: arch/x86/kernel/mpparse.c:729
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
```
In drivers/acpi/pci_slot.c (ffffffff816415af)
Location: drivers/acpi/pci_slot.c:45
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
