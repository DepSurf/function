# Function: <code>pci_dev_restore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81436150)
Location: drivers/pci/pci.c:3700
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_slot_restore
```
**Symbols:**

```
ffffffff81436150-ffffffff81436192: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81481c70)
Location: drivers/pci/pci.c:4021
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_restore
  - drivers/pci/pci.c:pci_bus_restore
```
**Symbols:**

```
ffffffff81481c70-ffffffff81481cb2: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a3140)
Location: drivers/pci/pci.c:4059
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_restore
  - drivers/pci/pci.c:pci_bus_restore
```
**Symbols:**

```
ffffffff814a3140-ffffffff814a3182: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814acf40)
Location: drivers/pci/pci.c:4138
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_restore
  - drivers/pci/pci.c:pci_bus_restore
```
**Symbols:**

```
ffffffff814acf40-ffffffff814acf95: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ec310)
Location: drivers/pci/pci.c:4175
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_restore
  - drivers/pci/pci.c:pci_bus_restore
```
**Symbols:**

```
ffffffff814ec310-ffffffff814ec368: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151be90)
Location: drivers/pci/pci.c:4424
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_restore
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff8151be90-ffffffff8151beeb: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81533cb0)
Location: drivers/pci/pci.c:4715
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff81533cb0-ffffffff81533d0b: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815631d0)
Location: drivers/pci/pci.c:4812
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff815631d0-ffffffff8156322a: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81584390)
Location: drivers/pci/pci.c:4942
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff81584390-ffffffff815843ea: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162abd0)
Location: drivers/pci/pci.c:4972
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff8162abd0-ffffffff8162ac2a: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164e380)
Location: drivers/pci/pci.c:5040
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff8164e380-ffffffff8164e3da: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81630f90)
Location: drivers/pci/pci.c:5089
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff81630f90-ffffffff81630fea: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a21b0)
Location: drivers/pci/pci.c:5154
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff816a21b0-ffffffff816a220d: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c4240)
Location: drivers/pci/pci.c:5250
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff817c4240-ffffffff817c42b2: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e1150)
Location: drivers/pci/pci.c:5187
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff818e1150-ffffffff818e11c2: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81924590)
Location: drivers/pci/pci.c:5309
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff81924590-ffffffff81924602: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196cc60)
Location: drivers/pci/pci.c:5419
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff8196cc60-ffffffff8196ccd2: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e86f8)
Location: drivers/pci/pci.c:4942
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffff8000106e86f8-ffff8000106e876c: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c08837c0)
Location: drivers/pci/pci.c:4942
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
c08837c0-c0883838: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000863380)
Location: drivers/pci/pci.c:4942
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
c000000000863380-c00000000086342c: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004becf2)
Location: drivers/pci/pci.c:4942
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffe0004becf2-ffffffe0004bed5a: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815788b0)
Location: drivers/pci/pci.c:4942
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff815788b0-ffffffff8157890a: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81566ff0)
Location: drivers/pci/pci.c:4942
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff81566ff0-ffffffff8156704a: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815780e0)
Location: drivers/pci/pci.c:4942
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff815780e0-ffffffff8157813a: pci_dev_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_dev_restore(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815925a0)
Location: drivers/pci/pci.c:4942
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
```
**Symbols:**

```
ffffffff815925a0-ffffffff815925fa: pci_dev_restore (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
