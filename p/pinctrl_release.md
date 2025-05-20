# Function: <code>pinctrl_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pinctrl_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8141d500)
Location: drivers/pinctrl/core.c:939
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff8141d500-ffffffff8141d519: pinctrl_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pinctrl_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81465bd0)
Location: drivers/pinctrl/core.c:952
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81465bd0-ffffffff81465be9: pinctrl_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pinctrl_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81484ed0)
Location: drivers/pinctrl/core.c:952
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81484ed0-ffffffff81484ee9: pinctrl_release (STB_LOCAL)
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
In drivers/pinctrl/core.c (ffffffff8148e68e)
Location: drivers/pinctrl/core.c:1149
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pinctrl_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814ca7e0)
Location: drivers/pinctrl/core.c:1149
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff814ca7e0-ffffffff814ca7f9: pinctrl_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pinctrl_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814fb740)
Location: drivers/pinctrl/core.c:1149
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff814fb740-ffffffff814fb759: pinctrl_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pinctrl_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81510210)
Location: drivers/pinctrl/core.c:1177
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81510210-ffffffff81510229: pinctrl_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pinctrl_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8153e900)
Location: drivers/pinctrl/core.c:1153
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff8153e900-ffffffff8153e919: pinctrl_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pinctrl_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8155f7a0)
Location: drivers/pinctrl/core.c:1181
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff8155f7a0-ffffffff8155f7b9: pinctrl_release (STB_LOCAL)
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
In drivers/pinctrl/core.c (ffffffff81602d91)
Location: drivers/pinctrl/core.c:1182
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
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
In drivers/pinctrl/core.c (ffffffff81627ca1)
Location: drivers/pinctrl/core.c:1183
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
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
In drivers/pinctrl/core.c (ffffffff8160b781)
Location: drivers/pinctrl/core.c:1183
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
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
In drivers/pinctrl/core.c (ffffffff8167a491)
Location: drivers/pinctrl/core.c:1183
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
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
In drivers/pinctrl/core.c (ffffffff81795a9d)
Location: drivers/pinctrl/core.c:1183
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
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
In drivers/pinctrl/core.c (ffffffff818aad9d)
Location: drivers/pinctrl/core.c:1183
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
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
In drivers/pinctrl/core.c (ffffffff818edc7d)
Location: drivers/pinctrl/core.c:1187
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
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
In drivers/pinctrl/core.c (ffffffff8193544d)
Location: drivers/pinctrl/core.c:1201
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
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
In drivers/pinctrl/core.c (ffff80001068bcd8)
Location: drivers/pinctrl/core.c:1181
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_put
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
In drivers/pinctrl/core.c (c082dfc4)
Location: drivers/pinctrl/core.c:1181
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_put
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
In drivers/pinctrl/core.c (c000000000824938)
Location: drivers/pinctrl/core.c:1181
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_put
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
In drivers/pinctrl/core.c (ffffffe00049946c)
Location: drivers/pinctrl/core.c:1181
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
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
void pinctrl_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81557d90)
Location: drivers/pinctrl/core.c:1181
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81557d90-ffffffff81557da9: pinctrl_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pinctrl_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81548250)
Location: drivers/pinctrl/core.c:1181
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81548250-ffffffff81548269: pinctrl_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pinctrl_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81553ad0)
Location: drivers/pinctrl/core.c:1181
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff81553ad0-ffffffff81553ae9: pinctrl_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pinctrl_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8156d960)
Location: drivers/pinctrl/core.c:1181
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
**Symbols:**

```
ffffffff8156d960-ffffffff8156d979: pinctrl_release (STB_LOCAL)
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
