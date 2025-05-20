# Function: <code>genpd_syscore_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815affe0)
Location: drivers/base/power/domain.c:955
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffffffff815affe0-ffffffff815b006d: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815def10)
Location: drivers/base/power/domain.c:1065
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffffffff815def10-ffffffff815def99: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f3b20)
Location: drivers/base/power/domain.c:1147
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffffffff815f3b20-ffffffff815f3bb0: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165b950)
Location: drivers/base/power/domain.c:1270
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffffffff8165b950-ffffffff8165b9e0: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81697620)
Location: drivers/base/power/domain.c:1276
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffffffff81697620-ffffffff816976be: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b8300)
Location: drivers/base/power/domain.c:1355
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffffffff816b8300-ffffffff816b839e: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816f2050)
Location: drivers/base/power/domain.c:1358
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffffffff816f2050-ffffffff816f20ee: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817167d0)
Location: drivers/base/power/domain.c:1353
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffffffff817167d0-ffffffff8171686e: genpd_syscore_switch (STB_LOCAL)
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
In drivers/base/power/domain.c (ffffffff817d2565)
Location: drivers/base/power/domain.c:1342
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010908f70)
Location: drivers/base/power/domain.c:1353
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffff800010908f70-ffff800010909028: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f2a84)
Location: drivers/base/power/domain.c:1353
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
c09f2a84-c09f2b24: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a7e50)
Location: drivers/base/power/domain.c:1353
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
c0000000009a7e50-c0000000009a7f70: genpd_syscore_switch (STB_LOCAL)
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
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816dcb00)
Location: drivers/base/power/domain.c:1353
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffffffff816dcb00-ffffffff816dcb9e: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b7180)
Location: drivers/base/power/domain.c:1353
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffffffff816b7180-ffffffff816b721e: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8170a490)
Location: drivers/base/power/domain.c:1353
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffffffff8170a490-ffffffff8170a52e: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void genpd_syscore_switch(struct device *dev, bool suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81725190)
Location: drivers/base/power/domain.c:1353
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweron
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
```
**Symbols:**

```
ffffffff81725190-ffffffff8172522e: genpd_syscore_switch (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
