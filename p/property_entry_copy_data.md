# Function: <code>property_entry_copy_data</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6da1)
Location: drivers/base/property.c:685
Inline: True
Inline callers:
  - drivers/base/property.c:property_entries_dup
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
In drivers/base/property.c (ffffffff8164e171)
Location: drivers/base/property.c:726
Inline: True
Inline callers:
  - drivers/base/property.c:property_entries_dup
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
In drivers/base/property.c (ffffffff8168995e)
Location: drivers/base/property.c:805
Inline: True
Inline callers:
  - drivers/base/property.c:property_entries_dup
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
In drivers/base/swnode.c (ffffffff816aa6dc)
Location: drivers/base/swnode.c:326
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entries_dup
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
In drivers/base/swnode.c (ffffffff816e4420)
Location: drivers/base/swnode.c:365
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
In drivers/base/swnode.c (ffffffff817083f0)
Location: drivers/base/swnode.c:365
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int property_entry_copy_data(struct property_entry *dst, const struct property_entry *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c2ae0)
Location: drivers/base/swnode.c:235
Inline: False
```
**Symbols:**

```
ffffffff817c2ae0-ffffffff817c2c83: property_entry_copy_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int property_entry_copy_data(struct property_entry *dst, const struct property_entry *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d78f0)
Location: drivers/base/swnode.c:235
Inline: False
```
**Symbols:**

```
ffffffff817d78f0-ffffffff817d7a93: property_entry_copy_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int property_entry_copy_data(struct property_entry *dst, const struct property_entry *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bb4d0)
Location: drivers/base/swnode.c:249
Inline: False
```
**Symbols:**

```
ffffffff817bb4d0-ffffffff817bb673: property_entry_copy_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int property_entry_copy_data(struct property_entry *dst, const struct property_entry *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:251
Inline: False
```
**Symbols:**

```
ffffffff818459d0-ffffffff81845bcc: property_entry_copy_data (STB_LOCAL)
ffffffff81d03420-ffffffff81d03477: property_entry_copy_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int property_entry_copy_data(struct property_entry *dst, const struct property_entry *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:251
Inline: False
```
**Symbols:**

```
ffffffff81989d00-ffffffff81989f21: property_entry_copy_data (STB_LOCAL)
ffffffff81ecbb63-ffffffff81ecbbdd: property_entry_copy_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int property_entry_copy_data(struct property_entry *dst, const struct property_entry *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:251
Inline: False
```
**Symbols:**

```
ffffffff81af91e0-ffffffff81af9401: property_entry_copy_data (STB_LOCAL)
ffffffff820987cb-ffffffff82098845: property_entry_copy_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int property_entry_copy_data(struct property_entry *dst, const struct property_entry *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:251
Inline: False
```
**Symbols:**

```
ffffffff81b47750-ffffffff81b479cf: property_entry_copy_data (STB_LOCAL)
ffffffff821197c2-ffffffff82119857: property_entry_copy_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int property_entry_copy_data(struct property_entry *dst, const struct property_entry *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (0)
Location: drivers/base/swnode.c:251
Inline: False
```
**Symbols:**

```
ffffffff81b9fae0-ffffffff81b9fd5f: property_entry_copy_data (STB_LOCAL)
ffffffff821f7784-ffffffff821f7819: property_entry_copy_data.cold (STB_LOCAL)
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
In drivers/base/swnode.c (ffff8000108f63c0)
Location: drivers/base/swnode.c:365
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
In drivers/base/swnode.c (c09e23f8)
Location: drivers/base/swnode.c:365
Inline: True
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
In drivers/base/swnode.c (c000000000991560)
Location: drivers/base/swnode.c:365
Inline: True
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
In drivers/base/swnode.c (ffffffe0005872de)
Location: drivers/base/swnode.c:365
Inline: True
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
In drivers/base/swnode.c (ffffffff816cdb40)
Location: drivers/base/swnode.c:365
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
In drivers/base/swnode.c (ffffffff816a8e70)
Location: drivers/base/swnode.c:365
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
In drivers/base/swnode.c (ffffffff816fc0b0)
Location: drivers/base/swnode.c:365
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
In drivers/base/swnode.c (ffffffff81716c50)
Location: drivers/base/swnode.c:365
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
