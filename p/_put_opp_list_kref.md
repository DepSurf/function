# Function: <code>_put_opp_list_kref</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void _put_opp_list_kref(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8184a150)
Location: drivers/opp/core.c:973
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
**Symbols:**

```
ffffffff8184a150-ffffffff8184a188: _put_opp_list_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _put_opp_list_kref(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188cfc0)
Location: drivers/opp/core.c:1047
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
**Symbols:**

```
ffffffff8188cfc0-ffffffff8188cffa: _put_opp_list_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _put_opp_list_kref(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bf200)
Location: drivers/opp/core.c:1096
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
**Symbols:**

```
ffffffff818bf200-ffffffff818bf23a: _put_opp_list_kref (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
void _put_opp_list_kref(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b1a4c0)
Location: drivers/opp/core.c:1096
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
**Symbols:**

```
ffff800010b1a4c0-ffff800010b1a514: _put_opp_list_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _put_opp_list_kref(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf50b0)
Location: drivers/opp/core.c:1096
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
**Symbols:**

```
c0bf50b0-c0bf50f4: _put_opp_list_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _put_opp_list_kref(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0c1d0)
Location: drivers/opp/core.c:1096
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
**Symbols:**

```
c000000000c0c1d0-c000000000c0c244: _put_opp_list_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _put_opp_list_kref(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000702c04)
Location: drivers/opp/core.c:1096
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
**Symbols:**

```
ffffffe000702c04-ffffffe000702c54: _put_opp_list_kref (STB_GLOBAL)
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
void _put_opp_list_kref(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81863920)
Location: drivers/opp/core.c:1096
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
**Symbols:**

```
ffffffff81863920-ffffffff8186395a: _put_opp_list_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _put_opp_list_kref(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182c5d0)
Location: drivers/opp/core.c:1096
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
**Symbols:**

```
ffffffff8182c5d0-ffffffff8182c60a: _put_opp_list_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _put_opp_list_kref(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b46b0)
Location: drivers/opp/core.c:1096
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
**Symbols:**

```
ffffffff818b46b0-ffffffff818b46ea: _put_opp_list_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _put_opp_list_kref(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818d0960)
Location: drivers/opp/core.c:1096
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
**Symbols:**

```
ffffffff818d0960-ffffffff818d099a: _put_opp_list_kref (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
