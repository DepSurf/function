# Function: <code>add_numbered_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff816f5175)
Location: drivers/mfd/twl-core.c:609
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
**Symbols:**

```
ffffffff816f5175-ffffffff816f5384: add_numbered_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81759d67)
Location: drivers/mfd/twl-core.c:609
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
**Symbols:**

```
ffffffff81759d67-ffffffff81759f50: add_numbered_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81786260)
Location: drivers/mfd/twl-core.c:608
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
**Symbols:**

```
ffffffff81786260-ffffffff81786449: add_numbered_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff8161d220)
Location: drivers/mfd/twl-core.c:608
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
**Symbols:**

```
ffffffff8161d220-ffffffff8161d425: add_numbered_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81685a60)
Location: drivers/mfd/twl-core.c:608
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
**Symbols:**

```
ffffffff81685a60-ffffffff81685c65: add_numbered_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:608
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
**Symbols:**

```
ffffffff816c1bb0-ffffffff816c1d77: add_numbered_child (STB_LOCAL)
ffffffff816c23de-ffffffff816c23ff: add_numbered_child.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:608
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
**Symbols:**

```
ffffffff816e2ff0-ffffffff816e31b7: add_numbered_child (STB_LOCAL)
ffffffff816e3fd7-ffffffff816e3ff8: add_numbered_child.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
```
**Symbols:**

```
ffffffff8171c670-ffffffff8171c857: add_numbered_child (STB_LOCAL)
ffffffff8171d5df-ffffffff8171d5fd: add_numbered_child.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
```
**Symbols:**

```
ffffffff81740940-ffffffff81740b27: add_numbered_child (STB_LOCAL)
ffffffff817418b2-ffffffff817418d0: add_numbered_child.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
```
**Symbols:**

```
ffffffff817fe7f0-ffffffff817fe9ca: add_numbered_child (STB_LOCAL)
ffffffff817ff4d4-ffffffff817ff4f5: add_numbered_child.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
```
**Symbols:**

```
ffffffff8180fc20-ffffffff8180fdfa: add_numbered_child (STB_LOCAL)
ffffffff81c130df-ffffffff81c13100: add_numbered_child.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
```
**Symbols:**

```
ffffffff817f4260-ffffffff817f443a: add_numbered_child (STB_LOCAL)
ffffffff81c051cf-ffffffff81c051f0: add_numbered_child.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
```
**Symbols:**

```
ffffffff8187d090-ffffffff8187d261: add_numbered_child (STB_LOCAL)
ffffffff81d08456-ffffffff81d08477: add_numbered_child.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
```
**Symbols:**

```
ffffffff819c54d0-ffffffff819c56b7: add_numbered_child (STB_LOCAL)
ffffffff81ed08f1-ffffffff81ed0912: add_numbered_child.cold (STB_LOCAL)
```
</details>
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
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffff80001093c0c8)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
```
**Symbols:**

```
ffff80001093c0c8-ffff80001093c2d0: add_numbered_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (c0a24914)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_regulator_linked
```
**Symbols:**

```
c0a24914-c0a24b10: add_numbered_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (c0000000009e3a70)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
```
**Symbols:**

```
c0000000009e3a70-c0000000009e3cf0: add_numbered_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffe0005b05ae)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
```
**Symbols:**

```
ffffffe0005b05ae-ffffffe0005b0798: add_numbered_child (STB_LOCAL)
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
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
```
**Symbols:**

```
ffffffff81733e00-ffffffff81733fe7: add_numbered_child (STB_LOCAL)
ffffffff81734d72-ffffffff81734d90: add_numbered_child.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct device *add_numbered_child(unsigned int mod_no, const char *name, int num, void *pdata, unsigned int pdata_len, bool can_wakeup, int irq0, int irq1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:595
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
  - drivers/mfd/twl-core.c:add_children
```
**Symbols:**

```
ffffffff8174f240-ffffffff8174f427: add_numbered_child (STB_LOCAL)
ffffffff817501b2-ffffffff817501d0: add_numbered_child.cold (STB_LOCAL)
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
