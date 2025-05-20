# Function: <code>opp_debug_create_bw</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void opp_debug_create_bw(struct dev_pm_opp *opp, struct opp_table *opp_table, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff81991e20)
Location: drivers/opp/debugfs.c:53
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81991e20-ffffffff81991f27: opp_debug_create_bw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void opp_debug_create_bw(struct dev_pm_opp *opp, struct opp_table *opp_table, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/debugfs.c (ffffffff819950b0)
Location: drivers/opp/debugfs.c:53
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff819950b0-ffffffff819951b7: opp_debug_create_bw (STB_LOCAL)
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
In drivers/opp/debugfs.c (ffffffff8197a25f)
Location: drivers/opp/debugfs.c:53
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff81a2326f)
Location: drivers/opp/debugfs.c:53
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff81b8c4a6)
Location: drivers/opp/debugfs.c:54
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff81d2be16)
Location: drivers/opp/debugfs.c:54
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff81d9509e)
Location: drivers/opp/debugfs.c:54
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In drivers/opp/debugfs.c (ffffffff81e4cbae)
Location: drivers/opp/debugfs.c:54
Inline: True
Inline callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
