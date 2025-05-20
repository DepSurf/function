# Function: <code>watchdog_core_data_release</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void watchdog_core_data_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff816ec554)
Location: drivers/watchdog/watchdog_dev.c:716
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
```
**Symbols:**

```
ffffffff816ebf00-ffffffff816ebf10: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void watchdog_core_data_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8171d547)
Location: drivers/watchdog/watchdog_dev.c:806
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
```
**Symbols:**

```
ffffffff8171cef0-ffffffff8171cf00: watchdog_core_data_release (STB_LOCAL)
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
In drivers/watchdog/watchdog_dev.c (ffffffff81736060)
Location: drivers/watchdog/watchdog_dev.c:814
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void watchdog_core_data_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817a74d0)
Location: drivers/watchdog/watchdog_dev.c:817
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
```
**Symbols:**

```
ffffffff817a6e20-ffffffff817a6e30: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void watchdog_core_data_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817eedcc)
Location: drivers/watchdog/watchdog_dev.c:837
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
```
**Symbols:**

```
ffffffff817ee8a0-ffffffff817ee8b0: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void watchdog_core_data_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8181ac9c)
Location: drivers/watchdog/watchdog_dev.c:837
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
```
**Symbols:**

```
ffffffff8181a770-ffffffff8181a780: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void watchdog_core_data_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8185cec2)
Location: drivers/watchdog/watchdog_dev.c:863
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
```
**Symbols:**

```
ffffffff8185c950-ffffffff8185c960: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8188e500)
Location: drivers/watchdog/watchdog_dev.c:862
Inline: False
```
**Symbols:**

```
ffffffff8188e500-ffffffff8188e510: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d100)
Location: drivers/watchdog/watchdog_dev.c:882
Inline: False
```
**Symbols:**

```
ffffffff8195d100-ffffffff8195d110: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81963ab0)
Location: drivers/watchdog/watchdog_dev.c:883
Inline: False
```
**Symbols:**

```
ffffffff81963ab0-ffffffff81963ac0: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81947ed0)
Location: drivers/watchdog/watchdog_dev.c:883
Inline: False
```
**Symbols:**

```
ffffffff81947ed0-ffffffff81947ee0: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff819ece80)
Location: drivers/watchdog/watchdog_dev.c:889
Inline: False
```
**Symbols:**

```
ffffffff819ece80-ffffffff819ece90: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81b53730)
Location: drivers/watchdog/watchdog_dev.c:892
Inline: False
```
**Symbols:**

```
ffffffff81b53730-ffffffff81b53746: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81cec330)
Location: drivers/watchdog/watchdog_dev.c:900
Inline: False
```
**Symbols:**

```
ffffffff81cec330-ffffffff81cec346: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81d55050)
Location: drivers/watchdog/watchdog_dev.c:922
Inline: False
```
**Symbols:**

```
ffffffff81d55050-ffffffff81d55066: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0bf20)
Location: drivers/watchdog/watchdog_dev.c:922
Inline: False
```
**Symbols:**

```
ffffffff81e0bf20-ffffffff81e0bf36: watchdog_core_data_release (STB_LOCAL)
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
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffff800010adf0c8)
Location: drivers/watchdog/watchdog_dev.c:862
Inline: False
```
**Symbols:**

```
ffff800010adf0c8-ffff800010adf0f4: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c0bc0bb8)
Location: drivers/watchdog/watchdog_dev.c:862
Inline: False
```
**Symbols:**

```
c0bc0bb8-c0bc0bd4: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c000000000bc6ea0)
Location: drivers/watchdog/watchdog_dev.c:862
Inline: False
```
**Symbols:**

```
c000000000bc6ea0-c000000000bc6ed4: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d711e)
Location: drivers/watchdog/watchdog_dev.c:862
Inline: False
```
**Symbols:**

```
ffffffe0006d711e-ffffffe0006d7148: watchdog_core_data_release (STB_LOCAL)
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
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81834380)
Location: drivers/watchdog/watchdog_dev.c:862
Inline: False
```
**Symbols:**

```
ffffffff81834380-ffffffff81834390: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817fba10)
Location: drivers/watchdog/watchdog_dev.c:862
Inline: False
```
**Symbols:**

```
ffffffff817fba10-ffffffff817fba20: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff818839b0)
Location: drivers/watchdog/watchdog_dev.c:862
Inline: False
```
**Symbols:**

```
ffffffff818839b0-ffffffff818839c0: watchdog_core_data_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void watchdog_core_data_release(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8189f470)
Location: drivers/watchdog/watchdog_dev.c:862
Inline: False
```
**Symbols:**

```
ffffffff8189f470-ffffffff8189f480: watchdog_core_data_release (STB_LOCAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kref *kref</code>
</li>
</ul>
</details>
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
