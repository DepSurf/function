# Function: <code>pwm_export_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8142d754)
Location: drivers/pwm/sysfs.c:191
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81478ac7)
Location: drivers/pwm/sysfs.c:249
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81499e57)
Location: drivers/pwm/sysfs.c:249
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
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
In drivers/pwm/sysfs.c (ffffffff814a3aa0)
Location: drivers/pwm/sysfs.c:249
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff814e2810)
Location: drivers/pwm/sysfs.c:249
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8151203c)
Location: drivers/pwm/sysfs.c:249
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81527760)
Location: drivers/pwm/sysfs.c:249
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81556a01)
Location: drivers/pwm/sysfs.c:241
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81578021)
Location: drivers/pwm/sysfs.c:241
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pwm_export_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8161cca0)
Location: drivers/pwm/sysfs.c:241
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:export_store
```
**Symbols:**

```
ffffffff8161cca0-ffffffff8161cde5: pwm_export_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pwm_export_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff816433d0)
Location: drivers/pwm/sysfs.c:241
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:export_store
```
**Symbols:**

```
ffffffff816433d0-ffffffff81643515: pwm_export_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pwm_export_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff816261f0)
Location: drivers/pwm/sysfs.c:241
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:export_store
```
**Symbols:**

```
ffffffff816261f0-ffffffff81626335: pwm_export_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pwm_export_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81695a30)
Location: drivers/pwm/sysfs.c:241
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:export_store
```
**Symbols:**

```
ffffffff81695a30-ffffffff81695b75: pwm_export_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pwm_export_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff817b67e0)
Location: drivers/pwm/sysfs.c:241
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:export_store
```
**Symbols:**

```
ffffffff817b67e0-ffffffff817b6942: pwm_export_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pwm_export_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff818d1030)
Location: drivers/pwm/sysfs.c:241
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:export_store
```
**Symbols:**

```
ffffffff818d1030-ffffffff818d1192: pwm_export_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pwm_export_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81914020)
Location: drivers/pwm/sysfs.c:241
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:export_store
```
**Symbols:**

```
ffffffff81914020-ffffffff81914182: pwm_export_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pwm_export_child(struct device *parent, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8195bf60)
Location: drivers/pwm/sysfs.c:241
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:export_store
```
**Symbols:**

```
ffffffff8195bf60-ffffffff8195c0f1: pwm_export_child (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffff8000106d9c34)
Location: drivers/pwm/sysfs.c:241
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (c0876548)
Location: drivers/pwm/sysfs.c:241
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (c000000000851718)
Location: drivers/pwm/sysfs.c:241
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffe0004b292a)
Location: drivers/pwm/sysfs.c:241
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8156ce31)
Location: drivers/pwm/sysfs.c:241
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8156bd71)
Location: drivers/pwm/sysfs.c:241
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81586271)
Location: drivers/pwm/sysfs.c:241
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:export_store
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
