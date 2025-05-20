# Function: <code>amd_pinconf_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814221a0)
Location: drivers/pinctrl/pinctrl-amd.c:633
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff814221a0-ffffffff814222d5: amd_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8146a900)
Location: drivers/pinctrl/pinctrl-amd.c:608
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff8146a900-ffffffff8146aa3b: amd_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81489c10)
Location: drivers/pinctrl/pinctrl-amd.c:619
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff81489c10-ffffffff81489d4b: amd_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814936e0)
Location: drivers/pinctrl/pinctrl-amd.c:631
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff814936e0-ffffffff81493825: amd_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cf970)
Location: drivers/pinctrl/pinctrl-amd.c:639
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff814cf970-ffffffff814cfab5: amd_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81500b60)
Location: drivers/pinctrl/pinctrl-amd.c:662
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff81500b60-ffffffff81500ca1: amd_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81515630)
Location: drivers/pinctrl/pinctrl-amd.c:675
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff81515630-ffffffff81515771: amd_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:671
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff81543800-ffffffff81543912: amd_pinconf_set (STB_LOCAL)
ffffffff81543dbb-ffffffff81543dea: amd_pinconf_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:682
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff81564710-ffffffff81564822: amd_pinconf_set (STB_LOCAL)
ffffffff81564cb2-ffffffff81564ce1: amd_pinconf_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:685
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff81606c30-ffffffff81606d40: amd_pinconf_set (STB_LOCAL)
ffffffff81607274-ffffffff816072a4: amd_pinconf_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:708
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff8162b500-ffffffff8162b610: amd_pinconf_set (STB_LOCAL)
ffffffff81bf55a3-ffffffff81bf55d3: amd_pinconf_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:708
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff8160f1d0-ffffffff8160f2d5: amd_pinconf_set (STB_LOCAL)
ffffffff81be74c7-ffffffff81be74f7: amd_pinconf_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:766
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff8167e110-ffffffff8167e210: amd_pinconf_set (STB_LOCAL)
ffffffff81ce0b5f-ffffffff81ce0b8f: amd_pinconf_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:771
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff81799cf0-ffffffff81799e07: amd_pinconf_set (STB_LOCAL)
ffffffff81ea727a-ffffffff81ea72ab: amd_pinconf_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818afe40)
Location: drivers/pinctrl/pinctrl-amd.c:770
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff818afe40-ffffffff818aff87: amd_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f2c50)
Location: drivers/pinctrl/pinctrl-amd.c:761
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff818f2c50-ffffffff818f2e92: amd_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193a480)
Location: drivers/pinctrl/pinctrl-amd.c:761
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_set_config
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff8193a480-ffffffff8193a6c2: amd_pinconf_set (STB_LOCAL)
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
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffff800010693e28)
Location: drivers/pinctrl/pinctrl-amd.c:682
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffff800010693e28-ffff800010693fcc: amd_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (c08350b4)
Location: drivers/pinctrl/pinctrl-amd.c:682
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
c08350b4-c08351ec: amd_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (c00000000082fbd0)
Location: drivers/pinctrl/pinctrl-amd.c:682
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
c00000000082fbd0-c00000000082fe50: amd_pinconf_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049e8d0)
Location: drivers/pinctrl/pinctrl-amd.c:682
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffe00049e8d0-ffffffe00049ea8c: amd_pinconf_set (STB_LOCAL)
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
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:682
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff8155cd00-ffffffff8155ce12: amd_pinconf_set (STB_LOCAL)
ffffffff8155d2a2-ffffffff8155d2d1: amd_pinconf_set.cold (STB_LOCAL)
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
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:682
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff81558a40-ffffffff81558b52: amd_pinconf_set (STB_LOCAL)
ffffffff81558fe2-ffffffff81559011: amd_pinconf_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int amd_pinconf_set(struct pinctrl_dev *pctldev, unsigned int pin, long unsigned int *configs, unsigned int num_configs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:682
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set
```
**Symbols:**

```
ffffffff815728d0-ffffffff815729e2: amd_pinconf_set (STB_LOCAL)
ffffffff81572e72-ffffffff81572ea1: amd_pinconf_set.cold (STB_LOCAL)
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
