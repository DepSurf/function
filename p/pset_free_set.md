# Function: <code>pset_free_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pset_free_set(struct property_set *pset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551220)
Location: drivers/base/property.c:684
Inline: False
Direct callers:
  - drivers/base/property.c:device_remove_property_set
  - drivers/base/property.c:device_add_property_set
```
**Symbols:**

```
ffffffff81551220-ffffffff815512d7: pset_free_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pset_free_set(struct property_set *pset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a3120)
Location: drivers/base/property.c:692
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff815a3120-ffffffff815a31d7: pset_free_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pset_free_set(struct property_set *pset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d1830)
Location: drivers/base/property.c:692
Inline: False
Direct callers:
  - drivers/base/property.c:device_add_properties
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_remove_properties
```
**Symbols:**

```
ffffffff815d1830-ffffffff815d18e7: pset_free_set (STB_LOCAL)
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
In drivers/base/property.c (ffffffff815e6d0a)
Location: drivers/base/property.c:809
Inline: True
Inline callers:
  - drivers/base/property.c:device_remove_properties
  - drivers/base/property.c:device_remove_properties
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
In drivers/base/property.c (ffffffff8164d8f9)
Location: drivers/base/property.c:850
Inline: True
Inline callers:
  - drivers/base/property.c:device_remove_properties
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
In drivers/base/property.c (ffffffff816892e9)
Location: drivers/base/property.c:910
Inline: True
Inline callers:
  - drivers/base/property.c:device_remove_properties
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
