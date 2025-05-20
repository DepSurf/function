# Function: <code>hwmon_genattrs</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81714263)
Location: drivers/hwmon/hwmon.c:470
Inline: True
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
In drivers/hwmon/hwmon.c (ffffffff8172c726)
Location: drivers/hwmon/hwmon.c:470
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
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
In drivers/hwmon/hwmon.c (ffffffff8179def6)
Location: drivers/hwmon/hwmon.c:477
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
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
In drivers/hwmon/hwmon.c (ffffffff817e52cb)
Location: drivers/hwmon/hwmon.c:477
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
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
In drivers/hwmon/hwmon.c (ffffffff81810d5e)
Location: drivers/hwmon/hwmon.c:495
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
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
In drivers/hwmon/hwmon.c (ffffffff81852c25)
Location: drivers/hwmon/hwmon.c:495
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
In drivers/hwmon/hwmon.c (ffffffff818847e0)
Location: drivers/hwmon/hwmon.c:511
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hwmon_genattrs(const void *drvdata, struct attribute **attrs, const struct hwmon_ops *ops, const struct hwmon_channel_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81952fb0)
Location: drivers/hwmon/hwmon.c:616
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
**Symbols:**

```
ffffffff81952fb0-ffffffff81953251: hwmon_genattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hwmon_genattrs(const void *drvdata, struct attribute **attrs, const struct hwmon_ops *ops, const struct hwmon_channel_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81957e20)
Location: drivers/hwmon/hwmon.c:626
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
**Symbols:**

```
ffffffff81957e20-ffffffff819580c1: hwmon_genattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hwmon_genattrs(const void *drvdata, struct attribute **attrs, const struct hwmon_ops *ops, const struct hwmon_channel_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8193ba60)
Location: drivers/hwmon/hwmon.c:626
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff8193ba60-ffffffff8193bcfe: hwmon_genattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hwmon_genattrs(const void *drvdata, struct attribute **attrs, const struct hwmon_ops *ops, const struct hwmon_channel_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:664
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff819e0290-ffffffff819e057d: hwmon_genattrs (STB_LOCAL)
ffffffff81d26bf3-ffffffff81d26c38: hwmon_genattrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hwmon_genattrs(const void *drvdata, struct attribute **attrs, const struct hwmon_ops *ops, const struct hwmon_channel_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:683
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81b44f80-ffffffff81b45278: hwmon_genattrs (STB_LOCAL)
ffffffff81ef2a2e-ffffffff81ef2a74: hwmon_genattrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hwmon_genattrs(const void *drvdata, struct attribute **attrs, const struct hwmon_ops *ops, const struct hwmon_channel_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:684
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81cdc100-ffffffff81cdc3f8: hwmon_genattrs (STB_LOCAL)
ffffffff820a79c6-ffffffff820a7a0c: hwmon_genattrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hwmon_genattrs(const void *drvdata, struct attribute **attrs, const struct hwmon_ops *ops, const struct hwmon_channel_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwmon/hwmon.c (0)
Location: drivers/hwmon/hwmon.c:688
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81d445e0-ffffffff81d448ce: hwmon_genattrs (STB_LOCAL)
ffffffff82128de6-ffffffff82128e2c: hwmon_genattrs.cold (STB_LOCAL)
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
In drivers/hwmon/hwmon.c (ffffffff81dfb472)
Location: drivers/hwmon/hwmon.c:688
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
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
In drivers/hwmon/hwmon.c (ffff800010ad14d8)
Location: drivers/hwmon/hwmon.c:511
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
In drivers/hwmon/hwmon.c (c0bb2240)
Location: drivers/hwmon/hwmon.c:511
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
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
In drivers/hwmon/hwmon.c (c000000000bb5fb0)
Location: drivers/hwmon/hwmon.c:511
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
In drivers/hwmon/hwmon.c (ffffffe0006cdea6)
Location: drivers/hwmon/hwmon.c:511
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
In drivers/hwmon/hwmon.c (ffffffff8182a660)
Location: drivers/hwmon/hwmon.c:511
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
In drivers/hwmon/hwmon.c (ffffffff817f1cf0)
Location: drivers/hwmon/hwmon.c:511
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
In drivers/hwmon/hwmon.c (ffffffff81879c90)
Location: drivers/hwmon/hwmon.c:511
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
In drivers/hwmon/hwmon.c (ffffffff81895690)
Location: drivers/hwmon/hwmon.c:511
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
</ul>
