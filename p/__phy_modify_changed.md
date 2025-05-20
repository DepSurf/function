# Function: <code>__phy_modify_changed</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __phy_modify_changed(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796980)
Location: drivers/net/phy/phy-core.c:456
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff81796980-ffffffff817969fd: __phy_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __phy_modify_changed(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba410)
Location: drivers/net/phy/phy-core.c:495
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff817ba410-ffffffff817ba48d: __phy_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81882278)
Location: include/linux/phy.h:873
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818909a8)
Location: include/linux/phy.h:1006
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818732aa)
Location: include/linux/phy.h:1026
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81903a7a)
Location: include/linux/phy.h:1034
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a56495)
Location: include/linux/phy.h:1078
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81be0225)
Location: include/linux/phy.h:1116
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c37b15)
Location: include/linux/phy.h:1273
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cecdd5)
Location: include/linux/phy.h:1314
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
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
int __phy_modify_changed(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d2b18)
Location: drivers/net/phy/phy-core.c:495
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffff8000109d2b18-ffff8000109d2ba0: __phy_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __phy_modify_changed(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0ababec)
Location: drivers/net/phy/phy-core.c:495
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
c0ababec-c0abac60: __phy_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __phy_modify_changed(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a92d20)
Location: drivers/net/phy/phy-core.c:495
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
c000000000a92d20-c000000000a92df0: __phy_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __phy_modify_changed(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f3cc)
Location: drivers/net/phy/phy-core.c:495
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffe00061f3cc-ffffffe00061f452: __phy_modify_changed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __phy_modify_changed(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177eee0)
Location: drivers/net/phy/phy-core.c:495
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff8177eee0-ffffffff8177ef5d: __phy_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __phy_modify_changed(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175ec80)
Location: drivers/net/phy/phy-core.c:495
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff8175ec80-ffffffff8175ecfd: __phy_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __phy_modify_changed(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af290)
Location: drivers/net/phy/phy-core.c:495
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff817af290-ffffffff817af30d: __phy_modify_changed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __phy_modify_changed(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c9220)
Location: drivers/net/phy/phy-core.c:495
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_modify_paged_changed
  - drivers/net/phy/phy-core.c:phy_modify
  - drivers/net/phy/phy-core.c:phy_modify_changed
```
**Symbols:**

```
ffffffff817c9220-ffffffff817c929d: __phy_modify_changed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
