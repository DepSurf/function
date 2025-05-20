# Function: <code>scsi_dev_type_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff815b91bc)
Location: drivers/scsi/scsi_pm.c:51
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81611abc)
Location: drivers/scsi/scsi_pm.c:51
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8164134c)
Location: drivers/scsi/scsi_pm.c:51
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
In drivers/scsi/scsi_pm.c (ffffffff81655c2c)
Location: drivers/scsi/scsi_pm.c:51
Inline: True
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
In drivers/scsi/scsi_pm.c (ffffffff816bf1dc)
Location: drivers/scsi/scsi_pm.c:51
Inline: True
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
In drivers/scsi/scsi_pm.c (ffffffff816fb7fc)
Location: drivers/scsi/scsi_pm.c:51
Inline: True
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
In drivers/scsi/scsi_pm.c (ffffffff8171e1dc)
Location: drivers/scsi/scsi_pm.c:52
Inline: True
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
In drivers/scsi/scsi_pm.c (ffffffff8175990d)
Location: drivers/scsi/scsi_pm.c:53
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
In drivers/scsi/scsi_pm.c (ffffffff8177d81d)
Location: drivers/scsi/scsi_pm.c:53
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_dev_type_suspend(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81840b50)
Location: drivers/scsi/scsi_pm.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
**Symbols:**

```
ffffffff81840b50-ffffffff81840bed: scsi_dev_type_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_dev_type_suspend(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81851090)
Location: drivers/scsi/scsi_pm.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
**Symbols:**

```
ffffffff81851090-ffffffff8185112d: scsi_dev_type_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_dev_type_suspend(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81834120)
Location: drivers/scsi/scsi_pm.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
**Symbols:**

```
ffffffff81834120-ffffffff818341bd: scsi_dev_type_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_dev_type_suspend(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff818c0120)
Location: drivers/scsi/scsi_pm.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
**Symbols:**

```
ffffffff818c0120-ffffffff818c01ba: scsi_dev_type_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_dev_type_suspend(struct device *dev, int (*cb)(struct device *, const struct dev_pm_ops *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81a0c620)
Location: drivers/scsi/scsi_pm.c:52
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
**Symbols:**

```
ffffffff81a0c620-ffffffff81a0c6c3: scsi_dev_type_suspend (STB_LOCAL)
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
In drivers/scsi/scsi_pm.c (ffffffff81b8c2c5)
Location: drivers/scsi/scsi_pm.c:52
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
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
In drivers/scsi/scsi_pm.c (ffffffff81be04b5)
Location: drivers/scsi/scsi_pm.c:52
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
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
In drivers/scsi/scsi_pm.c (ffffffff81c354e5)
Location: drivers/scsi/scsi_pm.c:52
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
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
In drivers/scsi/scsi_pm.c (ffff800010983abc)
Location: drivers/scsi/scsi_pm.c:53
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
In drivers/scsi/scsi_pm.c (c0a562d0)
Location: drivers/scsi/scsi_pm.c:53
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
In drivers/scsi/scsi_pm.c (c000000000a40688)
Location: drivers/scsi/scsi_pm.c:53
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/scsi/scsi_pm.c (ffffffff81731f0d)
Location: drivers/scsi/scsi_pm.c:53
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
In drivers/scsi/scsi_pm.c (ffffffff8170b32d)
Location: drivers/scsi/scsi_pm.c:53
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
In drivers/scsi/scsi_pm.c (ffffffff81770cdd)
Location: drivers/scsi/scsi_pm.c:53
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
In drivers/scsi/scsi_pm.c (ffffffff8178c47d)
Location: drivers/scsi/scsi_pm.c:53
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
</ul>
