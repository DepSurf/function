# Function: <code>handle_eject_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int handle_eject_request(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81484d88)
Location: drivers/acpi/dock.c:405
Inline: True
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff81484d88-ffffffff81484e51: handle_eject_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int handle_eject_request(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff814d38f6)
Location: drivers/acpi/dock.c:400
Inline: True
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff814d38f6-ffffffff814d39bd: handle_eject_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int handle_eject_request(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff814f5f45)
Location: drivers/acpi/dock.c:400
Inline: True
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff814f5f45-ffffffff814f600c: handle_eject_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int handle_eject_request(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff815045f0)
Location: drivers/acpi/dock.c:400
Inline: False
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff815045f0-ffffffff815046dd: handle_eject_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int handle_eject_request(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81546910)
Location: drivers/acpi/dock.c:400
Inline: False
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff81546910-ffffffff815469fd: handle_eject_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int handle_eject_request(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff8157c960)
Location: drivers/acpi/dock.c:400
Inline: True
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff8157c960-ffffffff8157ca3f: handle_eject_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int handle_eject_request(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff815946a0)
Location: drivers/acpi/dock.c:400
Inline: True
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff815946a0-ffffffff8159477f: handle_eject_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int handle_eject_request(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff815c5730)
Location: drivers/acpi/dock.c:387
Inline: True
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff815c5730-ffffffff815c5817: handle_eject_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int handle_eject_request(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff815e6960)
Location: drivers/acpi/dock.c:387
Inline: True
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff815e6960-ffffffff815e6a47: handle_eject_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff8169225c)
Location: drivers/acpi/dock.c:387
Inline: True
Inline callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff81692100-ffffffff8169222f: handle_eject_request.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff816afd0c)
Location: drivers/acpi/dock.c:386
Inline: True
Inline callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff816afbb0-ffffffff816afcdf: handle_eject_request.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff816921ec)
Location: drivers/acpi/dock.c:387
Inline: True
Inline callers:
  - drivers/acpi/dock.c:undock_store
  - drivers/acpi/dock.c:dock_notify
Direct callers:
  - drivers/acpi/dock.c:undock_store
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff81692080-ffffffff816921b4: handle_eject_request.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81707cfc)
Location: drivers/acpi/dock.c:387
Inline: True
Inline callers:
  - drivers/acpi/dock.c:undock_store
  - drivers/acpi/dock.c:dock_notify
Direct callers:
  - drivers/acpi/dock.c:undock_store
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff81707b90-ffffffff81707cc4: handle_eject_request.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81835ec0)
Location: drivers/acpi/dock.c:387
Inline: True
Direct callers:
  - drivers/acpi/dock.c:undock_store
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff81835ec0-ffffffff81836035: handle_eject_request.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81969eb0)
Location: drivers/acpi/dock.c:387
Inline: True
Direct callers:
  - drivers/acpi/dock.c:undock_store
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff81969eb0-ffffffff8196a025: handle_eject_request.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff819b0470)
Location: drivers/acpi/dock.c:387
Inline: True
Direct callers:
  - drivers/acpi/dock.c:undock_store
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff819b0470-ffffffff819b05e5: handle_eject_request.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff819fa9d0)
Location: drivers/acpi/dock.c:387
Inline: True
Direct callers:
  - drivers/acpi/dock.c:undock_store
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff819fa9d0-ffffffff819fab45: handle_eject_request.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int handle_eject_request(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffff800010773a40)
Location: drivers/acpi/dock.c:387
Inline: True
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffff800010773a40-ffff800010773b68: handle_eject_request (STB_LOCAL)
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
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int handle_eject_request(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff815dac40)
Location: drivers/acpi/dock.c:387
Inline: True
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff815dac40-ffffffff815dad27: handle_eject_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int handle_eject_request(struct dock_station *ds, u32 event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff815f4b00)
Location: drivers/acpi/dock.c:387
Inline: True
Direct callers:
  - drivers/acpi/dock.c:write_undock
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff815f4b00-ffffffff815f4be7: handle_eject_request (STB_LOCAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
