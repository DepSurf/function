# Function: <code>shpchp_configure_device</code>

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
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8153d9a0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff8153d9a0-ffffffff8153daee: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81554d50)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81554d50-ffffffff81554e9e: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81584fd2-ffffffff8158504e: shpchp_configure_device.cold (STB_LOCAL)
ffffffff81584e60-ffffffff81584f3b: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff815a69b2-ffffffff815a6a2e: shpchp_configure_device.cold (STB_LOCAL)
ffffffff815a6840-ffffffff815a691b: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff8164f6c0-ffffffff8164f73c: shpchp_configure_device.cold (STB_LOCAL)
ffffffff8164f550-ffffffff8164f62b: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81bfcf97-ffffffff81bfd013: shpchp_configure_device.cold (STB_LOCAL)
ffffffff81672ab0-ffffffff81672b8b: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81beee72-ffffffff81beeeeb: shpchp_configure_device.cold (STB_LOCAL)
ffffffff81654fb0-ffffffff8165508b: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81ce9ec4-ffffffff81ce9f3d: shpchp_configure_device.cold (STB_LOCAL)
ffffffff816c6ed0-ffffffff816c6fa9: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81eb0f83-ffffffff81eb0ffa: shpchp_configure_device.cold (STB_LOCAL)
ffffffff817ece60-ffffffff817ecf49: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81914010)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81914010-ffffffff8191416b: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81957670)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81957670-ffffffff819577cb: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff819a0be0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff819a0be0-ffffffff819a0d3b: shpchp_configure_device (STB_GLOBAL)
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
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (ffff80001070f380)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffff80001070f380-ffff80001070f4cc: shpchp_configure_device (STB_GLOBAL)
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
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (ffffffe0004db69c)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffe0004db69c-ffffffe0004db7dc: shpchp_configure_device (STB_GLOBAL)
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
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff8159a1c2-ffffffff8159a23e: shpchp_configure_device.cold (STB_LOCAL)
ffffffff8159a050-ffffffff8159a12b: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff81589352-ffffffff815893ce: shpchp_configure_device.cold (STB_LOCAL)
ffffffff815891e0-ffffffff815892bb: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff8159a702-ffffffff8159a77e: shpchp_configure_device.cold (STB_LOCAL)
ffffffff8159a590-ffffffff8159a66b: shpchp_configure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int shpchp_configure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:23
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
```
**Symbols:**

```
ffffffff815b4b42-ffffffff815b4bbe: shpchp_configure_device.cold (STB_LOCAL)
ffffffff815b49d0-ffffffff815b4aab: shpchp_configure_device (STB_GLOBAL)
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
