# Function: <code>add_prop_uevent</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int add_prop_uevent(struct device *dev, struct kobj_uevent_env *env, enum power_supply_property prop, char *prop_buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff8194f480)
Location: drivers/power/supply/power_supply_sysfs.c:416
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff8194f480-ffffffff8194f510: add_prop_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int add_prop_uevent(struct device *dev, struct kobj_uevent_env *env, enum power_supply_property prop, char *prop_buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81954ea0)
Location: drivers/power/supply/power_supply_sysfs.c:421
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff81954ea0-ffffffff81954f30: add_prop_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int add_prop_uevent(struct device *dev, struct kobj_uevent_env *env, enum power_supply_property prop, char *prop_buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81938cd0)
Location: drivers/power/supply/power_supply_sysfs.c:421
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff81938cd0-ffffffff81938d60: add_prop_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int add_prop_uevent(struct device *dev, struct kobj_uevent_env *env, enum power_supply_property prop, char *prop_buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff819dd2e0)
Location: drivers/power/supply/power_supply_sysfs.c:421
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff819dd2e0-ffffffff819dd399: add_prop_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int add_prop_uevent(struct device *dev, struct kobj_uevent_env *env, enum power_supply_property prop, char *prop_buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81b418f0)
Location: drivers/power/supply/power_supply_sysfs.c:430
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff81b418f0-ffffffff81b419bc: add_prop_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int add_prop_uevent(const struct device *dev, struct kobj_uevent_env *env, enum power_supply_property prop, char *prop_buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81cd7f20)
Location: drivers/power/supply/power_supply_sysfs.c:430
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff81cd7f20-ffffffff81cd7fec: add_prop_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int add_prop_uevent(const struct device *dev, struct kobj_uevent_env *env, enum power_supply_property prop, char *prop_buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81d40070)
Location: drivers/power/supply/power_supply_sysfs.c:435
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff81d40070-ffffffff81d4013c: add_prop_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int add_prop_uevent(const struct device *dev, struct kobj_uevent_env *env, enum power_supply_property prop, char *prop_buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81df6a20)
Location: drivers/power/supply/power_supply_sysfs.c:429
Inline: True
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff81df6a20-ffffffff81df6aec: add_prop_uevent (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device *dev</code> ➡️ <code>const struct device *dev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
