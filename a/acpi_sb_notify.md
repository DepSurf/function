# Function: <code>acpi_sb_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814cd25e)
Location: drivers/acpi/bus.c:514
Inline: False
```
**Symbols:**

```
ffffffff814cd25e-ffffffff814cd2a7: acpi_sb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814ef18c)
Location: drivers/acpi/bus.c:524
Inline: False
```
**Symbols:**

```
ffffffff814ef18c-ffffffff814ef1d5: acpi_sb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814fc0f0)
Location: drivers/acpi/bus.c:510
Inline: True
```
**Symbols:**

```
ffffffff814fc0f0-ffffffff814fc13b: acpi_sb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8153de60)
Location: drivers/acpi/bus.c:537
Inline: True
```
**Symbols:**

```
ffffffff8153de60-ffffffff8153deab: acpi_sb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (0)
Location: drivers/acpi/bus.c:544
Inline: True
```
**Symbols:**

```
ffffffff81573b90-ffffffff81573bd1: acpi_sb_notify (STB_LOCAL)
ffffffff815740e9-ffffffff815740fa: acpi_sb_notify.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8158b7d7)
Location: drivers/acpi/bus.c:513
Inline: True
```
**Symbols:**

```
ffffffff8158b7b0-ffffffff8158b7f1: acpi_sb_notify (STB_LOCAL)
ffffffff8158bd0c-ffffffff8158bd1d: acpi_sb_notify.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815bc617)
Location: drivers/acpi/bus.c:500
Inline: True
```
**Symbols:**

```
ffffffff815bc5f0-ffffffff815bc631: acpi_sb_notify (STB_LOCAL)
ffffffff815bcb02-ffffffff815bcb13: acpi_sb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815dd8d7)
Location: drivers/acpi/bus.c:500
Inline: True
```
**Symbols:**

```
ffffffff815dd8b0-ffffffff815dd8f1: acpi_sb_notify (STB_LOCAL)
ffffffff815dddc2-ffffffff815dddd3: acpi_sb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (0)
Location: drivers/acpi/bus.c:500
Inline: False
```
**Symbols:**

```
ffffffff81687f60-ffffffff81687fa1: acpi_sb_notify (STB_LOCAL)
ffffffff816886c5-ffffffff816886d6: acpi_sb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (0)
Location: drivers/acpi/bus.c:504
Inline: False
```
**Symbols:**

```
ffffffff816a5cd0-ffffffff816a5d11: acpi_sb_notify (STB_LOCAL)
ffffffff81c01013-ffffffff81c01024: acpi_sb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (0)
Location: drivers/acpi/bus.c:583
Inline: False
```
**Symbols:**

```
ffffffff816889d0-ffffffff81688a11: acpi_sb_notify (STB_LOCAL)
ffffffff81bf29b7-ffffffff81bf29c8: acpi_sb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (0)
Location: drivers/acpi/bus.c:585
Inline: False
```
**Symbols:**

```
ffffffff816fde10-ffffffff816fde51: acpi_sb_notify (STB_LOCAL)
ffffffff81cef343-ffffffff81cef354: acpi_sb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81eb6db0)
Location: drivers/acpi/bus.c:622
Inline: True
```
**Symbols:**

```
ffffffff8182b790-ffffffff8182b7e9: acpi_sb_notify (STB_LOCAL)
ffffffff81eb6db0-ffffffff81eb6dc1: acpi_sb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8195e0b0)
Location: drivers/acpi/bus.c:628
Inline: True
```
**Symbols:**

```
ffffffff8195e0b0-ffffffff8195e111: acpi_sb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819a42e0)
Location: drivers/acpi/bus.c:582
Inline: True
```
**Symbols:**

```
ffffffff819a42e0-ffffffff819a4341: acpi_sb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819eca10)
Location: drivers/acpi/bus.c:632
Inline: True
```
**Symbols:**

```
ffffffff819eca10-ffffffff819eca71: acpi_sb_notify (STB_LOCAL)
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
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffff800010769af0)
Location: drivers/acpi/bus.c:500
Inline: True
```
**Symbols:**

```
ffff800010769af0-ffff800010769b68: acpi_sb_notify (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815cfdb7)
Location: drivers/acpi/bus.c:500
Inline: True
```
**Symbols:**

```
ffffffff815cfd90-ffffffff815cfdd1: acpi_sb_notify (STB_LOCAL)
ffffffff815d02a2-ffffffff815d02b3: acpi_sb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815b9977)
Location: drivers/acpi/bus.c:500
Inline: True
```
**Symbols:**

```
ffffffff815b9950-ffffffff815b9991: acpi_sb_notify (STB_LOCAL)
ffffffff815b9e62-ffffffff815b9e73: acpi_sb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815d1bb7)
Location: drivers/acpi/bus.c:500
Inline: True
```
**Symbols:**

```
ffffffff815d1b90-ffffffff815d1bd1: acpi_sb_notify (STB_LOCAL)
ffffffff815d20a2-ffffffff815d20b3: acpi_sb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_sb_notify(acpi_handle handle, u32 event, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815eba77)
Location: drivers/acpi/bus.c:500
Inline: True
```
**Symbols:**

```
ffffffff815eba50-ffffffff815eba91: acpi_sb_notify (STB_LOCAL)
ffffffff815ebf62-ffffffff815ebf73: acpi_sb_notify.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
