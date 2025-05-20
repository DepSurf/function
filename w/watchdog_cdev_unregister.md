# Function: <code>watchdog_cdev_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff816ec020)
Location: drivers/watchdog/watchdog_dev.c:885
Inline: True
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff816ec020-ffffffff816ec0a4: watchdog_cdev_unregister.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8171d010)
Location: drivers/watchdog/watchdog_dev.c:975
Inline: True
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8171d010-ffffffff8171d094: watchdog_cdev_unregister.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81735740)
Location: drivers/watchdog/watchdog_dev.c:988
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81735740-ffffffff817357ec: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817a7450)
Location: drivers/watchdog/watchdog_dev.c:990
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff817a7450-ffffffff817a7502: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817eed40)
Location: drivers/watchdog/watchdog_dev.c:1012
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff817eed40-ffffffff817eee01: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8181ac10)
Location: drivers/watchdog/watchdog_dev.c:1012
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8181ac10-ffffffff8181acd1: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8185ce30)
Location: drivers/watchdog/watchdog_dev.c:1039
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8185ce30-ffffffff8185cf02: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8188ed80)
Location: drivers/watchdog/watchdog_dev.c:1053
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8188ed80-ffffffff8188ee4f: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8195da20)
Location: drivers/watchdog/watchdog_dev.c:1074
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8195da20-ffffffff8195daf0: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81964420)
Location: drivers/watchdog/watchdog_dev.c:1077
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81964420-ffffffff819644f0: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81948840)
Location: drivers/watchdog/watchdog_dev.c:1077
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81948840-ffffffff81948910: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed840)
Location: drivers/watchdog/watchdog_dev.c:1084
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff819ed840-ffffffff819ed910: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81b54160)
Location: drivers/watchdog/watchdog_dev.c:1088
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81b54160-ffffffff81b5422f: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81cec5d0)
Location: drivers/watchdog/watchdog_dev.c:1100
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81cec5d0-ffffffff81cec69f: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81d552f0)
Location: drivers/watchdog/watchdog_dev.c:1121
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81d552f0-ffffffff81d553bf: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c1c0)
Location: drivers/watchdog/watchdog_dev.c:1120
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81e0c1c0-ffffffff81e0c28f: watchdog_cdev_unregister (STB_LOCAL)
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
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffff800010adfc88)
Location: drivers/watchdog/watchdog_dev.c:1053
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffff800010adfc88-ffff800010adfd3c: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c0bc1600)
Location: drivers/watchdog/watchdog_dev.c:1053
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
c0bc1600-c0bc16b0: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c000000000bc7b40)
Location: drivers/watchdog/watchdog_dev.c:1053
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
c000000000bc7b40-c000000000bc7c40: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7794)
Location: drivers/watchdog/watchdog_dev.c:1053
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffe0006d7794-ffffffe0006d784e: watchdog_cdev_unregister (STB_LOCAL)
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
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81834c00)
Location: drivers/watchdog/watchdog_dev.c:1053
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81834c00-ffffffff81834ccf: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817fc290)
Location: drivers/watchdog/watchdog_dev.c:1053
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff817fc290-ffffffff817fc35f: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81884230)
Location: drivers/watchdog/watchdog_dev.c:1053
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81884230-ffffffff818842ff: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void watchdog_cdev_unregister(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8189fcf0)
Location: drivers/watchdog/watchdog_dev.c:1053
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8189fcf0-ffffffff8189fdbf: watchdog_cdev_unregister (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
