# Function: <code>amd_pinconf_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81422370)
Location: drivers/pinctrl/pinctrl-amd.c:592
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff81422370-ffffffff8142242a: amd_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8146aad0)
Location: drivers/pinctrl/pinctrl-amd.c:567
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff8146aad0-ffffffff8146ab8a: amd_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81489de0)
Location: drivers/pinctrl/pinctrl-amd.c:578
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff81489de0-ffffffff81489e9a: amd_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814938d0)
Location: drivers/pinctrl/pinctrl-amd.c:590
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff814938d0-ffffffff81493989: amd_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cfb60)
Location: drivers/pinctrl/pinctrl-amd.c:598
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff814cfb60-ffffffff814cfc19: amd_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81500d50)
Location: drivers/pinctrl/pinctrl-amd.c:621
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff81500d50-ffffffff81500e09: amd_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81515820)
Location: drivers/pinctrl/pinctrl-amd.c:634
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff81515820-ffffffff815158d9: amd_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:630
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff815439c0-ffffffff81543a57: amd_pinconf_get (STB_LOCAL)
ffffffff81543dea-ffffffff81543e0e: amd_pinconf_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:641
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff815648d0-ffffffff81564967: amd_pinconf_get (STB_LOCAL)
ffffffff81564ce1-ffffffff81564d05: amd_pinconf_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:644
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff81606d40-ffffffff81606dd7: amd_pinconf_get (STB_LOCAL)
ffffffff816072a4-ffffffff816072c8: amd_pinconf_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:667
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff8162b610-ffffffff8162b6a7: amd_pinconf_get (STB_LOCAL)
ffffffff81bf55d3-ffffffff81bf55f7: amd_pinconf_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:667
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff8160f2e0-ffffffff8160f373: amd_pinconf_get (STB_LOCAL)
ffffffff81be74f7-ffffffff81be751b: amd_pinconf_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:725
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff8167e210-ffffffff8167e2a3: amd_pinconf_get (STB_LOCAL)
ffffffff81ce0b8f-ffffffff81ce0bb3: amd_pinconf_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:730
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff81799e10-ffffffff81799eb1: amd_pinconf_get (STB_LOCAL)
ffffffff81ea72ab-ffffffff81ea72cf: amd_pinconf_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818affa0)
Location: drivers/pinctrl/pinctrl-amd.c:729
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff818affa0-ffffffff818b0068: amd_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f2f70)
Location: drivers/pinctrl/pinctrl-amd.c:720
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff818f2f70-ffffffff818f304c: amd_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193a7a0)
Location: drivers/pinctrl/pinctrl-amd.c:720
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff8193a7a0-ffffffff8193a87c: amd_pinconf_get (STB_LOCAL)
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
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffff800010693c78)
Location: drivers/pinctrl/pinctrl-amd.c:641
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffff800010693c78-ffff800010693db8: amd_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (c0835274)
Location: drivers/pinctrl/pinctrl-amd.c:641
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
c0835274-c0835340: amd_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (c000000000830c90)
Location: drivers/pinctrl/pinctrl-amd.c:641
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
c000000000830c90-c000000000830de8: amd_pinconf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049eb1a)
Location: drivers/pinctrl/pinctrl-amd.c:641
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffe00049eb1a-ffffffe00049ebe6: amd_pinconf_get (STB_LOCAL)
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
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:641
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff8155cec0-ffffffff8155cf57: amd_pinconf_get (STB_LOCAL)
ffffffff8155d2d1-ffffffff8155d2f5: amd_pinconf_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:641
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff81558c00-ffffffff81558c97: amd_pinconf_get (STB_LOCAL)
ffffffff81559011-ffffffff81559035: amd_pinconf_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_get(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *config);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:641
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get
```
**Symbols:**

```
ffffffff81572a90-ffffffff81572b27: amd_pinconf_get (STB_LOCAL)
ffffffff81572ea1-ffffffff81572ec5: amd_pinconf_get.cold (STB_LOCAL)
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
