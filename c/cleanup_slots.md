# Function: <code>cleanup_slots</code>

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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8144d022)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:624
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81499756)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:624
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814bb346)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:624
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814c5c36)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:625
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815061e6)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:625
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81537028)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:611
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8153bdd0)
Location: drivers/pci/hotplug/shpchp_core.c:165
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff8153bdd0-ffffffff8153be5e: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8154e6fa)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81553270)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff81553270-ffffffff81553302: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8157e55a)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81583110)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff81583110-ffffffff815831a7: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8159ff9a)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815a4af0)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff815a4af0-ffffffff815a4b87: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81648ffa)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8164d970)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff8164d970-ffffffff8164da07: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8166e0ba)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81671b30)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff81671b30-ffffffff81671bc7: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8165060a)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81654040)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff81654040-ffffffff816540d7: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff816c234a)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff816c5e70)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff816c5e70-ffffffff816c5f07: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff817e7c7a)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff817ebd50)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff817ebd50-ffffffff817ebdeb: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190d34a)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81912430)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff81912430-ffffffff819124cb: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff819509ca)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81955ac0)
Location: drivers/pci/hotplug/shpchp_core.c:129
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff81955ac0-ffffffff81955b5b: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81999e2a)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8199efb0)
Location: drivers/pci/hotplug/shpchp_core.c:129
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff8199efb0-ffffffff8199f04b: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010708580)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffff80001070d850)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffff80001070d850-ffff80001070d8f0: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (c000000000880ffc)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d5f58)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffe0004d9f4c)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffe0004d9f4c-ffffffe0004d9fde: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815937aa)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81598300)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff81598300-ffffffff81598397: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8158293a)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81587490)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff81587490-ffffffff81587527: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81593cea)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81598840)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff81598840-ffffffff815988d7: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void cleanup_slots();
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815ae16a)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815b2c80)
Location: drivers/pci/hotplug/shpchp_core.c:130
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
```
**Symbols:**

```
ffffffff815b2c80-ffffffff815b2d17: cleanup_slots (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
