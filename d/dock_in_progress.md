# Function: <code>dock_in_progress</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int dock_in_progress(struct dock_station *ds);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81484b3c)
Location: drivers/acpi/dock.c:391
Inline: True
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff81484b3c-ffffffff81484b67: dock_in_progress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int dock_in_progress(struct dock_station *ds);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff814d36aa)
Location: drivers/acpi/dock.c:386
Inline: True
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff814d36aa-ffffffff814d36d5: dock_in_progress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int dock_in_progress(struct dock_station *ds);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff814f5cf9)
Location: drivers/acpi/dock.c:386
Inline: True
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff814f5cf9-ffffffff814f5d24: dock_in_progress (STB_LOCAL)
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
In drivers/acpi/dock.c (ffffffff81504880)
Location: drivers/acpi/dock.c:386
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_eject_request
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
In drivers/acpi/dock.c (ffffffff81546ba0)
Location: drivers/acpi/dock.c:386
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_eject_request
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
In drivers/acpi/dock.c (ffffffff8157cc34)
Location: drivers/acpi/dock.c:386
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff81594914)
Location: drivers/acpi/dock.c:386
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff815c59a2)
Location: drivers/acpi/dock.c:373
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff815e6bd2)
Location: drivers/acpi/dock.c:373
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff8169225c)
Location: drivers/acpi/dock.c:373
Inline: True
Inline callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff816afd0c)
Location: drivers/acpi/dock.c:372
Inline: True
Inline callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff816921ec)
Location: drivers/acpi/dock.c:373
Inline: True
Inline callers:
  - drivers/acpi/dock.c:undock_store
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff81707cfc)
Location: drivers/acpi/dock.c:373
Inline: True
Inline callers:
  - drivers/acpi/dock.c:undock_store
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff8183626a)
Location: drivers/acpi/dock.c:373
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff8196a28a)
Location: drivers/acpi/dock.c:373
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff819b084a)
Location: drivers/acpi/dock.c:373
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff819fad6a)
Location: drivers/acpi/dock.c:373
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffff800010773d48)
Location: drivers/acpi/dock.c:373
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff815daeb2)
Location: drivers/acpi/dock.c:373
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff815f4d72)
Location: drivers/acpi/dock.c:373
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
