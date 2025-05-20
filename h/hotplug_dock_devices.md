# Function: <code>hotplug_dock_devices</code>

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
In drivers/acpi/dock.c (ffffffff81485198)
Location: drivers/acpi/dock.c:270
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff814d3cca)
Location: drivers/acpi/dock.c:265
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff814f6319)
Location: drivers/acpi/dock.c:265
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff815048ed)
Location: drivers/acpi/dock.c:265
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff81546c0d)
Location: drivers/acpi/dock.c:265
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff8157cc8c)
Location: drivers/acpi/dock.c:265
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff8159496c)
Location: drivers/acpi/dock.c:265
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff815c59fd)
Location: drivers/acpi/dock.c:252
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff815e6c2d)
Location: drivers/acpi/dock.c:252
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hotplug_dock_devices(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81691fd0)
Location: drivers/acpi/dock.c:252
Inline: False
Direct callers:
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff81691fd0-ffffffff816920fd: hotplug_dock_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hotplug_dock_devices(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff816afa70)
Location: drivers/acpi/dock.c:251
Inline: False
Direct callers:
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff816afa70-ffffffff816afba3: hotplug_dock_devices (STB_LOCAL)
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
In drivers/acpi/dock.c (ffffffff81692450)
Location: drivers/acpi/dock.c:251
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff81707f96)
Location: drivers/acpi/dock.c:251
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff818363a8)
Location: drivers/acpi/dock.c:251
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff8196a3c5)
Location: drivers/acpi/dock.c:251
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff819b0984)
Location: drivers/acpi/dock.c:251
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff819faea4)
Location: drivers/acpi/dock.c:251
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffff800010773da0)
Location: drivers/acpi/dock.c:252
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
```
</details>
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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff815daf0d)
Location: drivers/acpi/dock.c:252
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff815f4dcd)
Location: drivers/acpi/dock.c:252
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
