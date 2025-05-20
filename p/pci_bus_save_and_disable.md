# Function: <code>pci_bus_save_and_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_bus_save_and_disable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81436820)
Location: drivers/pci/pci.c:3987
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_save_and_disable
  - drivers/pci/pci.c:pci_slot_save_and_disable
  - drivers/pci/pci.c:pci_try_reset_bus
```
**Symbols:**

```
ffffffff81436820-ffffffff8143685c: pci_bus_save_and_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_bus_save_and_disable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482380)
Location: drivers/pci/pci.c:4308
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_slot_save_and_disable
  - drivers/pci/pci.c:pci_bus_save_and_disable
```
**Symbols:**

```
ffffffff81482380-ffffffff814823bc: pci_bus_save_and_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_bus_save_and_disable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a3910)
Location: drivers/pci/pci.c:4346
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_slot_save_and_disable
  - drivers/pci/pci.c:pci_bus_save_and_disable
```
**Symbols:**

```
ffffffff814a3910-ffffffff814a394c: pci_bus_save_and_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_bus_save_and_disable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ad910)
Location: drivers/pci/pci.c:4500
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_slot_save_and_disable
  - drivers/pci/pci.c:pci_bus_save_and_disable
```
**Symbols:**

```
ffffffff814ad910-ffffffff814ad979: pci_bus_save_and_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_bus_save_and_disable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ecce0)
Location: drivers/pci/pci.c:4524
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_slot_save_and_disable
  - drivers/pci/pci.c:pci_bus_save_and_disable
```
**Symbols:**

```
ffffffff814ecce0-ffffffff814ecd49: pci_bus_save_and_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_bus_save_and_disable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151c8b0)
Location: drivers/pci/pci.c:4771
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_reset_bus
  - drivers/pci/pci.c:pci_reset_bus
  - drivers/pci/pci.c:pci_slot_save_and_disable
  - drivers/pci/pci.c:pci_bus_save_and_disable
```
**Symbols:**

```
ffffffff8151c8b0-ffffffff8151c917: pci_bus_save_and_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_bus_save_and_disable(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815321a0)
Location: drivers/pci/pci.c:5062
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_save_and_disable
```
**Symbols:**

```
ffffffff815321a0-ffffffff81532207: pci_bus_save_and_disable (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
