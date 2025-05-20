# Function: <code>software_node_notify_remove</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void software_node_notify_remove(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81846c40)
Location: drivers/base/swnode.c:1148
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/swnode.c:device_remove_software_node
```
**Symbols:**

```
ffffffff81846c40-ffffffff81846cec: software_node_notify_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void software_node_notify_remove(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198b5b0)
Location: drivers/base/swnode.c:1142
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/swnode.c:device_remove_software_node
```
**Symbols:**

```
ffffffff8198b5b0-ffffffff8198b66e: software_node_notify_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void software_node_notify_remove(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81afaae0)
Location: drivers/base/swnode.c:1142
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/swnode.c:device_remove_software_node
```
**Symbols:**

```
ffffffff81afaae0-ffffffff81afab9e: software_node_notify_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void software_node_notify_remove(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b48ed0)
Location: drivers/base/swnode.c:1081
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/swnode.c:device_remove_software_node
```
**Symbols:**

```
ffffffff81b48ed0-ffffffff81b48f8e: software_node_notify_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void software_node_notify_remove(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba12c0)
Location: drivers/base/swnode.c:1084
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/swnode.c:device_remove_software_node
```
**Symbols:**

```
ffffffff81ba12c0-ffffffff81ba137e: software_node_notify_remove (STB_GLOBAL)
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
