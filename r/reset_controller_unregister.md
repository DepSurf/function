# Function: <code>reset_controller_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff814df3e0)
Location: drivers/reset/core.c:81
Inline: False
```
**Symbols:**

```
ffffffff814df3e0-ffffffff814df433: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81530310)
Location: drivers/reset/core.c:88
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff81530310-ffffffff81530363: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8155c8e0)
Location: drivers/reset/core.c:92
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff8155c8e0-ffffffff8155c933: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81571340)
Location: drivers/reset/core.c:93
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff81571340-ffffffff8157138f: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815d5610)
Location: drivers/reset/core.c:106
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff815d5610-ffffffff815d565f: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8160e3e0)
Location: drivers/reset/core.c:109
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff8160e3e0-ffffffff8160e42f: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162af00)
Location: drivers/reset/core.c:109
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff8162af00-ffffffff8162af4f: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8165ead0)
Location: drivers/reset/core.c:118
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff8165ead0-ffffffff8165eb1d: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff816811c0)
Location: drivers/reset/core.c:117
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff816811c0-ffffffff8168120d: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732c14)
Location: drivers/reset/core.c:119
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff817323a0-ffffffff817323f0: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174edd4)
Location: drivers/reset/core.c:120
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff8174e450-ffffffff8174e4a0: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732a94)
Location: drivers/reset/core.c:120
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff81731fd0-ffffffff81732020: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817b33a4)
Location: drivers/reset/core.c:120
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff817b2730-ffffffff817b2780: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff818eee44)
Location: drivers/reset/core.c:121
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff818ee0d0-ffffffff818ee12a: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a46ad4)
Location: drivers/reset/core.c:121
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff81a45c60-ffffffff81a45cba: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a90c74)
Location: drivers/reset/core.c:121
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff81a8fe10-ffffffff81a8fe6a: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81ae36e4)
Location: drivers/reset/core.c:121
Inline: True
Inline callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff81ae2850-ffffffff81ae28aa: reset_controller_unregister (STB_GLOBAL)
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
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084c040)
Location: drivers/reset/core.c:117
Inline: False
Direct callers:
  - drivers/clk/hisilicon/reset.c:hisi_reset_exit
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffff80001084c040-ffff80001084c09c: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c09583d0)
Location: drivers/reset/core.c:117
Inline: False
Direct callers:
  - drivers/clk/hisilicon/reset.c:hisi_reset_exit
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
c09583d0-c0958420: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008ea5a0)
Location: drivers/reset/core.c:117
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
c0000000008ea5a0-c0000000008ea638: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052b928)
Location: drivers/reset/core.c:117
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffe00052b928-ffffffe00052b97c: reset_controller_unregister (STB_GLOBAL)
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
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81646c40)
Location: drivers/reset/core.c:117
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff81646c40-ffffffff81646c8d: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff816270a0)
Location: drivers/reset/core.c:117
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff816270a0-ffffffff816270ed: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81675000)
Location: drivers/reset/core.c:117
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff81675000-ffffffff8167504d: reset_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void reset_controller_unregister(struct reset_controller_dev *rcdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8168f660)
Location: drivers/reset/core.c:117
Inline: False
Direct callers:
  - drivers/reset/core.c:devm_reset_controller_release
```
**Symbols:**

```
ffffffff8168f660-ffffffff8168f6ad: reset_controller_unregister (STB_GLOBAL)
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
