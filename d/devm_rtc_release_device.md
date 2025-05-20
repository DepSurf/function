# Function: <code>devm_rtc_release_device</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81719200)
Location: drivers/rtc/class.c:378
Inline: False
```
**Symbols:**

```
ffffffff81719200-ffffffff81719223: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff8178a460)
Location: drivers/rtc/class.c:381
Inline: False
```
**Symbols:**

```
ffffffff8178a460-ffffffff8178a483: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff817cb570)
Location: drivers/rtc/class.c:449
Inline: False
```
**Symbols:**

```
ffffffff817cb570-ffffffff817cb5a1: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff817f2b50)
Location: drivers/rtc/class.c:299
Inline: False
```
**Symbols:**

```
ffffffff817f2b50-ffffffff817f2bc3: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81833820)
Location: drivers/rtc/class.c:294
Inline: False
```
**Symbols:**

```
ffffffff81833820-ffffffff8183389b: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81865160)
Location: drivers/rtc/class.c:294
Inline: False
```
**Symbols:**

```
ffffffff81865160-ffffffff818651db: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff819389b0)
Location: drivers/rtc/class.c:338
Inline: False
```
**Symbols:**

```
ffffffff819389b0-ffffffff81938a2b: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_rtc_release_device(void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff8193f394)
Location: drivers/rtc/class.c:345
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff8193ebb0-ffffffff8193ebc0: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_rtc_release_device(void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81922b74)
Location: drivers/rtc/class.c:342
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff819223a0-ffffffff819223b0: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void devm_rtc_release_device(void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff819c5b24)
Location: drivers/rtc/class.c:342
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff819c5350-ffffffff819c5360: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void devm_rtc_release_device(void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81b26340)
Location: drivers/rtc/class.c:353
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff81b25970-ffffffff81b25986: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devm_rtc_release_device(void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81cb9aa5)
Location: drivers/rtc/class.c:353
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff81cb8f40-ffffffff81cb8f56: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devm_rtc_release_device(void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81d211dc)
Location: drivers/rtc/class.c:353
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff81d20670-ffffffff81d20686: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devm_rtc_release_device(void *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81dd6f3c)
Location: drivers/rtc/class.c:353
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
**Symbols:**

```
ffffffff81dd63a0-ffffffff81dd63b6: devm_rtc_release_device (STB_LOCAL)
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
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffff800010aa69c0)
Location: drivers/rtc/class.c:294
Inline: False
```
**Symbols:**

```
ffff800010aa69c0-ffff800010aa6a40: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (c0b854fc)
Location: drivers/rtc/class.c:294
Inline: False
```
**Symbols:**

```
c0b854fc-c0b85570: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (c000000000b87640)
Location: drivers/rtc/class.c:294
Inline: False
```
**Symbols:**

```
c000000000b87640-c000000000b87710: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffe0006b2cb2)
Location: drivers/rtc/class.c:294
Inline: False
```
**Symbols:**

```
ffffffe0006b2cb2-ffffffe0006b2d3c: devm_rtc_release_device (STB_LOCAL)
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
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81817e10)
Location: drivers/rtc/class.c:294
Inline: False
```
**Symbols:**

```
ffffffff81817e10-ffffffff81817e8b: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff817df500)
Location: drivers/rtc/class.c:294
Inline: False
```
**Symbols:**

```
ffffffff817df500-ffffffff817df57b: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff818592f0)
Location: drivers/rtc/class.c:294
Inline: False
```
**Symbols:**

```
ffffffff818592f0-ffffffff8185936b: devm_rtc_release_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devm_rtc_release_device(struct device *dev, void *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff818743d0)
Location: drivers/rtc/class.c:294
Inline: False
```
**Symbols:**

```
ffffffff818743d0-ffffffff8187444b: devm_rtc_release_device (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, res</code> ➡️ <code>res</code>
</li>
</ul>
</details>
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
