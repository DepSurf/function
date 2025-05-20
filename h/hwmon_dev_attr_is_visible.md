# Function: <code>hwmon_dev_attr_is_visible</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
umode_t hwmon_dev_attr_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81b44540)
Location: drivers/hwmon/hwmon.c:89
Inline: False
```
**Symbols:**

```
ffffffff81b44540-ffffffff81b44589: hwmon_dev_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
umode_t hwmon_dev_attr_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81cdb580)
Location: drivers/hwmon/hwmon.c:90
Inline: False
```
**Symbols:**

```
ffffffff81cdb580-ffffffff81cdb5c9: hwmon_dev_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
umode_t hwmon_dev_attr_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81d438e0)
Location: drivers/hwmon/hwmon.c:90
Inline: False
```
**Symbols:**

```
ffffffff81d438e0-ffffffff81d43929: hwmon_dev_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
umode_t hwmon_dev_attr_is_visible(struct kobject *kobj, struct attribute *attr, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81dfa2b0)
Location: drivers/hwmon/hwmon.c:90
Inline: False
```
**Symbols:**

```
ffffffff81dfa2b0-ffffffff81dfa2f9: hwmon_dev_attr_is_visible (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
