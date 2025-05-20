# Function: <code>__cmci_disable_bank</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047490)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:350
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_clear
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_disable_bank
```
**Symbols:**

```
ffffffff81047490-ffffffff8104752a: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff810475b0)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:350
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_clear
```
**Symbols:**

```
ffffffff810475b0-ffffffff81047617: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81049150)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:352
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_clear
```
**Symbols:**

```
ffffffff81049150-ffffffff810491b7: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81048b00)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:352
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_clear
```
**Symbols:**

```
ffffffff81048b00-ffffffff81048b67: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104c370)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:353
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104c370-ffffffff8104c3d7: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f080)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:353
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104f080-ffffffff8104f0e7: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104c750)
Location: arch/x86/kernel/cpu/mce/intel.c:353
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104c750-ffffffff8104c7b7: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104f420)
Location: arch/x86/kernel/cpu/mce/intel.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104f420-ffffffff8104f487: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fda0)
Location: arch/x86/kernel/cpu/mce/intel.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104fda0-ffffffff8104fe07: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810544a0)
Location: arch/x86/kernel/cpu/mce/intel.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff810544a0-ffffffff81054507: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810533e0)
Location: arch/x86/kernel/cpu/mce/intel.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff810533e0-ffffffff81053447: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054cb0)
Location: arch/x86/kernel/cpu/mce/intel.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff81054cb0-ffffffff81054d17: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105d600)
Location: arch/x86/kernel/cpu/mce/intel.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8105d600-ffffffff8105d667: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81069e40)
Location: arch/x86/kernel/cpu/mce/intel.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff81069e40-ffffffff81069ebf: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81079920)
Location: arch/x86/kernel/cpu/mce/intel.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff81079920-ffffffff8107999f: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107bbd0)
Location: arch/x86/kernel/cpu/mce/intel.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8107bbd0-ffffffff8107bc4f: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81083140)
Location: arch/x86/kernel/cpu/mce/intel.c:320
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff81083140-ffffffff810831e6: __cmci_disable_bank (STB_LOCAL)
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
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fea0)
Location: arch/x86/kernel/cpu/mce/intel.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104fea0-ffffffff8104ff07: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103f970)
Location: arch/x86/kernel/cpu/mce/intel.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8103f970-ffffffff8103fa0d: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fd50)
Location: arch/x86/kernel/cpu/mce/intel.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104fd50-ffffffff8104fdb7: __cmci_disable_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __cmci_disable_bank(int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051190)
Location: arch/x86/kernel/cpu/mce/intel.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff81051190-ffffffff810511f7: __cmci_disable_bank (STB_LOCAL)
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
