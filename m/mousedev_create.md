# Function: <code>mousedev_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff8166c450)
Location: drivers/input/mousedev.c:840
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff8166c450-ffffffff8166c7b4: mousedev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff816cc8a0)
Location: drivers/input/mousedev.c:840
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff816cc8a0-ffffffff816ccc04: mousedev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff816fa840)
Location: drivers/input/mousedev.c:840
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff816fa840-ffffffff816faba4: mousedev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff817102d0)
Location: drivers/input/mousedev.c:838
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff817102d0-ffffffff817105bf: mousedev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff81781550)
Location: drivers/input/mousedev.c:844
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff81781550-ffffffff8178183f: mousedev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:844
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff817c2840-ffffffff817c2b12: mousedev_create (STB_LOCAL)
ffffffff817c2d0e-ffffffff817c2d3a: mousedev_create.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:845
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff817e9c80-ffffffff817e9f54: mousedev_create (STB_LOCAL)
ffffffff817ea2ac-ffffffff817ea2d8: mousedev_create.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff8182a1e0-ffffffff8182a4b4: mousedev_create (STB_LOCAL)
ffffffff8182adb4-ffffffff8182ade0: mousedev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff8185bb70-ffffffff8185be44: mousedev_create (STB_LOCAL)
ffffffff8185c744-ffffffff8185c770: mousedev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff8192e710-ffffffff8192e9e4: mousedev_create (STB_LOCAL)
ffffffff8192f48d-ffffffff8192f4b9: mousedev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff81935ab0-ffffffff81935d84: mousedev_create (STB_LOCAL)
ffffffff81c234ab-ffffffff81c234d7: mousedev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff81919850-ffffffff81919b16: mousedev_create (STB_LOCAL)
ffffffff81c15581-ffffffff81c155ad: mousedev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff819bbc60-ffffffff819bbf26: mousedev_create (STB_LOCAL)
ffffffff81d235df-ffffffff81d2360b: mousedev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff81b1bf60-ffffffff81b1c227: mousedev_create (STB_LOCAL)
ffffffff81eef4cf-ffffffff81eef4fb: mousedev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff81caddb0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff81caddb0-ffffffff81cae0a3: mousedev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff81d153a0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff81d153a0-ffffffff81d1569a: mousedev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffff81dcaff0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff81dcaff0-ffffffff81dcb319: mousedev_create (STB_LOCAL)
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
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffff800010a9c070)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffff800010a9c070-ffff800010a9c380: mousedev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (c0b7d774)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
c0b7d774-c0b7da64: mousedev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (c000000000b7d640)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
c000000000b7d640-c000000000b7da1c: mousedev_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/mousedev.c (ffffffe0006ac7ca)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffe0006ac7ca-ffffffe0006aca8e: mousedev_create (STB_LOCAL)
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
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff81810b80-ffffffff81810e54: mousedev_create (STB_LOCAL)
ffffffff81811754-ffffffff81811780: mousedev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff817d82c0-ffffffff817d8594: mousedev_create (STB_LOCAL)
ffffffff817d8e94-ffffffff817d8ec0: mousedev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff8184fd00-ffffffff8184ffd4: mousedev_create (STB_LOCAL)
ffffffff818508d4-ffffffff81850900: mousedev_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct mousedev *mousedev_create(struct input_dev *dev, struct input_handler *handler, bool mixdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/mousedev.c (0)
Location: drivers/input/mousedev.c:842
Inline: False
Direct callers:
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_connect
```
**Symbols:**

```
ffffffff8186b0e0-ffffffff8186b3b4: mousedev_create (STB_LOCAL)
ffffffff8186ba54-ffffffff8186ba80: mousedev_create.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
