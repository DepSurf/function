# Function: <code>get_phy_c45_ids</code>

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
In drivers/net/phy/phy_device.c (ffffffff815ec707)
Location: drivers/net/phy/phy_device.c:252
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
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
In drivers/net/phy/phy_device.c (ffffffff8164b601)
Location: drivers/net/phy/phy_device.c:414
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
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
In drivers/net/phy/phy_device.c (ffffffff8167cb41)
Location: drivers/net/phy/phy_device.c:462
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
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
In drivers/net/phy/phy_device.c (ffffffff81691af0)
Location: drivers/net/phy/phy_device.c:457
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
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
In drivers/net/phy/phy_device.c (ffffffff816fb8e0)
Location: drivers/net/phy/phy_device.c:457
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:505
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:683
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:705
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:710
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81885040)
Location: drivers/net/phy/phy_device.c:709
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
**Symbols:**

```
ffffffff81885040-ffffffff8188517b: get_phy_c45_ids.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_phy_c45_ids(struct mii_bus *bus, int addr, struct phy_c45_device_ids *c45_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff818933b0)
Location: drivers/net/phy/phy_device.c:698
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
**Symbols:**

```
ffffffff818933b0-ffffffff81893581: get_phy_c45_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_phy_c45_ids(struct mii_bus *bus, int addr, struct phy_c45_device_ids *c45_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81875f90)
Location: drivers/net/phy/phy_device.c:715
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
**Symbols:**

```
ffffffff81875f90-ffffffff8187616b: get_phy_c45_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_phy_c45_ids(struct mii_bus *bus, int addr, struct phy_c45_device_ids *c45_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81906b10)
Location: drivers/net/phy/phy_device.c:716
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_get_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
```
**Symbols:**

```
ffffffff81906b10-ffffffff81906ceb: get_phy_c45_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_phy_c45_ids(struct mii_bus *bus, int addr, struct phy_c45_device_ids *c45_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a59a00)
Location: drivers/net/phy/phy_device.c:747
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_get_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
```
**Symbols:**

```
ffffffff81a59a00-ffffffff81a59be7: get_phy_c45_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_phy_c45_ids(struct mii_bus *bus, int addr, struct phy_c45_device_ids *c45_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be3820)
Location: drivers/net/phy/phy_device.c:751
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_get_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
```
**Symbols:**

```
ffffffff81be3820-ffffffff81be3a07: get_phy_c45_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_phy_c45_ids(struct mii_bus *bus, int addr, struct phy_c45_device_ids *c45_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3a3a0)
Location: drivers/net/phy/phy_device.c:782
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_get_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
```
**Symbols:**

```
ffffffff81c3a3a0-ffffffff81c3a5ed: get_phy_c45_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_phy_c45_ids(struct mii_bus *bus, int addr, struct phy_c45_device_ids *c45_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cef590)
Location: drivers/net/phy/phy_device.c:785
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_get_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_device
  - drivers/net/phy/phy_device.c:get_phy_device
```
**Symbols:**

```
ffffffff81cef590-ffffffff81cef7dd: get_phy_c45_ids (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:710
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:710
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:710
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe000621dee)
Location: drivers/net/phy/phy_device.c:710
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:710
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:710
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:710
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:710
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_device
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
