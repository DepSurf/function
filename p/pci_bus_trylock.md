# Function: <code>pci_bus_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81435a30)
Location: drivers/pci/pci.c:3886
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_bus
```
**Symbols:**

```
ffffffff81435a30-ffffffff81435ab6: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81481510)
Location: drivers/pci/pci.c:4207
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff81481510-ffffffff81481596: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a2a40)
Location: drivers/pci/pci.c:4245
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff814a2a40-ffffffff814a2ac6: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ac870)
Location: drivers/pci/pci.c:4399
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff814ac870-ffffffff814ac8f5: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eb960)
Location: drivers/pci/pci.c:4419
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff814eb960-ffffffff814eb9e5: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b3a0)
Location: drivers/pci/pci.c:4666
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff8151b3a0-ffffffff8151b43c: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531250)
Location: drivers/pci/pci.c:4957
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff81531250-ffffffff815312d6: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81560aa0)
Location: drivers/pci/pci.c:5055
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff81560aa0-ffffffff81560b26: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81581bc0)
Location: drivers/pci/pci.c:5185
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff81581bc0-ffffffff81581c46: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81628940)
Location: drivers/pci/pci.c:5215
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff81628940-ffffffff81628a37: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164eb60)
Location: drivers/pci/pci.c:5283
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff8164eb60-ffffffff8164ec57: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81631780)
Location: drivers/pci/pci.c:5332
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff81631780-ffffffff81631877: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a1010)
Location: drivers/pci/pci.c:5522
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff816a1010-ffffffff816a1107: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c2df0)
Location: drivers/pci/pci.c:5618
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff817c2df0-ffffffff817c2ef3: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dfbb0)
Location: drivers/pci/pci.c:5555
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff818dfbb0-ffffffff818dfcb3: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81923010)
Location: drivers/pci/pci.c:5677
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff81923010-ffffffff81923113: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196b590)
Location: drivers/pci/pci.c:5787
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff8196b590-ffffffff8196b693: pci_bus_trylock (STB_LOCAL)
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
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e4dc8)
Location: drivers/pci/pci.c:5185
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffff8000106e4dc8-ffff8000106e4e70: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0880a98)
Location: drivers/pci/pci.c:5185
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
c0880a98-c0880b3c: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085f500)
Location: drivers/pci/pci.c:5185
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
c00000000085f500-c00000000085f5ec: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bc124)
Location: drivers/pci/pci.c:5185
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffe0004bc124-ffffffe0004bc1b4: pci_bus_trylock (STB_LOCAL)
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
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815760e0)
Location: drivers/pci/pci.c:5185
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff815760e0-ffffffff81576166: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564840)
Location: drivers/pci/pci.c:5185
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff81564840-ffffffff815648c6: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575910)
Location: drivers/pci/pci.c:5185
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff81575910-ffffffff81575996: pci_bus_trylock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_bus_trylock(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158fee0)
Location: drivers/pci/pci.c:5185
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_trylock
```
**Symbols:**

```
ffffffff8158fee0-ffffffff8158ff66: pci_bus_trylock (STB_LOCAL)
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
