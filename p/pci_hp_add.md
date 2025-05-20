# Function: <code>pci_hp_add</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8154e167)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: True
Direct callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8154e167-ffffffff8154e191: pci_hp_add.cold.15 (STB_LOCAL)
ffffffff8154dd70-ffffffff8154e03b: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8157dfcb)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: True
Direct callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8157dfcb-ffffffff8157dff5: pci_hp_add.cold (STB_LOCAL)
ffffffff8157db90-ffffffff8157de5b: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8159fa07)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: True
Direct callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8159fa07-ffffffff8159fa31: pci_hp_add.cold (STB_LOCAL)
ffffffff8159f5f0-ffffffff8159f8bb: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81648398-ffffffff816483bf: pci_hp_add.cold (STB_LOCAL)
ffffffff816481c0-ffffffff8164824a: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81bfb3e8-ffffffff81bfb40f: pci_hp_add.cold (STB_LOCAL)
ffffffff8166d340-ffffffff8166d3ca: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81bed23a-ffffffff81bed261: pci_hp_add.cold (STB_LOCAL)
ffffffff8164f680-ffffffff8164f70a: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81ce7f3b-ffffffff81ce7f77: pci_hp_add.cold (STB_LOCAL)
ffffffff816c13c0-ffffffff816c1459: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81eaefb9-ffffffff81eaeff5: pci_hp_add.cold (STB_LOCAL)
ffffffff817e6ba0-ffffffff817e6c51: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8208f7da-ffffffff8208f7ef: pci_hp_add.cold (STB_LOCAL)
ffffffff8190bb00-ffffffff8190bbcf: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8210fb3b-ffffffff8210fb50: pci_hp_add.cold (STB_LOCAL)
ffffffff8194f180-ffffffff8194f24f: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff821ed863-ffffffff821ed878: pci_hp_add.cold (STB_LOCAL)
ffffffff819985b0-ffffffff8199867f: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffff800010707b50)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: True
Direct callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffff800010707b50-ffff800010707e1c: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (c0000000008802a0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: True
Direct callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
```
**Symbols:**

```
c0000000008802a0-c000000000880680: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffe0004d5510)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: True
Direct callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffe0004d5510-ffffffe0004d5758: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81593217)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: True
Direct callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81593217-ffffffff81593241: pci_hp_add.cold (STB_LOCAL)
ffffffff81592e00-ffffffff815930cb: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815823a7)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: True
Direct callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff815823a7-ffffffff815823d1: pci_hp_add.cold (STB_LOCAL)
ffffffff81581f90-ffffffff8158225b: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81593757)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: True
Direct callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81593757-ffffffff81593781: pci_hp_add.cold (STB_LOCAL)
ffffffff81593340-ffffffff8159360b: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_hp_add(struct hotplug_slot *slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff815adbd7)
Location: drivers/pci/hotplug/pci_hotplug_core.c:477
Inline: True
Direct callers:
  - drivers/pci/hotplug/pci_hotplug_core.c:__pci_hp_register
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff815adbd7-ffffffff815adc01: pci_hp_add.cold (STB_LOCAL)
ffffffff815ad7c0-ffffffff815ada8b: pci_hp_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
