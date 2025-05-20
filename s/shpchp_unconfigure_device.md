# Function: <code>shpchp_unconfigure_device</code>

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
int shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff8153daf0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff8153daf0-ffffffff8153dbb6: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (ffffffff81554ea0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff81554ea0-ffffffff81554f66: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff8158504e-ffffffff81585088: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff81584f40-ffffffff81584fd2: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff815a6a2e-ffffffff815a6a68: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff815a6920-ffffffff815a69b2: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:remove_board
```
**Symbols:**

```
ffffffff8164f73c-ffffffff8164f776: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff8164f630-ffffffff8164f6c0: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:remove_board
```
**Symbols:**

```
ffffffff81bfd013-ffffffff81bfd04d: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff81672b90-ffffffff81672c20: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff81beeeeb-ffffffff81beef25: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff81655090-ffffffff81655120: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff81ce9f3d-ffffffff81ce9f92: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff816c6fb0-ffffffff816c704d: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff81eb0ffa-ffffffff81eb104f: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff817ecf50-ffffffff817ecfff: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff8208fbc9-ffffffff8208fbdd: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff81914180-ffffffff8191426c: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff8210ff25-ffffffff8210ff39: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff819577e0-ffffffff819578cc: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff821edc4d-ffffffff821edc61: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff819a0d50-ffffffff819a0e3c: shpchp_unconfigure_device (STB_GLOBAL)
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
int shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (ffff80001070f4d0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffff80001070f4d0-ffff80001070f59c: shpchp_unconfigure_device (STB_GLOBAL)
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
int shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (ffffffe0004db7dc)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffe0004db7dc-ffffffe0004db8ac: shpchp_unconfigure_device (STB_GLOBAL)
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
int shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff8159a23e-ffffffff8159a278: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff8159a130-ffffffff8159a1c2: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff815893ce-ffffffff81589408: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff815892c0-ffffffff81589352: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff8159a77e-ffffffff8159a7b8: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff8159a670-ffffffff8159a702: shpchp_unconfigure_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int shpchp_unconfigure_device(struct slot *p_slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_pci.c (0)
Location: drivers/pci/hotplug/shpchp_pci.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff815b4bbe-ffffffff815b4bf8: shpchp_unconfigure_device.cold (STB_LOCAL)
ffffffff815b4ab0-ffffffff815b4b42: shpchp_unconfigure_device (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
