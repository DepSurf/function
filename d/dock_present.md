# Function: <code>dock_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dock_present(struct dock_station *ds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff814849df)
Location: drivers/acpi/dock.c:227
Inline: False
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff814849df-ffffffff81484a3d: dock_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dock_present(struct dock_station *ds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff814d354d)
Location: drivers/acpi/dock.c:222
Inline: False
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff814d354d-ffffffff814d35ab: dock_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dock_present(struct dock_station *ds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff814f5b9c)
Location: drivers/acpi/dock.c:222
Inline: False
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff814f5b9c-ffffffff814f5bfa: dock_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81504884)
Location: drivers/acpi/dock.c:222
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_eject_request
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_eject_request
```
**Symbols:**

```
ffffffff81504390-ffffffff815043e9: dock_present.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81546ba4)
Location: drivers/acpi/dock.c:222
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_eject_request
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_eject_request
```
**Symbols:**

```
ffffffff815466b0-ffffffff81546709: dock_present.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff8157cc7c)
Location: drivers/acpi/dock.c:222
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff8157c760-ffffffff8157c7b9: dock_present.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff8159495c)
Location: drivers/acpi/dock.c:222
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff815944a0-ffffffff815944f9: dock_present.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff815c59ed)
Location: drivers/acpi/dock.c:209
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff815c5520-ffffffff815c557b: dock_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff815e6c1d)
Location: drivers/acpi/dock.c:209
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff815e6750-ffffffff815e67ab: dock_present.part.0 (STB_LOCAL)
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
In drivers/acpi/dock.c (ffffffff816924c0)
Location: drivers/acpi/dock.c:209
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff816aff73)
Location: drivers/acpi/dock.c:207
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff81692427)
Location: drivers/acpi/dock.c:207
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff81707f6d)
Location: drivers/acpi/dock.c:207
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
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
In drivers/acpi/dock.c (ffffffff818362bc)
Location: drivers/acpi/dock.c:207
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
In drivers/acpi/dock.c (ffffffff8196a2d9)
Location: drivers/acpi/dock.c:207
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
In drivers/acpi/dock.c (ffffffff819b0898)
Location: drivers/acpi/dock.c:207
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
In drivers/acpi/dock.c (ffffffff819fadb8)
Location: drivers/acpi/dock.c:207
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffff800010773d90)
Location: drivers/acpi/dock.c:209
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffff8000107737f0-ffff80001077386c: dock_present.part.0 (STB_LOCAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff815daefd)
Location: drivers/acpi/dock.c:209
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff815daa30-ffffffff815daa8b: dock_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/dock.c (ffffffff815f4dbd)
Location: drivers/acpi/dock.c:209
Inline: True
Inline callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
Direct callers:
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
**Symbols:**

```
ffffffff815f48f0-ffffffff815f494b: dock_present.part.0 (STB_LOCAL)
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
