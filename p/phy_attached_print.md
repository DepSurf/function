# Function: <code>phy_attached_print</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8164a070)
Location: drivers/net/phy/phy_device.c:821
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff8164a070-ffffffff8164a154: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167b490)
Location: drivers/net/phy/phy_device.c:870
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff8167b490-ffffffff8167b574: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81690350)
Location: drivers/net/phy/phy_device.c:865
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff81690350-ffffffff8169042f: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fa020)
Location: drivers/net/phy/phy_device.c:878
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff816fa020-ffffffff816fa14a: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81737730)
Location: drivers/net/phy/phy_device.c:904
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff81737730-ffffffff81737849: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175a900)
Location: drivers/net/phy/phy_device.c:1080
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff8175a900-ffffffff8175aa19: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81799a5e)
Location: drivers/net/phy/phy_device.c:1101
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff81799a5e-ffffffff81799b78: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bd56a)
Location: drivers/net/phy/phy_device.c:1109
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff817bd56a-ffffffff817bd684: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1131
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff81885ea1-ffffffff81885f44: phy_attached_print.cold (STB_LOCAL)
ffffffff818853d0-ffffffff81885484: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1162
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff81c19344-ffffffff81c193e7: phy_attached_print.cold (STB_LOCAL)
ffffffff81893c80-ffffffff81893d34: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1179
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff81c0b24d-ffffffff81c0b2f0: phy_attached_print.cold (STB_LOCAL)
ffffffff818767b0-ffffffff81876864: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1226
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff81d10652-ffffffff81d106f5: phy_attached_print.cold (STB_LOCAL)
ffffffff819073c0-ffffffff81907474: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1257
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff81edb3c2-ffffffff81edb485: phy_attached_print.cold (STB_LOCAL)
ffffffff81a59eb0-ffffffff81a59f6e: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be41a0)
Location: drivers/net/phy/phy_device.c:1262
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff81be41a0-ffffffff81be431c: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3be10)
Location: drivers/net/phy/phy_device.c:1293
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff81c3be10-ffffffff81c3bf9f: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cf1210)
Location: drivers/net/phy/phy_device.c:1297
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff81cf1210-ffffffff81cf139f: phy_attached_print (STB_GLOBAL)
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
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d6934)
Location: drivers/net/phy/phy_device.c:1109
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffff8000109d6934-ffff8000109d6a6c: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abe290)
Location: drivers/net/phy/phy_device.c:1109
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
c0abe290-c0abe39c: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a98084)
Location: drivers/net/phy/phy_device.c:1109
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
c000000000a98084-c000000000a981cc: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe0006229c6)
Location: drivers/net/phy/phy_device.c:1109
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffe0006229c6-ffffffe000622a94: phy_attached_print (STB_GLOBAL)
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
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8178203a)
Location: drivers/net/phy/phy_device.c:1109
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff8178203a-ffffffff81782154: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81761dca)
Location: drivers/net/phy/phy_device.c:1109
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff81761dca-ffffffff81761ee4: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817b23ea)
Location: drivers/net/phy/phy_device.c:1109
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff817b23ea-ffffffff817b2504: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void phy_attached_print(struct phy_device *phydev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817cc37a)
Location: drivers/net/phy/phy_device.c:1109
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_attached_info
```
**Symbols:**

```
ffffffff817cc37a-ffffffff817cc494: phy_attached_print (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
