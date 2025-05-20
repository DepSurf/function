# Function: <code>extcon_set_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, u32 state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff816eeae0)
Location: drivers/extcon/extcon.c:344
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:state_store
```
**Symbols:**

```
ffffffff816eeae0-ffffffff816eeb02: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, u32 state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81753cca)
Location: drivers/extcon/extcon.c:332
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:state_store
```
**Symbols:**

```
ffffffff81753be0-ffffffff81753c02: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool cable_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8177fed0)
Location: drivers/extcon/extcon.c:523
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8177fed0-ffffffff8178006e: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool cable_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8179e450)
Location: drivers/extcon/extcon.c:537
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8179e450-ffffffff8179e5f4: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818155b0)
Location: drivers/extcon/extcon.c:529
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff818155b0-ffffffff81815754: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8185f4a0)
Location: drivers/extcon/extcon.c:530
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8185f4a0-ffffffff8185f649: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8187ee40)
Location: drivers/extcon/extcon.c:530
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8187ee40-ffffffff8187efe9: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818c9460)
Location: drivers/extcon/extcon.c:522
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff818c9460-ffffffff818c95f5: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818fb8b0)
Location: drivers/extcon/extcon.c:522
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff818fb8b0-ffffffff818fba45: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d2762)
Location: drivers/extcon/extcon.c:522
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff819d2590-ffffffff819d26bf: extcon_set_state.part.0 (STB_LOCAL)
ffffffff819d26c0-ffffffff819d26de: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d2342)
Location: drivers/extcon/extcon.c:522
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff819d2170-ffffffff819d229f: extcon_set_state.part.0 (STB_LOCAL)
ffffffff819d22a0-ffffffff819d22be: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819b7602)
Location: drivers/extcon/extcon.c:522
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff819b73d0-ffffffff819b7551: extcon_set_state.part.0 (STB_LOCAL)
ffffffff819b7560-ffffffff819b757e: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81a66343)
Location: drivers/extcon/extcon.c:522
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff81a65f80-ffffffff81a6616c: extcon_set_state.part.0 (STB_LOCAL)
ffffffff81d334ee-ffffffff81d335e4: extcon_set_state.part.0.cold (STB_LOCAL)
ffffffff81a66170-ffffffff81a6618e: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81bd76e5)
Location: drivers/extcon/extcon.c:523
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff81bd7540-ffffffff81bd769e: extcon_set_state.part.0 (STB_LOCAL)
ffffffff81eff9d9-ffffffff81effa7a: extcon_set_state.part.0.cold (STB_LOCAL)
ffffffff81bd76a0-ffffffff81bd76d2: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81d84035)
Location: drivers/extcon/extcon.c:533
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff81d83e70-ffffffff81d83fce: extcon_set_state.part.0 (STB_LOCAL)
ffffffff820aa51f-ffffffff820aa5c0: extcon_set_state.part.0.cold (STB_LOCAL)
ffffffff81d83fe0-ffffffff81d84012: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81df23f5)
Location: drivers/extcon/extcon.c:543
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff81df2260-ffffffff81df2382: extcon_set_state.part.0 (STB_LOCAL)
ffffffff8212ba0a-ffffffff8212bab9: extcon_set_state.part.0.cold (STB_LOCAL)
ffffffff81df23a0-ffffffff81df23d2: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81ea8a45)
Location: drivers/extcon/extcon.c:543
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff81ea88b0-ffffffff81ea89d2: extcon_set_state.part.0 (STB_LOCAL)
ffffffff8220d69f-ffffffff8220d74e: extcon_set_state.part.0.cold (STB_LOCAL)
ffffffff81ea89f0-ffffffff81ea8a22: extcon_set_state (STB_GLOBAL)
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
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffff800010b88a28)
Location: drivers/extcon/extcon.c:522
Inline: False
```
**Symbols:**

```
ffff800010b88a28-ffff800010b88c24: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (c0c6cf10)
Location: drivers/extcon/extcon.c:522
Inline: True
```
**Symbols:**

```
c0c6cf10-c0c6d0b4: extcon_set_state.part.0 (STB_LOCAL)
c0c6d0b4-c0c6d0e0: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (c000000000c68010)
Location: drivers/extcon/extcon.c:522
Inline: True
```
**Symbols:**

```
c000000000c68010-c000000000c6827c: extcon_set_state.part.0 (STB_LOCAL)
c000000000c68280-c000000000c682a4: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffe0007315c6)
Location: drivers/extcon/extcon.c:522
Inline: True
```
**Symbols:**

```
ffffffe0007315c6-ffffffe000731790: extcon_set_state.part.0 (STB_LOCAL)
ffffffe000731790-ffffffe0007317d0: extcon_set_state (STB_GLOBAL)
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
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8189cbe0)
Location: drivers/extcon/extcon.c:522
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8189cbe0-ffffffff8189cd75: extcon_set_state (STB_GLOBAL)
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
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818ec2d0)
Location: drivers/extcon/extcon.c:522
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff818ec2d0-ffffffff818ec465: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int extcon_set_state(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8190d350)
Location: drivers/extcon/extcon.c:522
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_set_state_sync
```
**Symbols:**

```
ffffffff8190d350-ffffffff8190d4e5: extcon_set_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int id</code>
</li>
<li>
<b>Param added. </b>
<code>bool cable_state</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool state</code>
</li>
<li>
<b>Param removed. </b>
<code>bool cable_state</code>
</li>
</ul>
</details>
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
