# Function: <code>add_edac_dev_to_global_list</code>

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
In drivers/edac/edac_device.c (ffffffff8175df7d)
Location: drivers/edac/edac_device.c:273
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
In drivers/edac/edac_device.c (ffffffff817cffed)
Location: drivers/edac/edac_device.c:273
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
In drivers/edac/edac_device.c (ffffffff81818cad)
Location: drivers/edac/edac_device.c:273
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
In drivers/edac/edac_device.c (ffffffff8184454d)
Location: drivers/edac/edac_device.c:273
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
In drivers/edac/edac_device.c (ffffffff8188701d)
Location: drivers/edac/edac_device.c:273
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
In drivers/edac/edac_device.c (ffffffff818b8fdd)
Location: drivers/edac/edac_device.c:273
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int add_edac_dev_to_global_list(struct edac_device_ctl_info *edac_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:273
Inline: False
Direct callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
**Symbols:**

```
ffffffff81989550-ffffffff819895c3: add_edac_dev_to_global_list (STB_LOCAL)
ffffffff81989d9a-ffffffff81989df7: add_edac_dev_to_global_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int add_edac_dev_to_global_list(struct edac_device_ctl_info *edac_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_device.c (0)
Location: drivers/edac/edac_device.c:273
Inline: False
Direct callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
**Symbols:**

```
ffffffff8198d2c0-ffffffff8198d333: add_edac_dev_to_global_list (STB_LOCAL)
ffffffff81c2893b-ffffffff81c28998: add_edac_dev_to_global_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (ffffffff81971bbd)
Location: drivers/edac/edac_device.c:273
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (ffffffff81a1a86d)
Location: drivers/edac/edac_device.c:273
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_device.c (ffffffff81b8360d)
Location: drivers/edac/edac_device.c:243
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
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
In drivers/edac/edac_device.c (ffffffff81d2210d)
Location: drivers/edac/edac_device.c:246
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
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
In drivers/edac/edac_device.c (ffffffff81d8b30b)
Location: drivers/edac/edac_device.c:246
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
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
In drivers/edac/edac_device.c (ffffffff81e42b8b)
Location: drivers/edac/edac_device.c:246
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
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
In drivers/edac/edac_device.c (ffff800010b110f4)
Location: drivers/edac/edac_device.c:273
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
In drivers/edac/edac_device.c (c0bef560)
Location: drivers/edac/edac_device.c:273
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
In drivers/edac/edac_device.c (c000000000c05030)
Location: drivers/edac/edac_device.c:273
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
In drivers/edac/edac_device.c (ffffffe0006fe082)
Location: drivers/edac/edac_device.c:273
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
In drivers/edac/edac_device.c (ffffffff8185ee5d)
Location: drivers/edac/edac_device.c:273
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
In drivers/edac/edac_device.c (ffffffff8182642d)
Location: drivers/edac/edac_device.c:273
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
In drivers/edac/edac_device.c (ffffffff818ae48d)
Location: drivers/edac/edac_device.c:273
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
In drivers/edac/edac_device.c (ffffffff818ca71d)
Location: drivers/edac/edac_device.c:273
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
</ul>
