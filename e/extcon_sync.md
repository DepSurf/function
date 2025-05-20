# Function: <code>extcon_sync</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8177f430)
Location: drivers/extcon/extcon.c:423
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8177f430-ffffffff8177f662: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8179df00)
Location: drivers/extcon/extcon.c:426
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8179df00-ffffffff8179e13f: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81815060)
Location: drivers/extcon/extcon.c:416
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff81815060-ffffffff8181529f: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8185ef70)
Location: drivers/extcon/extcon.c:416
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8185ef70-ffffffff8185f1cc: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8187e910)
Location: drivers/extcon/extcon.c:416
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8187e910-ffffffff8187eb6c: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818c8f80)
Location: drivers/extcon/extcon.c:408
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff818c8f80-ffffffff818c91a2: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818fb3d0)
Location: drivers/extcon/extcon.c:408
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff818fb3d0-ffffffff818fb5f2: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d2c6c)
Location: drivers/extcon/extcon.c:408
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff819d1f20-ffffffff819d2136: extcon_sync.part.0 (STB_LOCAL)
ffffffff819d2140-ffffffff819d215b: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d284c)
Location: drivers/extcon/extcon.c:408
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff819d1b00-ffffffff819d1d16: extcon_sync.part.0 (STB_LOCAL)
ffffffff819d1d20-ffffffff819d1d3b: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819b7cdc)
Location: drivers/extcon/extcon.c:408
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff819b6de0-ffffffff819b6ff6: extcon_sync.part.0 (STB_LOCAL)
ffffffff819b7000-ffffffff819b701b: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81a66bdc)
Location: drivers/extcon/extcon.c:408
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff81a65940-ffffffff81a65bab: extcon_sync.part.0 (STB_LOCAL)
ffffffff81d334b2-ffffffff81d334cb: extcon_sync.part.0.cold (STB_LOCAL)
ffffffff81a65bb0-ffffffff81a65bcb: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:409
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff81eff98f-ffffffff81eff9b6: extcon_sync.cold (STB_LOCAL)
ffffffff81bd6bf0-ffffffff81bd6eee: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:419
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff820aa4f8-ffffffff820aa51f: extcon_sync.cold (STB_LOCAL)
ffffffff81d834a0-ffffffff81d83797: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:429
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8212b9e3-ffffffff8212ba0a: extcon_sync.cold (STB_LOCAL)
ffffffff81df18f0-ffffffff81df1bf4: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:429
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8220d678-ffffffff8220d69f: extcon_sync.cold (STB_LOCAL)
ffffffff81ea7f40-ffffffff81ea8244: extcon_sync (STB_GLOBAL)
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
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffff800010b89340)
Location: drivers/extcon/extcon.c:408
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
```
**Symbols:**

```
ffff800010b89340-ffff800010b89634: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (c0c6d90c)
Location: drivers/extcon/extcon.c:408
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
```
**Symbols:**

```
c0c6cccc-c0c6cee4: extcon_sync.part.0 (STB_LOCAL)
c0c6cee4-c0c6cf10: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (c000000000c67fc8)
Location: drivers/extcon/extcon.c:408
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
```
**Symbols:**

```
c000000000c67c60-c000000000c67f60: extcon_sync.part.0 (STB_LOCAL)
c000000000c67f60-c000000000c67f84: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffe00073153e)
Location: drivers/extcon/extcon.c:408
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
```
**Symbols:**

```
ffffffe0007312fe-ffffffe0007314d0: extcon_sync.part.0 (STB_LOCAL)
ffffffe0007314d0-ffffffe000731508: extcon_sync (STB_GLOBAL)
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
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8189c700)
Location: drivers/extcon/extcon.c:408
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8189c700-ffffffff8189c922: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818ebdf0)
Location: drivers/extcon/extcon.c:408
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff818ebdf0-ffffffff818ec012: extcon_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int extcon_sync(struct extcon_dev *edev, unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8190ce70)
Location: drivers/extcon/extcon.c:408
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_property_sync
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8190ce70-ffffffff8190d092: extcon_sync (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
