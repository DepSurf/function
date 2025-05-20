# Function: <code>hotplug_event</code>

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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81452e5a)
Location: drivers/pci/hotplug/acpiphp_glue.c:750
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149f70a)
Location: drivers/pci/hotplug/acpiphp_glue.c:756
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c128a)
Location: drivers/pci/hotplug/acpiphp_glue.c:727
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cb93a)
Location: drivers/pci/hotplug/acpiphp_glue.c:727
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8150beea)
Location: drivers/pci/hotplug/acpiphp_glue.c:724
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81540e0a)
Location: drivers/pci/hotplug/acpiphp_glue.c:766
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8155809a)
Location: drivers/pci/hotplug/acpiphp_glue.c:766
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815880ca)
Location: drivers/pci/hotplug/acpiphp_glue.c:766
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a9aca)
Location: drivers/pci/hotplug/acpiphp_glue.c:772
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hotplug_event(u32 type, struct acpiphp_context *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81652890)
Location: drivers/pci/hotplug/acpiphp_glue.c:773
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff81652890-ffffffff81652ace: hotplug_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hotplug_event(u32 type, struct acpiphp_context *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81675250)
Location: drivers/pci/hotplug/acpiphp_glue.c:773
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff81675250-ffffffff8167548e: hotplug_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hotplug_event(u32 type, struct acpiphp_context *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81657780)
Location: drivers/pci/hotplug/acpiphp_glue.c:774
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff81657780-ffffffff816579ba: hotplug_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hotplug_event(u32 type, struct acpiphp_context *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: drivers/pci/hotplug/acpiphp_glue.c:774
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff816c9750-ffffffff816c99c2: hotplug_event (STB_LOCAL)
ffffffff81ceae2d-ffffffff81ceae69: hotplug_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hotplug_event(u32 type, struct acpiphp_context *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: drivers/pci/hotplug/acpiphp_glue.c:775
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff817ef9c0-ffffffff817efc66: hotplug_event (STB_LOCAL)
ffffffff81eb1e72-ffffffff81eb1eae: hotplug_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hotplug_event(u32 type, struct acpiphp_context *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: drivers/pci/hotplug/acpiphp_glue.c:783
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff81917b40-ffffffff81917de9: hotplug_event (STB_LOCAL)
ffffffff8208fe82-ffffffff8208febe: hotplug_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hotplug_event(u32 type, struct acpiphp_context *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: drivers/pci/hotplug/acpiphp_glue.c:786
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff8195b190-ffffffff8195b406: hotplug_event (STB_LOCAL)
ffffffff821101e2-ffffffff82110220: hotplug_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hotplug_event(u32 type, struct acpiphp_context *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: drivers/pci/hotplug/acpiphp_glue.c:783
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
```
**Symbols:**

```
ffffffff819a4740-ffffffff819a49b6: hotplug_event (STB_LOCAL)
ffffffff821edf0a-ffffffff821edf48: hotplug_event.cold (STB_LOCAL)
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
In drivers/pci/hotplug/acpiphp_glue.c (ffff800010712da4)
Location: drivers/pci/hotplug/acpiphp_glue.c:772
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159d29a)
Location: drivers/pci/hotplug/acpiphp_glue.c:772
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158c42a)
Location: drivers/pci/hotplug/acpiphp_glue.c:772
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159d81a)
Location: drivers/pci/hotplug/acpiphp_glue.c:772
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b7c4a)
Location: drivers/pci/hotplug/acpiphp_glue.c:772
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
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
