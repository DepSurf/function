# Function: <code>phy_modify</code>

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
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81736ad0)
Location: drivers/net/phy/phy-core.c:362
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff81736ad0-ffffffff81736b2e: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81759c70)
Location: drivers/net/phy/phy-core.c:533
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff81759c70-ffffffff81759cce: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796b40)
Location: drivers/net/phy/phy-core.c:532
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff81796b40-ffffffff81796ba3: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba5d0)
Location: drivers/net/phy/phy-core.c:571
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff817ba5d0-ffffffff817ba633: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81881a80)
Location: drivers/net/phy/phy-core.c:583
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81881a80-ffffffff81881af6: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818901b0)
Location: drivers/net/phy/phy-core.c:630
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff818901b0-ffffffff81890226: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81872ab0)
Location: drivers/net/phy/phy-core.c:630
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81872ab0-ffffffff81872b23: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff819031c0)
Location: drivers/net/phy/phy-core.c:631
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff819031c0-ffffffff81903233: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a55cc0)
Location: drivers/net/phy/phy-core.c:626
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81a55cc0-ffffffff81a55d42: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81bdf7e0)
Location: drivers/net/phy/phy-core.c:709
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff81bdf7e0-ffffffff81bdf862: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c370d0)
Location: drivers/net/phy/phy-core.c:712
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff81c370d0-ffffffff81c37152: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cebe80)
Location: drivers/net/phy/phy-core.c:850
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff81cebe80-ffffffff81cebf02: phy_modify (STB_GLOBAL)
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
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d2d28)
Location: drivers/net/phy/phy-core.c:571
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffff8000109d2d28-ffff8000109d2d98: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abad8c)
Location: drivers/net/phy/phy-core.c:571
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
c0abad8c-c0abade8: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a93010)
Location: drivers/net/phy/phy-core.c:571
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
c000000000a93010-c000000000a9309c: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f5b8)
Location: drivers/net/phy/phy-core.c:571
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffe00061f5b8-ffffffe00061f628: phy_modify (STB_GLOBAL)
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
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177f0a0)
Location: drivers/net/phy/phy-core.c:571
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff8177f0a0-ffffffff8177f103: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175ee40)
Location: drivers/net/phy/phy-core.c:571
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff8175ee40-ffffffff8175eea3: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af450)
Location: drivers/net/phy/phy-core.c:571
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff817af450-ffffffff817af4b3: phy_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int phy_modify(struct phy_device *phydev, u32 regnum, u16 mask, u16 set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c93e0)
Location: drivers/net/phy/phy-core.c:571
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_resume
  - drivers/net/phy/phy_device.c:genphy_suspend
  - drivers/net/phy/phy_device.c:genphy_setup_forced
```
**Symbols:**

```
ffffffff817c93e0-ffffffff817c9443: phy_modify (STB_GLOBAL)
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
