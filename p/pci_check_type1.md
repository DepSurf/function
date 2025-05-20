# Function: <code>pci_check_type1</code>

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
In arch/x86/pci/direct.c (ffffffff81fb86ba)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff81fe6283)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff82024ac7)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff82107f6d)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff827118b3)
Location: arch/x86/pci/direct.c:224
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
In arch/x86/pci/direct.c (ffffffff8273bb9f)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff828f5bb1)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff829115fd)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff8291b394)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff82d310fa)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff83020084)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff8322b277)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff833159fb)
Location: arch/x86/pci/direct.c:223
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
int pci_check_type1();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff834d01a4)
Location: arch/x86/pci/direct.c:223
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff834d01a4-ffffffff834d0219: pci_check_type1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_check_type1();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff83f14020)
Location: arch/x86/pci/direct.c:223
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff83f14020-ffffffff83f140a2: pci_check_type1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_check_type1();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8373a7a0)
Location: arch/x86/pci/direct.c:223
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8373a7a0-ffffffff8373a822: pci_check_type1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_check_type1();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8396f020)
Location: arch/x86/pci/direct.c:223
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8396f020-ffffffff8396f0a2: pci_check_type1 (STB_LOCAL)
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
In arch/x86/pci/direct.c (ffffffff829000a3)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff828f86b7)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff8291569f)
Location: arch/x86/pci/direct.c:223
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
In arch/x86/pci/direct.c (ffffffff8291c3f6)
Location: arch/x86/pci/direct.c:223
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
