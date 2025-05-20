# Function: <code>__hwmon_sanitize_name</code>

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
char *__hwmon_sanitize_name(struct device *dev, const char *old_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81b44a60)
Location: drivers/hwmon/hwmon.c:1083
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:devm_hwmon_sanitize_name
  - drivers/hwmon/hwmon.c:hwmon_sanitize_name
```
**Symbols:**

```
ffffffff81b44a60-ffffffff81b44ae0: __hwmon_sanitize_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *__hwmon_sanitize_name(struct device *dev, const char *old_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81cdbb50)
Location: drivers/hwmon/hwmon.c:1084
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:devm_hwmon_sanitize_name
  - drivers/hwmon/hwmon.c:hwmon_sanitize_name
```
**Symbols:**

```
ffffffff81cdbb50-ffffffff81cdbbd0: __hwmon_sanitize_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *__hwmon_sanitize_name(struct device *dev, const char *old_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81d43eb0)
Location: drivers/hwmon/hwmon.c:1091
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:devm_hwmon_sanitize_name
  - drivers/hwmon/hwmon.c:hwmon_sanitize_name
```
**Symbols:**

```
ffffffff81d43eb0-ffffffff81d43f30: __hwmon_sanitize_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *__hwmon_sanitize_name(struct device *dev, const char *old_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81dfa880)
Location: drivers/hwmon/hwmon.c:1091
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:devm_hwmon_sanitize_name
  - drivers/hwmon/hwmon.c:hwmon_sanitize_name
```
**Symbols:**

```
ffffffff81dfa880-ffffffff81dfa900: __hwmon_sanitize_name (STB_LOCAL)
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
