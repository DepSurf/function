# Function: <code>pwm_class_get_state</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pwm_export *pwm_class_get_state(struct device *parent, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81556100)
Location: drivers/pwm/sysfs.c:377
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
```
**Symbols:**

```
ffffffff81556100-ffffffff81556169: pwm_class_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pwm_export *pwm_class_get_state(struct device *parent, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81577720)
Location: drivers/pwm/sysfs.c:377
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
```
**Symbols:**

```
ffffffff81577720-ffffffff81577789: pwm_class_get_state (STB_LOCAL)
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
In drivers/pwm/sysfs.c (ffffffff8161d033)
Location: drivers/pwm/sysfs.c:377
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
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
In drivers/pwm/sysfs.c (ffffffff81643775)
Location: drivers/pwm/sysfs.c:377
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
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
In drivers/pwm/sysfs.c (ffffffff81626595)
Location: drivers/pwm/sysfs.c:377
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
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
In drivers/pwm/sysfs.c (ffffffff81695de5)
Location: drivers/pwm/sysfs.c:377
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
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
In drivers/pwm/sysfs.c (ffffffff817b6bfa)
Location: drivers/pwm/sysfs.c:377
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pwm_export *pwm_class_get_state(struct device *parent, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff818d04d0)
Location: drivers/pwm/sysfs.c:377
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
```
**Symbols:**

```
ffffffff818d04d0-ffffffff818d0558: pwm_class_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pwm_export *pwm_class_get_state(struct device *parent, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81913470)
Location: drivers/pwm/sysfs.c:377
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
```
**Symbols:**

```
ffffffff81913470-ffffffff819134e4: pwm_class_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pwm_export *pwm_class_get_state(struct device *parent, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8195b3b0)
Location: drivers/pwm/sysfs.c:377
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
```
**Symbols:**

```
ffffffff8195b3b0-ffffffff8195b424: pwm_class_get_state (STB_LOCAL)
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
struct pwm_export *pwm_class_get_state(struct device *parent, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffff8000106d9150)
Location: drivers/pwm/sysfs.c:377
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
```
**Symbols:**

```
ffff8000106d9150-ffff8000106d91ec: pwm_class_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pwm_export *pwm_class_get_state(struct device *parent, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (c0875be4)
Location: drivers/pwm/sysfs.c:377
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
```
**Symbols:**

```
c0875be4-c0875c44: pwm_class_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pwm_export *pwm_class_get_state(struct device *parent, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (c000000000850930)
Location: drivers/pwm/sysfs.c:377
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
```
**Symbols:**

```
c000000000850930-c000000000850a10: pwm_class_get_state (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct pwm_export *pwm_class_get_state(struct device *parent, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8156c530)
Location: drivers/pwm/sysfs.c:377
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
```
**Symbols:**

```
ffffffff8156c530-ffffffff8156c599: pwm_class_get_state (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pwm_export *pwm_class_get_state(struct device *parent, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8156b470)
Location: drivers/pwm/sysfs.c:377
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
```
**Symbols:**

```
ffffffff8156b470-ffffffff8156b4d9: pwm_class_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pwm_export *pwm_class_get_state(struct device *parent, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81585970)
Location: drivers/pwm/sysfs.c:377
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
```
**Symbols:**

```
ffffffff81585970-ffffffff815859d9: pwm_class_get_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
