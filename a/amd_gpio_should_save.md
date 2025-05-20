# Function: <code>amd_gpio_should_save</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81493d20)
Location: drivers/pinctrl/pinctrl-amd.c:730
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff81493d20-ffffffff81493d71: amd_gpio_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cffc0)
Location: drivers/pinctrl/pinctrl-amd.c:738
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff814cffc0-ffffffff814d0011: amd_gpio_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814fff30)
Location: drivers/pinctrl/pinctrl-amd.c:761
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff814fff30-ffffffff814fff89: amd_gpio_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815149a0)
Location: drivers/pinctrl/pinctrl-amd.c:774
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff815149a0-ffffffff815149f9: amd_gpio_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81542b70)
Location: drivers/pinctrl/pinctrl-amd.c:770
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff81542b70-ffffffff81542bd4: amd_gpio_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81563a00)
Location: drivers/pinctrl/pinctrl-amd.c:781
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff81563a00-ffffffff81563a64: amd_gpio_should_save (STB_LOCAL)
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81607127)
Location: drivers/pinctrl/pinctrl-amd.c:784
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162a837)
Location: drivers/pinctrl/pinctrl-amd.c:807
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160e517)
Location: drivers/pinctrl/pinctrl-amd.c:807
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167e6b7)
Location: drivers/pinctrl/pinctrl-amd.c:893
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81798c40)
Location: drivers/pinctrl/pinctrl-amd.c:898
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff81798c40-ffffffff81798cbc: amd_gpio_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818aec00)
Location: drivers/pinctrl/pinctrl-amd.c:897
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff818aec00-ffffffff818aec7c: amd_gpio_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f1b50)
Location: drivers/pinctrl/pinctrl-amd.c:893
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff818f1b50-ffffffff818f1bcc: amd_gpio_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81939300)
Location: drivers/pinctrl/pinctrl-amd.c:893
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff81939300-ffffffff8193937c: amd_gpio_should_save (STB_LOCAL)
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
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffff800010692850)
Location: drivers/pinctrl/pinctrl-amd.c:781
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffff800010692850-ffff8000106928d0: amd_gpio_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (c0834264)
Location: drivers/pinctrl/pinctrl-amd.c:781
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
c0834264-c08342c4: amd_gpio_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (c00000000082efa0)
Location: drivers/pinctrl/pinctrl-amd.c:781
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
c00000000082efa0-c00000000082f06c: amd_gpio_should_save (STB_LOCAL)
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
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155bff0)
Location: drivers/pinctrl/pinctrl-amd.c:781
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff8155bff0-ffffffff8155c054: amd_gpio_should_save (STB_LOCAL)
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
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81557d30)
Location: drivers/pinctrl/pinctrl-amd.c:781
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff81557d30-ffffffff81557d94: amd_gpio_should_save (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool amd_gpio_should_save(struct amd_gpio *gpio_dev, unsigned int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81571bc0)
Location: drivers/pinctrl/pinctrl-amd.c:781
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff81571bc0-ffffffff81571c24: amd_gpio_should_save (STB_LOCAL)
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
