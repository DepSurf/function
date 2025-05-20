# Function: <code>shpchp_sysfs_disable_slot</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153d890)
Location: drivers/pci/hotplug/shpchp_ctrl.c:683
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff8153d890-ffffffff8153d991: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81554c50)
Location: drivers/pci/hotplug/shpchp_ctrl.c:673
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff81554c50-ffffffff81554d4d: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:673
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff81584dd5-ffffffff81584e5b: shpchp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff81584400-ffffffff81584479: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:673
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff815a67b5-ffffffff815a683b: shpchp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff815a5de0-ffffffff815a5e59: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:672
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff8164f4c0-ffffffff8164f546: shpchp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff8164eac0-ffffffff8164eb39: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:671
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff81bfcf11-ffffffff81bfcf97: shpchp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff81672a30-ffffffff81672aa9: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:671
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff81beedec-ffffffff81beee72: shpchp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff81654f30-ffffffff81654fa9: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:671
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff81ce9e3e-ffffffff81ce9ec4: shpchp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff816c6e50-ffffffff816c6ec9: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:671
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff81eb0f0f-ffffffff81eb0f83: shpchp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff817ecdd0-ffffffff817ece55: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81913f00)
Location: drivers/pci/hotplug/shpchp_ctrl.c:671
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff81913f00-ffffffff81913ff2: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81957570)
Location: drivers/pci/hotplug/shpchp_ctrl.c:671
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff81957570-ffffffff8195765f: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff819a0ae0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:671
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff819a0ae0-ffffffff819a0bcf: shpchp_sysfs_disable_slot (STB_GLOBAL)
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
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070f278)
Location: drivers/pci/hotplug/shpchp_ctrl.c:673
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffff80001070f278-ffff80001070f380: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004db5a2)
Location: drivers/pci/hotplug/shpchp_ctrl.c:673
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffe0004db5a2-ffffffe0004db69c: shpchp_sysfs_disable_slot (STB_GLOBAL)
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
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:673
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff81599fc5-ffffffff8159a04b: shpchp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff815995f0-ffffffff81599669: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:673
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff81589155-ffffffff815891db: shpchp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff81588780-ffffffff815887f9: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:673
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff8159a505-ffffffff8159a58b: shpchp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff81599b30-ffffffff81599ba9: shpchp_sysfs_disable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_disable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:673
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
```
**Symbols:**

```
ffffffff815b4945-ffffffff815b49cb: shpchp_sysfs_disable_slot.cold (STB_LOCAL)
ffffffff815b3f70-ffffffff815b3fe9: shpchp_sysfs_disable_slot (STB_GLOBAL)
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
