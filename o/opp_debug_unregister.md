# Function: <code>opp_debug_unregister</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff817d6570)
Location: drivers/opp/debugfs.c:222
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff817d6570-ffffffff817d667e: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff8181f260)
Location: drivers/opp/debugfs.c:233
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff8181f260-ffffffff8181f370: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff8184b100)
Location: drivers/opp/debugfs.c:233
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff8184b100-ffffffff8184b210: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/debugfs.c (0)
Location: drivers/opp/debugfs.c:182
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff8188e293-ffffffff8188e2ce: opp_debug_unregister.cold (STB_LOCAL)
ffffffff8188e1c0-ffffffff8188e293: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/debugfs.c (0)
Location: drivers/opp/debugfs.c:182
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff818c0423-ffffffff818c045e: opp_debug_unregister.cold (STB_LOCAL)
ffffffff818c0350-ffffffff818c0423: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81992340)
Location: drivers/opp/debugfs.c:224
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff81992340-ffffffff819923ab: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff819955d0)
Location: drivers/opp/debugfs.c:224
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff819955d0-ffffffff8199563b: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/debugfs.c (0)
Location: drivers/opp/debugfs.c:224
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff81c1ba0a-ffffffff81c1ba46: opp_debug_unregister.cold (STB_LOCAL)
ffffffff8197a3d0-ffffffff8197a4a2: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/debugfs.c (0)
Location: drivers/opp/debugfs.c:224
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff81d2bd14-ffffffff81d2bd50: opp_debug_unregister.cold (STB_LOCAL)
ffffffff81a233e0-ffffffff81a234b2: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/debugfs.c (0)
Location: drivers/opp/debugfs.c:236
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff81ef7f29-ffffffff81ef7f64: opp_debug_unregister.cold (STB_LOCAL)
ffffffff81b8c640-ffffffff81b8c72f: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81d2bff0)
Location: drivers/opp/debugfs.c:255
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff81d2bff0-ffffffff81d2c115: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81d95280)
Location: drivers/opp/debugfs.c:254
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff81d95280-ffffffff81d953a3: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81e4cd90)
Location: drivers/opp/debugfs.c:254
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_table_kref_release
```
**Symbols:**

```
ffffffff81e4cd90-ffffffff81e4ceb3: opp_debug_unregister (STB_GLOBAL)
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
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffff800010b1cc88)
Location: drivers/opp/debugfs.c:182
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffff800010b1cc88-ffff800010b1cdb4: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (c0bf73f0)
Location: drivers/opp/debugfs.c:182
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
c0bf73f0-c0bf7520: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (c000000000c0f650)
Location: drivers/opp/debugfs.c:182
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
c000000000c0f650-c000000000c0f824: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffe000704bde)
Location: drivers/opp/debugfs.c:182
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffe000704bde-ffffffe000704cdc: opp_debug_unregister (STB_GLOBAL)
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
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/debugfs.c (0)
Location: drivers/opp/debugfs.c:182
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff81864b43-ffffffff81864b7e: opp_debug_unregister.cold (STB_LOCAL)
ffffffff81864a70-ffffffff81864b43: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/debugfs.c (0)
Location: drivers/opp/debugfs.c:182
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff8182d7f3-ffffffff8182d82e: opp_debug_unregister.cold (STB_LOCAL)
ffffffff8182d720-ffffffff8182d7f3: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/debugfs.c (0)
Location: drivers/opp/debugfs.c:182
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff818b58d3-ffffffff818b590e: opp_debug_unregister.cold (STB_LOCAL)
ffffffff818b5800-ffffffff818b58d3: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void opp_debug_unregister(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/debugfs.c (0)
Location: drivers/opp/debugfs.c:182
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_put_opp_table
```
**Symbols:**

```
ffffffff818d1b83-ffffffff818d1bbe: opp_debug_unregister.cold (STB_LOCAL)
ffffffff818d1ab0-ffffffff818d1b83: opp_debug_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
