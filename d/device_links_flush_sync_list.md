# Function: <code>device_links_flush_sync_list</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_links_flush_sync_list(struct list_head *list, struct device *dont_lock_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b2690)
Location: drivers/base/core.c:775
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_supplier_sync_state_resume
```
**Symbols:**

```
ffffffff817b2690-ffffffff817b2779: device_links_flush_sync_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_links_flush_sync_list(struct list_head *list, struct device *dont_lock_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c7080)
Location: drivers/base/core.c:1036
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_supplier_sync_state_resume
```
**Symbols:**

```
ffffffff817c7080-ffffffff817c7169: device_links_flush_sync_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_links_flush_sync_list(struct list_head *list, struct device *dont_lock_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aa560)
Location: drivers/base/core.c:1073
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_supplier_sync_state_resume
```
**Symbols:**

```
ffffffff817aa560-ffffffff817aa649: device_links_flush_sync_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_links_flush_sync_list(struct list_head *list, struct device *dont_lock_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81833720)
Location: drivers/base/core.c:1088
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_supplier_sync_state_resume
```
**Symbols:**

```
ffffffff81833720-ffffffff81833809: device_links_flush_sync_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_links_flush_sync_list(struct list_head *list, struct device *dont_lock_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81974e40)
Location: drivers/base/core.c:1100
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_supplier_sync_state_resume
```
**Symbols:**

```
ffffffff81974e40-ffffffff81974f73: device_links_flush_sync_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_links_flush_sync_list(struct list_head *list, struct device *dont_lock_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae05d0)
Location: drivers/base/core.c:1207
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_supplier_sync_state_resume
```
**Symbols:**

```
ffffffff81ae05d0-ffffffff81ae0703: device_links_flush_sync_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_links_flush_sync_list(struct list_head *list, struct device *dont_lock_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2e7f0)
Location: drivers/base/core.c:1149
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_probing_done
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_supplier_sync_state_resume
```
**Symbols:**

```
ffffffff81b2e7f0-ffffffff81b2e923: device_links_flush_sync_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_links_flush_sync_list(struct list_head *list, struct device *dont_lock_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b85ff0)
Location: drivers/base/core.c:1152
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_probing_done
  - drivers/base/core.c:device_links_driver_bound
  - drivers/base/core.c:device_links_supplier_sync_state_resume
```
**Symbols:**

```
ffffffff81b85ff0-ffffffff81b86123: device_links_flush_sync_list (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
