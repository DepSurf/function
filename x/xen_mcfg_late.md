# Function: <code>xen_mcfg_late</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xen_mcfg_late();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff81fa5043)
Location: drivers/xen/pci.c:216
Inline: True
```
**Symbols:**

```
ffffffff81fa5043-ffffffff81fa511e: xen_mcfg_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xen_mcfg_late();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff81fd15c8)
Location: drivers/xen/pci.c:216
Inline: True
```
**Symbols:**

```
ffffffff81fd15c8-ffffffff81fd16a9: xen_mcfg_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xen_mcfg_late();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff8200ef63)
Location: drivers/xen/pci.c:216
Inline: True
```
**Symbols:**

```
ffffffff8200ef63-ffffffff8200f044: xen_mcfg_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int xen_mcfg_late();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff820f0a41)
Location: drivers/xen/pci.c:216
Inline: True
```
**Symbols:**

```
ffffffff820f0a41-ffffffff820f0b27: xen_mcfg_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int xen_mcfg_late();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff826fa24b)
Location: drivers/xen/pci.c:216
Inline: True
```
**Symbols:**

```
ffffffff826fa24b-ffffffff826fa331: xen_mcfg_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_mcfg_late();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff8272458c)
Location: drivers/xen/pci.c:216
Inline: False
```
**Symbols:**

```
ffffffff8272458c-ffffffff8272465c: xen_mcfg_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_mcfg_late();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff828dc765)
Location: drivers/xen/pci.c:216
Inline: False
```
**Symbols:**

```
ffffffff828dc765-ffffffff828dc835: xen_mcfg_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xen_mcfg_late();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff828f705b)
Location: drivers/xen/pci.c:204
Inline: False
```
**Symbols:**

```
ffffffff828f705b-ffffffff828f7113: xen_mcfg_late (STB_LOCAL)
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
In drivers/xen/pci.c (ffffffff816710b6)
Location: drivers/xen/pci.c:217
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/pci.c (0)
Location: drivers/xen/pci.c:217
Inline: True
Direct callers:
  - drivers/xen/pci.c:xen_add_device
```
**Symbols:**

```
ffffffff817214a0-ffffffff8172154e: xen_mcfg_late.isra.0 (STB_LOCAL)
ffffffff8172198b-ffffffff817219a2: xen_mcfg_late.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/pci.c (0)
Location: drivers/xen/pci.c:217
Inline: True
Direct callers:
  - drivers/xen/pci.c:xen_add_device
```
**Symbols:**

```
ffffffff8173e170-ffffffff8173e21e: xen_mcfg_late.isra.0 (STB_LOCAL)
ffffffff81c05a22-ffffffff81c05a39: xen_mcfg_late.isra.0.cold (STB_LOCAL)
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
In drivers/xen/pci.c (ffffffff81721f0c)
Location: drivers/xen/pci.c:217
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff817a0d4a)
Location: drivers/xen/pci.c:217
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff818dab9c)
Location: drivers/xen/pci.c:218
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
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
In drivers/xen/pci.c (ffffffff81a2db5c)
Location: drivers/xen/pci.c:218
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
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
In drivers/xen/pci.c (ffffffff81a772fc)
Location: drivers/xen/pci.c:218
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
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
In drivers/xen/pci.c (ffffffff81ac950c)
Location: drivers/xen/pci.c:218
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
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
In drivers/xen/pci.c (ffffffff81637176)
Location: drivers/xen/pci.c:217
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff81664ef6)
Location: drivers/xen/pci.c:217
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
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
In drivers/xen/pci.c (ffffffff8167f4a6)
Location: drivers/xen/pci.c:217
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
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
</ul>
