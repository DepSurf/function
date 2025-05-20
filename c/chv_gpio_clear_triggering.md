# Function: <code>chv_gpio_clear_triggering</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815195a2)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:849
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81547771)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:849
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81568691)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:851
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160bece)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:785
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void chv_gpio_clear_triggering(struct intel_pinctrl *pctrl, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8162eb80)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:769
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
```
**Symbols:**

```
ffffffff8162eb80-ffffffff8162ebf9: chv_gpio_clear_triggering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void chv_gpio_clear_triggering(struct intel_pinctrl *pctrl, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81612820)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:769
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
```
**Symbols:**

```
ffffffff81612820-ffffffff81612899: chv_gpio_clear_triggering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void chv_gpio_clear_triggering(struct intel_pinctrl *pctrl, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81681950)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:769
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
```
**Symbols:**

```
ffffffff81681950-ffffffff816819c9: chv_gpio_clear_triggering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void chv_gpio_clear_triggering(struct intel_pinctrl *pctrl, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179d9b0)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:771
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
```
**Symbols:**

```
ffffffff8179d9b0-ffffffff8179da3b: chv_gpio_clear_triggering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void chv_gpio_clear_triggering(struct intel_pinctrl *pctrl, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b45e0)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:773
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
```
**Symbols:**

```
ffffffff818b45e0-ffffffff818b466b: chv_gpio_clear_triggering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void chv_gpio_clear_triggering(struct intel_pinctrl *pctrl, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f7660)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:773
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
```
**Symbols:**

```
ffffffff818f7660-ffffffff818f76eb: chv_gpio_clear_triggering (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void chv_gpio_clear_triggering(struct intel_pinctrl *pctrl, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8193ec30)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:718
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
```
**Symbols:**

```
ffffffff8193ec30-ffffffff8193ecbb: chv_gpio_clear_triggering (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154eca1)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:851
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155c9c1)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:851
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81576851)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:851
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
