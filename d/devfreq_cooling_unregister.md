# Function: <code>devfreq_cooling_unregister</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817a6190)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
ffffffff817a6190-ffffffff817a61dc: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817edc10)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
ffffffff817edc10-ffffffff817edc5b: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81819ae0)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
ffffffff81819ae0-ffffffff81819b2b: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff8185bc50)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
ffffffff8185bc50-ffffffff8185bca2: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff8188d760)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
ffffffff8188d760-ffffffff8188d7b2: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff8195bd50)
Location: drivers/thermal/devfreq_cooling.c:568
Inline: True
```
**Symbols:**

```
ffffffff8195bd50-ffffffff8195bdae: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81962dc0)
Location: drivers/thermal/devfreq_cooling.c:518
Inline: True
```
**Symbols:**

```
ffffffff81962dc0-ffffffff81962e30: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff819463b0)
Location: drivers/thermal/devfreq_cooling.c:510
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff819463b0-ffffffff8194640f: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff819eadb0)
Location: drivers/thermal/devfreq_cooling.c:510
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff819eadb0-ffffffff819eae0f: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81b507b0)
Location: drivers/thermal/devfreq_cooling.c:531
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff81b507b0-ffffffff81b5082c: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81ce8750)
Location: drivers/thermal/devfreq_cooling.c:525
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff81ce8750-ffffffff81ce87b9: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81d50f10)
Location: drivers/thermal/devfreq_cooling.c:525
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff81d50f10-ffffffff81d50f79: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81e07c60)
Location: drivers/thermal/devfreq_cooling.c:525
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_device
```
**Symbols:**

```
ffffffff81e07c60-ffffffff81e07cc9: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffff800010adced8)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
ffff800010adced8-ffff800010adcf38: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (c0bbd528)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
c0bbd528-c0bbd57c: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (c000000000bc5820)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
c000000000bc5820-c000000000bc58a4: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffe0006d632c)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
ffffffe0006d632c-ffffffe0006d638c: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff818335e0)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
ffffffff818335e0-ffffffff81833632: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff817fac70)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
ffffffff817fac70-ffffffff817facc2: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff81882c10)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
ffffffff81882c10-ffffffff81882c62: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devfreq_cooling_unregister(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/devfreq_cooling.c (ffffffff8189e6d0)
Location: drivers/thermal/devfreq_cooling.c:592
Inline: True
```
**Symbols:**

```
ffffffff8189e6d0-ffffffff8189e722: devfreq_cooling_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
