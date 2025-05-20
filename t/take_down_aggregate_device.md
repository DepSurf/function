# Function: <code>take_down_aggregate_device</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void take_down_aggregate_device(struct aggregate_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81973534)
Location: drivers/base/component.c:278
Inline: True
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff81973510-ffffffff81973564: take_down_aggregate_device (STB_LOCAL)
ffffffff81ecaa02-ffffffff81ecaa17: take_down_aggregate_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void take_down_aggregate_device(struct aggregate_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81ade9c4)
Location: drivers/base/component.c:278
Inline: True
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff81ade9a0-ffffffff81ade9f4: take_down_aggregate_device (STB_LOCAL)
ffffffff8209829a-ffffffff820982af: take_down_aggregate_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void take_down_aggregate_device(struct aggregate_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81b2cc44)
Location: drivers/base/component.c:278
Inline: True
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff81b2cc20-ffffffff81b2cc74: take_down_aggregate_device (STB_LOCAL)
ffffffff821192c6-ffffffff821192db: take_down_aggregate_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void take_down_aggregate_device(struct aggregate_device *adev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81b843e4)
Location: drivers/base/component.c:278
Inline: True
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff81b843c0-ffffffff81b84414: take_down_aggregate_device (STB_LOCAL)
ffffffff821f7289-ffffffff821f729e: take_down_aggregate_device.cold (STB_LOCAL)
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
