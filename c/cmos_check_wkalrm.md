# Function: <code>cmos_check_wkalrm</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff817083f2)
Location: drivers/rtc/rtc-cmos.c:981
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/rtc/rtc-cmos.c (ffffffff8171e012)
Location: drivers/rtc/rtc-cmos.c:984
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/rtc/rtc-cmos.c (ffffffff8178f295)
Location: drivers/rtc/rtc-cmos.c:984
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/rtc/rtc-cmos.c (ffffffff817d1ac3)
Location: drivers/rtc/rtc-cmos.c:1014
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/rtc/rtc-cmos.c (ffffffff817f8c15)
Location: drivers/rtc/rtc-cmos.c:1035
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/rtc/rtc-cmos.c (ffffffff81839832)
Location: drivers/rtc/rtc-cmos.c:1031
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/rtc/rtc-cmos.c (ffffffff8186b1a2)
Location: drivers/rtc/rtc-cmos.c:1031
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cmos_check_wkalrm(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff8193ee10)
Location: drivers/rtc/rtc-cmos.c:1032
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff8193ee10-ffffffff8193eed0: cmos_check_wkalrm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cmos_check_wkalrm(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff81944970)
Location: drivers/rtc/rtc-cmos.c:1042
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff81944970-ffffffff81944a5c: cmos_check_wkalrm (STB_LOCAL)
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
In drivers/rtc/rtc-cmos.c (ffffffff819281e1)
Location: drivers/rtc/rtc-cmos.c:1035
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/rtc/rtc-cmos.c (ffffffff819cba2a)
Location: drivers/rtc/rtc-cmos.c:1032
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cmos_check_wkalrm(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:1088
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff81b2c860-ffffffff81b2c9c9: cmos_check_wkalrm (STB_LOCAL)
ffffffff81ef110c-ffffffff81ef1121: cmos_check_wkalrm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cmos_check_wkalrm(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:1268
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff81cc06c0-ffffffff81cc082d: cmos_check_wkalrm (STB_LOCAL)
ffffffff820a74f7-ffffffff820a750c: cmos_check_wkalrm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cmos_check_wkalrm(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:1268
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff81d28020-ffffffff81d2818d: cmos_check_wkalrm (STB_LOCAL)
ffffffff821288fa-ffffffff8212890f: cmos_check_wkalrm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cmos_check_wkalrm(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:1285
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
**Symbols:**

```
ffffffff81ddde40-ffffffff81dddfad: cmos_check_wkalrm (STB_LOCAL)
ffffffff8220a28c-ffffffff8220a2a1: cmos_check_wkalrm.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff8181de52)
Location: drivers/rtc/rtc-cmos.c:1031
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff817e5502)
Location: drivers/rtc/rtc-cmos.c:1031
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/rtc/rtc-cmos.c (ffffffff8185f332)
Location: drivers/rtc/rtc-cmos.c:1031
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
In drivers/rtc/rtc-cmos.c (ffffffff8187a1b2)
Location: drivers/rtc/rtc-cmos.c:1031
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
