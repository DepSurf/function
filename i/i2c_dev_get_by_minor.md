# Function: <code>i2c_dev_get_by_minor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff8167dca0)
Location: drivers/i2c/i2c-dev.c:56
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
  - drivers/i2c/i2c-dev.c:i2cdev_open
```
**Symbols:**

```
ffffffff8167dca0-ffffffff8167dd04: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff816dea30)
Location: drivers/i2c/i2c-dev.c:58
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
ffffffff816dea30-ffffffff816dea97: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff8170edf0)
Location: drivers/i2c/i2c-dev.c:58
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
ffffffff8170edf0-ffffffff8170ee57: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81724d50)
Location: drivers/i2c/i2c-dev.c:58
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
ffffffff81724d50-ffffffff81724db4: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81796210)
Location: drivers/i2c/i2c-dev.c:59
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
ffffffff81796210-ffffffff81796274: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff817d9400)
Location: drivers/i2c/i2c-dev.c:59
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
ffffffff817d9400-ffffffff817d9464: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81800780)
Location: drivers/i2c/i2c-dev.c:59
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
ffffffff81800780-ffffffff818007e4: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff818417d0)
Location: drivers/i2c/i2c-dev.c:51
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
ffffffff818417d0-ffffffff8184182b: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81873150)
Location: drivers/i2c/i2c-dev.c:51
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
ffffffff81873150-ffffffff818731ab: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff819473d2)
Location: drivers/i2c/i2c-dev.c:51
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:name_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff8194d1e2)
Location: drivers/i2c/i2c-dev.c:51
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:name_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81931432)
Location: drivers/i2c/i2c-dev.c:51
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:name_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff819d4712)
Location: drivers/i2c/i2c-dev.c:53
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:name_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81b36b86)
Location: drivers/i2c/i2c-dev.c:53
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:name_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81ccbe76)
Location: drivers/i2c/i2c-dev.c:53
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:name_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81d337df)
Location: drivers/i2c/i2c-dev.c:53
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_detach_adapter
  - drivers/i2c/i2c-dev.c:name_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81de982f)
Location: drivers/i2c/i2c-dev.c:53
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_detach_adapter
  - drivers/i2c/i2c-dev.c:name_show
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
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffff800010ab7240)
Location: drivers/i2c/i2c-dev.c:51
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
ffff800010ab7240-ffff800010ab7318: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (c0b96f60)
Location: drivers/i2c/i2c-dev.c:51
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
c0b96f60-c0b96fe4: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (c000000000b9a740)
Location: drivers/i2c/i2c-dev.c:51
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
c000000000b9a740-c000000000b9a840: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffe0006bd038)
Location: drivers/i2c/i2c-dev.c:51
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
ffffffe0006bd038-ffffffe0006bd0d6: i2c_dev_get_by_minor (STB_LOCAL)
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
<summary>In <code>gcp</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff818672e0)
Location: drivers/i2c/i2c-dev.c:51
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
ffffffff818672e0-ffffffff8186733b: i2c_dev_get_by_minor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct i2c_dev *i2c_dev_get_by_minor(unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-dev.c (ffffffff81882010)
Location: drivers/i2c/i2c-dev.c:51
Inline: False
Direct callers:
  - drivers/i2c/i2c-dev.c:name_show
```
**Symbols:**

```
ffffffff81882010-ffffffff8188206f: i2c_dev_get_by_minor (STB_LOCAL)
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
