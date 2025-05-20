# Function: <code>opp_migrate_dentry</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff817d65c5)
Location: drivers/opp/debugfs.c:185
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff8181f2b5)
Location: drivers/opp/debugfs.c:196
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff8184b155)
Location: drivers/opp/debugfs.c:196
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff8188e214)
Location: drivers/opp/debugfs.c:145
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff818c03a4)
Location: drivers/opp/debugfs.c:145
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void opp_migrate_dentry(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/debugfs.c (0)
Location: drivers/opp/debugfs.c:187
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff819920c0-ffffffff81992149: opp_migrate_dentry (STB_LOCAL)
ffffffff819923ab-ffffffff819923e7: opp_migrate_dentry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void opp_migrate_dentry(struct opp_device *opp_dev, struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/debugfs.c (0)
Location: drivers/opp/debugfs.c:187
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff81995350-ffffffff819953d9: opp_migrate_dentry (STB_LOCAL)
ffffffff81c29663-ffffffff81c2969f: opp_migrate_dentry.cold (STB_LOCAL)
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
In drivers/opp/debugfs.c (ffffffff8197a425)
Location: drivers/opp/debugfs.c:187
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff81a23435)
Location: drivers/opp/debugfs.c:187
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff81b8c6a5)
Location: drivers/opp/debugfs.c:195
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff81d2c055)
Location: drivers/opp/debugfs.c:214
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff81d952e5)
Location: drivers/opp/debugfs.c:213
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff81e4cdf5)
Location: drivers/opp/debugfs.c:213
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffff800010b1ccf0)
Location: drivers/opp/debugfs.c:145
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (c0bf7454)
Location: drivers/opp/debugfs.c:145
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (c000000000c0f6e8)
Location: drivers/opp/debugfs.c:145
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffe000704c3a)
Location: drivers/opp/debugfs.c:145
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff81864ac4)
Location: drivers/opp/debugfs.c:145
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff8182d774)
Location: drivers/opp/debugfs.c:145
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff818b5854)
Location: drivers/opp/debugfs.c:145
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
In drivers/opp/debugfs.c (ffffffff818d1b04)
Location: drivers/opp/debugfs.c:145
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
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
