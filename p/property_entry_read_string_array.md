# Function: <code>property_entry_read_string_array</code>

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
In drivers/base/swnode.c (ffffffff816aa260)
Location: drivers/base/swnode.c:246
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff816e3c4d)
Location: drivers/base/swnode.c:285
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff81707e3d)
Location: drivers/base/swnode.c:285
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff817c3513)
Location: drivers/base/swnode.c:169
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d84a6)
Location: drivers/base/swnode.c:169
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff817bbcfb)
Location: drivers/base/swnode.c:183
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff8184632b)
Location: drivers/base/swnode.c:185
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff8198a469)
Location: drivers/base/swnode.c:185
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int property_entry_read_string_array(const struct property_entry *props, const char *propname, const char **strings, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:185
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
```
**Symbols:**

```
ffffffff81af9820-ffffffff81af995a: property_entry_read_string_array (STB_LOCAL)
ffffffff8209885a-ffffffff8209886f: property_entry_read_string_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int property_entry_read_string_array(const struct property_entry *props, const char *propname, const char **strings, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:185
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
```
**Symbols:**

```
ffffffff81b47dd0-ffffffff81b47f0a: property_entry_read_string_array (STB_LOCAL)
ffffffff8211986c-ffffffff82119881: property_entry_read_string_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int property_entry_read_string_array(const struct property_entry *props, const char *propname, const char **strings, size_t nval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:185
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_read_string_array
```
**Symbols:**

```
ffffffff81ba0160-ffffffff81ba029a: property_entry_read_string_array (STB_LOCAL)
ffffffff821f782e-ffffffff821f7843: property_entry_read_string_array.cold (STB_LOCAL)
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
In drivers/base/swnode.c (ffff8000108f58d0)
Location: drivers/base/swnode.c:285
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (c09e1cd0)
Location: drivers/base/swnode.c:285
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (c000000000990624)
Location: drivers/base/swnode.c:285
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffe000586ae8)
Location: drivers/base/swnode.c:285
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff816cd58d)
Location: drivers/base/swnode.c:285
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff816a88bd)
Location: drivers/base/swnode.c:285
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff816fbafd)
Location: drivers/base/swnode.c:285
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
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
In drivers/base/swnode.c (ffffffff8171647d)
Location: drivers/base/swnode.c:285
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_read_string_array
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
