# Function: <code>regulator_summary_lock</code>

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
In drivers/regulator/core.c (ffffffff816233a3)
Location: drivers/regulator/core.c:5431
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffffffff81655553)
Location: drivers/regulator/core.c:5548
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffffffff81677a83)
Location: drivers/regulator/core.c:5576
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void regulator_summary_lock(struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81728270)
Location: drivers/regulator/core.c:5615
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show
```
**Symbols:**

```
ffffffff81728270-ffffffff817283a4: regulator_summary_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void regulator_summary_lock(struct ww_acquire_ctx *ww_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff81744e20)
Location: drivers/regulator/core.c:5773
Inline: False
Direct callers:
  - drivers/regulator/core.c:regulator_summary_show
```
**Symbols:**

```
ffffffff81744e20-ffffffff81744f54: regulator_summary_lock (STB_LOCAL)
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
In drivers/regulator/core.c (ffffffff81728803)
Location: drivers/regulator/core.c:5777
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffffffff817a8e67)
Location: drivers/regulator/core.c:5915
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffffffff818e35bf)
Location: drivers/regulator/core.c:5980
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffffffff81a386ff)
Location: drivers/regulator/core.c:6037
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffffffff81a822cf)
Location: drivers/regulator/core.c:6101
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffffffff81ad48af)
Location: drivers/regulator/core.c:6156
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffff8000108420b8)
Location: drivers/regulator/core.c:5576
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (c094c828)
Location: drivers/regulator/core.c:5576
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (c0000000008da9a8)
Location: drivers/regulator/core.c:5576
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffffffe0005229e0)
Location: drivers/regulator/core.c:5576
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffffffff8163d773)
Location: drivers/regulator/core.c:5576
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffffffff8161d963)
Location: drivers/regulator/core.c:5576
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffffffff8166b8c3)
Location: drivers/regulator/core.c:5576
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
In drivers/regulator/core.c (ffffffff81685e83)
Location: drivers/regulator/core.c:5576
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
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
</ul>
