# Function: <code>ab3100_set_register_interruptible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff81592450)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:set_register_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
**Symbols:**

```
ffffffff81592450-ffffffff815924fe: ab3100_set_register_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff815e7260)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
ffffffff815e7260-ffffffff815e730e: ab3100_set_register_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff81614070)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
ffffffff81614070-ffffffff8161411e: ab3100_set_register_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff81628040)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
ffffffff81628040-ffffffff816280f8: ab3100_set_register_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff81690950)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
ffffffff81690950-ffffffff81690a08: ab3100_set_register_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff816cca40)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
ffffffff816cca40-ffffffff816ccb07: ab3100_set_register_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff816ee000)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
ffffffff816ee000-ffffffff816ee0c7: ab3100_set_register_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (0)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
ffffffff81727660-ffffffff817276e6: ab3100_set_register_interruptible (STB_LOCAL)
ffffffff81727ddd-ffffffff81727e1a: ab3100_set_register_interruptible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (0)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
ffffffff8174b910-ffffffff8174b996: ab3100_set_register_interruptible (STB_LOCAL)
ffffffff8174c090-ffffffff8174c0cd: ab3100_set_register_interruptible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff81809ffc)
Location: drivers/mfd/ab3100-core.c:72
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:set_register_interruptible
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_setup
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
```
**Symbols:**

```
ffffffff818099d0-ffffffff81809a56: ab3100_set_register_interruptible (STB_LOCAL)
ffffffff8180a199-ffffffff8180a1d6: ab3100_set_register_interruptible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff81819e6c)
Location: drivers/mfd/ab3100-core.c:72
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:set_register_interruptible
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_setup
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
```
**Symbols:**

```
ffffffff81819810-ffffffff81819896: ab3100_set_register_interruptible (STB_LOCAL)
ffffffff81c14879-ffffffff81c148b6: ab3100_set_register_interruptible.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffff800010949c48)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
ffff800010949c48-ffff800010949d20: ab3100_set_register_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (c0a32ab4)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
c0a32ab4-c0a32b88: ab3100_set_register_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (c0000000009f5280)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
c0000000009f5280-c0000000009f537c: ab3100_set_register_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffe0005bb886)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
ffffffe0005bb886-ffffffe0005bb938: ab3100_set_register_interruptible (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (0)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
ffffffff8173edd0-ffffffff8173ee56: ab3100_set_register_interruptible (STB_LOCAL)
ffffffff8173f550-ffffffff8173f58d: ab3100_set_register_interruptible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ab3100_set_register_interruptible(struct ab3100 *ab3100, u8 reg, u8 regval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (0)
Location: drivers/mfd/ab3100-core.c:72
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:set_register_interruptible
```
**Symbols:**

```
ffffffff8175a210-ffffffff8175a296: ab3100_set_register_interruptible (STB_LOCAL)
ffffffff8175a990-ffffffff8175a9cd: ab3100_set_register_interruptible.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
