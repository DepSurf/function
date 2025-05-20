# Function: <code>pci_bus_insert_busn_res</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81431d40)
Location: drivers/pci/probe.c:2198
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff81431d40-ffffffff81431eb0: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147d570)
Location: drivers/pci/probe.c:2238
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8147d570-ffffffff8147d6dd: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149eae0)
Location: drivers/pci/probe.c:2318
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus_msi
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8149eae0-ffffffff8149ec4d: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a8930)
Location: drivers/pci/probe.c:2434
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff814a8930-ffffffff814a8a9c: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e7960)
Location: drivers/pci/probe.c:2661
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff814e7960-ffffffff814e7acc: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81517010)
Location: drivers/pci/probe.c:2878
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81517010-ffffffff8151717d: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152ca90)
Location: drivers/pci/probe.c:3004
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8152ca90-ffffffff8152cbf2: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3230
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8155d47b-ffffffff8155d4be: pci_bus_insert_busn_res.cold (STB_LOCAL)
ffffffff8155b3f0-ffffffff8155b50e: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2964
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8157e4ef-ffffffff8157e532: pci_bus_insert_busn_res.cold (STB_LOCAL)
ffffffff8157c4a0-ffffffff8157c5be: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3016
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff816239d8-ffffffff81623a1b: pci_bus_insert_busn_res.cold (STB_LOCAL)
ffffffff816219d0-ffffffff81621aee: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3023
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81bf76e2-ffffffff81bf7725: pci_bus_insert_busn_res.cold (STB_LOCAL)
ffffffff81648590-ffffffff816486ae: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3067
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81be9508-ffffffff81be954b: pci_bus_insert_busn_res.cold (STB_LOCAL)
ffffffff8162b1a0-ffffffff8162b2bc: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3109
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81ce3eae-ffffffff81ce3ef1: pci_bus_insert_busn_res.cold (STB_LOCAL)
ffffffff8169a670-ffffffff8169a78c: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:3080
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81eaa904-ffffffff81eaa947: pci_bus_insert_busn_res.cold (STB_LOCAL)
ffffffff817bbde0-ffffffff817bbf0e: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d79a0)
Location: drivers/pci/probe.c:3090
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff818d79a0-ffffffff818d7b04: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191ac30)
Location: drivers/pci/probe.c:3104
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8191ac30-ffffffff8191ad94: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81963030)
Location: drivers/pci/probe.c:3153
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81963030-ffffffff819631c6: pci_bus_insert_busn_res (STB_GLOBAL)
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
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106dfaf0)
Location: drivers/pci/probe.c:2964
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffff8000106dfaf0-ffff8000106dfc44: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087b790)
Location: drivers/pci/probe.c:2964
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
c087b790-c087b8dc: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000858650)
Location: drivers/pci/probe.c:2964
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
c000000000858650-c0000000008587f4: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b7a66)
Location: drivers/pci/probe.c:2964
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffe0004b7a66-ffffffe0004b7ba4: pci_bus_insert_busn_res (STB_GLOBAL)
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
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2964
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81572a0f-ffffffff81572a52: pci_bus_insert_busn_res.cold (STB_LOCAL)
ffffffff815709c0-ffffffff81570ade: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2964
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8156116f-ffffffff815611b2: pci_bus_insert_busn_res.cold (STB_LOCAL)
ffffffff8155f120-ffffffff8155f23e: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2964
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8157223f-ffffffff81572282: pci_bus_insert_busn_res.cold (STB_LOCAL)
ffffffff815701f0-ffffffff8157030e: pci_bus_insert_busn_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_bus_insert_busn_res(struct pci_bus *b, int bus, int bus_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2964
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
  - drivers/pci/probe.c:pci_scan_root_bus_bridge
  - drivers/pci/probe.c:pci_bus_update_busn_res_end
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8158c71f-ffffffff8158c762: pci_bus_insert_busn_res.cold (STB_LOCAL)
ffffffff8158a6d0-ffffffff8158a7ee: pci_bus_insert_busn_res (STB_GLOBAL)
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
