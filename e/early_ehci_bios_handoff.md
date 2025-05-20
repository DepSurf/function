# Function: <code>early_ehci_bios_handoff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff81fb0db3)
Location: drivers/usb/early/ehci-dbgp.c:715
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff81fdd8d1)
Location: drivers/usb/early/ehci-dbgp.c:715
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff8201b4e8)
Location: drivers/usb/early/ehci-dbgp.c:714
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff820fdd83)
Location: drivers/usb/early/ehci-dbgp.c:713
Inline: True
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
In drivers/usb/early/ehci-dbgp.c (ffffffff82707672)
Location: drivers/usb/early/ehci-dbgp.c:714
Inline: True
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
In drivers/usb/early/ehci-dbgp.c (ffffffff82731566)
Location: drivers/usb/early/ehci-dbgp.c:714
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff828ea227)
Location: drivers/usb/early/ehci-dbgp.c:714
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff82904c4c)
Location: drivers/usb/early/ehci-dbgp.c:714
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff8290e687)
Location: drivers/usb/early/ehci-dbgp.c:714
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void early_ehci_bios_handoff();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff82d22312)
Location: drivers/usb/early/ehci-dbgp.c:714
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
```
**Symbols:**

```
ffffffff82d22312-ffffffff82d2242c: early_ehci_bios_handoff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void early_ehci_bios_handoff();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff8301010b)
Location: drivers/usb/early/ehci-dbgp.c:709
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
```
**Symbols:**

```
ffffffff8301010b-ffffffff83010225: early_ehci_bios_handoff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void early_ehci_bios_handoff();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff8321b111)
Location: drivers/usb/early/ehci-dbgp.c:709
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff8321b111-ffffffff8321b22e: early_ehci_bios_handoff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void early_ehci_bios_handoff();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff83304cef)
Location: drivers/usb/early/ehci-dbgp.c:709
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
```
**Symbols:**

```
ffffffff83304cef-ffffffff83304e0c: early_ehci_bios_handoff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void early_ehci_bios_handoff();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff834bddc2)
Location: drivers/usb/early/ehci-dbgp.c:709
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
```
**Symbols:**

```
ffffffff834bddc2-ffffffff834bdeee: early_ehci_bios_handoff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void early_ehci_bios_handoff();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff83efbbd0)
Location: drivers/usb/early/ehci-dbgp.c:709
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
```
**Symbols:**

```
ffffffff83efbbd0-ffffffff83efbd20: early_ehci_bios_handoff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void early_ehci_bios_handoff();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff837219e0)
Location: drivers/usb/early/ehci-dbgp.c:709
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
```
**Symbols:**

```
ffffffff837219e0-ffffffff83721b30: early_ehci_bios_handoff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void early_ehci_bios_handoff();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff83955810)
Location: drivers/usb/early/ehci-dbgp.c:709
Inline: False
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
```
**Symbols:**

```
ffffffff83955810-ffffffff83955960: early_ehci_bios_handoff (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff828f57e1)
Location: drivers/usb/early/ehci-dbgp.c:714
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In drivers/usb/early/ehci-dbgp.c (ffffffff828ed0f1)
Location: drivers/usb/early/ehci-dbgp.c:714
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff82909a82)
Location: drivers/usb/early/ehci-dbgp.c:714
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff8290f6e9)
Location: drivers/usb/early/ehci-dbgp.c:714
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
