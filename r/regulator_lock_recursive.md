# Function: <code>regulator_lock_recursive</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81623e70)
Location: drivers/regulator/core.c:274
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81623e70-ffffffff81623ff9: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81656b80)
Location: drivers/regulator/core.c:256
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81656b80-ffffffff81656d76: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8167a0c0)
Location: drivers/regulator/core.c:256
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff8167a0c0-ffffffff8167a2b6: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81729300)
Location: drivers/regulator/core.c:259
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81729300-ffffffff817294a1: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81745eb0)
Location: drivers/regulator/core.c:258
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81745eb0-ffffffff81746051: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817298c0)
Location: drivers/regulator/core.c:258
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff817298c0-ffffffff81729a61: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff817aba30)
Location: drivers/regulator/core.c:248
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff817aba30-ffffffff817abc21: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff818e6750)
Location: drivers/regulator/core.c:249
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff818e6750-ffffffff818e698e: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a3aa80)
Location: drivers/regulator/core.c:249
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81a3aa80-ffffffff81a3acbe: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81a848e0)
Location: drivers/regulator/core.c:314
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81a848e0-ffffffff81a84b22: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81ad70c0)
Location: drivers/regulator/core.c:316
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81ad70c0-ffffffff81ad7302: regulator_lock_recursive (STB_LOCAL)
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
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff800010842400)
Location: drivers/regulator/core.c:256
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffff800010842400-ffff8000108425c8: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c094cf4c)
Location: drivers/regulator/core.c:256
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
c094cf4c-c094d138: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008de280)
Location: drivers/regulator/core.c:256
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
c0000000008de280-c0000000008de57c: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe000524776)
Location: drivers/regulator/core.c:256
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffe000524776-ffffffe0005248fa: regulator_lock_recursive (STB_LOCAL)
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
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8163fbc0)
Location: drivers/regulator/core.c:256
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff8163fbc0-ffffffff8163fdb6: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8161ffa0)
Location: drivers/regulator/core.c:256
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff8161ffa0-ffffffff81620196: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8166df00)
Location: drivers/regulator/core.c:256
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff8166df00-ffffffff8166e0f6: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regulator_lock_recursive(struct regulator_dev *rdev, struct regulator_dev **new_contended_rdev, struct regulator_dev **old_contended_rdev, struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81688560)
Location: drivers/regulator/core.c:256
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
```
**Symbols:**

```
ffffffff81688560-ffffffff81688756: regulator_lock_recursive (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
