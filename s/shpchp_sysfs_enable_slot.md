# Function: <code>shpchp_sysfs_enable_slot</code>

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
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153d780)
Location: drivers/pci/hotplug/shpchp_ctrl.c:648
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff8153d780-ffffffff8153d881: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81554b50)
Location: drivers/pci/hotplug/shpchp_ctrl.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff81554b50-ffffffff81554c48: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff81584d49-ffffffff81584dd5: shpchp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff81584380-ffffffff815843f2: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff815a6729-ffffffff815a67b5: shpchp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff815a5d60-ffffffff815a5dd2: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:636
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff8164f434-ffffffff8164f4c0: shpchp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff8164ea40-ffffffff8164eab2: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:635
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff81bfce85-ffffffff81bfcf11: shpchp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff816729b0-ffffffff81672a22: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:635
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff81beed60-ffffffff81beedec: shpchp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff81654eb0-ffffffff81654f22: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:635
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff81ce9db2-ffffffff81ce9e3e: shpchp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff816c6dd0-ffffffff816c6e42: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:635
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff81eb0e99-ffffffff81eb0f0f: shpchp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff817ecd50-ffffffff817ecdcc: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81913e00)
Location: drivers/pci/hotplug/shpchp_ctrl.c:635
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff81913e00-ffffffff81913eeb: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81957470)
Location: drivers/pci/hotplug/shpchp_ctrl.c:635
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff81957470-ffffffff8195755b: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff819a09e0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:635
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff819a09e0-ffffffff819a0acb: shpchp_sysfs_enable_slot (STB_GLOBAL)
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
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070f168)
Location: drivers/pci/hotplug/shpchp_ctrl.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffff80001070f168-ffff80001070f278: shpchp_sysfs_enable_slot (STB_GLOBAL)
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
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004db4a8)
Location: drivers/pci/hotplug/shpchp_ctrl.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffe0004db4a8-ffffffe0004db5a2: shpchp_sysfs_enable_slot (STB_GLOBAL)
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
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff81599f39-ffffffff81599fc5: shpchp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff81599570-ffffffff815995e2: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff815890c9-ffffffff81589155: shpchp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff81588700-ffffffff81588772: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff8159a479-ffffffff8159a505: shpchp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff81599ab0-ffffffff81599b22: shpchp_sysfs_enable_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int shpchp_sysfs_enable_slot(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
```
**Symbols:**

```
ffffffff815b48b9-ffffffff815b4945: shpchp_sysfs_enable_slot.cold (STB_LOCAL)
ffffffff815b3ef0-ffffffff815b3f62: shpchp_sysfs_enable_slot (STB_GLOBAL)
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
