# Function: <code>_opp_set_availability</code>

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
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d4db0)
Location: drivers/opp/core.c:1697
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff817d4db0-ffffffff817d4eba: _opp_set_availability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181db60)
Location: drivers/opp/core.c:1588
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff8181db60-ffffffff8181dc6a: _opp_set_availability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81849850)
Location: drivers/opp/core.c:1882
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff81849850-ffffffff8184995a: _opp_set_availability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1999
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff8188c660-ffffffff8188c73c: _opp_set_availability (STB_LOCAL)
ffffffff8188d7f4-ffffffff8188d813: _opp_set_availability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2048
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff818be7d0-ffffffff818be8ac: _opp_set_availability (STB_LOCAL)
ffffffff818bf9f6-ffffffff818bfa15: _opp_set_availability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2162
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff8198f280-ffffffff8198f48b: _opp_set_availability (STB_LOCAL)
ffffffff819915af-ffffffff819915ea: _opp_set_availability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2259
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff81993280-ffffffff8199348b: _opp_set_availability (STB_LOCAL)
ffffffff81c29393-ffffffff81c293ce: _opp_set_availability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2633
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff81977b60-ffffffff81977d67: _opp_set_availability (STB_LOCAL)
ffffffff81c1b4d8-ffffffff81c1b513: _opp_set_availability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2643
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff81a20a60-ffffffff81a20c77: _opp_set_availability (STB_LOCAL)
ffffffff81d2b637-ffffffff81d2b68e: _opp_set_availability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2783
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff81b896c0-ffffffff81b898c6: _opp_set_availability (STB_LOCAL)
ffffffff81ef780b-ffffffff81ef7861: _opp_set_availability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2780
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff81d28f20-ffffffff81d2917b: _opp_set_availability (STB_LOCAL)
ffffffff820a8afd-ffffffff820a8b18: _opp_set_availability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2794
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff81d920c0-ffffffff81d9231b: _opp_set_availability (STB_LOCAL)
ffffffff82129cd3-ffffffff82129cee: _opp_set_availability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2878
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff81e499f0-ffffffff81e49c4b: _opp_set_availability (STB_LOCAL)
ffffffff8220ba1c-ffffffff8220ba37: _opp_set_availability.cold (STB_LOCAL)
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
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b19878)
Location: drivers/opp/core.c:2048
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffff800010b19878-ffff800010b199a4: _opp_set_availability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf45b8)
Location: drivers/opp/core.c:2048
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
c0bf45b8-c0bf46b8: _opp_set_availability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0b2c0)
Location: drivers/opp/core.c:2048
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
c000000000c0b2c0-c000000000c0b448: _opp_set_availability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000702198)
Location: drivers/opp/core.c:2048
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffe000702198-ffffffe00070229c: _opp_set_availability (STB_LOCAL)
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
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2048
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff81862ef0-ffffffff81862fcc: _opp_set_availability (STB_LOCAL)
ffffffff81864116-ffffffff81864135: _opp_set_availability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2048
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff8182bba0-ffffffff8182bc7c: _opp_set_availability (STB_LOCAL)
ffffffff8182cdc6-ffffffff8182cde5: _opp_set_availability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2048
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff818b3c80-ffffffff818b3d5c: _opp_set_availability (STB_LOCAL)
ffffffff818b4ea6-ffffffff818b4ec5: _opp_set_availability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int _opp_set_availability(struct device *dev, long unsigned int freq, bool availability_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2048
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_disable
  - drivers/opp/core.c:dev_pm_opp_enable
```
**Symbols:**

```
ffffffff818cff30-ffffffff818d000c: _opp_set_availability (STB_LOCAL)
ffffffff818d1156-ffffffff818d1175: _opp_set_availability.cold (STB_LOCAL)
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
