# Function: <code>pbus_size_io</code>

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
In drivers/pci/setup-bus.c (ffffffff8143fa9f)
Location: drivers/pci/setup-bus.c:902
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
In drivers/pci/setup-bus.c (ffffffff8148b95c)
Location: drivers/pci/setup-bus.c:906
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
In drivers/pci/setup-bus.c (ffffffff814ad14c)
Location: drivers/pci/setup-bus.c:907
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
In drivers/pci/setup-bus.c (ffffffff814b7515)
Location: drivers/pci/setup-bus.c:898
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
In drivers/pci/setup-bus.c (ffffffff814f7665)
Location: drivers/pci/setup-bus.c:898
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
In drivers/pci/setup-bus.c (ffffffff8152818c)
Location: drivers/pci/setup-bus.c:893
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
In drivers/pci/setup-bus.c (ffffffff8153e02e)
Location: drivers/pci/setup-bus.c:899
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
In drivers/pci/setup-bus.c (ffffffff8156d607)
Location: drivers/pci/setup-bus.c:864
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
In drivers/pci/setup-bus.c (ffffffff8158e5e7)
Location: drivers/pci/setup-bus.c:864
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pbus_size_io(struct pci_bus *bus, resource_size_t min_size, resource_size_t add_size, struct list_head *realloc_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:877
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
**Symbols:**

```
ffffffff81636170-ffffffff816364bb: pbus_size_io (STB_LOCAL)
ffffffff816375c3-ffffffff816375e7: pbus_size_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pbus_size_io(struct pci_bus *bus, resource_size_t min_size, resource_size_t add_size, struct list_head *realloc_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:878
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
**Symbols:**

```
ffffffff8165b230-ffffffff8165b57b: pbus_size_io (STB_LOCAL)
ffffffff81bf8a2c-ffffffff81bf8a50: pbus_size_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pbus_size_io(struct pci_bus *bus, resource_size_t min_size, resource_size_t add_size, struct list_head *realloc_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:878
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
**Symbols:**

```
ffffffff8163d770-ffffffff8163daba: pbus_size_io (STB_LOCAL)
ffffffff81bea886-ffffffff81bea8aa: pbus_size_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pbus_size_io(struct pci_bus *bus, resource_size_t min_size, resource_size_t add_size, struct list_head *realloc_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:878
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
**Symbols:**

```
ffffffff816ae280-ffffffff816ae5f5: pbus_size_io (STB_LOCAL)
ffffffff81ce5708-ffffffff81ce572c: pbus_size_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pbus_size_io(struct pci_bus *bus, resource_size_t min_size, resource_size_t add_size, struct list_head *realloc_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:878
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
**Symbols:**

```
ffffffff817d1750-ffffffff817d1acd: pbus_size_io (STB_LOCAL)
ffffffff81eac1da-ffffffff81eac1fc: pbus_size_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pbus_size_io(struct pci_bus *bus, resource_size_t min_size, resource_size_t add_size, struct list_head *realloc_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818f1b80)
Location: drivers/pci/setup-bus.c:878
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
**Symbols:**

```
ffffffff818f1b80-ffffffff818f1f16: pbus_size_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pbus_size_io(struct pci_bus *bus, resource_size_t min_size, resource_size_t add_size, struct list_head *realloc_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81934fb0)
Location: drivers/pci/setup-bus.c:874
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
**Symbols:**

```
ffffffff81934fb0-ffffffff81935327: pbus_size_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pbus_size_io(struct pci_bus *bus, resource_size_t min_size, resource_size_t add_size, struct list_head *realloc_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197dd10)
Location: drivers/pci/setup-bus.c:883
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
**Symbols:**

```
ffffffff8197dd10-ffffffff8197e0c4: pbus_size_io (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f3944)
Location: drivers/pci/setup-bus.c:864
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088e364)
Location: drivers/pci/setup-bus.c:864
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c000000000871dc4)
Location: drivers/pci/setup-bus.c:864
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c6c16)
Location: drivers/pci/setup-bus.c:864
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
</details>
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
In drivers/pci/setup-bus.c (ffffffff81582467)
Location: drivers/pci/setup-bus.c:864
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
In drivers/pci/setup-bus.c (ffffffff81571247)
Location: drivers/pci/setup-bus.c:864
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
In drivers/pci/setup-bus.c (ffffffff81582337)
Location: drivers/pci/setup-bus.c:864
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
In drivers/pci/setup-bus.c (ffffffff8159c7e7)
Location: drivers/pci/setup-bus.c:864
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
