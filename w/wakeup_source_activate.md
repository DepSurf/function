# Function: <code>wakeup_source_activate</code>

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
In drivers/base/power/wakeup.c (ffffffff8155bab1)
Location: drivers/base/power/wakeup.c:522
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
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
In drivers/base/power/wakeup.c (ffffffff815adcc1)
Location: drivers/base/power/wakeup.c:520
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
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
In drivers/base/power/wakeup.c (ffffffff815dca91)
Location: drivers/base/power/wakeup.c:520
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
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
In drivers/base/power/wakeup.c (ffffffff815f1c47)
Location: drivers/base/power/wakeup.c:522
Inline: True
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
In drivers/base/power/wakeup.c (ffffffff816591f7)
Location: drivers/base/power/wakeup.c:523
Inline: True
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
In drivers/base/power/wakeup.c (ffffffff81694ed8)
Location: drivers/base/power/wakeup.c:522
Inline: True
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
In drivers/base/power/wakeup.c (ffffffff816b5578)
Location: drivers/base/power/wakeup.c:528
Inline: True
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
In drivers/base/power/wakeup.c (ffffffff816ef118)
Location: drivers/base/power/wakeup.c:512
Inline: True
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
In drivers/base/power/wakeup.c (ffffffff81713278)
Location: drivers/base/power/wakeup.c:532
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wakeup_source_activate(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817ce5e0)
Location: drivers/base/power/wakeup.c:591
Inline: False
```
**Symbols:**

```
ffffffff817ce5e0-ffffffff817ce6a8: wakeup_source_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wakeup_source_activate(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e3250)
Location: drivers/base/power/wakeup.c:591
Inline: False
```
**Symbols:**

```
ffffffff817e3250-ffffffff817e32f8: wakeup_source_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wakeup_source_activate(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c7610)
Location: drivers/base/power/wakeup.c:592
Inline: False
```
**Symbols:**

```
ffffffff817c7610-ffffffff817c76b8: wakeup_source_activate (STB_LOCAL)
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
In drivers/base/power/wakeup.c (ffffffff81851c73)
Location: drivers/base/power/wakeup.c:593
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void wakeup_source_activate(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:593
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
**Symbols:**

```
ffffffff819970a0-ffffffff81997182: wakeup_source_activate (STB_LOCAL)
ffffffff81ecc735-ffffffff81ecc749: wakeup_source_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void wakeup_source_activate(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:563
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
**Symbols:**

```
ffffffff81b08780-ffffffff81b08862: wakeup_source_activate (STB_LOCAL)
ffffffff82098980-ffffffff82098994: wakeup_source_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void wakeup_source_activate(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:558
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
**Symbols:**

```
ffffffff81b567b0-ffffffff81b56882: wakeup_source_activate (STB_LOCAL)
ffffffff8211994c-ffffffff82119960: wakeup_source_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void wakeup_source_activate(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (0)
Location: drivers/base/power/wakeup.c:558
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
**Symbols:**

```
ffffffff81baeda0-ffffffff81baee72: wakeup_source_activate (STB_LOCAL)
ffffffff821f790e-ffffffff821f7922: wakeup_source_activate.cold (STB_LOCAL)
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
In drivers/base/power/wakeup.c (ffff800010903cbc)
Location: drivers/base/power/wakeup.c:532
Inline: True
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
In drivers/base/power/wakeup.c (c09edda8)
Location: drivers/base/power/wakeup.c:532
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_report_event
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
In drivers/base/power/wakeup.c (c0000000009a2a30)
Location: drivers/base/power/wakeup.c:532
Inline: True
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d95ff)
Location: drivers/base/power/wakeup.c:532
Inline: True
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
In drivers/base/power/wakeup.c (ffffffff816b3c38)
Location: drivers/base/power/wakeup.c:532
Inline: True
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
In drivers/base/power/wakeup.c (ffffffff81706f38)
Location: drivers/base/power/wakeup.c:532
Inline: True
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
In drivers/base/power/wakeup.c (ffffffff81721968)
Location: drivers/base/power/wakeup.c:532
Inline: True
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
