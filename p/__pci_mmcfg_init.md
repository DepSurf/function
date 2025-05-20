# Function: <code>__pci_mmcfg_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81fb88aa)
Location: arch/x86/pci/mmconfig-shared.c:639
Inline: True
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
```
**Symbols:**

```
ffffffff81fb88aa-ffffffff81fb8951: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81fe6478)
Location: arch/x86/pci/mmconfig-shared.c:639
Inline: True
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff81fe6478-ffffffff81fe6526: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82024cbc)
Location: arch/x86/pci/mmconfig-shared.c:639
Inline: True
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff82024cbc-ffffffff82024d6a: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82108167)
Location: arch/x86/pci/mmconfig-shared.c:639
Inline: True
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff82108167-ffffffff8210821a: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82711aad)
Location: arch/x86/pci/mmconfig-shared.c:640
Inline: True
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff82711aad-ffffffff82711b60: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8273bd9a)
Location: arch/x86/pci/mmconfig-shared.c:635
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff8273bd9a-ffffffff8273be4d: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff828f5dac)
Location: arch/x86/pci/mmconfig-shared.c:635
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff828f5dac-ffffffff828f5e5f: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82911805)
Location: arch/x86/pci/mmconfig-shared.c:635
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff82911805-ffffffff829118b8: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8291b59c)
Location: arch/x86/pci/mmconfig-shared.c:636
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff8291b59c-ffffffff8291b64f: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82d31405)
Location: arch/x86/pci/mmconfig-shared.c:636
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff82d31405-ffffffff82d314b8: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8302038f)
Location: arch/x86/pci/mmconfig-shared.c:636
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff8302038f-ffffffff83020442: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8322b48f)
Location: arch/x86/pci/mmconfig-shared.c:636
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff8322b48f-ffffffff8322b542: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff83315c64)
Location: arch/x86/pci/mmconfig-shared.c:636
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff83315c64-ffffffff83315d17: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff834d0508)
Location: arch/x86/pci/mmconfig-shared.c:636
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff834d0508-ffffffff834d05d5: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff83f14490)
Location: arch/x86/pci/mmconfig-shared.c:668
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff83f14490-ffffffff83f1458a: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8373ac10)
Location: arch/x86/pci/mmconfig-shared.c:668
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff8373ac10-ffffffff8373ad0a: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8396f4e0)
Location: arch/x86/pci/mmconfig-shared.c:668
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff8396f4e0-ffffffff8396f626: __pci_mmcfg_init (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff829002ab)
Location: arch/x86/pci/mmconfig-shared.c:636
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff829002ab-ffffffff8290035e: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff828f88a1)
Location: arch/x86/pci/mmconfig-shared.c:636
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff828f88a1-ffffffff828f8954: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff829158a7)
Location: arch/x86/pci/mmconfig-shared.c:636
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff829158a7-ffffffff8291595a: __pci_mmcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __pci_mmcfg_init(int early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8291c5fe)
Location: arch/x86/pci/mmconfig-shared.c:636
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_late_init
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff8291c5fe-ffffffff8291c6b1: __pci_mmcfg_init (STB_LOCAL)
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
