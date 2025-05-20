# Function: <code>property_entry_free_data</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6510)
Location: drivers/base/property.c:733
Inline: False
Direct callers:
  - drivers/base/property.c:property_entries_free
  - drivers/base/property.c:property_entries_dup
```
**Symbols:**

```
ffffffff815e6510-ffffffff815e6580: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d7e0)
Location: drivers/base/property.c:774
Inline: False
Direct callers:
  - drivers/base/property.c:property_entries_free
  - drivers/base/property.c:property_entries_dup
```
**Symbols:**

```
ffffffff8164d7e0-ffffffff8164d850: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816891b0)
Location: drivers/base/property.c:762
Inline: False
Direct callers:
  - drivers/base/property.c:property_entries_free
  - drivers/base/property.c:property_entries_dup
  - drivers/base/property.c:property_entries_dup
```
**Symbols:**

```
ffffffff816891b0-ffffffff81689239: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816aa0e0)
Location: drivers/base/swnode.c:283
Inline: False
Direct callers:
  - drivers/base/swnode.c:property_entries_dup
  - drivers/base/swnode.c:property_entries_dup
```
**Symbols:**

```
ffffffff816aa0e0-ffffffff816aa169: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e3ae0)
Location: drivers/base/swnode.c:322
Inline: False
```
**Symbols:**

```
ffffffff816e3ae0-ffffffff816e3b65: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81707cd0)
Location: drivers/base/swnode.c:322
Inline: False
```
**Symbols:**

```
ffffffff81707cd0-ffffffff81707d55: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c2a50)
Location: drivers/base/swnode.c:199
Inline: False
Direct callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:property_entry_copy_data
```
**Symbols:**

```
ffffffff817c2a50-ffffffff817c2ad5: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d7860)
Location: drivers/base/swnode.c:199
Inline: False
Direct callers:
  - drivers/base/swnode.c:swnode_register
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:property_entry_copy_data
```
**Symbols:**

```
ffffffff817d7860-ffffffff817d78e5: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bb440)
Location: drivers/base/swnode.c:213
Inline: False
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:property_entry_copy_data
```
**Symbols:**

```
ffffffff817bb440-ffffffff817bb4c8: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:215
Inline: False
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:property_entry_copy_data
```
**Symbols:**

```
ffffffff81845930-ffffffff818459c8: property_entry_free_data (STB_LOCAL)
ffffffff81d033f3-ffffffff81d03420: property_entry_free_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:215
Inline: False
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:property_entry_copy_data
```
**Symbols:**

```
ffffffff81989c00-ffffffff81989cb3: property_entry_free_data (STB_LOCAL)
ffffffff81ecbb36-ffffffff81ecbb63: property_entry_free_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:215
Inline: False
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:property_entry_copy_data
```
**Symbols:**

```
ffffffff81af8f60-ffffffff81af9013: property_entry_free_data (STB_LOCAL)
ffffffff8209879e-ffffffff820987cb: property_entry_free_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:215
Inline: False
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:property_entry_copy_data
```
**Symbols:**

```
ffffffff81b474d0-ffffffff81b47583: property_entry_free_data (STB_LOCAL)
ffffffff82119795-ffffffff821197c2: property_entry_free_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:215
Inline: False
Direct callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:software_node_release
  - drivers/base/swnode.c:property_entry_copy_data
```
**Symbols:**

```
ffffffff81b9f860-ffffffff81b9f913: property_entry_free_data (STB_LOCAL)
ffffffff821f7757-ffffffff821f7784: property_entry_free_data.cold (STB_LOCAL)
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
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f56d8)
Location: drivers/base/swnode.c:322
Inline: False
```
**Symbols:**

```
ffff8000108f56d8-ffff8000108f5798: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e1b20)
Location: drivers/base/swnode.c:322
Inline: False
```
**Symbols:**

```
c09e1b20-c09e1bc0: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c0000000009901a0)
Location: drivers/base/swnode.c:322
Inline: False
```
**Symbols:**

```
c0000000009901a0-c0000000009902c8: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe000586942)
Location: drivers/base/swnode.c:322
Inline: False
```
**Symbols:**

```
ffffffe000586942-ffffffe0005869dc: property_entry_free_data (STB_LOCAL)
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
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816cd420)
Location: drivers/base/swnode.c:322
Inline: False
```
**Symbols:**

```
ffffffff816cd420-ffffffff816cd4a5: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a8750)
Location: drivers/base/swnode.c:322
Inline: False
```
**Symbols:**

```
ffffffff816a8750-ffffffff816a87d5: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fb990)
Location: drivers/base/swnode.c:322
Inline: False
```
**Symbols:**

```
ffffffff816fb990-ffffffff816fba15: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void property_entry_free_data(const struct property_entry *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81716310)
Location: drivers/base/swnode.c:322
Inline: False
```
**Symbols:**

```
ffffffff81716310-ffffffff81716395: property_entry_free_data (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
