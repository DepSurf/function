# Function: <code>try_to_bring_up_aggregate_device</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int try_to_bring_up_aggregate_device(struct aggregate_device *adev, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:227
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
```
**Symbols:**

```
ffffffff81972ed0-ffffffff81972fed: try_to_bring_up_aggregate_device (STB_LOCAL)
ffffffff81eca910-ffffffff81eca928: try_to_bring_up_aggregate_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int try_to_bring_up_aggregate_device(struct aggregate_device *adev, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81ade280)
Location: drivers/base/component.c:227
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
```
**Symbols:**

```
ffffffff81ade280-ffffffff81ade3c3: try_to_bring_up_aggregate_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int try_to_bring_up_aggregate_device(struct aggregate_device *adev, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81b2c4f0)
Location: drivers/base/component.c:227
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
```
**Symbols:**

```
ffffffff81b2c4f0-ffffffff81b2c643: try_to_bring_up_aggregate_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int try_to_bring_up_aggregate_device(struct aggregate_device *adev, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81b83c90)
Location: drivers/base/component.c:227
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
```
**Symbols:**

```
ffffffff81b83c90-ffffffff81b83de3: try_to_bring_up_aggregate_device (STB_LOCAL)
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
