# Function: <code>pci_register_host_bridge</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149ec50)
Location: drivers/pci/probe.c:722
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus_msi
```
**Symbols:**

```
ffffffff8149ec50-ffffffff8149f087: pci_register_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a8aa0)
Location: drivers/pci/probe.c:749
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff814a8aa0-ffffffff814a8ed6: pci_register_host_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e7ad0)
Location: drivers/pci/probe.c:749
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff814e7ad0-ffffffff814e7f06: pci_register_host_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:773
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff81517180-ffffffff8151759e: pci_register_host_bridge (STB_LOCAL)
ffffffff815185a4-ffffffff815185b8: pci_register_host_bridge.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:773
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8152cc00-ffffffff8152d01e: pci_register_host_bridge (STB_LOCAL)
ffffffff8152e026-ffffffff8152e03a: pci_register_host_bridge.cold.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:830
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8155b510-ffffffff8155b7b1: pci_register_host_bridge (STB_LOCAL)
ffffffff8155d4be-ffffffff8155d65d: pci_register_host_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:826
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8157c5c0-ffffffff8157c861: pci_register_host_bridge (STB_LOCAL)
ffffffff8157e532-ffffffff8157e6d1: pci_register_host_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:870
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff81621af0-ffffffff81621d98: pci_register_host_bridge (STB_LOCAL)
ffffffff81623a1b-ffffffff81623be8: pci_register_host_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:877
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff816486b0-ffffffff81648984: pci_register_host_bridge (STB_LOCAL)
ffffffff81bf7725-ffffffff81bf7900: pci_register_host_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:895
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8162b2c0-ffffffff8162b5a7: pci_register_host_bridge (STB_LOCAL)
ffffffff81be954b-ffffffff81be97a6: pci_register_host_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:901
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8169a790-ffffffff8169aa74: pci_register_host_bridge (STB_LOCAL)
ffffffff81ce3ef1-ffffffff81ce414c: pci_register_host_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:883
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff817bbf10-ffffffff817bc20c: pci_register_host_bridge (STB_LOCAL)
ffffffff81eaa947-ffffffff81eaab61: pci_register_host_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d7b20)
Location: drivers/pci/probe.c:881
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff818d7b20-ffffffff818d8065: pci_register_host_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191adb0)
Location: drivers/pci/probe.c:881
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8191adb0-ffffffff8191b33f: pci_register_host_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff819631e0)
Location: drivers/pci/probe.c:892
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff819631e0-ffffffff8196376f: pci_register_host_bridge (STB_LOCAL)
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
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106dfc48)
Location: drivers/pci/probe.c:826
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffff8000106dfc48-ffff8000106dffb0: pci_register_host_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087b8dc)
Location: drivers/pci/probe.c:826
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
c087b8dc-c087bc74: pci_register_host_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000858800)
Location: drivers/pci/probe.c:826
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
c000000000858800-c000000000858cc4: pci_register_host_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b7ba4)
Location: drivers/pci/probe.c:826
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffe0004b7ba4-ffffffe0004b7ee4: pci_register_host_bridge (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:826
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff81570ae0-ffffffff81570d81: pci_register_host_bridge (STB_LOCAL)
ffffffff81572a52-ffffffff81572bf1: pci_register_host_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:826
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8155f240-ffffffff8155f4e1: pci_register_host_bridge (STB_LOCAL)
ffffffff815611b2-ffffffff81561351: pci_register_host_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:826
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff81570310-ffffffff815705b1: pci_register_host_bridge (STB_LOCAL)
ffffffff81572282-ffffffff81572421: pci_register_host_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_register_host_bridge(struct pci_host_bridge *bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:826
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_create_root_bus
```
**Symbols:**

```
ffffffff8158a7f0-ffffffff8158aa91: pci_register_host_bridge (STB_LOCAL)
ffffffff8158c762-ffffffff8158c901: pci_register_host_bridge.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
