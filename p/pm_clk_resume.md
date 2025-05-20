# Function: <code>pm_clk_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff8155d6c0)
Location: drivers/base/power/clock_ops.c:293
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff8155d6c0-ffffffff8155d7a0: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff815b1350)
Location: drivers/base/power/clock_ops.c:424
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff815b1350-ffffffff815b1435: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff815e0630)
Location: drivers/base/power/clock_ops.c:424
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff815e0630-ffffffff815e0715: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff815f54d0)
Location: drivers/base/power/clock_ops.c:424
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff815f54d0-ffffffff815f5595: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff8165d3f0)
Location: drivers/base/power/clock_ops.c:424
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff8165d3f0-ffffffff8165d4b5: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff81699130)
Location: drivers/base/power/clock_ops.c:424
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff81699130-ffffffff81699206: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff816b9990)
Location: drivers/base/power/clock_ops.c:424
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff816b9990-ffffffff816b9a66: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:426
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff816f4350-ffffffff816f4372: pm_clk_resume.cold (STB_LOCAL)
ffffffff816f3cb0-ffffffff816f3d69: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:426
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff81718750-ffffffff81718772: pm_clk_resume.cold (STB_LOCAL)
ffffffff817180b0-ffffffff81718169: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:426
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff817d42f0-ffffffff817d4312: pm_clk_resume.cold (STB_LOCAL)
ffffffff817d3be0-ffffffff817d3c99: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:426
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff81c0f0c2-ffffffff81c0f0e4: pm_clk_resume.cold (STB_LOCAL)
ffffffff817e8630-ffffffff817e86e9: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff817ccec0)
Location: drivers/base/power/clock_ops.c:564
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff817ccec0-ffffffff817cd01f: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff818574a0)
Location: drivers/base/power/clock_ops.c:581
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff818574a0-ffffffff818575ff: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff8199df10)
Location: drivers/base/power/clock_ops.c:581
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff8199df10-ffffffff8199e085: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff81b0f720)
Location: drivers/base/power/clock_ops.c:581
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff81b0f720-ffffffff81b0f88f: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff81b5d7e0)
Location: drivers/base/power/clock_ops.c:581
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff81b5d7e0-ffffffff81b5d94f: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffff81bb10c0)
Location: drivers/base/power/clock_ops.c:581
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff81bb10c0-ffffffff81bb122f: pm_clk_resume (STB_GLOBAL)
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
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffff80001090b770)
Location: drivers/base/power/clock_ops.c:426
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffff80001090b770-ffff80001090b8e0: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (c09f4c30)
Location: drivers/base/power/clock_ops.c:426
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
c09f4c30-c09f4d58: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/clock_ops.c (ffffffe000590bd4)
Location: drivers/base/power/clock_ops.c:426
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffe000590bd4-ffffffe000590ce4: pm_clk_resume (STB_GLOBAL)
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
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:426
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff816dea80-ffffffff816deaa2: pm_clk_resume.cold (STB_LOCAL)
ffffffff816de3e0-ffffffff816de499: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:426
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff816b90ba-ffffffff816b90dc: pm_clk_resume.cold (STB_LOCAL)
ffffffff816b8a40-ffffffff816b8af9: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:426
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff8170c410-ffffffff8170c432: pm_clk_resume.cold (STB_LOCAL)
ffffffff8170bd70-ffffffff8170be29: pm_clk_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pm_clk_resume(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/clock_ops.c (0)
Location: drivers/base/power/clock_ops.c:426
Inline: False
Direct callers:
  - drivers/base/power/clock_ops.c:pm_clk_runtime_resume
```
**Symbols:**

```
ffffffff81726de3-ffffffff81726e05: pm_clk_resume.cold (STB_LOCAL)
ffffffff81726ba0-ffffffff81726c59: pm_clk_resume (STB_GLOBAL)
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
