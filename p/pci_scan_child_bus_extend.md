# Function: <code>pci_scan_child_bus_extend</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e87b0)
Location: drivers/pci/probe.c:2491
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff814e87b0-ffffffff814e8a3f: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81517d90)
Location: drivers/pci/probe.c:2649
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81517d90-ffffffff8151807d: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152d810)
Location: drivers/pci/probe.c:2775
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8152d810-ffffffff8152dafd: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155bf90)
Location: drivers/pci/probe.c:3001
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8155bf90-ffffffff8155c278: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157d060)
Location: drivers/pci/probe.c:2735
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8157d060-ffffffff8157d348: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81622650)
Location: drivers/pci/probe.c:2787
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81622650-ffffffff8162293c: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81649240)
Location: drivers/pci/probe.c:2794
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81649240-ffffffff8164952c: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162be00)
Location: drivers/pci/probe.c:2838
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8162be00-ffffffff8162c0eb: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8169b2d0)
Location: drivers/pci/probe.c:2880
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8169b2d0-ffffffff8169b5b5: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817bcab0)
Location: drivers/pci/probe.c:2866
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff817bcab0-ffffffff817bcd76: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d8a20)
Location: drivers/pci/probe.c:2878
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff818d8a20-ffffffff818d8cd2: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191bd60)
Location: drivers/pci/probe.c:2892
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8191bd60-ffffffff8191c012: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81964190)
Location: drivers/pci/probe.c:2941
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81964190-ffffffff81964442: pci_scan_child_bus_extend (STB_LOCAL)
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
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106e0770)
Location: drivers/pci/probe.c:2735
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffff8000106e0770-ffff8000106e0ac4: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087c4d4)
Location: drivers/pci/probe.c:2735
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
c087c4d4-c087c858: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0000000008596f0)
Location: drivers/pci/probe.c:2735
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
c0000000008596f0-c000000000859b74: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b8524)
Location: drivers/pci/probe.c:2735
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffe0004b8524-ffffffe0004b8836: pci_scan_child_bus_extend (STB_LOCAL)
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
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81571580)
Location: drivers/pci/probe.c:2735
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81571580-ffffffff81571868: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155fce0)
Location: drivers/pci/probe.c:2735
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8155fce0-ffffffff8155ffc8: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81570db0)
Location: drivers/pci/probe.c:2735
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81570db0-ffffffff81571098: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int pci_scan_child_bus_extend(struct pci_bus *bus, unsigned int available_buses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8158b290)
Location: drivers/pci/probe.c:2735
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_scan_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8158b290-ffffffff8158b578: pci_scan_child_bus_extend (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
