# Function: <code>pci_sanity_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff81fb853c)
Location: arch/x86/pci/direct.c:194
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff81fb853c-ffffffff81fb861b: pci_sanity_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff81fe6106)
Location: arch/x86/pci/direct.c:194
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff81fe6106-ffffffff81fe61e5: pci_sanity_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8202494a)
Location: arch/x86/pci/direct.c:194
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8202494a-ffffffff82024a29: pci_sanity_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff82107dea)
Location: arch/x86/pci/direct.c:194
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff82107dea-ffffffff82107ec4: pci_sanity_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8271172c)
Location: arch/x86/pci/direct.c:195
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8271172c-ffffffff8271180a: pci_sanity_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8273ba2b)
Location: arch/x86/pci/direct.c:195
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8273ba2b-ffffffff8273baf6: pci_sanity_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff828f5a3d)
Location: arch/x86/pci/direct.c:195
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff828f5a3d-ffffffff828f5b08: pci_sanity_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff82911488)
Location: arch/x86/pci/direct.c:195
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff82911488-ffffffff82911553: pci_sanity_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8291b21f)
Location: arch/x86/pci/direct.c:195
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8291b21f-ffffffff8291b2ea: pci_sanity_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_sanity_check(const struct pci_raw_ops *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff82d30f83)
Location: arch/x86/pci/direct.c:195
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff82d30f83-ffffffff82d3104e: pci_sanity_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_sanity_check(const struct pci_raw_ops *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8301ff0d)
Location: arch/x86/pci/direct.c:195
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8301ff0d-ffffffff8301ffd8: pci_sanity_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_sanity_check(const struct pci_raw_ops *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8322b100)
Location: arch/x86/pci/direct.c:195
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8322b100-ffffffff8322b1cb: pci_sanity_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_sanity_check(const struct pci_raw_ops *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff83315884)
Location: arch/x86/pci/direct.c:195
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff83315884-ffffffff8331594f: pci_sanity_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_sanity_check(const struct pci_raw_ops *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff834d00c7)
Location: arch/x86/pci/direct.c:195
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type1
```
**Symbols:**

```
ffffffff834d00c7-ffffffff834d01a4: pci_sanity_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_sanity_check(const struct pci_raw_ops *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff83f13f20)
Location: arch/x86/pci/direct.c:195
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type1
```
**Symbols:**

```
ffffffff83f13f20-ffffffff83f1400f: pci_sanity_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_sanity_check(const struct pci_raw_ops *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8373a6a0)
Location: arch/x86/pci/direct.c:195
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type1
```
**Symbols:**

```
ffffffff8373a6a0-ffffffff8373a78f: pci_sanity_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_sanity_check(const struct pci_raw_ops *o);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8396ef20)
Location: arch/x86/pci/direct.c:195
Inline: False
Direct callers:
  - arch/x86/pci/direct.c:pci_check_type2
  - arch/x86/pci/direct.c:pci_check_type1
```
**Symbols:**

```
ffffffff8396ef20-ffffffff8396f00f: pci_sanity_check (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff828fff2e)
Location: arch/x86/pci/direct.c:195
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff828fff2e-ffffffff828ffff9: pci_sanity_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff828f8546)
Location: arch/x86/pci/direct.c:195
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff828f8546-ffffffff828f8611: pci_sanity_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8291552a)
Location: arch/x86/pci/direct.c:195
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8291552a-ffffffff829155f5: pci_sanity_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/pci/direct.c (ffffffff8291c281)
Location: arch/x86/pci/direct.c:195
Inline: True
Direct callers:
  - arch/x86/pci/direct.c:pci_direct_probe
  - arch/x86/pci/direct.c:pci_direct_probe
```
**Symbols:**

```
ffffffff8291c281-ffffffff8291c34c: pci_sanity_check.isra.0 (STB_LOCAL)
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
