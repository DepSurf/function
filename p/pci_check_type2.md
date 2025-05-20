# Function: <code>pci_check_type2</code>

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
In arch/x86/pci/direct.c (ffffffff81fb879e)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff81fe6362)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff82024ba6)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff8210804c)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff82711992)
Location: arch/x86/pci/direct.c:244
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff8273bc7e)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff828f5c90)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff829116e0)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff8291b477)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff82d311de)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff83020168)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff8322b360)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff83315ae4)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_check_type2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff834d0219)
Location: arch/x86/pci/direct.c:243
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff834d0219-ffffffff834d028a: pci_check_type2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_check_type2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff83f140c0)
Location: arch/x86/pci/direct.c:243
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff83f140c0-ffffffff83f1413c: pci_check_type2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_check_type2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8373a840)
Location: arch/x86/pci/direct.c:243
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8373a840-ffffffff8373a8bc: pci_check_type2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_check_type2();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8396f0c0)
Location: arch/x86/pci/direct.c:243
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8396f0c0-ffffffff8396f13c: pci_check_type2 (STB_LOCAL)
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
In arch/x86/pci/direct.c (ffffffff82900186)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff828f8789)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff82915782)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
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
In arch/x86/pci/direct.c (ffffffff8291c4d9)
Location: arch/x86/pci/direct.c:243
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_direct_probe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
