# Function: <code>dbgp_ehci_controller_reset</code>

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
In drivers/usb/early/ehci-dbgp.c (ffffffff81662ef9)
Location: drivers/usb/early/ehci-dbgp.c:470
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
In drivers/usb/early/ehci-dbgp.c (ffffffff816c3135)
Location: drivers/usb/early/ehci-dbgp.c:470
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
In drivers/usb/early/ehci-dbgp.c (ffffffff816f10f5)
Location: drivers/usb/early/ehci-dbgp.c:469
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
In drivers/usb/early/ehci-dbgp.c (ffffffff81706977)
Location: drivers/usb/early/ehci-dbgp.c:469
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
In drivers/usb/early/ehci-dbgp.c (ffffffff81777b37)
Location: drivers/usb/early/ehci-dbgp.c:470
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
In drivers/usb/early/ehci-dbgp.c (ffffffff827316cb)
Location: drivers/usb/early/ehci-dbgp.c:470
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
In drivers/usb/early/ehci-dbgp.c (ffffffff828ea393)
Location: drivers/usb/early/ehci-dbgp.c:470
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
In drivers/usb/early/ehci-dbgp.c (ffffffff82904db9)
Location: drivers/usb/early/ehci-dbgp.c:470
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
In drivers/usb/early/ehci-dbgp.c (ffffffff8290e7f4)
Location: drivers/usb/early/ehci-dbgp.c:470
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dbgp_ehci_controller_reset();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff81922db6)
Location: drivers/usb/early/ehci-dbgp.c:470
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
```
**Symbols:**

```
ffffffff81922460-ffffffff819224a3: dbgp_ehci_controller_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dbgp_ehci_controller_reset();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff8192a4d6)
Location: drivers/usb/early/ehci-dbgp.c:465
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
```
**Symbols:**

```
ffffffff81929b50-ffffffff81929b93: dbgp_ehci_controller_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff8321b557)
Location: drivers/usb/early/ehci-dbgp.c:465
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dbgp_ehci_controller_reset();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff819ae79c)
Location: drivers/usb/early/ehci-dbgp.c:465
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
```
**Symbols:**

```
ffffffff819add50-ffffffff819add93: dbgp_ehci_controller_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dbgp_ehci_controller_reset();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff81b0cf40)
Location: drivers/usb/early/ehci-dbgp.c:465
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
```
**Symbols:**

```
ffffffff81b0c480-ffffffff81b0c4cf: dbgp_ehci_controller_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff83efbe5c)
Location: drivers/usb/early/ehci-dbgp.c:465
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff83721c6c)
Location: drivers/usb/early/ehci-dbgp.c:465
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff83955a9c)
Location: drivers/usb/early/ehci-dbgp.c:465
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:ehci_setup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
In drivers/usb/early/ehci-dbgp.c (ffffffff828f594e)
Location: drivers/usb/early/ehci-dbgp.c:470
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
In drivers/usb/early/ehci-dbgp.c (ffffffff828ed25e)
Location: drivers/usb/early/ehci-dbgp.c:470
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
In drivers/usb/early/ehci-dbgp.c (ffffffff82909bef)
Location: drivers/usb/early/ehci-dbgp.c:470
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
In drivers/usb/early/ehci-dbgp.c (ffffffff8290f856)
Location: drivers/usb/early/ehci-dbgp.c:470
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
