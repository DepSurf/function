# Function: <code>pci_bus_resetable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81433800)
Location: drivers/pci/pci.c:3848
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_resetable
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_try_reset_bus
```
**Symbols:**

```
ffffffff81433800-ffffffff8143384f: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8147f0a0)
Location: drivers/pci/pci.c:4169
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff8147f0a0-ffffffff8147f0fb: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a0780)
Location: drivers/pci/pci.c:4207
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff814a0780-ffffffff814a07db: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814aa440)
Location: drivers/pci/pci.c:4361
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff814aa440-ffffffff814aa48f: pci_bus_resetable (STB_LOCAL)
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
In drivers/pci/pci.c (ffffffff814ebadb)
Location: drivers/pci/pci.c:4377
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_reset
Direct callers:
  - drivers/pci/pci.c:pci_slot_reset
```
**Symbols:**

```
ffffffff814eb9f0-ffffffff814eba51: pci_bus_resetable.part.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81518e50)
Location: drivers/pci/pci.c:4624
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff81518e50-ffffffff81518eb4: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152e8c0)
Location: drivers/pci/pci.c:4915
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff8152e8c0-ffffffff8152e924: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155e060)
Location: drivers/pci/pci.c:5013
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff8155e060-ffffffff8155e0c4: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8157f0d0)
Location: drivers/pci/pci.c:5143
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff8157f0d0-ffffffff8157f134: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81624660)
Location: drivers/pci/pci.c:5173
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff81624660-ffffffff816246c4: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164a220)
Location: drivers/pci/pci.c:5241
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff8164a220-ffffffff8164a284: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162ce10)
Location: drivers/pci/pci.c:5290
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff8162ce10-ffffffff8162ce74: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169c0a0)
Location: drivers/pci/pci.c:5480
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff8169c0a0-ffffffff8169c104: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817bda00)
Location: drivers/pci/pci.c:5576
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff817bda00-ffffffff817bda7c: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818d9bf0)
Location: drivers/pci/pci.c:5513
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff818d9bf0-ffffffff818d9c6c: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191cf40)
Location: drivers/pci/pci.c:5635
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff8191cf40-ffffffff8191cfbc: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e1a48)
Location: drivers/pci/pci.c:5143
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffff8000106e1a48-ffff8000106e1acc: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087d6dc)
Location: drivers/pci/pci.c:5143
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
c087d6dc-c087d764: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085afb0)
Location: drivers/pci/pci.c:5143
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
c00000000085afb0-c00000000085b07c: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004b9654)
Location: drivers/pci/pci.c:5143
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffe0004b9654-ffffffe0004b96c6: pci_bus_resetable (STB_LOCAL)
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
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815735f0)
Location: drivers/pci/pci.c:5143
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff815735f0-ffffffff81573654: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81561d50)
Location: drivers/pci/pci.c:5143
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff81561d50-ffffffff81561db4: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81572e20)
Location: drivers/pci/pci.c:5143
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff81572e20-ffffffff81572e84: pci_bus_resetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158d300)
Location: drivers/pci/pci.c:5143
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_bus
  - drivers/pci/pci.c:pci_bus_error_reset
  - drivers/pci/pci.c:pci_slot_reset
  - drivers/pci/pci.c:pci_bus_resetable
```
**Symbols:**

```
ffffffff8158d300-ffffffff8158d364: pci_bus_resetable (STB_LOCAL)
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
